This project develops a machine learning framework to predict the Air Quality Index (AQI) using meteorological factors and chemical pollutant data.
Utilizing a dataset of 5,000 observations, the research integrates advanced Exploratory Data Analysis, including skewness analysis and quantitative outlier detection via the Interquartile Range method.
A Decision Tree Regressor was implemented as the primary algorithm, supported by strategic feature engineering of a "PM Ratio" and ordinal encoding of categorical air quality levels. 
The model was optimized through hyperparameter tuning and evaluated using Mean Absolute Error (MAE) and R-squared ($R^2$) metrics to ensure high predictive accuracy. 
Results indicate that tree-based models effectively capture the non-linear threshold effects and skewed distributions inherent in environmental data. 
A comparative analysis with a Random Forest Regressor further validated the model's robustness and precision. 
Ultimately, this study provides a scalable and interpretable solution for real-time air quality monitoring and predictive environmental analytics.
