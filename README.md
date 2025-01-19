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
git clone https://github.com/steelersrg8/Bootcamp-RUT-VIRT-AI-PT-09-2024-U-LOLC-MTTH-Project-2
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

###### **Run the Analysis**

Start Jupyter Notebook:
```
jupyter notebook
```
Then, open the relevant .ipynb file to view and execute the analysis.
## Analysis Results
| Feature Importances: |                                                 |          |
|----------------------|-------------------------------------------------|----------|
| Feature              | Importance                                      |          |
| 5                    | Number of Failures                              | 0.206499 |
| 12                   | Number of Absences                              | 0.069192 |
| 2                    | Father's Education                              | 0.048847 |
| 9                    | Workday Alcohol Consumption                     | 0.040835 |
| 10                   | Weekend Alcohol Consumption                     | 0.038697 |
| 7                    | Free Time After School                          | 0.034355 |
| 0                    | Age                                             | 0.033105 |
| 8                    | Likleyhood of Going Out With Friends            | 0.032456 |
| 11                   | Current Health Status                           | 0.032153 |
| 1                    | Mother's Education                              | 0.030054 |
| 4                    | Weekly Study Time                               | 0.028983 |
| 13                   | Goes to School at Gabriel Pereira               | 0.027032 |
| 6                    | Quality of Family Relationships                 | 0.022793 |
| 14                   | Goes to School at Mousinho da Silveira          | 0.022579 |
| 3                    | Home to School Travel Time                      | 0.016851 |
| 35                   | Chsoe The School for Other Reasons              | 0.016677 |
| 51                   | Does Want to Take Higher Education              | 0.015948 |
| 50                   | Does Not Want to Take Higher Education          | 0.015499 |
| 40                   | Does Not Have Extra Educational Support         | 0.014307 |
| 41                   | Does Have Extra Educational Support             | 0.013404 |
| 36                   | Chose The School Bc Reputation                  | 0.011276 |
| 33                   | Chose The School Bc of Courses Offered          | 0.011156 |
| 25                   | Mother's job as Another Job                     | 0.010987 |
| 38                   | Guardian is Mother                              | 0.009559 |
| 42                   | Does Not Have Family Educational Support        | 0.009489 |
| 23                   | Mother's job as a Stay at Home Parent           | 0.009126 |
| 34                   | Chose School Bc it's Close to Home              | 0.009097 |
| 31                   | Father's job in the Field of Service            | 0.008809 |
| 15                   | Female                                          | 0.008536 |
| 26                   | Mother's job in the Field of Service            | 0.008427 |
| 27                   | Mother's job as a Teacher                       | 0.008121 |
| 43                   | Does Have Family Educational Support            | 0.007826 |
| 17                   | Rural Home Address                              | 0.007761 |
| 49                   | Did Attended Nursery School                     | 0.007615 |
| 46                   | Does Not Do Extra-curricular Activities         | 0.007217 |
| 32                   | Father's job as a Teacher                       | 0.007054 |
| 18                   | Urban Home Address                              | 0.007047 |
| 47                   | Does Do Extra-curricular Activities             | 0.006780 |
| 30                   | Father's job as Another Job                     | 0.006702 |
| 16                   | Male                                            | 0.006630 |
| 48                   | Did Not Attended Nursery School                 | 0.006625 |
| 55                   | Is In a Romantic Relationship                   | 0.006533 |
| 54                   | Is Not In a Romantic Relationship               | 0.006063 |
| 52                   | Does Not Have Internet Access At Home           | 0.006020 |
| 20                   | Family is Less Than or Equal To 3 Members       | 0.005913 |
| 37                   | Guardian is Father                              | 0.005859 |
| 19                   | Family is Greater Than or Equal To 3 Members    | 0.005687 |
| 39                   | Guardian is Someone Else                        | 0.005530 |
| 53                   | Does Have Internet Access At Home               | 0.005134 |
| 24                   | Mother's job in the Health Field                | 0.003849 |
| 28                   | Father's job as a Stay at Home Parent           | 0.003221 |
| 22                   | Parent's Cohabitation Status is Together        | 0.002913 |
| 21                   | Parent's Cohabitation Status is Apart           | 0.002909 |
| 44                   | Does Have Extra Paid Classes in Portuguese      | 0.001483 |
| 45                   | Does Not Have Extra Paid Classes in Portuguese  | 0.001436 |
| 29                   | Father's job in the Health Field                | 0.001344 |
## Future Analysis Considerations


## Dataset License  
This dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.
<br>
This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.



## Team Members and Roles



## Contributing
If you would like to contact us you may use the Issues tab to get in touch.
IF there are any edits you would like to make use the issues/pull requests tab.

## Acknowledgments

Mention any resources, tutorials, or contributors that helped you build this project.
Provide links to relevant documentation or tools.

Dataset: https://archive.ics.uci.edu/dataset/320/student+performance

Questions:


                           

