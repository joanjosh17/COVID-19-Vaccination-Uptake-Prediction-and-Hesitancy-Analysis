# 💉 COVID-19 Vaccination Uptake Prediction and Hesitancy Analysis

## 📌 Project Overview

COVID-19 vaccination campaigns faced major challenges globally due to vaccine hesitancy, misinformation, trust issues, and demographic differences. This project applies Machine Learning techniques to predict vaccination uptake while analyzing the factors contributing to vaccine hesitancy.

The project combines predictive analytics and public health insights to identify individuals more likely to receive vaccination and uncover patterns influencing hesitancy.

This project includes:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Vaccine hesitancy analysis
- Machine Learning classification
- Feature importance evaluation
- Model performance assessment
- Data visualization

---

## 🎯 Objectives

The primary objectives of this project are:

1. Predict COVID-19 vaccination uptake using demographic and behavioral variables.
2. Analyze factors influencing vaccine hesitancy.
3. Explore relationships between misinformation exposure and vaccination status.
4. Identify important predictors affecting vaccination decisions.
5. Build interpretable ML models for public health decision support.

---

## 🗂 Project Structure

```bash
COVID-19-Vaccination-Uptake-Prediction-and-Hesitancy-Analysis/

│
├── data/
│   └── covid19_vaccination_hesitancy_synthetic_dataset.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── outputs/
│   ├── feature_importance.csv
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── vaccination_distribution.png
│   ├── hesitancy_distribution.png
│   └── correlation_heatmap.png
│
├── covid_vaccination_analysis.py
│
├── requirements.txt
│
└── README.md
```

---

## 📊 Dataset Description

A synthetic dataset was created to simulate COVID-19 vaccination behaviors and hesitancy patterns.

### Features Included

| Feature | Description |
|----------|-------------|
| Age | Participant age |
| Gender | Male, Female, Other |
| Education_Level | Educational attainment |
| Income_Level | Income category |
| Employment_Status | Employment type |
| Residence_Type | Urban or Rural |
| Chronic_Disease | Presence of chronic illness |
| Trust_in_Healthcare_Score | Confidence in healthcare systems |
| Misinformation_Exposure_Score | Exposure to misinformation |
| COVID_Risk_Perception_Score | Perceived infection risk |
| Vaccinated | Target variable |
| Vaccine_Hesitancy_Level | Low, Moderate, High |

Dataset Size:

- Records: **5,000**
- Format: **CSV**
- Type: **Synthetic Public Health Dataset**

---

## 🔍 Exploratory Data Analysis (EDA)

The project performs several analyses including:

### Vaccination Distribution

- Vaccinated vs Non-vaccinated populations

### Hesitancy Distribution

- Low hesitancy
- Moderate hesitancy
- High hesitancy

### Demographic Analysis

- Education vs Hesitancy
- Age distribution
- Healthcare trust relationships

### Correlation Analysis

- Feature interaction heatmaps
- Risk factor exploration

---

## 🤖 Machine Learning Pipeline

### Data Preparation

- Missing value inspection
- Encoding categorical variables
- Feature engineering
- Dataset splitting

### Model Used

Random Forest Classifier

Model parameters:

```python
RandomForestClassifier(
    n_estimators=200,
    random_state=42
)
```

---

## 📈 Evaluation Metrics

The model is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- Feature Importance Ranking

---

## 📷 Visual Outputs

The project generates:

✅ Vaccination distribution chart

✅ Vaccine hesitancy distribution

✅ Age histogram

✅ Education vs hesitancy visualization

✅ Trust score analysis

✅ Confusion matrix

✅ ROC curve

✅ Feature importance plot

✅ Correlation heatmap

---

## ⚙️ Installation

Clone repository:

```bash
git clone https://github.com/yourusername/COVID-19-Vaccination-Uptake-Prediction-and-Hesitancy-Analysis.git
```

Move into project folder:

```bash
cd COVID-19-Vaccination-Uptake-Prediction-and-Hesitancy-Analysis
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ Running the Project

Run Python script:

```bash
python covid_vaccination_analysis.py
```

Or launch notebook:

```bash
jupyter notebook
```

Open:

```bash
analysis.ipynb
```

---

## 📌 Example Workflow

```text
Load Dataset
      ↓
Data Cleaning
      ↓
Exploratory Analysis
      ↓
Feature Encoding
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Prediction
      ↓
Evaluation
      ↓
Feature Importance Analysis
```

---

## 🧠 Key Insights Generated

This project helps answer questions such as:

- Which demographic groups show higher vaccine hesitancy?
- Does misinformation influence vaccination uptake?
- How important is trust in healthcare systems?
- Which features contribute most to prediction performance?
- What public health factors influence vaccine acceptance?

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 🚀 Future Improvements

Possible enhancements:

- Add XGBoost and LightGBM models
- Integrate SHAP explainability
- Build deployment dashboard using Streamlit
- Add geographic visualization
- Perform hyperparameter optimization
- Include real-world vaccination datasets

---

## 👨‍💻 Author

**Joshua Joan**

Machine Learning | Data Analytics | Public Health Analytics

---

## 📄 License

This project is intended for educational, research, and portfolio purposes.

MIT License

---

## ⭐ Repository Highlights

- End-to-end Machine Learning workflow
- Public health analytics application
- Vaccine hesitancy insights
- Predictive modeling
- Data visualization
- Portfolio-ready project
