# Retail Strategy & Analytics: Customer Insights & Trial Evaluation
## 📌 Project Overview
This project is a comprehensive analysis of retail transaction data for a supermarket chain. It focuses on identifying high-value customer segments and evaluating the success of store trials (A/B testing) through statistical validation. The goal is to provide the CMO with actionable recommendations to drive sales growth and optimize product placement.


## 🛠️ Project Phases
### 1. Data Wrangling & Customer Insights
- Data Cleaning: Processed 264,834 transaction records, handled date inconsistencies, and removed outliers (e.g., bulk commercial transactions).
- 
- Exploratory Data Analysis (EDA): Identified that Mainstream - Young Singles/Couples are the highest drivers of sales, specifically preferring Kettle brand chips and 175g pack sizes.
- 
- Metric Development: Created features for Total Sales, Pack Size, and Brand extraction to deepen the analysis.

### 2. Trial Store Analysis (A/B Testing)
- Control Store Selection: Used Pearson Correlation and Magnitude Distance (Total Sales and Customer Counts) to match Trial Stores (77, 86, 88) with statistically identical Control Stores.

- Impact Assessment: Compared performance during the trial period against the control baseline.

- Results: The trial layout resulted in a 15% lift in total sales and an 8% increase in unique customers, confirmed at a 95% confidence level.

### 3. Business Visualization
- Developed a Snacks Sales Dashboard to monitor performance.

- KPIs Tracked: Total Sales ($335.90K), Total Transactions (49.76K), and Market Share by Brand.


## 🧰 Tech Stack
Language: Python (Pandas, NumPy, Matplotlib, Seaborn)

Statistical Analysis: SciPy (T-Tests, Correlation Analysis)

Visualization: Power BI (Dashboarding)

Presentation: Microsoft PowerPoint (Executive Reporting)


## 📂 Repository Structure
**Snacks_Data_Analytics.ipynb**: End-to-end Python analysis (Cleaning, EDA, Statistics).

**cleaned_store_data.csv**: The cleaned and prepared dataset.

**Snacks Sales Dashboard.pdf**: Interactive visual reporting.

**Trail Results.pptx**: Executive summary and recommendations for the CMO.


## 📈 Key Findings & Recommendations
Recommendation: Roll out the tested shelf layout across the broader store network.

Insight: Focus marketing efforts on the Mainstream segment with premium brands (Kettle, Tyrrells) to maximize basket value.

Validation: The consistent sales lift across all trial locations proves the strategy is scalable and robust.


## How to use this repository:
Read the Notebook: Start with **Snacks_Data_Analytics.ipynb** to see the data processing and statistical logic.

View the Dashboard: Open **Snacks Sales Dashboard.pdf** to see the high-level business KPIs.

Review the PPT: Check **Trail Results.pptx** to see how technical data is translated for executive leadership.
