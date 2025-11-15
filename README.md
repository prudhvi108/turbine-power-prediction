
 Turbine Power Output Prediction
 Project Overview: 

This project focuses on predicting turbine power output using machine learning regression models.
By analyzing sensor and operational data, the goal is to understand how various turbine parameters affect performance and help improve power generation efficiency.

Objectives:

Perform Exploratory Data Analysis (EDA) to identify key trends and relationships.

Build and compare multiple regression models (Linear Regression, Random Forest, and MLP Regressor).

Evaluate models using metrics like R² Score and Root Mean Squared Error (RMSE).

Visualize model performance and important features influencing power output.

Dataset Description:
Each row represents turbine sensor data captured over time.

Key Features:
 `wind_speed_raw`: Measured wind speed  
 `ambient_temperature`: Temperature outside the turbine  
 `generator_speed`: Rotational speed of the turbine generator  
 `nacelle_temp`: Internal turbine compartment temperature  
 `active_power_raw`: Measured turbine output (target variable: `Target`)  


Tech Stack:

Programming Language: Python

Libraries: 

• Pandas 
• Scikit-learn 
• Matplotlib 
• RandomForest 
• MLP Regressor

Techniques: Regression Modeling, Feature Engineering, Data Visualization

Environment: Jupyter Notebook

Workflow:

Data Loading and Cleaning

Imported the dataset and checked for missing values or inconsistencies.

Exploratory Data Analysis (EDA)

Used statistical summaries and visualizations (pairplot, heatmap) to understand relationships between variables.

Feature Engineering

Selected relevant features for prediction.

Scaled features where required.

Model Building

Implemented Linear Regression, Random Forest, and MLP Regressor models using Scikit-learn.

Model Evaluation

Compared model performance using R² Score and RMSE.

Random Forest performed best with an R² value of approximately 0.89.

Results Summary :
Model	R² Score	RMSE
Linear Regression	0.84	2.76
Random Forest	0.89	2.10
MLP Regressor	0.86	2.45

Visualizations:
vizualized Predicted vs Actual plot.
<img width="531" height="547" alt="ACTUAL VS PREDICTED" src="https://github.com/user-attachments/assets/66f7ebe4-2483-4edd-982f-96ab3edf0647" />

vizualized Feature Importance.
<img width="966" height="528" alt="FEATURE IMPORTANCE" src="https://github.com/user-attachments/assets/188103a2-99c0-45d6-b7bc-c60b5c4e8537" />


Key Insights:

Random Forest outperformed other models, providing the highest accuracy.

Features like ambient temperature, wind speed, and generator speed were most influential.

The model can help industries improve turbine efficiency through predictive analysis.

---

How to Run: 

Clone this repo and open `Turbine_Power_Prediction.ipynb` in Jupyter or Colab.


