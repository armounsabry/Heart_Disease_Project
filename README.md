# Heart Disease Prediction Project

## Project Overview
This project predicts the presence of heart disease using patient data. It includes:
- Data preprocessing and feature engineering
- PCA and feature selection
- Supervised and unsupervised learning models
- Hyperparameter optimization
- Streamlit web app for interactive predictions

## File Structure
Heart_Disease_Project/
│── data/ # Raw and processed datasets
│── notebooks/ # EDA, modeling, PCA, feature selection, tuning
│── models/ # Saved models and pipelines
│── ui/ # Streamlit app
│── deployment/ # Ngrok setup instructions
│── results/ # Evaluation metrics and plots
│── README.md
│── requirements.txt
│── .gitignore

## Requirements
Install dependencies using:
```bash
pip install -r requirements.txt



Preprocess the data and create pipeline:

python models/final_pipeline.py


Run the Streamlit app:

streamlit run ui/app.py


Optionally, expose via Ngrok (see deployment/ngrok_setup.txt).

Notebooks

01_data_preprocessing.ipynb – Clean and preprocess data

02_pca_analysis.ipynb – PCA and explained variance

03_feature_selection.ipynb – Feature selection (RFE, Chi-Square)

04_supervised_learning.ipynb – Train & evaluate models

05_unsupervised_learning.ipynb – KMeans & Hierarchical clustering

06_hyperparameter_tuning.ipynb – GridSearchCV & RandomizedSearchCV

Author

Fady Armoun


---

## **4️⃣ `requirements.txt`**

Minimum dependencies for your project:



pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
streamlit
scipy


*(You can also freeze versions after testing: `pip freeze > requirements.txt`.)*

---

## **5️⃣ `.gitignore`**

To avoid committing unnecessary files:


Python

pycache/
*.pyc
*.pyo
*.pyd
*.pkl

Jupyter

.ipynb_checkpoints/

Streamlit

.streamlit/
