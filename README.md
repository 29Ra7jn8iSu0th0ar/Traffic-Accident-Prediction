# 🚦 Traffic Accident Prediction

This project explores how **machine learning can predict the likelihood and severity of traffic accidents** using historical datasets from the **US, UK, and global driving spots**.  

It was my **first end-to-end ML project**, where I learned how to handle datasets, prepare features, and evaluate different ML models.  

The goal is to provide insights into accident risks and help **city planners, traffic authorities, and drivers** improve road safety.

---

## 📊 Datasets Used
- **US Accidents (2016–2023)** → [Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents/data) 
- **UK Road Accident Dataset** → [Kaggle](https://www.kaggle.com/datasets/devansodariya/road-accident-united-kingdom-uk-dataset)
- **Hazardous Driving Spots (Global)** → [OpenML](https://www.openml.org/search?type=data&status=active&id=43372&sort=runs)

---

## 🔍 Steps Performed
### 1. Data Cleaning & Preprocessing
- Removed missing values and duplicates  
- Handled outliers in numeric features  
- Unified columns across datasets  

### 2. Exploratory Data Analysis (EDA)
- Distribution of accidents across months & years  
- Identified accident hotspots  
- Correlated weather, time, and location with accident frequency  

### 3. Model Training
Trained multiple ML models on cleaned features:
- **Linear Regression**  
- **Decision Trees**  
- **Support Vector Machine (SVM)**  
- **Random Forest Classifier**  

---

## 📈 Results

| Model              | Accuracy / Score | Notes                |
|--------------------|-----------------|----------------------|
| Linear Regression  | ~0.65 (R²)      | Basic baseline       |
| Decision Trees     | ~0.78 accuracy  | Interpretable model  |
| SVM Classifier     | ~0.81 accuracy  | Good generalization  |
| **Random Forest**  | **~0.87 accuracy** | Best performing model |

✅ **Random Forest performed best**, achieving ~87% accuracy in predicting accident likelihood.  
📌 Results show that accident risk is **strongly correlated with month, time, and location factors**.  

---

## 📂 Project Structure
```
├── README.md # Project documentation
├── data_analysis_for_ml_project.ipynb # Jupyter notebook with full workflow
├── TRAFFIC ACCIDENT PREDICTION.pptx # Project presentation
```

---
1. Clone the repo:
   ```bash
   git clone https://github.com/29Ra7jn8iSu0th0ar/Traffic-Accident-Prediction.git
   cd Traffic-Accident-Prediction

---

2. Install dependencies:

   ```bash
      pip install -r requirements.txt

---
3. Open the notebook and run:

   ```bash
      jupyter notebook data_analysis_for_ml_project.ipynb

---

📌 Key Learnings

* Hands-on experience with **data preprocessing, EDA, and ML model comparison**

* Gained confidence in using **pandas, scikit-learn, matplotlib** for ML projects

* Learned how model choice impacts **performance and interpretability**
