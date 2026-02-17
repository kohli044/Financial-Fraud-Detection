# Financial-Fraud-Detection
Built an end-to-end Financial Fraud Detection Dashboard analyzing 500K+ transactions using SQL, Python, and Tableau. Identified seasonal transaction peaks (44K/month), geo-based fraud clusters, and $946K inflation-adjusted weekly spikes. Delivered interactive visual analytics enabling fraud pattern detection across demographics and regions.
Tools Used: Python, SQL, Tableau, Excel
Dataset: 500K+ financial transaction records (multi-state US dataset)

📊 Quantitative Impact & Analytical Findings:

Analyzed 500,000+ credit card transactions across multiple US states using SQL and Python.
Identified monthly transaction peak of 44,021 transactions (May) and lowest volume of ~20,501 (October), revealing strong seasonal variation.
Detected Q2 transaction surge (March–June) contributing to the highest fraud exposure window.
Built inflation-adjusted time-series model identifying Week 25 peak adjusted value of $946,723, revealing real-value volatility trends.
Mapped geo-distribution of 1,000+ high-risk transaction clusters, highlighting dense fraud patterns in urban regions.

Performed category-wise gender spending analysis, identifying:

Highest category spend: $2.68M
Median transaction range: $850K–$1.15M across demographics.
Designed fraud vs non-fraud visualization showing regional fraud density concentrations.
Used SQL aggregation and joins to optimize fraud filtering logic, reducing query execution complexity.
Applied data cleaning and preprocessing techniques to handle missing geolocation and timestamp inconsistencies.

📈 Business Insights Generated

Fraud exposure increases during high transaction volume months (Q2 and December).
Urban transaction clusters show higher fraud density than rural regions.
Seasonal dips (Sept–Oct) indicate lower fraud probability windows.
Inflation-adjusted trends reveal underlying purchasing power shifts beyond nominal transaction spikes.
Category-based spending analysis highlights disproportionate spend behavior patterns useful for anomaly detection.

🧠 Technical Implementation

Built interactive Tableau dashboard integrating:
Fraud heat maps
Monthly trend analysis
Inflation-adjusted time series
Gender & category distribution boxplots
Wrote advanced SQL queries (GROUP BY, JOIN, CASE WHEN) for fraud flag segmentation.
Conducted EDA in Python (Pandas, Matplotlib/Seaborn).
Engineered inflation-adjusted feature for real-value trend analysis.
Created an end-to-end data pipeline from raw dataset → cleaned dataset → SQL transformation → dashboard reporting.
