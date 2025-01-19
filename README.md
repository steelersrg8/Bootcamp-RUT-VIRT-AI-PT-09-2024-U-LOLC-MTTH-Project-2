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
| Feature Importances: |                        |          |
|----------------------|------------------------|----------|
| Feature              | Importance             |          |
| 5                    | num__failures          | 0.206499 |
| 12                   | num__absences          | 0.069192 |
| 2                    | num__Fedu              | 0.048847 |
| 9                    | num__Dalc              | 0.040835 |
| 10                   | num__Walc              | 0.038697 |
| 7                    | num__freetime          | 0.034355 |
| 0                    | num__age               | 0.033105 |
| 8                    | num__goout             | 0.032456 |
| 11                   | num__health            | 0.032153 |
| 1                    | num__Medu              | 0.030054 |
| 4                    | num__studytime         | 0.028983 |
| 13                   | cat__school_GP         | 0.027032 |
| 6                    | num__famrel            | 0.022793 |
| 14                   | cat__school_MS         | 0.022579 |
| 3                    | num__traveltime        | 0.016851 |
| 35                   | cat__reason_other      | 0.016677 |
| 51                   | cat__higher_yes        | 0.015948 |
| 50                   | cat__higher_no         | 0.015499 |
| 40                   | cat__schoolsup_no      | 0.014307 |
| 41                   | cat__schoolsup_yes     | 0.013404 |
| 36                   | cat__reason_reputation | 0.011276 |
| 33                   | cat__reason_course     | 0.011156 |
| 25                   | cat__Mjob_other        | 0.010987 |
| 38                   | cat__guardian_mother   | 0.009559 |
| 42                   | cat__famsup_no         | 0.009489 |
| 23                   | cat__Mjob_at_home      | 0.009126 |
| 34                   | cat__reason_home       | 0.009097 |
| 31                   | cat__Fjob_services     | 0.008809 |
| 15                   | cat__sex_F             | 0.008536 |
| 26                   | cat__Mjob_services     | 0.008427 |
| 27                   | cat__Mjob_teacher      | 0.008121 |
| 43                   | cat__famsup_yes        | 0.007826 |
| 17                   | cat__address_R         | 0.007761 |
| 49                   | cat__nursery_yes       | 0.007615 |
| 46                   | cat__activities_no     | 0.007217 |
| 32                   | cat__Fjob_teacher      | 0.007054 |
| 18                   | cat__address_U         | 0.007047 |
| 47                   | cat__activities_yes    | 0.006780 |
| 30                   | cat__Fjob_other        | 0.006702 |
| 16                   | cat__sex_M             | 0.006630 |
| 48                   | cat__nursery_no        | 0.006625 |
| 55                   | cat__romantic_yes      | 0.006533 |
| 54                   | cat__romantic_no       | 0.006063 |
| 52                   | cat__internet_no       | 0.006020 |
| 20                   | cat__famsize_LE3       | 0.005913 |
| 37                   | cat__guardian_father   | 0.005859 |
| 19                   | cat__famsize_GT3       | 0.005687 |
| 39                   | cat__guardian_other    | 0.005530 |
| 53                   | cat__internet_yes      | 0.005134 |
| 24                   | cat__Mjob_health       | 0.003849 |
| 28                   | cat__Fjob_at_home      | 0.003221 |
| 22                   | cat__Pstatus_T         | 0.002913 |
| 21                   | cat__Pstatus_A         | 0.002909 |
| 44                   | cat__paid_no           | 0.001483 |
| 45                   | cat__paid_yes          | 0.001436 |
| 29                   | cat__Fjob_health       | 0.001344 |
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


                           

