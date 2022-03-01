# Python: Personal-Loan-Analysis



## Project Description

- This project is created with the intension to find out which factor causes clients to accept a personal loan from the bank. 
- We found out that an individual's annual income and the number of family members are the most important factors
- The dataset can be obtain from Kaggle.
- The libraries used in project include: pandas, Matplotlib, Seaborn, Plotly
- [Link to this Project](https://github.com/ewang58/Personal-Loan-Analysis/blob/master/Code/Finance_data_analysis.ipynb)



## Objectives

**Main Question**: What is the most influential factor to receive a personal loan?



## Data Cleaning and Organization

- Some nominal variables (such as "ID" and "Zip Code") are eliminated

- No missing data is found.

- Anomaly values (such as negative values in "Experience") are replaced with the mean

  ![outliers](Images/outliers.png)

- There is also a large number of outliers in "Income"

- Explore the Correlation in the attributes

  ![heatmap](Images/heatmap.png)

  ## Analyzing The Data

- Although there are more people with an "undergraduate" degree, the distribution of education level amongst people who receive a loan is relatively equivalent. 

  ![pie_education_level](Images/pie_education_level.png)

  ![bar_education_level](Images/bar_education_level.png)



- Most individuals who receive a personal does not hold any securities or bank deposits in their investment account

  ![pie_investment_type](Images/pie_investment_type.png)



- Most people with an higher income receives a loan

  ![credit_card_distribution](Images/credit_card_distribution.png)



- Individuals who have family size 3 or greater with a higher income between 100k to 200k are more likely to apply for a loan.

  ![catplot](Images/catplot.png)





## Interpreting the Results

- "Income" and "number of family member" has more correlation with personal loan.
- "Education level" and investments seem to have the least impact on an individual's decision on accepting the loan.
- Further investigation is needed to find the correlation between "income" and other factors such as "mortgage" or "CCAvg" etc.
- You can access the Jupyter [here](https://github.com/ewang58/Personal-Loan-Analysis/blob/master/Code/Finance_data_analysis.ipynb).





(**Back to Main**)[INSET_LINK]
