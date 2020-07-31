# PREDICTIVE ANALYSIS
Machine Learning: Predicting housing prices using advanced regression technique (Random Forest)

Tools: Phython (Numpy, Pandas, Seaborn, Matplotlib, Scikit -learn)

Data Source: Kaggle (training/test data) <br />
<br />
<br />
**CONTENT**
- Exploratory Data Analysis
- Data Cleaning
- Feature Engineering
- Model Building
- Prediction / Accuracy<br /><br />

**EXPLORATORY DATA ANALYSIS**<br />
This is aimed at understanding the dataset. By visualizing the features we can make assumptions on features that could likely influence housing prices. On face value I selected the following features to most likely influence housing prices
- Basement, lot and garage size
- Type of utilities available
- Neighbourhood
- Overall quality/condition of house
- Year built
- Sale type<br />

![](Image/Correlation.png)

Visualizing the correlation between the numerical features and sales price using a correlation plot, I observed 10 numerical variables with a correlation of at least 0.5 with saleprice.
