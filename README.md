# Boston-housing-price
Project Summary: Prediction of Housing Prices in Boston Suburbs
Overview
The project aims to predict the housing prices in the suburbs of Boston using regression models, leveraging socio-economic and geographical data. The analysis involves several steps, including exploratory data analysis, feature selection, model comparison, and optimization.

Key Steps and Findings
Exploratory Data Analysis (EDA):

The Boston Housing Dataset consists of 506 observations and 14 attributes.
Key attributes include crime rate, residential land zoning, number of rooms, age of houses, and more.
The distribution of the target variable, median house value (MEDV), shows a concentration around $20,000 to $25,000, with a noticeable peak at $50,000 indicating potential data censorship.
Feature Selection:

Important features for predicting house prices include the average number of rooms (RM), percentage of the population with low socio-economic status (LSTAT), and pupil-teacher ratio (PTRATIO).
These features were selected based on their significant correlations with the target variable.
Model Comparison:

Various regression models were tested, including Linear Regression, Lasso, Ridge, Decision Trees, and ensemble methods like Random Forest, Gradient Boosting, and Extra Trees.
Ensemble methods, particularly ExtraTreesRegressor and RandomForestRegressor, showed superior performance with lower Mean Squared Error (MSE).
Model Optimization:

Hyperparameter tuning using GridSearchCV improved the performance of the RandomForestRegressor significantly.
The optimized model demonstrated a considerable reduction in prediction error.
Results:

The ExtraTreesRegressor achieved the best performance with an MSE of 6.370.
The optimized RandomForestRegressor also showed strong performance with an MSE of 7.216.
GradientBoostingRegressor, while effective, had a higher MSE compared to the other two.
Conclusions:

Ensemble methods are highly effective for predicting housing prices due to their ability to handle complex, non-linear relationships.
Optimization of hyperparameters is crucial for enhancing model performance.
Selected features (RM, LSTAT, PTRATIO) are significant predictors of house prices in Boston suburbs.
Future Work:

Exploring more advanced models like neural networks and incorporating additional data sources such as local economic conditions and infrastructure details could further improve predictions.
Practical applications of these models include real estate analysis, policy-making, and investment decision support.
Practical Implications
The developed models can assist stakeholders in making informed decisions in real estate investments and urban planning, providing insights into the factors influencing housing prices in Boston suburbs. The project highlights the value of machine learning techniques in predictive modeling within the real estate sector.
