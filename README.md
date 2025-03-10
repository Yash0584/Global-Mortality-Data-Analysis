# Global-Mortality-Data-Analysis

**1. Data Exploration and Preprocessing:**
 * The dataset included mortality rates for various causes across different countries and years.
 *  Missing value analysis was performed, though no missing values were found in the selected data.
 * The user selected a specific country and disease for analysis.

**2. Model Training and Evaluation:**
* A linear regression model was trained to predict mortality rates based on the year.
* Model performance was evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.  The provided metrics (MAE, MSE, R^2) quantify the model's accuracy in predicting the chosen disease's mortality rate based on the year.  A higher R^2 value suggests a better fit of the linear model to the data.
* The model's performance varies depending on the selected country and disease.
* A scatter plot of the actual vs. predicted values for both training and testing sets visualized model fit.
* The model provides a predicted value for a user-specified future year.  The reliability of predictions for future years is limited by the model's accuracy and the assumption of linear progression.
  
**3.Country-wise Mortality Rate Comparison:**
* Line plots compared mortality rates across different countries for selected causes.  Visual comparison allows for quick identification of trends and differences in mortality across nations.
* This analysis helps highlight variations in mortality trends among different countries.

**4. Correlation Analysis:**
* Correlation heatmaps visualized relationships between different causes of mortality within each country.  Correlation coefficients indicate the strength and direction of linear relationships between different mortality rates.
*  Insights into how various mortality causes relate to one another within a given country can be gained from these heatmaps.  For example, a strong positive correlation might suggest similar underlying factors influence multiple mortality rates.
