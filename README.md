# CryptoClustering
Module 19 Challenge
_____________________________________________

## Summary:

Anayzed Crypto currency markert changes over different time frames. Used K means clustering to group the data.

_____________________________________________


## Procedure:

Normalized the data using StandardScaler().

Found the best k value for the data using the elbow method. 

Fit the model with the data with k value of 4 and then made predictions for the segmentations.

Made a scatter plot of the results with the predicted clusters. 

Optimized the clusters with PCA. 

_____________________________________________


## Analysis

Optimal k value for normalized data and data after using PCA was 4. There were no differences in the elbow plot besides the elbow for the PCA inertia's having a lower y-intercept. 

The k means algorithm made the same predictions for the normalized data and the data after being treated with PCA. In this case, it did not make a difference to collapse some of the axes. 