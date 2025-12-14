🎵 Spotify Song Popularity Prediction
📌 Project Overview

This project builds a machine learning regression model to predict the popularity score of songs using Spotify audio features and metadata. The dataset is sourced from Spotify’s public API and includes tracks from 2009 to 2025, covering both classic and contemporary music.

The goal is to understand what makes a song popular and build a robust predictive model with explainability.

📊 Dataset Description

The dataset contains track-level information, including:

Audio features (danceability, energy, loudness, tempo, etc.)

Song metadata

Artist and album-related attributes

Target variable: song popularity score

⚙️ Libraries & Tools Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

SHAP

Joblib

🔍 Project Workflow
1️⃣ Importing Libraries

All required data processing, visualization, modeling, and explainability libraries are imported.

2️⃣ Data Loading

The Spotify dataset is loaded into a Pandas DataFrame for analysis.

3️⃣ Data Cleaning

Handling missing values

Removing inconsistencies

Ensuring correct data types

4️⃣ Exploratory Data Analysis (EDA)

Distribution analysis of features

Correlation analysis

Identifying important attributes influencing popularity

5️⃣ Data Preparation

Numerical feature scaling using StandardScaler

Categorical feature encoding using OneHotEncoder

Combined using ColumnTransformer

Pipeline-based preprocessing

6️⃣ Train-Test Split

Data split into training and testing sets using train_test_split

7️⃣ Model Training

The following regression models are trained and compared:

Linear Regression

Random Forest Regressor

XGBoost Regressor

8️⃣ Model Evaluation

Model performance evaluated on test data

Best-performing model selected based on predictive accuracy

9️⃣ Model Explainability

SHAP (SHapley Additive exPlanations) used to:

Interpret feature importance

Understand model predictions

Generate summary plots

🔟 Model Saving

Best model saved using Joblib

Stored at:

models/best_model.pkl

🏆 Key Outcomes

XGBoost achieved the best predictive performance

SHAP analysis revealed the most influential audio features affecting song popularity

End-to-end ML pipeline implemented with preprocessing, modeling, and explainability

🚀 Future Enhancements

Classification-based popularity buckets

Time-series trend analysis

Genre-specific popularity prediction

Deployment using Streamlit or Flask

📌 Author

Rijul Jamwal
Data Science & Machine Learning Enthusiast
