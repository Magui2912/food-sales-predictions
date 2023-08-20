<p align = "center"> 
<img src = "https://github.com/Magui2912/food-sales-predictions/assets/135860668/aa72a565-8793-471e-a607-2534851868ef">
  </p>

# Sales Prediction
## Data Science Food sales prediction


### Business problem:

The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store.
Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

### Data Source
Data_sales_prediction 
https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/#About

### Data Dictionary
<p align = "center"> 
  <img src = "https://github.com/Magui2912/food-sales-predictions/assets/135860668/bac591c0-665f-43be-9e6e-e472d37c1927">
</p>


## To prepare this data, the data was cleaned, and the following processes were performed:

## Exploratory Data Analysis
- During the exploratory data analysis, a boxplot and histogram was visualized for each numeric datatype column. 
- Also, a barplot was visualized for each categorical column. 
- This gave a good baseline for all of the numeric and categorical columns for univariate EDA.
<p align = "center"> 
  <img src = "https://github.com/Magui2912/food-sales-predictions/assets/135860668/5031b890-7251-4431-ab2a-e73033b05c58">
</p>
### This histogram shows that are the majority of the weight product are around 12.5


#### Histogram for The percentage of total display area of all products in a store allocated to the particular product
![téléchargement (3)](https://github.com/Magui2912/food-sales-predictions/assets/135860668/18a90f8c-6696-4e42-8605-6e64dc7e5485)

### This histogram shows that are the our percentage visibility between 0 and 0.05

#### multivariate Visualization
![téléchargement (5)](https://github.com/Magui2912/food-sales-predictions/assets/135860668/d9bf68db-3c4a-41c4-9249-f00cfeaad451)

### We interpret here that 'low fat' used in this data in relation to 'regular' in the column


## Model

Based on the provided training and testing scores for the three models (Linear Regression, High Variance Decision Tree, and Random Forests), it appears that the Random Forests model is the most suitable choice for your dataset. Here's the justification for this recommendation:

Performance Metrics:


When comparing the testing scores of the models, the Random Forests model performs better than the other two models in terms of Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) values. Lower MAE, MSE, and RMSE values indicate better predictive accuracy, while a higher R2 value indicates a better fit of the model to the data. The Random Forests model has the lowest MAE, MSE, and RMSE values, as well as the highest R2 value among the models.

Overfitting:


The High Variance Decision Tree model shows a sign of overfitting, as evidenced by the large discrepancy between the training and testing scores. The model has almost perfect scores on the training data (MAE: 0.00, MSE: 0.00, RMSE: 0.00, R2: 1.00), but the testing scores are much worse (MAE: 1051.16, MSE: 2,268,578.46, RMSE: 1506.18, R2: 0.18). This suggests that the model doesn't generalize well to unseen data, which is a common issue with high variance models like decision trees.

Random Forests Model Performance:


The Random Forests model strikes a balance between bias and variance by aggregating multiple decision trees. This ensemble approach tends to improve generalization and reduce overfitting compared to individual decision trees. The Random Forests model has notably better testing scores than the High Variance Decision Tree model, indicating that it's able to capture more complex relationships in the data without overfitting to noise.

Conclusion:

In conclusion, based on the provided information, the Random Forests model is recommended due to its better predictive performance on the testing data and its ability to mitigate overfitting compared to the High Variance Decision Tree model. However, keep in mind that the choice of the model also depends on the specific characteristics of your dataset and the goals of your analysis, so further experimentation and evaluation might be necessary to make a final decision.








For any additional questions, please contact **email**
