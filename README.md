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
| 5                    | failures          | 0.206499 |
| 12                   | absences          | 0.069192 |
| 2                    | Fedu              | 0.048847 |
| 9                    | Dalc              | 0.040835 |
| 10                   | Walc              | 0.038697 |
| 7                    | freetime          | 0.034355 |
| 0                    | age               | 0.033105 |
| 8                    | goout             | 0.032456 |
| 11                   | health            | 0.032153 |
| 1                    | Medu              | 0.030054 |
| 4                    | studytime         | 0.028983 |
| 13                   | school_GP         | 0.027032 |
| 6                    | famrel            | 0.022793 |
| 14                   | school_MS         | 0.022579 |
| 3                    | traveltime        | 0.016851 |
| 35                   | reason_other      | 0.016677 |
| 51                   | higher_yes        | 0.015948 |
| 50                   | higher_no         | 0.015499 |
| 40                   | schoolsup_no      | 0.014307 |
| 41                   | schoolsup_yes     | 0.013404 |
| 36                   | reason_reputation | 0.011276 |
| 33                   | reason_course     | 0.011156 |
| 25                   | Mjob_other        | 0.010987 |
| 38                   | guardian_mother   | 0.009559 |
| 42                   | famsup_no         | 0.009489 |
| 23                   | Mjob_at_home      | 0.009126 |
| 34                   | reason_home       | 0.009097 |
| 31                   | Fjob_services     | 0.008809 |
| 15                   | sex_F             | 0.008536 |
| 26                   | Mjob_services     | 0.008427 |
| 27                   | Mjob_teacher      | 0.008121 |
| 43                   | famsup_yes        | 0.007826 |
| 17                   | address_R         | 0.007761 |
| 49                   | nursery_yes       | 0.007615 |
| 46                   | activities_no     | 0.007217 |
| 32                   | Fjob_teacher      | 0.007054 |
| 18                   | address_U         | 0.007047 |
| 47                   | activities_yes    | 0.006780 |
| 30                   | Fjob_other        | 0.006702 |
| 16                   | sex_M             | 0.006630 |
| 48                   | nursery_no        | 0.006625 |
| 55                   | romantic_yes      | 0.006533 |
| 54                   | romantic_no       | 0.006063 |
| 52                   | internet_no       | 0.006020 |
| 20                   | famsize_LE3       | 0.005913 |
| 37                   | guardian_father   | 0.005859 |
| 19                   | famsize_GT3       | 0.005687 |
| 39                   | guardian_other    | 0.005530 |
| 53                   | internet_yes      | 0.005134 |
| 24                   | Mjob_health       | 0.003849 |
| 28                   | Fjob_at_home      | 0.003221 |
| 22                   | Pstatus_T         | 0.002913 |
| 21                   | Pstatus_A         | 0.002909 |
| 44                   | paid_no           | 0.001483 |
| 45                   | paid_yes          | 0.001436 |
| 29                   | Fjob_health       | 0.001344 |
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


                           

