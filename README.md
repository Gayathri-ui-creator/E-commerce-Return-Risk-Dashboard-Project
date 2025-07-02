# E-commerce_Return_Risk_Dashboard_Project
Return Risk Summary and Drill-Through Dashboard

This project analyzes customer return behavior using predictive modeling and creates a professional Power BI dashboard for business insights.

# Objective:
Identify why customers return products and how return rates vary by:
- Product Category
- Geography (Country/State)
- Marketing Channel

Also, predict the probability of return using logistic regression.

# Dataset Files:
| File Name | Description |
|-----------|-------------|
| `Customer360Insights.csv` | Base customer purchase and return data |
| `Cleaned_Customer360Insights.csv` | Preprocessed version of the main dataset |
| `ReturnRate_By_Product.csv` | Return rate aggregated by product |
| `ReturnRate_By_Category.csv` | Return rate aggregated by category |
| `ReturnRate_By_Geography.csv` | Return rate by Country + State |
| `ReturnRate_By_Channel.csv` | Return rate by marketing campaign |
| `High_Risk_Products.csv` | Products with high return rate (%) |
| `Predicted_Return_Probabilities.csv` | Output from logistic regression model |

 # Tools Used:
- **Power BI** – for dashboard design and data visualization
- **Python (Pandas, Scikit-learn)** – for data cleaning and predictive modeling
- **Excel** – for initial data format
  
  # Power BI Dashboard Highlights:
- **KPI Cards**: Return Rate %, Avg. Predicted Return Probability, Gender-wise return %, Campaign-wise return %
- **Visuals**:
  - Bar/Donut/Map: Returns by Category, Country, Reason, Gender
  - Line/Area Chart: Rolling 30-Day Return Rate Trend
  - Drill-through Page: Detailed Return Risk per Product & Customer
- **Filters/Slicers**: Product, Category, Gender, Country, Campaign

 *Drill-through enabled for: Product, Category, CampaignSchema, Country, Return Reason*

 # Model Summary (Python Notebook):
- Logistic Regression used to predict probability of return
- Trained on cleaned features (Campaign, Category, Gender, Country, etc.)
- Output saved in `Predicted_Return_Probabilities.csv`, `High_Risk_Products.csv`for Power BI integration



![image alt](https://github.com/Gayathri-ui-creator/E-commerce-Return-Risk-Dashboard-Project/blob/main/Screenshot%202025-07-02%20223155.png?raw=true)

![image alt](https://github.com/Gayathri-ui-creator/E-commerce-Return-Risk-Dashboard-Project/blob/main/Screenshot%202025-07-02%20223022.png?raw=true)
