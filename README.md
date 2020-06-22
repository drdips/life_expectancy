# Can we predict life expectancy?

### Introduction
In this project, data was gathered from kaggle to help gain an insight into life expectancy. There are many factors that can effect the length of a person's life. This information will hopefully help guide policymakers to make changes to help increase the life expectancy of their people.

### Questions
- What factors have the most influence on Life Expectancy?
- Can we predict how long a person will live on average?
- How does obesity relate to life expectancy?

### Process
1) See **data_cleaning_engineering.ipynb**: This file contains the seperate data files obtained through Kaggle. The data was sorted through, analyzed, cleaned and concatted into one.
2) See **data_visualization.ipynb**: To see how the data looked, a of hypothesis testing were ran and graphed.
3) See **regression_analysis.ipynb**: Lastly, used linear regression techniques to create the most accurate model into predicting life expectancy.

## Libraries

* Data Cleaning and Visualization:
  * Matplotlib
  * Seaborn
  * Plotly
  * Pandas
  * SkLearn
  * Statsmodels

## Findings
Through data analysis, factors such as Schooling, Obesity, Alcohol Consumption, Immunization, Percentage Expenditure, and country had the highest impact in predicting life expectancy with a Root Mean Squared Error of only 0.25 Standard deviation. This is important because policy makers can take these findings and create changes in the law to better serve their people. 
  * Schools should be made more accessible and more prevalent.
  * Countries who have a lower life expectancy should increase their healthcare expenditure in order to improve its average lifespan.
  * Governments should allocate more budget into physical and mental health to help increase life expectancy and quality of life.
