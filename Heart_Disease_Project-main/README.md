

# Heart Disease Prediction Project

This project implements a full machine learning pipeline for predicting heart disease.  
It includes data preprocessing, PCA analysis, feature selection, supervised and unsupervised learning, and hyperparameter tuning.

---

## 📁 File Structure
Heart_Disease_Project/
│── data/
│── models/
│── notebooks/  
│── results/
│── README.md
│── requirements.txt
│── .gitignore

---

## How to Run (Google Colab)

1. **Upload dataset**  
   - Place `heart_disease.csv` inside `data/` or upload it in Colab.

2. **Run preprocessing**  
   - Open and run `01_data_preprocessing.ipynb` → produces `cleaned_heart_disease.csv`.

3. **Run PCA analysis**  
   - Open and run `02_pca_analysis.ipynb`.

4. **Run feature selection**  
   - Open and run `03_feature_selection.ipynb` → produces `selected_features.txt`.

5. **Run supervised learning**  
   - Open `04_supervised_learning.ipynb`.  
   - **Upload `selected_features.txt` when prompted**.  
   - The notebook will load the selected features and train models.

6. **Run unsupervised learning**  
   - Open `05_unsupervised_learning.ipynb`.  
   - **Upload `selected_features.txt` when prompted** if required.

7. **Run hyperparameter tuning**  
   - Open `06_hyperparameter_tuning.ipynb`.  
   - **Upload `selected_features.txt` when prompted**.  
   - The notebook will perform GridSearchCV/RandomizedSearchCV to optimize models.

8. **Final model**  
   - The best model will be saved in `models/final_model.pkl`.
