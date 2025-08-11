Project Summary

In this project, we aimed to optimize logistics processes using a supply chain dataset. The main objective was to develop machine learning models capable of predicting shipping costs and times, and to identify the factors that most influence these predictions.

Methodology

Data Analysis and Preprocessing: The dataset's structure was examined, and categorical variables (transportation modes, shipping carriers, etc.) were converted into numerical data using the One-Hot Encoding method.

Model Development and Comparison: Advanced regression algorithms, including Random Forest, XGBoost, and LightGBM, were trained to predict shipping costs and times.

Model Evaluation: Model performance was evaluated using metrics such as R-squared (R2) and Mean Absolute Error (MAE).

Findings and Results

Shipping Cost Prediction:

The RandomForestRegressor model yielded an R2 score of -0.43 and an MAE of 2.66.

The XGBoost Regressor model yielded an R2 score of -1.00 and an MAE of 3.12.

The LightGBM Regressor model yielded an R2 score of -1.35 and an MAE of 3.52.

Shipping Time Prediction:

The RandomForestRegressor model yielded an R2 score of -0.12 and an MAE of 2.22.

The XGBoost Regressor model yielded an R2 score of -0.42 and an MAE of 2.36.

The LightGBM Regressor model yielded an R2 score of -0.27 and an MAE of 2.22.

The low and negative R2 scores indicated that the current dataset is insufficient for accurately predicting shipping costs and times. This revealed that the limitation was not the complexity of the models, but the explanatory power of the data itself.

Key Takeaways and Next Steps

Despite the low model performance, feature importance analysis provided valuable insights:

The most influential factors on shipping costs were determined to be Production volumes and Price.

The most influential factor on shipping times was found to be Manufacturing lead time.

Based on these findings, the project concluded that to achieve more accurate predictions, the dataset needs to be enriched with additional data such as seasonality, fuel prices, and weather conditions. This approach demonstrates the critical thinking of a data analyst in evaluating a model's limitations and the data's capabilities.
