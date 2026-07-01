# E-Commerce Customer Spending Prediction

## Project Overview
This project analyzes customer data from an e-commerce company to understand purchasing behavior and predict future spending. By exploring the relationships between various customer engagement metrics, the goal is to build a predictive Linear Regression model targeting the `Yearly Amount Spent`. The core business objective is to help the company determine whether they should prioritize their development and marketing efforts on improving their mobile app or their website experience.

## Dataset Information
The dataset contains customer information, including categorical identifiers (Email, Address, Avatar) and the following numerical features:
* **Avg. Session Length:** Average time of in-store style advice sessions.
* **Time on App:** Average time spent on the mobile app (in minutes).
* **Time on Website:** Average time spent on the website (in minutes).
* **Length of Membership:** The number of years the customer has been a member of the platform.
* **Yearly Amount Spent:** *(Target Variable)* The total amount spent by the customer in a given year.

## Technologies Used
* **Data Manipulation & Analysis:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Machine Learning:** `scikit-learn` (Linear Regression)
* **Statistical Analysis:** `scipy.stats` (Probability plots for residual analysis)

## Methodology
1. **Data Loading & Inspection:** Cleaning and preparing the e-commerce data for analysis.
2. **Exploratory Data Analysis (EDA):** Visualizing patterns to understand the correlations between customer engagement metrics (Time on App, Time on Website, Length of Membership) and overall revenue.
3. **Model Training:** Splitting the dataset into training and testing sets, and building a Linear Regression model to predict future spending.
4. **Model Evaluation:** Assessing the model's accuracy using standard regression metrics. To ensure the model's assumptions hold true and confirm its robustness, the normality of residuals was verified using Q-Q probability plots.

## Final Thoughts & Business Insights
Through this analysis, a robust Linear Regression model was successfully developed to predict customer spending based on platform engagement. By analyzing the model's coefficients, this project provides a concrete, data-driven answer to the company's business problem regarding where to focus their development efforts—revealing the comparative ROI of the Mobile App versus the Website.
