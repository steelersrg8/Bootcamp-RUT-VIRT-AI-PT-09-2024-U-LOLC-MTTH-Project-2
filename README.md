## Table of Contents

1. [Project Overview](#Project-Overview)  
2. [Research Questions and Findings](#Research-Questions-and-Findings)
3. [Technologies Used](#Technologies-Used)  
4. [Installation and Usage](#Installation-and-Usage)  
5. [Analysis Results](#Analysis-Results)  
6. [Future Analysis Considerations](#Future-Analysis-Considerations)  
7. [Dataset License](#Dataset-License)  
8. [Team Members and Roles](#Team-Members-and-Roles)
9. [Contributing](#Contributing)
10. [Acknowledgments](#acknowledgments)  


## Project Overview

Provide a detailed description of the project, its purpose, and what problems it solves. Include screenshots or links to relevant resources if applicable.


## Research Questions and Findings

1. How does a student pursuing extra curricular activities (activities) affect the students final grades (G3)?(John)
2. What is the relationship between number of failures (failures) and grades(G3)?(John)
3. Does going out with friends(goout) correlate to good grades(G3)?(John)
4. Does age(age) correlate to grades(G3)?(John)
5. Does the mothers education level (Medu) affect the students grades (G3)? (Will)
6. Does the fathers education level (Fedu) affect the students grades (G3)? (Will)
7. Does the mothers jobs(Mjob) affect the students grades (G3)? (Will)
8. Does the fathers jobs(Fjob) affect the students grades (G3)? (Will)
---
## Technologies Used
Python (version 3.9.6)
<br>
Pandas for data manipulation and analysis
<br>
Matplotlib for data visualization
<br>
Git/GitHub for version control
<br>
Pandas for handling tabular data
<br>
Numpy for numerical operations
<br>
Sklearn.model_selection specifically train_test_split for splitting data into training and testing sets
<br>
Matplotlib.pyplot for plotting and visualization
<br>
Sklearn.compose specifically ColumnTransformer for applying transformations to specific columns
<br>
Sklearn.preprocessing specifically StandardScaler and OneHotEncoder for scaling and encoding features
<br>
Sklearn.pipeline specifically Pipeline for creating a machine learning pipeline
<br>
Sklearn.ensemble specifically RandomForestRegressor for building a random forest regression model

## Installation and Usage
Step-by-step instructions on how to get a development environment running.
<br>
###### **Clone the repository**
```
git clone[ [https://github.com/steelersrg8/Bootcamp-RUT-VIRT-AI-PT-09-2024-U-LOLC-MTTH-Project-2]
```

###### **Navigate to the project directory**

```
cd Bootcamp-RUT-VIRT-AI-PT-09-2024-U-LOLC-MTTH-Project-2]
```

###### **Install Dependencies**
Manually install the required packages. For example, if the project uses Python and requires pandas and matplotlib, install them using:

```
pip install pandas matplotlib
```
<br>
###### **Run the Analysis**

Start Jupyter Notebook:
```
jupyter notebook
```
Then, open the relevant .ipynb file to view and execute the analysis.
## Analysis Results
# OLS Regression Results

## Summary
| Metric               | Value          |
|----------------------|----------------|
| Dependent Variable   | G3            |
| R-squared            | 0.857         |
| Adjusted R-squared   | 0.850         |
| F-statistic          | 115.5         |
| Prob (F-statistic)   | 1.20e-236     |
| Log-Likelihood       | -1050.0       |
| AIC                  | 2166.0        |
| BIC                  | 2314.0        |
| Observations         | 649           |
| Df Residuals         | 616           |
| Df Model             | 32            |
| Covariance Type      | Nonrobust     |

## Coefficients
| Metric             | coef    | std err | t      | P>\|t\| | [0.025 | 0.975] |
|--------------------|---------|---------|--------|---------|--------|--------|
| const              | -0.0769 | 0.917   | -0.084 | 0.933   | -1.877 | 1.723  |
| age                | 0.0351  | 0.047   | 0.751  | 0.453   | -0.057 | 0.127  |
| Medu               | -0.0379 | 0.062   | -0.611 | 0.541   | -0.160 | 0.084  |
| Fedu               | 0.0145  | 0.061   | 0.238  | 0.812   | -0.105 | 0.134  |
| traveltime         | 0.1300  | 0.074   | 1.747  | 0.081   | -0.016 | 0.276  |
| studytime          | 0.0398  | 0.065   | 0.610  | 0.542   | -0.088 | 0.168  |
| failures           | -0.2414 | 0.098   | -2.454 | 0.014   | -0.435 | -0.048 |
| famrel             | -0.0362 | 0.054   | -0.667 | 0.505   | -0.143 | 0.070  |
| freetime           | -0.0343 | 0.052   | -0.655 | 0.513   | -0.137 | 0.068  |
| goout              | -0.0150 | 0.050   | -0.300 | 0.765   | -0.113 | 0.083  |
| Dalc               | -0.0718 | 0.071   | -1.011 | 0.312   | -0.211 | 0.068  |
| Walc               | -0.0182 | 0.055   | -0.332 | 0.740   | -0.126 | 0.089  |
| health             | -0.0446 | 0.036   | -1.252 | 0.211   | -0.115 | 0.025  |
| absences           | 0.0155  | 0.012   | 1.337  | 0.182   | -0.007 | 0.038  |
| G1                 | 0.1257  | 0.038   | 3.348  | 0.001   | 0.052  | 0.199  |
| G2                 | 0.8735  | 0.035   | 25.032 | 0.000   | 0.805  | 0.942  |
| school_numeric     | 0.2217  | 0.125   | 1.772  | 0.077   | -0.024 | 0.467  |
| gender_numeric     | 0.1181  | 0.118   | 1.004  | 0.316   | -0.113 | 0.349  |
| address_numeric    | -0.1534 | 0.122   | -1.261 | 0.208   | -0.392 | 0.086  |
| famsize_numeric    | 0.0411  | 0.115   | 0.358  | 0.720   | -0.184 | 0.266  |
| Pstatus_numeric    | -0.1181 | 0.160   | -0.739 | 0.460   | -0.432 | 0.196  |
| Mjob_numeric       | -0.0400 | 0.032   | -1.264 | 0.207   | -0.102 | 0.022  |
| Fjob_numeric       | 0.0001  | 0.035   | 0.004  | 0.997   | -0.068 | 0.068  |
| reason_numeric     | -0.0482 | 0.043   | -1.124 | 0.262   | -0.132 | 0.036  |
| guardian_numeric   | 0.0816  | 0.088   | 0.931  | 0.352   | -0.091 | 0.254  |
| schoolsup_numeric  | 0.2075  | 0.172   | 1.208  | 0.227   | -0.130 | 0.545  |
| famsup_numeric     | -0.1300 | 0.106   | -1.222 | 0.222   | -0.339 | 0.079  |
| paid_numeric       | 0.1613  | 0.214   | 0.753  | 0.452   | -0.259 | 0.582  |
| activities_numeric | -0.0200 | 0.104   | -0.193 | 0.847   | -0.224 | 0.184  |
| nursery_numeric    | 0.0892  | 0.127   | 0.702  | 0.483   | -0.160 | 0.339  |
| higher_numeric     | -0.2182 | 0.182   | -1.198 | 0.232   | -0.576 | 0.140  |
| internet_numeric   | -0.0976 | 0.127   | -0.768 | 0.443   | -0.347 | 0.152  |
| romantic_numeric   | 0.0461  | 0.107   | 0.431  | 0.667   | -0.164 | 0.256  |

## Diagnostics
| Metric         | Value   | Metric            | Value    |
|----------------|---------|-------------------|----------|
| Omnibus:       | 437.030 | Durbin-Watson:    | 1.836    |
| Prob(Omnibus): | 0.000   | Jarque-Bera (JB): | 8829.738 |
| Skew:          | -2.682  | Prob(JB):         | 0.00     |
| Kurtosis:      | 20.256  | Cond. No.         | 480      |

## Notes
1. Standard Errors assume that the covariance matrix of the errors is correctly specified.

## Future Analysis Considerations


## Dataset License  



## Team Members and Roles



## Contributing
If you would like to contact us you may use the Issues tab to get in touch.
IF there are any edits you would like to make use the issues/pull requests tab.

## Acknowledgments

Mention any resources, tutorials, or contributors that helped you build this project.
Provide links to relevant documentation or tools.

Dataset: https://archive.ics.uci.edu/dataset/320/student+performance

Questions:


                           

