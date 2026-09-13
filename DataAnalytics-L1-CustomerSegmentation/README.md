# Customer Segmentation Analysis

## OASIS INFOBYTE Data Analytics Internship — Task 2

### Objective

Segment e-commerce customers based on their purchasing behaviour using RFM analysis and K-Means clustering.

## Dataset

UCI Online Retail Dataset.

The analysis started with 541,909 transaction records and retained 392,617 valid transaction records after data cleaning.

## Methodology

1. Data Loading
2. Data Inspection
3. Data Cleaning
4. RFM Analysis
5. Average Purchase Value
6. Historical CLV Proxy
7. Feature Standardization
8. Elbow Method
9. Silhouette Score
10. K-Means Clustering
11. Customer Segment Profiling
12. Business Recommendations

## RFM Features

- Recency
- Frequency
- Monetary

## Clustering

Log1p transformation and StandardScaler were applied before the final K-Means model.

The final model selected K = 2 based on the highest Silhouette Score of 0.3997 among the tested values.

## Final Customer Segments

| Segment | Customers | Percentage |
|---|---:|---:|
| High-Value Active Customers | 1,906 | 43.94% |
| At-Risk / Low-Engagement Customers | 2,432 | 56.06% |

## Business Insights

### High-Value Active Customers

These customers show recent activity, higher transaction frequency, and higher historical spending.

Recommended actions:

- Loyalty rewards
- VIP benefits
- Exclusive offers
- Personalized recommendations
- Retention campaigns

### At-Risk / Low-Engagement Customers

These customers show higher recency and lower transaction frequency and historical spending.

Recommended actions:

- Re-engagement campaigns
- Personalized promotions
- Purchase reminders
- Targeted incentives
- Repeat-purchase campaigns

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Files

- `Customer_Segmentation.ipynb` — Complete analysis
- `customer_segments_final.csv` — Final customer-level segmentation output
- `requirements.txt` — Python dependencies

## Limitations

Frequency is based on transaction records rather than unique orders because InvoiceNo was not included in the selected dataset features.

The CLV value is a historical CLV proxy based on total historical spending rather than a predictive CLV model.
