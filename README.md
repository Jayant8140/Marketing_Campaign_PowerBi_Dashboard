# 📊 Marketing Campaign Analysis – Power BI Dashboard Project

## 🔍 Overview

This project explores and analyzes a marketing campaign dataset using Python and Power BI. The project consists of two major parts:

1. **Data Preparation for Machine Learning** – where data cleaning, outlier removal, encoding, and scaling are performed.
2. **Feature Engineering for Power BI** – where useful business columns (like ROI, CPA, Total Conversions, etc.) are created to enable powerful dashboard visualizations.

---

## 📁 Folder Structure

```
MarketingCampaignDashboard/
├── RawData/
│ └── marketing_campaign.csv
├── ProcessedData/
│ ├── processed_ml_ready.csv
│ └── updated_last.csv
├── PythonNotebook/
│ ├── Data_Preparation_ML.ipynb
│ └── Feature_Engineering_For_PowerBI.ipynb
├── PowerBIDashboard/
│ └── FinalDashboard.pbix
├── DashboardImage/
│ └── dashboard_screenshot.jpg
└── README.md
```

---

## 🧪 Dataset

- `marketing_campaign.csv`: Raw data with customer demographics, campaign details, income, spending behavior, etc.

---

## 📓 Python Notebooks

### 1. `Data_Preparation_ML.ipynb` (For ML Projects)
This notebook includes:
- Handling missing values
- Outlier removal (`Income`)
- Scaling using `MinMaxScaler` from `sklearn`
- Categorical encoding using `pd.get_dummies()`

> ✅ Resulting file: `processed_ml_ready.csv` (ML-friendly format)

### 2. `Feature_Engineering_For_PowerBI.ipynb` (For Dashboarding)
This notebook includes:
- Added business-focused columns:
  - `Total_Conversions`
  - `Conversion_Rate`
  - `CPA` (Cost Per Acquisition)
  - `ROI` (Return on Investment)
  - `Total_Leads`
  - `Max_Leads_Source`
  - `Total_Purchases`
  - `Total_Spent`
- No one-hot encoding or scaling (to keep categorical values intact for visualization)

> ✅ Resulting file: `updated_last.csv` (ready for Power BI)

---

## 💡 When to Use Which Dataset?

| Use Case               | Recommended Dataset      |
|------------------------|--------------------------|
| Power BI Dashboards    | `updated_last.csv`       |
| Machine Learning Models| `processed_ml_ready.csv` |

---

## 🧠 Key Skills Demonstrated

- Data Cleaning & Preprocessing
- Outlier Detection & Removal
- Feature Engineering
- Categorical Encoding
- Business Metric Calculation (ROI, CPA, etc.)
- Data Visualization in Power BI
- Report Writing & Storytelling with Data
- Git & GitHub for Version Control

---

## 📊 Power BI Dashboard Highlights

- Visuals for **Income Distribution**, **Campaign Conversions**, and **Customer Segmentation**
- KPIs like **CPA**, **ROI**, **Total Leads**, and **Top Performing Channels**
- Interactive filters for marital status, education, campaign type, and more

---

## 🛠 Tools & Technologies Used

- **Python (Pandas, NumPy, Sklearn)**
- **Google Colab**
- **Power BI**
- **Git & GitHub**

---

## 📬 Contact

For any questions, feel free to raise an issue or contact me via GitHub.

