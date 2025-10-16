# Trend-Analyses-of-Washington-DC-Metro
Analyze and predict the public DC WMATA Metro Average Ridership.

## Team members
Chen-Wei Lee, 
I-Hsien Chen, 
Shuo-An Wu, 
Bei-Yu Xing

## Goal
<img width="168" height="168" alt="image" src="https://github.com/user-attachments/assets/ddc11ed7-5352-4322-bab0-b4db25d54e39" /> 
<img width="168" height="168" alt="image" src="https://github.com/user-attachments/assets/661b03f1-2ddd-4ac3-a325-43c900e11b49" />
<img width="131" height="168" alt="image" src="https://github.com/user-attachments/assets/9999da34-d36d-400b-9c3a-7452232d5d39" />
<img width="993" height="92" alt="image" src="https://github.com/user-attachments/assets/31a278d9-8c83-49ff-b057-f6a4ad581825" />


This is a data analytics team project we did for the 2025 Info Challenge, a one-week competition aimed to expose students to real-life problems, held by EY and UMD.
The main goal of the project is to analyze the public DC WMATA Metro Average Ridership data and predict future trends, providing useful suggestions for the WMATA operation and revenue.

## Steps
See the data preparation process, EDA, modeling, and final report individually here on GitHub.

## Modeling & Machine Learning Pipeline
| Model                                | Key Notes                        | Performance Highlights                                                        |
| ------------------------------------ | -------------------------------- | ----------------------------------------------------------------------------- |
| **GaussianNB**                       | Baseline model                   | Fast but limited accuracy                                                     |
| **SVM (Support Vector Machine)**     | Handled nonlinear boundaries     | Significantly improved classification, especially for “Standard” credit users |
| **Logistic Regression**              | Added interpretability           | Used for gain & lift analysis                                                 |
| **Decision Tree**                    | Transparent decision paths       | Useful for feature interpretation                                             |
| **Random Forest / Bagging Ensemble** | Best generalization & robustness | Achieved **~75% accuracy** and **F1-score ≈ 0.75**                            |

## Data Source
WMATA Ridership Data Portal
https://www.wmata.com/initiatives/ridership-portal/

Federal Transit Administration
https://www.transit.dot.gov/ntd/data-product/monthly-module-adjusted-data-release

Weather API by Visual Crossing
https://www.visualcrossing.com/weather-api/


