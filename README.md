# kaggleHousePrices
This is my first attempt at tackline any Kaggle project so I went with their entry level one. The goal is to predict house sale prices based on a variety of property features

## Project overview
- #### Initial Approach
Started with LinReg as a simple baseline model. Natural first step since its easy to implement however its performance was limited due to the comlexity of the data
- #### Random Forest
Switched to random forest since it handles non linearities and interactions well. After encoding categorical variables and tuning hyperparams via gridsearchCV, the models RMSE improved significantly
- #### Final Approach
The tuned Random Forest gave a much better validation scor. I used this model to create preds on the test set and submitted to kaggle as my final attempt for the project

[Kaggle House Price](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview)
