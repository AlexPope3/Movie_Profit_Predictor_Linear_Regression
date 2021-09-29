The goal of this project is to find the best determinants of box office revenue, and how those determinants are related to one another.





![OLS_stats](https://user-images.githubusercontent.com/86431477/135280161-ad1bcea6-5ed6-4ebd-a334-5511198fdd97.png)





To start exploring this goal, I created a simple linear regression model with my train data that shows the R-squared value and beta coefficients. The results likely mean that there isn’t an issue with overfitting, and the adjusted R-squared hasn’t really penalized for the number of features selected. The beta coefficients represent a change in the target variable for a one unit increase in each of the features.  
