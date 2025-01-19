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
| Feature              | Importance                                      | Impact   |
| 5                    | Number of Failures                              | 20.6499% |
| 12                   | Number of Absences                              | 6.9192%  |
| 2                    | Father's Education                              | 4.8847%  |
| 9                    | Workday Alcohol Consumption                     | 4.0835%  |
| 10                   | Weekend Alcohol Consumption                     | 3.8697%  |
| 7                    | Free Time After School                          | 3.4355%  |
| 0                    | Age                                             | 3.3105%  |
| 8                    | Likleyhood of Going Out With Friends            | 3.2456%  |
| 11                   | Current Health Status                           | 3.2153%  |
| 1                    | Mother's Education                              | 3.54%    |
| 4                    | Weekly Study Time                               | 2.8983%  |
| 13                   | Goes to School at Gabriel Pereira               | 2.7032%  |
| 6                    | Quality of Family Relationships                 | 2.2793%  |
| 14                   | Goes to School at Mousinho da Silveira          | 2.2579%  |
| 3                    | Home to School Travel Time                      | 1.6851%  |
| 35                   | Chsoe The School for Other Reasons              | 1.6677%  |
| 51                   | Does Want to Take Higher Education              | 1.5948%  |
| 50                   | Does Not Want to Take Higher Education          | 1.5499%  |
| 40                   | Does Not Have Extra Educational Support         | 1.4307%  |
| 41                   | Does Have Extra Educational Support             | 1.3404%  |
| 36                   | Chose The School Bc Reputation                  | 1.1276%  |
| 33                   | Chose The School Bc of Courses Offered          | 1.1156%  |
| 25                   | Mother's job as Another Job                     | 1.0987%  |
| 38                   | Guardian is Mother                              | 0.9559%  |
| 42                   | Does Not Have Family Educational Support        | 0.9489%  |
| 23                   | Mother's job as a Stay at Home Parent           | 0.9126%  |
| 34                   | Chose School Bc it's Close to Home              | 0.9097%  |
| 31                   | Father's job in the Field of Service            | 0.8809%  |
| 15                   | Female                                          | 0.8536%  |
| 26                   | Mother's job in the Field of Service            | 0.8427%  |
| 27                   | Mother's job as a Teacher                       | 0.8121%  |
| 43                   | Does Have Family Educational Support            | 0.7826%  |
| 17                   | Rural Home Address                              | 0.7761%  |
| 49                   | Did Attended Nursery School                     | 0.7615%  |
| 46                   | Does Not Do Extra-curricular Activities         | 0.7217%  |
| 32                   | Father's job as a Teacher                       | 0.7054%  |
| 18                   | Urban Home Address                              | 0.7047%  |
| 47                   | Does Do Extra-curricular Activities             | 0.6780%  |
| 30                   | Father's job as Another Job                     | 0.6702%  |
| 16                   | Male                                            | 0.6630%  |
| 48                   | Did Not Attended Nursery School                 | 0.6625%  |
| 55                   | Is In a Romantic Relationship                   | 0.6533%  |
| 54                   | Is Not In a Romantic Relationship               | 0.6063%  |
| 52                   | Does Not Have Internet Access At Home           | 0.6020%  |
| 20                   | Family is Less Than or Equal To 3 Members       | 0.5913%  |
| 37                   | Guardian is Father                              | 0.5859%  |
| 19                   | Family is Greater Than or Equal To 3 Members    | 0.5687%  |
| 39                   | Guardian is Someone Else                        | 0.5530%  |
| 53                   | Does Have Internet Access At Home               | 0.5134%  |
| 24                   | Mother's job in the Health Field                | 0.3849%  |
| 28                   | Father's job as a Stay at Home Parent           | 0.3221%  |
| 22                   | Parent's Cohabitation Status is Together        | 0.2913%  |
| 21                   | Parent's Cohabitation Status is Apart           | 0.2909%  |
| 44                   | Does Have Extra Paid Classes in Portuguese      | 0.1483%  |
| 45                   | Does Not Have Extra Paid Classes in Portuguese  | 0.1436%  |
| 29                   | Father's job in the Health Field                | 0.1344%  |
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


                           

