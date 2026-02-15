# 📊 Customer Churn Analysis (Exploratory Data Analysis)

## 📂 Repository Structure
* **`churn_analysis(1).ipynb`**: The complete technical workflow including data cleaning, exploratory data analysis (EDA), and visualizations.
* **`telco customer churn analysis.pdf`**: A high-level executive summary and strategic recommendations report.
*  **`Customer Churn.csv`**: The primary dataset (7,043 customers).

## 🔍 Project Objective
This project performs Exploratory Data Analysis (EDA) on a telecom customer dataset to identify key drivers of customer churn and generate data-driven retention insights.

- Total Records: **7,043 customers**
- Target Variable: **Churn (Yes/No)**
- Overall Churn Rate: **26.5%**

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧹 Data Preprocessing
- Converted `TotalCharges` column to numeric
- Handled missing values
- Validated data types and distributions
- Performed univariate and bivariate analysis
- Checked categorical feature impact on churn

---

## 📊 Key Analytical Findings

### 1️⃣ Churn Distribution
- **26.5% of customers have churned**
- Moderate class imbalance observed

### 2️⃣ Tenure (Strongest Indicator)
- Highest churn observed in **0–2 month tenure**
- Churn probability decreases significantly after 12 months
- Long-tenure customers show strong retention patterns

### 3️⃣ Contract Type
- **Month-to-month contracts show highest churn**
- 1-year and 2-year contracts significantly reduce churn likelihood

### 4️⃣ Demographic Impact
- Gender has minimal impact on churn
- Senior citizens show relatively higher churn tendency

### 5️⃣ Billing & Revenue
- Higher monthly charges slightly increase churn probability
- Electronic payment methods show higher churn patterns

### 6️⃣ Service Engagement
- Customers with fewer subscribed services churn more
- Multi-service customers demonstrate stronger retention behavior

---

## 📈 Visualizations Performed
- Churn distribution count plots
- Tenure vs Churn analysis
- Contract type vs Churn comparison
- Monthly charges distribution by churn
- Service-wise churn segmentation

---

## 💡 Analytical Conclusion
Customer churn is primarily influenced by:
- Short tenure
- Month-to-month contracts
- Lower service engagement

The first 90 days represent the highest churn risk period. Long-term contract incentives and improved early-stage customer engagement strategies can significantly reduce churn probability.

---

## 🚀 Future Scope
- Build predictive models (Logistic Regression, Random Forest, XGBoost)
- Perform feature importance analysis
- Implement customer segmentation
- Evaluate models using ROC-AUC, F1-score, Precision-Recall
- Deploy churn prediction model

---
## 📈 Strategic Recommendations
Based on the analysis, the following actions are recommended:

* **Early Lifecycle Retention**: Focus on the first 90 days of the customer journey to reduce immediate churn.
* **Contract Conversion**: Offer incentives to move month-to-month users to 1-year or 2-year plans.
* **Targeted Support**: Enhance support for senior citizens to reduce technical friction and service complexity.
* **Bundling**: Encourage multi-service integration to increase switching costs and customer loyalty.

---
**Author**: Astha jadon
