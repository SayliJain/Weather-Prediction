# Weather-Prediction
Earth Observation using ML to Analyze Satellite Data to Monitor and Predict Weather Patterns, Natural Disasters and Climate Change

# Earth Observation using ML to Analyze Satellite Data to Monitor and Predict Weather Patterns, Natural Disasters and Climate Change

## **Abstract**
This research explores the application of machine learning techniques, including linear regression, decision trees, and random forests, for weather prediction using satellite data. The study aims to enhance weather forecasting accuracy, contributing to informed decision-making and supporting efforts to mitigate natural disasters and climate change impacts. The methodology involves preprocessing satellite data and employing machine learning algorithms for model training and testing.

## **Introduction**
Machine learning algorithms applied to Earth observation satellite data enable monitoring and prediction of weather patterns, natural disasters, and climate change. Historical weather factors inform accurate predictions, capturing long-term climate variations and influencing atmospheric conditions and precipitation formation.

## **Dataset Definition:**
The dataset spans the last 10 years, containing values like minimum and maximum temperatures, UV indices, sunrise, sunset, moonrise, moonset, heat index, dew point, etc. Feature selection is based on correlation with the target variables: MaxTempC, HeatIndexC, uvIndex1, FeelsLikeC, and WindchillC.

## **Software/Libraries**
Utilized modules include NumPy, Pandas, Scikit-learn, Matplotlib, and Seaborn for data manipulation, analysis, training, and visualization.

## **Model Creation**
Linear regression predicts continuous values, decision trees use a tree-like structure for decisions, and random forests combine multiple decision trees for more accurate predictions.

## **Experimentation**
Evaluation metrics include Variance Score, Mean Absolute Error (MAE), Residual Sum of Squares, and R2 Score. Linear regression, DecisionTreeRegressor, and RandomForestRegressor models are trained and tested, with tree-based models outperforming linear regression.

## **Conclusion**
Decision trees are deemed the most suitable algorithm for large-scale implementation in weather forecasting due to their accuracy, balancing complexity and time efficiency compared to linear regression and random forests.
