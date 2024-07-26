# Crop Yield Prediction

## Authors
- Aniket Sakhare 
- Atharva Tasare 
- Santosh Kakad

## Abstract
Agriculture plays a crucial role in the global economy, yet many agricultural regions remain underdeveloped due to insufficient technological integration. This project aims to improve agricultural productivity by predicting crop yields using machine learning techniques. We conducted a comparative analysis of various machine learning algorithms to identify the most accurate one for predicting crop yields.

## Introduction
Machine learning (ML) has revolutionized many industries by providing tools to learn from data and make predictions without explicit programming. This study explores the application of ML in agriculture, specifically focusing on predicting crop yields. By leveraging historical data, we aim to enhance strategic planning and decision-making in the agricultural sector.

## Methodology
### Data Composition and Preprocessing
The dataset used in this study spans from 1990 to 2013 and includes information on crop type, yield, average annual rainfall, pesticide usage, and average temperature. Data preprocessing involved cleaning the dataset and one-hot encoding categorical columns.

### Model Selection and Training
We evaluated the following machine learning models:
- Decision Tree Regressor (DT)
- XGBoost (XGB)
- K-Nearest Neighbors (KNN)
- Histogram Boosting (HB)
- Random Forest (RF)
- AdaBoost (ADB)

The dataset was split into training and testing sets with a 70-30 percentage split.

### Evaluation Metrics
Models were evaluated based on their accuracy, mean absolute error (MAE), mean squared error (MSE), root mean squared error (RMSE), and R² score.

## Results and Discussion
The table below summarizes the performance of each model:

| Model                         | Accuracy | MAE     | MSE     | RMSE    | R² Score |
|-------------------------------|----------|---------|---------|---------|----------|
| Histogram Gradient Boosting   | 0.813025 | 0.022416| 0.188349| 0.433992| 0.813025 |
| Decision Tree                 | 0.819743 | 0.014686| 0.181582| 0.426124| 0.819743 |
| XGBoost                       | 0.817762 | 0.017496| 0.183577| 0.428459| 0.817762 |
| Random Forest                 | 0.820164 | 0.014563| 0.181158| 0.425626| 0.820164 |
| AdaBoost                      | 0.829131 | 0.021894| 0.172125| 0.414880| 0.829131 |
| Gradient Boosting             | 0.840845 | 0.016341| 0.160325| 0.400406| 0.840845 |

## Conclusion
The comparative analysis highlights the effectiveness of Gradient Boosting and AdaBoost algorithms in predicting crop yields accurately. Future research will focus on integrating more diverse data such as remote sensing data, weather forecasts, and soil health indicators to refine these models further.

## References
- Bendre M. R., Thool R.C., Thool V. R. “Big Data in Precision Agriculture: Weather Forecasting for Future Agriculture” 1st International Conference on Next Generation Computing Technologies, 2015.
- Grajales D.F.P., Mosquera G.J.A, Mejia F., Piedrahita L.C., Basurto C. “Crop-Planning Making Smarter Agriculture With Climate Data” Fourth International Conference on Agro-GeoInformatics, 2015.
- Hemageetha N. “A survey on application of data mining techniques to analyze the soil for agricultural purpose” 3rd International Conference on Computing for Sustainable Global Development (INDIACom), 2016.

## Jupyter Notebook
The code for the crop yield prediction models and their evaluation can be found in the `yield_shap_paper.ipynb` Jupyter Notebook.

[View Jupyter Notebook](yield_shap_paper.ipynb)

