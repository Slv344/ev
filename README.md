# ev
# This analysis provides valuable insights for stakeholders in the used car industry.
# Data Collection and Preprocessing:
-->The dataset used for this analysis contains information about various used cars, including features like year, mileage, fuel type, seller type, transmission type, and more.
# EDA phase 
-->The distribution of car prices is right-skewed, with a few high-value outliers.
-->The majority of cars are fueled by diesel and are sold by individuals.
-->Manual transmission cars are more common than automatic.
-->Mileage, year, and fuel type appear to be significant factors affecting car prices.
# Machine Learning Models:
-->We applied multiple regression models to predict used car prices.
-->Linear Regression provided a baseline model, while Decision Tree, Random Forest were used to improve predictive accuracy.
-->Random Forest Regression outperformed other models with the lowest Mean Squared Error (MSE) and the highest R-squared (R2), indicating a good fit to the data.
# Cluster Analysis:
-->K-means clustering segmented the used car market into distinct clusters based on key features such as mileage, year, price and many more.
Cluster 0:
Contains cars with relatively good mileage (average of 23.51 km/l).
Engine capacities are moderate.
Maximum power output is decent.
Selling prices are in the mid-range.
Cluster 1:
Contains cars with relatively lower mileage (average of 14.29 km/l).
Engine capacities are higher, suitable for SUVs and larger vehicles.
Maximum power output is high.
Selling prices are relatively higher.
Cluster 2:
Contains cars with exceptional mileage (average of 42 km/l).
Engine capacities are in the mid-range.
Maximum power output is high.
Selling prices are relatively higher.
Cluster 3:
Contains cars with moderate mileage (average of 18.32 km/l).
Engine capacities are relatively low.
Maximum power output is decent.
Selling prices are in the mid-range.
# In terms of mileage, Cluster 2 contains cars with the best mileage, averaging 42 km/l. Cluster 0 also has decent mileage, averaging 23.51 km/l. Cluster 3 has moderate mileage, averaging 18.32 km/l, while Cluster 1 has relatively lower mileage, averaging 14.29 km/l.
# So, if you prioritize fuel efficiency and better mileage, cars in Cluster 2 would be the top choice.
