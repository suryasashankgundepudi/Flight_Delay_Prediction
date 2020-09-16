# Flight_Delay_Prediction
Flight scheduling has been a problem since the dawn of airtravel  and  is  something  that  airline  companies  wish  to  tackle.  For  anairport to be able to schedule the flights such that they reach on time,they must be able to tell if the flight will arrive on time or not. A flightis  said  to  be  delayed  if  the  flight  either  takes  off  or  arrives  later  thanthe scheduled time. This Project predicts whether if the flight will arrivedelayed or not, after the flight’s departure, and if the flight is classifiedas arriving late, then the arrival delay in minutes is predicted.

## Notebooks 

[1. Data-Preprocessing, processing the flight data](https://github.com/GV-9wj/Flight_Delay_Prediction/blob/master/Datapreprocessing1_Flight_Data.ipynb)

[2. Data-Preprocessing, processing the weather data](https://github.com/GV-9wj/Flight_Delay_Prediction/blob/master/Datapreprocessing2_Weather_Data.ipynb)

[3. Data-Preprocessing, merging the flight data and weather data](https://github.com/GV-9wj/Flight_Delay_Prediction/blob/master/Datapreprocessing3_Merging_Data.ipynb)

[4. Classification- Predicting if the flight will be delayed or not](https://github.com/GV-9wj/Flight_Delay_Prediction/blob/master/Classification_Delayed_or_Not.ipynb)

[5. Regression- Predicting the number of minutes by which a flight will be delayed](https://github.com/GV-9wj/Flight_Delay_Prediction/blob/master/Prediction_in_Minutes.ipynb)

[6. Using results from a Classifier for Regression](https://github.com/GV-9wj/Flight_Delay_Prediction/blob/master/Classification_And_Regression_Using_XGBOOST.ipynb)

[7. Regression for Ranges- Predicting the number of Minutes by which the flight will be delayed for various ranges](https://github.com/GV-9wj/Flight_Delay_Prediction/blob/master/Regression_For_Ranges.ipynb)

### Installation Requirements
1. jupyter
2. pandas
3. numpy
4. matplotlib
5. seaborn
6. sklearn
7. xgboost
8. imblearn
9. SciPy
10. scikit-learn

Use the following code to install the required packages
```python 
pip install -r requirements.txt
```

### Classification models and algorithms used:
1. Logistic regression 
2. Random Forest
3. Extra trees
4. Decision Trees
5. Gradient Descent 
5. XGBoost

## Regressors used in the Prediction file
1. Linear Regressor
2. Extra Trees Regressor
3. XGBoost Regressor
4. Random Forest Regressor

