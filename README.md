# F1-Prediction
### ML Project Update 2

#### Team Members:
- Ashutosh Malla
- Bharath Radhakrishnan
- Punnam Satpathy

#### Project Description:
The F1-Prediction project aims to predict the final positions of the entire grid in Formula 1 races using machine learning algorithms. We trained multiple regression models and evaluated their performance using Root Mean Squared Error (RMSE). Here are the models along with their RMSE scores:

- Support Vector Regressor: RMSE = 12.30
- Random Forest Regressor: RMSE = 4.12
- Gradient Boosting Regressor: RMSE = 4.12
- Random Forest Regressor with Randomized SearchCV: RMSE = 3.89
- Neural Network: RMSE = 5.34

Based on these results, the Random Forest Regressor with Randomized SearchCV showed the lowest RMSE, indicating its superior performance in predicting the final positions of the F1 grid. 

#### Project Structure:

- Data Collection: We collected data from the Ergast API, which provides historical Formula 1 data.
- Data Preprocessing: We cleaned the data, handled missing values, and created new features for model training.
- Model Training: We trained multiple regression models using the preprocessed data.
- Model Evaluation: We evaluated the models using RMSE and selected the best-performing model.

#### Notebooks:

- F1_EDA.ipynb: This notebook contains the exploratory data analysis (EDA) of the Formula 1 dataset.
- F1_NN_Model.ipynb: This notebook contains the neural network model for predicting F1 grid positions.
- F1_ALL_Models.ipynb: This notebook contains Support Vector Regressor, Random Forest Regressor, Gradient Boosting Regressor, Random Forest Regressor with Randomized SearchCV for predicting F1 grid positions.
