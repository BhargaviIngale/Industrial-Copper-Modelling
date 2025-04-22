# 🔧 Industrial Copper Modeling

A machine learning project focused on predictive modeling in the manufacturing domain using real-world copper sales data. This project covers both **regression** (predicting `Selling_Price`) and **classification** (predicting `Status` as WON or LOST), along with an interactive **Streamlit** web application for real-time predictions.

---

## 🏭 Domain  
**Manufacturing Industry**

---

## 🛠️ Skills & Technologies Used

- **Python Scripting**
- **Data Preprocessing & Feature Engineering**
- **Exploratory Data Analysis (EDA)**
- **Machine Learning (Regression & Classification)**
- **Streamlit Web Application**
- **Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib**

---

## 🧩 Problem Statement

The copper manufacturing industry often deals with skewed and noisy sales and pricing data. This can lead to inaccurate manual forecasting. To overcome this:

1. Implement **regression modeling** to predict the `Selling_Price`.
2. Build a **classification model** to predict lead `Status` (WON or LOST).
3. Develop a **Streamlit-based UI** for live predictions based on user inputs.

---

## 🗃️ Dataset Overview

The dataset includes various features such as:

| Column Name        | Description |
|--------------------|-------------|
| `id`               | Unique identifier |
| `item_date`        | Date of transaction |
| `quantity tons`    | Quantity in tons |
| `customer`         | Customer ID |
| `country`          | Customer's country |
| `status`           | Lead status (WON/LOST) |
| `item type`        | Type of item |
| `application`      | Application type |
| `thickness`        | Material thickness |
| `width`            | Material width |
| `material_ref`     | Material reference |
| `product_ref`      | Product reference |
| `delivery date`    | Expected delivery date |
| `selling_price`    | Target variable for regression |

---

## 📊 Approach

### 1. **Data Understanding & Cleaning**
- Drop non-informative columns.
- Remove garbage values.
- Convert columns into proper format.
- Treat categorical variables as category types.

### 2. **Data Preprocessing**
- Handle missing values using mean/median/mode.
- Detect and treat outliers using IQR.
- Apply transformations to reduce skewness.
- Encode categorical variables (Label or One-Hot Encoding).
- Standardize/normalize features.

### 3. **Exploratory Data Analysis (EDA)**
- Visualize skewness and outliers using:
  - Boxplots
  - Histograms
- Identify highly correlated features using heatmaps.

### 4. **Feature Engineering**
- Create new variables if applicable.
- Drop redundant or highly correlated features.

### 5. **Model Building**
#### 🔵 Regression Model
- Target: `Selling_Price`
- Models used: DecisionTreesRegressor
- Metrics: RMSE, R², MAE

#### 🔴 Classification Model
- Target: `Status` (WON/LOST)
- Models used: DecisionTreesClassifier
- Metrics: Accuracy, Precision, Recall, F1 Score

- Use cross-validation and grid search for hyperparameter tuning.

---

## 🌐 Streamlit Web App

The app consists of:

- A toggle to choose between **Regression** or **Classification**.
- Interactive form to input feature values.
- Model predictions displayed in real-time.
- Backend uses pre-fitted **pickle** models for:
  - Scalers
  - Encoders
  - ML Models

## 🏆 Project Outcomes

This project provided a comprehensive, hands-on learning experience in applying machine learning to real-world problems in the manufacturing domain. The following outcomes were achieved:

### 💻 Technical Skill Development
- **Python Proficiency**: Hands-on scripting using core libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.
- **Data Cleaning & Preprocessing**: Effective handling of missing values, outliers, categorical variables, and data transformations.
- **Exploratory Data Analysis (EDA)**: Gained the ability to extract insights from data using visual tools like heatmaps, boxplots and distribution plots.
- **Feature Engineering**: Learned how to identify, create, and refine features for improving model performance.
- **Model Building**:
  - Implemented **regression models** to predict `Selling_Price`.
  - Built **classification models** to predict lead conversion `Status` (WON/LOST).
- **Model Optimization**: Applied cross-validation and grid search for tuning hyperparameters to improve accuracy and generalization.
- **Model Evaluation**: Learned to use various metrics including RMSE, MAE, R², Accuracy, Precision, Recall, F1 Score to assess model performance.

### 🌍 Real-world Application
- Built and deployed a fully functional **Streamlit web application** to:
  - Predict selling prices for copper products.
  - Predict lead status (WON/LOST) from user inputs.
- Used **pickle** to persist ML models, scalers, and encoders for production-ready inference pipelines.

### 🧠 Domain Knowledge
- Developed an understanding of the manufacturing sector’s sales dynamics and pricing strategies.
- Learned how lead status impacts forecasting and planning in industrial operations.
---

## 🎯 Key Takeaways
- End-to-end ML project development lifecycle: From raw data to deployment.
- Experience working with noisy, skewed real-world data.
- Exposure to UI development for ML with Streamlit.
- Best practices in version control, documentation, and code sharing via GitHub.
<!--- 📎Dataset Link: *[Insert your GitHub repo or data link here]*.
- Demo link:*[Insert your linkedin here]*. -->
