# 🛒 Comprehensive Retail eCommerce Data Analysis

## Final Data Analytics Internship Project

This project presents an end-to-end analysis of a simulated retail eCommerce platform by integrating multiple analytical techniques developed throughout the internship.

The project connects **customer segmentation, sales forecasting, website analytics, conversion rate optimization, pricing experimentation, statistical analysis, and business recommendations** into one comprehensive analytical framework.

---

## 🎯 Project Objectives

- Develop an integrated eCommerce analytics framework
- Analyze customer segments and behavioral patterns
- Evaluate website engagement and conversion performance
- Compare traffic sources and device performance
- Analyze historical sales trends
- Forecast future sales performance
- Evaluate pricing strategies through statistical testing
- Perform cross-dimensional analysis
- Generate actionable business recommendations

---

## 🔄 End-to-End Analytical Framework

```text
Data Strategy & Collection
          ↓
Data Preparation
          ↓
Customer Segmentation
          ↓
Sales Trend & Forecasting
          ↓
Website Analytics & CRO
          ↓
Pricing Strategy Evaluation
          ↓
Cross-Analysis
          ↓
Integrated Business Insights
          ↓
Strategic Recommendations
```

---

## 👥 Customer Segmentation

Customers were analyzed across four simulated segments:

- High Value
- Regular
- Occasional
- At Risk

The analysis evaluates differences in conversion, engagement, revenue, and estimated profitability.

![Customer Segment Conversion](01_customer_segment_conversion.png)

![Customer Segment Revenue](02_customer_segment_revenue.png)

![Customer Segment Engagement](03_customer_segment_engagement.png)

---

## 📈 Sales Forecasting

Sales performance was analyzed using multiple forecasting approaches:

- 3-Month Moving Average
- Linear Regression
- Exponential Smoothing

The methods were compared using Mean Absolute Error (MAE).

![Monthly Sales Trend](04_monthly_sales_trend.png)

![Sales Forecast](05_sales_forecast_comparison.png)

![Forecasting MAE](06_forecasting_model_mae.png)

---

## 🌐 Website Analytics & Conversion Rate Optimization

Website performance was evaluated using:

- Conversion Rate
- Bounce Rate
- Session Duration
- Funnel Progression
- Traffic Source
- Device Performance
- Engagement Behavior

![Conversion Funnel](07_integrated_conversion_funnel.png)

![Traffic Conversion](08_traffic_source_conversion.png)

![Traffic Bounce](09_traffic_source_bounce.png)

![Device Conversion](10_device_conversion.png)

![Device Session Duration](11_device_session_duration.png)

![Engagement](12_engagement_by_conversion.png)

---

## 💰 Pricing Strategy Analysis

Three pricing conditions were evaluated:

| Strategy | Price |
|---|---:|
| Control | ₹1,000 |
| Discount | ₹900 |
| Premium | ₹1,100 |

Pricing performance was evaluated using:

- Conversion Rate
- Revenue per Visitor
- Profit per Visitor
- Chi-Square Testing
- 95% Confidence Intervals

![Pricing Conversion](13_pricing_conversion_ci.png)

![Pricing Profit](14_pricing_profit_per_visitor.png)

---

## 🔗 Cross-Analysis

Individual analytical areas were integrated to identify relationships across multiple dimensions.

### Customer Segment × Pricing

![Segment Pricing](15_segment_pricing_heatmap.png)

This analysis examines whether pricing performance differs across customer groups.

### Traffic Source × Device

![Traffic Device](16_traffic_device_heatmap.png)

This analysis evaluates conversion performance across combinations of acquisition channel and device.

### KPI Correlation Analysis

![Correlation Matrix](17_integrated_correlation_heatmap.png)

Correlation analysis was used to explore relationships between numerical variables. Correlation is interpreted as association rather than evidence of causation.

---

## 💡 Business Recommendations

The analytical framework supports recommendations in several areas:

- Prioritize and retain high-value customer groups
- Improve experiences with high drop-off or low conversion
- Optimize acquisition based on traffic quality, not volume alone
- Improve lower-performing device experiences
- Use forecasting for inventory and campaign planning
- Evaluate pricing using conversion and profitability together
- Validate major changes through controlled experiments
- Develop re-engagement strategies for at-risk customers

---

## 🚀 Future Scope

The project can be extended using:

- Customer Churn Prediction
- Customer Lifetime Value Modeling
- Recommendation Systems
- Advanced Time-Series Forecasting
- Dynamic Pricing
- Marketing Attribution
- Real-Time Analytics
- Cloud-Based Data Pipelines
- Machine Learning

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Statsmodels
- Scikit-learn
- Google Colab
- GitHub
- Microsoft Word

---

## 📁 Repository Structure

```text
Final-Retail-eCommerce-Data-Analysis/
│
├── Final_Retail_eCommerce_Analysis.ipynb
├── Comprehensive_Retail_eCommerce_Data_Analysis_Report.docx
│
├── final_ecommerce_integrated_dataset.csv
├── final_kpi_summary.csv
├── final_customer_segment_summary.csv
├── final_customer_engagement_summary.csv
├── final_monthly_sales_analysis.csv
├── final_sales_forecast_6_months.csv
├── final_forecasting_method_comparison.csv
├── final_conversion_funnel.csv
├── final_integrated_pricing_analysis.csv
├── final_integrated_findings.csv
├── final_strategic_recommendations.csv
│
├── 01_customer_segment_conversion.png
├── 02_customer_segment_revenue.png
├── 03_customer_segment_engagement.png
├── 04_monthly_sales_trend.png
├── 05_sales_forecast_comparison.png
├── 06_forecasting_model_mae.png
├── 07_integrated_conversion_funnel.png
├── ...
└── 17_integrated_correlation_heatmap.png
```

---

## ⚠️ Limitations

This project uses simulated data for educational and analytical purposes. The results should therefore be interpreted as demonstrations of analytical methodology rather than actual performance of a specific eCommerce company.

Real-world implementation would require production transaction data, customer behavior data, marketing costs, refunds, operational expenses, inventory information, and controlled experimentation.

---

## 📌 Conclusion

This project demonstrates how multiple data analytics techniques can be combined to create an end-to-end eCommerce decision-support framework.

Rather than evaluating customer behavior, website performance, sales trends, and pricing independently, the project connects these areas to provide a broader understanding of business performance.

The analysis demonstrates the importance of combining **customer analytics, forecasting, conversion optimization, experimentation, statistical analysis, and profitability metrics** when making data-driven eCommerce decisions.

---

## 👨‍💻 Author

**Nishant Kumar Nishee**

B.Tech – Computer Science and Engineering  
Centurion University of Technology and Management

**Career Focus:** Cloud Computing | Data Analytics | Data Science
