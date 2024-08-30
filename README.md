Multiple Regression:  Building more accurate prediction model for house price prediction. 
Initally, i tried multiple regression model 
Then i tried polynomial regression. It shows overfitting. 
To regularise the data, I  did lasso and ridge (L1 and L2 norm) 
Eventually i compared all model and suggest best predicting model based on MSE, R square value



Logistic Regression:  Dataset is about purchasing habit of Car with  variables such as age, salary, whether they purchased or not
From this model i can understand the target audience. 


Advance Regression: In my approach to predicting house prices in Ames, Iowa, I participated in a Kaggle-style competition that provided a dataset with 79 features. My objective was to build an accurate model using various machine learning techniques. I began with thorough exploratory data analysis (EDA) to understand the data, identifying key patterns through analysis of features, distributions, and correlations. I handled missing values using imputation strategies and removed features with excessive missing data. Additionally, I focused on feature engineering by creating new features, such as total square footage, and transforming categorical variables using one-hot encoding.

For modeling, I initially implemented a Random Forest Regressor, achieving a root mean squared error (RMSE) of 28,457. However, after tuning hyperparameters like the number of trees and maximum depth, the model's RMSE slightly worsened to 29,351, possibly due to overfitting. Recognizing the potential of Gradient Boosting, I applied this technique next, which performed better with an initial RMSE of 28,215. After further tuning, focusing on hyperparameters like learning rate and maximum depth, the Gradient Boosting model's RMSE improved significantly to 25,480, making it the top performer among the models I tested.

I also explored a deep learning approach by designing a neural network with several hidden layers, but the model produced a much higher RMSE of 187,780, indicating challenges such as overfitting or the unsuitability of neural networks for this tabular data. The Gradient Boosting Regressor ultimately proved to be the most effective model, and I used it for my final submission. This project reinforced the critical role of feature engineering and model tuning in machine learning, with ensemble methods like Gradient Boosting outperforming other approaches. The deep learning experience highlighted the need for further exploration, possibly with more advanced architectures or model stacking.
