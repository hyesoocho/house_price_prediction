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

Homeowners might consider renovations to increase their home’s value before selling. The analysis canprovide which home improvements add the most value in general. Of course, the range of renovation can bediverse depending on the scope of work. According to HomeWorx, the range of kitchen remodel costs canbe as little $5,000 to $40,000+ in Iowa. Based on the analysis, remodeling a kitchen may or may not be agood investment if the condition is average because kitchen in average condition can decrease house value byabout $2,000 on average, whereas kitchen in excellent condition can increase house value by about $20,000 onaverage. Also, in terms of overall quality, the house price increases by $27,609 from very good (level 8) toexcellent (level 9) and increases by $11,094 from excellent (level 9) to very excellent (level 10).Lastly, the house that has very excellent overall quality, kitchen quality, and pool quality with Wood Shinglesroof material, 100+ inches height of the basement, and proximity to the Northridge neighborhood wouldreceive the highest house price. 

It would be interesting to develop more generalizable regression models of predicting house prices by addingadditional variables, such as latitude, longitude and weather.27
