# Google-Ads-Cost-Analysis
🚀 Project Overview

This project analyzes Google Ads performance across different ad types and geographical locations. Using Python (Pandas, NumPy, Matplotlib, Seaborn) for data cleaning and analysis, and Tableau for interactive visualizations, we uncover insights on cost efficiency (CPM), ad performance, and geo-targeting strategies.

📁 Dataset

Source: Kaggle Google Ads Dataset

Columns:

ad_type: Type of ad (Image, Video, Text)

impressions: Number of times the ad was displayed

spend_usd: Total amount spent on the ad

geo_targeting_included: The regions where the ad was displayed

🔥 Key Objectives

✅ Calculate Cost Per Thousand Impressions (CPM)
✅ Compare CPM across different ad types
✅ Find the most cost-effective geo-locations
✅ Identify the most expensive ad type
✅ Visualize trends using Tableau

🛠️ Tools & Technologies

Python: Data cleaning & analysis (pandas, numpy, seaborn)

SQL: Querying insights

Tableau: Data visualization & dashboards

GitHub: Version control & documentation

📌 Steps Performed

1️⃣ Data Cleaning (Python & Pandas)

Converted impressions and spend_usd from string to numeric values

Handled missing values & removed duplicates

Created a new calculated column CPM ((spend_usd / impressions) * 1000)

2️⃣ Exploratory Data Analysis (EDA)

Calculated average CPM per ad type to find the most expensive format

Identified cheapest & most expensive geo locations for ads

Used seaborn & matplotlib for initial data visualizations

3️⃣ Data Visualization (Tableau)

📊 Bar Chart: CPM by Geo Location
📊 Bar Chart: CPM by Ad Type
📊 Heatmap: Geo vs. Ad Type CPM
📊 Interactive Dashboard: Combined all insights

🎯 Key Findings

🔹 Cheapest Geo Location for Ads: Rhode Island has the lowest CPM → Best for cost-effective advertising
🔹 Most Expensive Ad Type: Text Ads have the highest CPM → Budget-conscious advertisers should prefer image ads
🔹 Image Ads were the most cost-effective, while Text Ads were the most expensive

📌 How to Use This Project

1️⃣ Clone Repository

 git clone https://github.com/yourusername/google-ads-analysis.git
 cd google-ads-analysis

2️⃣ Install Dependencies

pip install pandas numpy matplotlib seaborn

3️⃣ Run Jupyter Notebook

jupyter notebook

4️⃣ Open Tableau & Load cleaned_google_ads_data.csv

Create visualizations based on the guide in the tableau_steps.md file

📜 Project Structure

📂 Google-Ads-Analysis
 ├── 📄 README.md          # Project Documentation
 ├── 📄 google_ads_analysis.ipynb  # Jupyter Notebook for Analysis
 ├── 📄 cleaned_google_ads_data.csv  # Cleaned dataset
 ├── 📊 tableau_dashboard.twbx  # Tableau Workbook


📌 Future Improvements

✅ Incorporate CTR (Click-Through Rate) analysis
✅ Predict which ad type performs best using Machine Learning
✅ Automate data pipeline using SQL & Google BigQuery


📢 If you found this project useful, don’t forget to ⭐ the repository!
