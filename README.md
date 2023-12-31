## End to End Data Science Project

In this project, I applied all the pipeline of Data Science Project.

### Data Ingestion --> Data Transformation --> Model Trainer --> Model Evaluation --> Deployement --
 
1. Git and Githup repository setup
2. Project setup
3. Requirement.txt
4. Dockerfile
5. Data Version Control (DVC)
6. Integrating With MLFLOW And Dagshub

In this we applied following model:
Linear Regression
Model performance for Training set
- Root Mean Squared Error: 5.3243
- Mean Absolute Error: 4.2671
- R2 Score: 0.8743
----------------------------------
Model performance for Test set
- Root Mean Squared Error: 5.3960
- Mean Absolute Error: 4.2158
- R2 Score: 0.8803
===================================


Lasso
Model performance for Training set
- Root Mean Squared Error: 6.5938
- Mean Absolute Error: 5.2063
- R2 Score: 0.8071
----------------------------------
Model performance for Test set
- Root Mean Squared Error: 6.5197
- Mean Absolute Error: 5.1579
- R2 Score: 0.8253
===================================


Ridge
Model performance for Training set
- Root Mean Squared Error: 5.3233
- Mean Absolute Error: 4.2650
- R2 Score: 0.8743
----------------------------------
Model performance for Test set
- Root Mean Squared Error: 5.3904
- Mean Absolute Error: 4.2111
- R2 Score: 0.8806
===================================


K-Neighbors Regressor
Model performance for Training set
- Root Mean Squared Error: 5.7077
- Mean Absolute Error: 4.5167
- R2 Score: 0.8555
----------------------------------
Model performance for Test set
- Root Mean Squared Error: 7.2530
- Mean Absolute Error: 5.6210
- R2 Score: 0.7838
===================================


Decision Tree
Model performance for Training set
- Root Mean Squared Error: 0.2795
- Mean Absolute Error: 0.0187
- R2 Score: 0.9997
----------------------------------
Model performance for Test set
- Root Mean Squared Error: 7.8237
- Mean Absolute Error: 6.1800
- R2 Score: 0.7485
===================================


Random Forest Regressor
Model performance for Training set
- Root Mean Squared Error: 2.2982
- Mean Absolute Error: 1.8239
- R2 Score: 0.9766
----------------------------------
Model performance for Test set
- Root Mean Squared Error: 5.9403
- Mean Absolute Error: 4.6515
- R2 Score: 0.8550
===================================


XGBRegressor
Model performance for Training set
- Root Mean Squared Error: 1.0073
- Mean Absolute Error: 0.6875
- R2 Score: 0.9955
----------------------------------
Model performance for Test set
- Root Mean Squared Error: 6.4733
- Mean Absolute Error: 5.0577
- R2 Score: 0.8278
===================================


CatBoosting Regressor
Model performance for Training set
- Root Mean Squared Error: 3.0427
- Mean Absolute Error: 2.4054
- R2 Score: 0.9589
----------------------------------
Model performance for Test set
- Root Mean Squared Error: 6.0086
- Mean Absolute Error: 4.6125
- R2 Score: 0.8516
===================================


AdaBoost Regressor
Model performance for Training set
- Root Mean Squared Error: 5.8692
- Mean Absolute Error: 4.7894
- R2 Score: 0.8472
----------------------------------
Model performance for Test set
- Root Mean Squared Error: 6.0892
- Mean Absolute Error: 4.7885
- R2 Score: 0.8476
===================================



MLFLOW_TRACKING_URI=https://dagshub.com/hitendrabhamare007/MLproject.mlflow \
MLFLOW_TRACKING_USERNAME=hitendrabhamare007 \
MLFLOW_TRACKING_PASSWORD=6fb58986df5f9fbcd93a5a728140cca62fd81cd6 \
python script.py
