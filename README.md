### House price prediction in Iowa from Kaggle using machine learning in R
- Predicted house prices based on analysis of 79 variables that describe aspects of housing using advanced regression in R
- Conducted exploratory data analysis (univariate analysis of outcome and explanatory variables and visualization)
- Evaluated missing data and mechanisms of missingness
- Performed data cleaning and handled multicollinearity issues
- Created training block and test block by randomly splitting the samples from the training dataset into two blocks to validate the model's accuracy
- Built Random Forest and Lasso models to identify statistical significance of variables and to calculate each test error
- Utilized cross-validation to select appropriate values for tuning parameters for random forest
- Identified which method yields smaller test error and determined final model to fit model to the whole available data
- Demonstrated 10 important features that increase house price more than $10,000 to share insights to stakeholders

#### Executive summary
From the Kaggle data, Random Forest and Lasso were performed to predict house price given the features of the house based on analysis of 79 explanatory variables describing every aspect of the residual house in Ames, Iowa. Before fitting the model, I handled missing data and multicollinearity, and I split training data into two subsets to validate the model's accuracy. The test MSEs obtained using random forest and Lasso are 959,091,256 and 775,154,586, respectively. Thus, I used Lasso, which yields smaller test error and more concrete prediction, to predict house price. In conclusion, the important predictors in determining house price are the following: 

* OverallQual (overall material and finish quality
* Neighborhood (Physical locations within Ames city limits)
* PoolQC (Pool quality), 
* RoofMatl (Roof material)
* BsmtQual (Height of the basement)
* KitchenQual (Kitchen quality)

Specifically, in terms of overall quality, the house price increased by $27,609 from very good (level 8) to excellent (level 9) and increased by $11,094 from excellent (level 9) to very excellent (level 10). The house that has very excellent overall quality, kitchen quality, and pool quality with Wood Shingles roof material, 100+ inches height of the basement, and proximity to the Northridge neighborhood would receive the highest house price.

