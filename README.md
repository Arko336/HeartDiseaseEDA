# ❤️ Heart Disease EDA

## 📌 Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** of a heart disease dataset to uncover insights related to cardiovascular health risks. The analysis aims to identify patterns, correlations, and potential risk factors associated with heart disease using statistical and visual techniques.

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy)
- **Data Visualization** (Matplotlib, Seaborn)
- **EDA Techniques** (Descriptive Statistics, Correlation Analysis, Outlier Detection)

## 📂 Dataset
- **File:** `heart_failure_clinical_records_dataset.csv`
- **Source:** [Kaggle](https://www.kaggle.com/) or publicly available medical datasets.
- **Key Features:**
  - `age`: Age of the patient
  - `anaemia`: Decrease of red blood cells or hemoglobin
  - `creatinine_phosphokinase`: Level of CPK enzyme in the blood
  - `diabetes`: Whether the patient has diabetes (0 = No, 1 = Yes)
  - `ejection_fraction`: Percentage of blood leaving the heart at each contraction
  - `high_blood_pressure`: Whether the patient has high blood pressure
  - `platelets`: Platelet count in the blood
  - `serum_creatinine`: Level of creatinine in the blood
  - `serum_sodium`: Level of sodium in the blood
  - `smoking`: Whether the patient smokes (0 = No, 1 = Yes)
  - `time`: Follow-up period (days)
  - `DEATH_EVENT`: Whether the patient died during the follow-up period (0 = No, 1 = Yes)

## 🔍 Key Insights from EDA
✅ Identified significant risk factors for heart disease.  
✅ Analyzed distributions and trends among different age groups.  
✅ Explored correlations between medical conditions and **DEATH_EVENT**.  
✅ Visualized relationships between features using histograms, box plots, and heatmaps.  

## 📊 Project Workflow
1. **Data Preprocessing** - Handling missing values, standardizing formats.
2. **Exploratory Data Analysis (EDA)** - Statistical analysis, visualizations, and hypothesis testing.
3. **Correlation Analysis** - Identifying relationships between key health indicators.
4. **Outlier Detection** - Identifying anomalies in features like CPK levels and serum creatinine.

## 📌 Results
- Discovered a **strong correlation** between `ejection_fraction` and heart failure risk.
- Found that **high blood pressure and diabetes increase mortality risk**.
- Identified **age and serum creatinine** as critical factors affecting heart disease outcomes.

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Arko336/heart-eda.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis script:
   ```bash
   python heart_eda.py
   ```

## 📌 Future Enhancements
- Implement **machine learning models** to predict heart disease risk.
- Integrate real-time health monitoring dashboards.
- Expand dataset with **additional medical indicators** for better analysis.

---
📢 **Contributions & Feedback:** Feel free to fork this repository, open issues, or contribute improvements! Let's explore heart health data together. 🚀
