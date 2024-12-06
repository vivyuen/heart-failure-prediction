<div style="gap: 20px; max-height:200px;">
  <img src="https://learn.utoronto.ca/themes/custom/de_theme/logo.svg" alt="UofT Logo" height="50">
  <img src="https://datasciences.utoronto.ca/wp-content/uploads/2021/12/Logo.png" alt="Data Sciences Logo" height="50" ">
</div>

# UofT | DSI - Team Project: 🔎 Heart Failure Prediction

![Heart](https://blog.bswhealth.med/wp-content/uploads/2019/06/thoracic-aorta-2000x1200.jpg)

## 🔍 Business Question
> Can heart failure be accurately predicted using only demographic and baseline pre-stress test data, without the need to conduct exercise stress tests? The goal is to explore whether machine learning models can predict heart disease risk by utilizing only basic data available prior to stress testing.

## Why Address This Problem?

#### Potential Value to Predict Heart Failure Without Stress Tests

Using only basic patient data, early screening could help identify high-risk patients who need to be prioritized for stress tests. This could make heart disease screening more accessible, especially in resource-limited settings.

#### Value for the Patient

Stress tests can be physically demanding, particularly for patients at higher risk for arrhythmias or cardiac events during the test. By predicting heart failure using baseline data, the physical and emotional burden is reduced, and the time to diagnosis is shortened. This approach allows for proactive interventions and lifestyle changes that can potentially reduce the progression of heart disease.

For Canadians in remote or underserved areas where exercise stress testing might not be available, heart disease could be identified through routine physical examinations, enhancing healthcare access.

#### Value for the Healthcare Provider

A reduction in the need for non-invasive cardiac diagnostic tests (NITs) improves the efficiency of healthcare providers, particularly physicians. They can use baseline data models for quick preliminary screening, saving time for acute cases. Additionally, developing a machine learning model to predict heart failure provides data-driven insights, improving decision-making and quality of care.

#### Value for the Healthcare System

In Ontario, around 500,000 NITs are performed annually, costing approximately C$300 million. Over half of these are exercise stress tests. If machine learning models can reduce the overuse of NITs while maintaining high-quality care, significant financial and logistical benefits could be achieved.

---

## 🎯 Project Overview
This project analyzes a dataset containing clinical and demographic features to predict heart disease events. The goal is to create a machine learning model capable of predicting the likelihood of heart disease using only basic patient data, improving accessibility to heart disease screening and potentially reducing mortality rates.

## 📊 Dataset
We are using the [Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/data) which includes:
* 11 clinical features (2 demographic and 9 medical measurements)
* Binary classification target (Heart Disease: Yes/No)

---

## 👥 Team Members

- **[Alfredo Natal](https://github.com/asnjunior)**
- **[Calen Lau](https://github.com/514ccmtl)**
- **[Juan Jimenez-Valero](https://github.com/actually-not-an-username)**
- **[Sehroz Khan](https://github.com/sehroz)
  <a href="https://www.linkedin.com/in/sehroz" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn" height="20"></a>
  <a href="https://sehroz.com" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/c/c4/Globe_icon.svg" alt="Website" height="20"></a>**
- **[Vivien Yuen](https://github.com/vivyuen)**

---

## 🏗️ Project Folder Structure

```markdown
|-- data
|   |-- processed     
|   |-- raw           
|-- experiments
|   |-- model_development  
|-- models
|   |-- logistic_regression  
|   |-- neural_networks      
|   |-- xgboost            
|-- reports
|   |-- figures   
```

## 🏁 Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/sehroz/heart-failure-prediction.git
cd heart-failure-prediction
```

2. Create and activate conda environment:
```bash

conda env create -f environment.yml

conda activate heart-ml
```

3. Run Jupyter Notebook:
```bash
jupyter notebook
```

----

## 💡 Project Context

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5 CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs, and this dataset contains 11 features that can be used to predict a possible heart disease.

People with cardiovascular disease or at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidemia, or already established disease) need early detection and management, where a machine learning model can be of great help.

---

## 📋 Attribute Information

- **Age:** Age of the patient [years]
- **Sex:** Sex of the patient [M: Male, F: Female]
- **ChestPainType:** Chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
- **RestingBP:** Resting blood pressure [mm Hg]
- **Cholesterol:** Serum cholesterol [mg/dl]
- **FastingBS:** Fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
- **RestingECG:** Resting electrocardiogram results [Normal: Normal, ST: ST-T wave abnormality, LVH: Left ventricular hypertrophy]
- **MaxHR:** Maximum heart rate achieved [Numeric]
- **ExerciseAngina:** Exercise-induced angina [Y: Yes, N: No]
- **Oldpeak:** ST depression induced by exercise [Numeric]
- **ST_Slope:** The slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
- **HeartDisease:** Target class [1: heart disease, 0: Normal]

---

[![Forks](https://img.shields.io/github/forks/sehroz/heart-failure-prediction)](https://github.com/sehroz/heart-failure-prediction/network/members)
[![Contributors](https://img.shields.io/github/contributors/sehroz/heart-failure-prediction)](https://github.com/sehroz/heart-failure-prediction/graphs/contributors)
[![Top Language](https://img.shields.io/github/languages/top/sehroz/heart-failure-prediction)](https://github.com/sehroz/heart-failure-prediction)


