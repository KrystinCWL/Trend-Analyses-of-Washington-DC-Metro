# Trend-Analyses-of-Washington-DC-Metro
Analyze and predict the public DC WMATA Metro Average Ridership.

## Team members
Chen-Wei Lee, 
I-Hsien Chen, 
Shuo-An Wu, 
Bei-Yu Xing


## Goal
This is a data analytics team project we did for the 2025 Info Challenge, a one-week competition aimed to expose students in real-life problems, held by EY and UMD.
The main goal of the project is to analyze the public DC WMATA Metro Average Ridership data to analyze trends across a time period across different stations. Perform exploratory data analysis to find trends, patterns, outliers, etc. and see if teams can formulate guesses on why those trends or outliers happened.

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
Federal Transit Administrationhttps://www.transit.dot.gov/ntd/data-product/monthly-module-adjusted-data-release
<img width="1213" height="130" alt="image" src="https://github.com/user-attachments/assets/43bc59c1-7c38-4e75-8861-8a81afa848e0" />

