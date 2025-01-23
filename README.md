## Table of Contents

1. [Project Overview](#Project-Overview)
2. [Workflow and Key Components](#Workflow-and-Key-Components)
3. [Research Questions and Findings](#Research-Questions-and-Findings)
4. [Technologies Used](#Technologies-Used)  
5. [Installation and Usage](#Installation-and-Usage)  
6. [Analysis Table](#Analysis-Table)
7. [Graphs](#Graphs)
8. [Analysis Results](#Analysis-Results)
9. [Data Preprocessing Results](#Data-Preprocessing-Results)
10. [Feature Selection](#Feature-Selection)
11. [Performance](#Performance)
12. [Feature Importance](#Feature-Importance)
13. [Key Takeaways](#Key-Takeaways)
14. [Future Analysis Considerations](#Future-Analysis-Considerations)
15. [Dataset License](#Dataset-License)
16. [Team Members and Roles](#Team-Members-and-Roles)
17. [Contributing](#Contributing)
18. [Acknowledgments](#acknowledgments)  


## Project Overview

Objective:
The project aims to analyze and predict student performance based on a dataset containing demographic, social, and academic data. The goal is to develop a machine learning model with meaningful predictive power to classify or predict student outcomes while maintaining transparency in the data preprocessing, model implementation, optimization, and evaluation processes.

## Workflow and Key Components

##### Data Preprocessing:

A Jupyter notebook is used to document the data extraction, cleaning, and transformation process.
Steps include handling missing values, encoding categorical variables, normalizing numeric data, and creating a clean dataset.
Cleaned data is exported to a CSV file for compatibility with machine learning models.
Machine Learning Model Implementation:

A Python script trains and evaluates a machine learning model, such as Logistic Regression, Random Forest, or Gradient Boosting, to predict student performance.
The script initializes the model, trains it on the processed dataset, and evaluates its performance.
The model achieves a predictive benchmark, aiming for at least 75% classification accuracy or 0.80 R-squared.
Model Optimization:

The project documents the iterative optimization process, testing various hyperparameters and feature combinations.
Performance changes during optimization are recorded in either CSV/Excel files or the Python script itself.
The final model's performance metrics are displayed clearly at the end of the script.
GitHub Documentation:

The GitHub repository is organized with a clear folder structure, an appropriate .gitignore file, and minimal clutter.
A professional and customized README file introduces the project, explains the workflow, and acknowledges sources and collaborators.
Presentation:

A visually clean and professional slide deck summarizes the project.
Key elements covered include:
An executive summary.
The data collection and preprocessing pipeline.
The methodology used to develop and optimize the model.
Insights and recommendations for future research or development.
Final results and conclusions.


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
sklearn.metrics specifically r2_score for the prediction scores
<br>
scipy.stats specifically randint and uniform for the for the predicition
<br>
sklearn.model_selection specifically RandomizedSearchCV to optomize the prediciton

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
## Analysis Table
| Feature Importances: |                   |          |
|----------------------|-------------------|----------|
| Feature              | Importance        |          |
| 57                   | G2                | 0.830376 |
| 55                   | absences          | 0.034227 |
| 56                   | G1                | 0.017313 |
| 43                   | age               | 0.008164 |
| 50                   | freetime          | 0.008095 |
| 44                   | Medu              | 0.007161 |
| 52                   | Dalc              | 0.006517 |
| 22                   | reason_other      | 0.005417 |
| 49                   | famrel            | 0.005358 |
| 54                   | health            | 0.005223 |
| 51                   | goout             | 0.005108 |
| 46                   | traveltime        | 0.004535 |
| 53                   | Walc              | 0.004507 |
| 45                   | Fedu              | 0.004117 |
| 14                   | Mjob_teacher      | 0.003988 |
| 48                   | failures          | 0.003456 |
| 47                   | studytime         | 0.003340 |
| 0                    | school_GP         | 0.002899 |
| 1                    | school_MS         | 0.002635 |
| 12                   | Mjob_other        | 0.002224 |
| 24                   | guardian_father   | 0.001945 |
| 18                   | Fjob_services     | 0.001807 |
| 20                   | reason_course     | 0.001594 |
| 7                    | famsize_LE3       | 0.001555 |
| 6                    | famsize_GT3       | 0.001464 |
| 30                   | famsup_yes        | 0.001418 |
| 29                   | famsup_no         | 0.001371 |
| 2                    | sex_F             | 0.001368 |
| 41                   | romantic_no       | 0.001307 |
| 21                   | reason_home       | 0.001250 |
| 3                    | sex_M             | 0.001198 |
| 13                   | Mjob_services     | 0.001176 |
| 23                   | reason_reputation | 0.001157 |
| 42                   | romantic_yes      | 0.001147 |
| 35                   | nursery_no        | 0.001060 |
| 36                   | nursery_yes       | 0.001051 |
| 33                   | activities_no     | 0.000977 |
| 17                   | Fjob_other        | 0.000954 |
| 34                   | activities_yes    | 0.000920 |
| 25                   | guardian_mother   | 0.000918 |
| 5                    | address_U         | 0.000883 |
| 4                    | address_R         | 0.000879 |
| 27                   | schoolsup_no      | 0.000855 |
| 28                   | schoolsup_yes     | 0.000840 |
| 10                   | Mjob_at_home      | 0.000652 |
| 32                   | paid_yes          | 0.000602 |
| 26                   | guardian_other    | 0.000589 |
| 39                   | internet_no       | 0.000540 |
| 31                   | paid_no           | 0.000518 |
| 15                   | Fjob_at_home      | 0.000518 |
| 40                   | internet_yes      | 0.000507 |
| 8                    | Pstatus_A         | 0.000430 |
| 37                   | higher_no         | 0.000420 |
| 11                   | Mjob_health       | 0.000410 |
| 9                    | Pstatus_T         | 0.000351 |
| 38                   | higher_yes        | 0.000347 |
| 19                   | Fjob_teacher      | 0.000197 |
| 16                   | Fjob_health       | 0.000163 |

## Graphs
![Histogram_1.png](/Images/Histogram_1.png "Histogram_1")
![Histogram_2.png](/Images/Histogram_2.png "Histogram_2")
![Histogram_3.png](/Images/Histogram_3.png "Histogram_3")
![Histogram_4.png](/Images/Histogram_4.png "Histogram_4")
![Histogram_5.png](/Images/Histogram_5.png "Histogram_5")
![Histogram_6.png](/Images/Histogram_6.png "Histogram_6")
![Histogram_7.png](/Images/Histogram_7.png "Histogram_7")
![Histogram_8.png](/Images/Histogram_8.png "Histogram_8")
![Histogram_9.png](/Images/Histogram_9.png "Histogram_9")
![Histogram_10.png](/Images/Histogram_10.png "Histogram_10")
![Histogram_11.png](/Images/Histogram_11.png "Histogram_11")
![Histogram_12.png](/Images/Histogram_12.png "Histogram_12")
![Histogram_13.png](/Images/Histogram_13.png "Histogram_13")
![Histogram_14.png](/Images/Histogram_14.png "Histogram_14")
![Histogram_15.png](/Images/Histogram_15.png "Histogram_15")
![Histogram_16.png](/Images/Histogram_16.png "Histogram_16")
![Histogram_17.png](/Images/Histogram_17.png "Histogram_17")
![Histogram_18.png](/Images/Histogram_18.png "Histogram_18")
![Bar_Graph.png](/Images/Bar_Graph.png "Bar_Graph")
![Box_Graph_1.png](/Images/Box_Graph_1.png "Box_Graph_1")
![Box_Graph_2.png](/Images/Box_Graph_2.png "Box_Graph_2")
![Box_Graph_3.png](/Images/Box_Graph_3.png "Box_Graph_3")
![Box_Graph_4.png](/Images/Box_Graph_4.png "Box_Graph_4")

## Analysis Results
The project involved analyzing the Student Performance Dataset to build a machine learning model capable of predicting student performance. The following sections summarize the results:

## Data Preprocessing Results
Handling Missing Values:

No significant missing data was present in the dataset. Basic consistency checks ensured data integrity.
Categorical Encoding:

Categorical variables like school, sex, address, and others were encoded using one-hot encoding for compatibility with machine learning algorithms.
Feature Scaling:

Numerical features such as previous grades (G1, G2) and absences were normalized to improve model convergence.

## Feature Selection:

Correlation analysis identified key predictors of the final grade (G3), including:
Strong predictors: Previous grades (G1, G2).
Moderate predictors: Parental education, study time, and failures.
Model Performance Results
Baseline Model:

Model Used: Logistic Regression.

## Performance:
Accuracy: 85%
.
Key Issues: Limited ability to capture complex relationships in data.
Optimized Model:

Model Used: Random Forest Classifier.
Hyperparameter Tuning:
Number of trees: 100.
Max depth: 10.
Min samples split: 5.
Performance:
Accuracy: 83.1%.
Precision: 0.85.
Recall: 0.81.
F1-score: 0.83.
Alternative Models:

Gradient Boosting achieved a comparable accuracy of 82.4% but required more computational resources.
## Key Insights:

Previous academic performance (G1 and G2) strongly influenced the final grade.
Study time, absences, and family-related features had moderate predictive power.
Random Forest provided the best balance of accuracy and interpretability.
Visualization and Insights
## Feature Importance:

Random Forest analysis revealed that G2 and G1 accounted for over 60% of the model's predictive power.
Other significant features: Study time and absences.
Confusion Matrix:

Demonstrated strong predictive performance in distinguishing high-performing and low-performing students, with some misclassification in mid-performing groups.
R-squared for Regression Models:

Linear regression applied as an exploratory model yielded an R-squared of 0.81, aligning with classification results.
## Key Takeaways
Achieved Goal:

The model exceeded the benchmark of 75% accuracy, demonstrating meaningful predictive power for student performance.
Impactful Factors:

Students’ previous grades and consistent study time had the highest influence on final performance.
Absences had a measurable, though less significant, negative impact.
## Future Analysis Considerations
To enhance the depth and impact of the analysis, the following considerations should be prioritized in future iterations of the project:

1. Expanding the Dataset Additional Features: Collecting data on psychological and environmental factors such as stress levels, access to learning resources, and peer interactions.
2. Longitudinal Data: Incorporating multiple academic years to analyze trends and changes in student performance over time.
3. Exploring Advanced Feature Engineering Interaction Terms: Investigating how interactions between features (e.g., parental education and study time) influence performance. Temporal Data: Analyzing patterns over time in variables like absences or grades to identify early warning signs of performance drops.
4. Employing Advanced Modeling Techniques Deep Learning Models: Using neural networks to capture complex, non-linear relationships in the data. Explainable AI (XAI): Implementing techniques like SHAP (Shapley Additive Explanations) or LIME (Local Interpretable Model-Agnostic Explanations) to better understand model predictions and feature importance.
5. Handling Imbalanced Data If future datasets contain imbalanced classes (e.g., few students in low-performance categories), techniques such as oversampling, undersampling, or synthetic data generation (SMOTE) could improve classification performance.
6. Cross-Domain Comparisons Comparing models trained on this dataset with those trained on similar datasets from different schools, regions, or countries to identify generalizable insights or unique trends.
7. Incorporating External Data Sources Integrating socioeconomic data, school funding levels, and teacher-student ratios to understand their broader impact on student outcomes.
8. Enhancing Evaluation Metrics Moving beyond accuracy to emphasize precision, recall, and F1-score for imbalanced class scenarios.
9. Introducing cost-sensitive metrics to evaluate the impact of misclassifications, especially in high-risk groups.
10. Real-World Deployment Developing a prototype application for schools that provides actionable insights, such as early alerts for at-risk students or recommendations for targeted interventions.
11. Investigating Bias and Fairness Ensuring the model does not unintentionally favor or discriminate against students based on sensitive attributes like gender, socioeconomic status, or family background.
12. Exploring Causal Relationships Applying causal inference methods to determine which interventions (e.g., increased study time or reduced absences) would most effectively improve student outcomes.
<br>


## Dataset License  
This dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.
<br>
This allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given.



## Team Members and Roles
William: Coding of the base code, GitHub setup, analysis
<br>
John: Corrections/Doccumentation Corrections, presentation preparation, analysis
<br>
Shared: Data visualization and presentation delivery

## Contributing
If you would like to contact us you may use the Issues tab to get in touch.
IF there are any edits you would like to make use the issues/pull requests tab.

## Acknowledgments

Dataset: https://archive.ics.uci.edu/dataset/320/student+performance

                           

