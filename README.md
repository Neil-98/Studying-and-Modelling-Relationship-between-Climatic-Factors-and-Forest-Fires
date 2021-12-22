# Studying-and-Modelling-Relationship-between-Climatic-Factors-and-Forest-Fires
https://www.kaggle.com/rtatman/188-million-us-wildfires and https://www.kaggle.com/econdata/climate-change datasets are explored and analysis. Then, following pre-processing of the data (conversion of Julian dates to Gregorian, removal of samples with missing data, computing monthly frequency and average sizes of forest fires, subsetting the two dataset on the basis of overlapping years, removal of all but one climatic factor with high correlation), a linear model and a random forest model are fit to the joint data. The results indicate that the linear model outperforms the random forest model. Also, accounting for the fact that 88% of fires are caused by humans (discovered during data exploration), the linear model's adjusted R-squared result of linear model, equaling 0.3022, indicating that 30.22% of the variation in the observed samples can be explained by the independent variables, is satisfactory.
