Overview:-
This project focuses on building an end-to-end sales forecasting solution for Rossmann Pharmaceuticals, which operates retail stores across various cities. 
The goal is to forecast daily sales up to six weeks in advance using machine learning and deep learning approaches, and to deploy the solution via a web interface

Learning Outcomes:-
End-to-end ML lifecycle: EDA → Modeling → Deployment
Use of Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, TensorFlow/PyTorch
Code modularization, logging, serialization, MLOps (MLFlow, DVC)
Web development using Flask or Streamlit
Deployment on Heroku or equivalent platform

 Exploratory Data Analysis:-
Analyze customer behavior using plots and statistical summaries.
Key questions explored:
How do promos, holidays, and store types affect sales?
Are there seasonal trends (e.g., Christmas/Easter)?
What’s the relationship between customer count and sales?
How does competition affect store performance

 Data Preprocessing:-
Convert dates to features: weekdays, holidays, month parts
Handle missing values
Feature scaling (StandardScaler)

 Model Building (Sklearn Pipelines):-
Train tree-based regressors (e.g., Random Forest)
Use pipelines for modularity

 Loss Function:-
Choose and justify a suitable regression loss function (e.g., RMSE)

 Post-Prediction Analysis:-
Feature importance analysis
Estimate confidence intervals

 Deep Learning Model (LSTM):-
Transform sales data into a time-series supervised format
Train LSTM model for forecasting
Ensure data stationarity and windowing

MLOps Integration:-
Use MLFlow to track experiments and serve predictions

 Technologies Used:-
Languages & Libraries: Python, Pandas, NumPy, Sklearn, TensorFlow/PyTorch, Matplotlib, Seaborn
ML Tools: MLFlow, DVC
Web: Flask or Streamlit, HTML/CSS


