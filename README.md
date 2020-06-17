## House price prediction in Iowa from Kaggle
- Predicted house prices based on analysis of 79 variables that describe aspect of house using advanced regression in R
- Conducted exploratory data analysis (univariate analysis of outcome and explanatory variables and visualization)
- Evaluated missing data and mechanisms of missingness
- Performed data cleaning and handled multicollinearity issues
- Created training block and test block by randomly splitting the samples from the training dataset into two blocks to validate the model's accuracy
- Built Random Forest and Lasso models to identify statistical significance of variables and to calculate each test error
- Utilized cross-validation to select appropriate values for tuning parameters for random forest
- Identified which method yields smaller test error and determined final model to fit model to the whole available data 
- Demonstrated 10 important features and effects of each price change to share insights and recommendations to stakeholders 

## Executive summary
Based on the Kaggle data, Random Forest and Lasso were performed to predict house price given the features of the house based on analysis of 79 explanatory variables describing every aspect of residual house in Ames, Iowa. Before fitting the model, missing data and multicollinearity were handled, and I split trainning data into two subsets to validate the model's accuracy. The test MSEs obtained using random forest and Lasso are 959,091,256 and 775,154,586, respectively. Thus, I used Lasso to predict house price. In conclusion, OverallQual (overall material and finish quality), Neighboorhood (Physical locations within Ames city limits), PoolQC (Pool quality), RoofMatl (Roof material), BsmtQual (Height of the basement), and KitchenQual (Kitchen quality) were important predictors in determining house price. Specifically, in terms of overall quality, the house price increased by $27,609 from very good to excellent and increased by $11,094 from excellent to very excellent. The house that has very excellent overall quality, kitchen quality, and pool quality with Wood Shingles roof material, 100+ inches height of the basement, and close to Northridge negihboorhood would get the highest house price. 
