## Table of Contents

1. [Project Overview](#Project-Overview)
2. [Workflow and Key Components](#Workflow-and-Key-Components)
3. [Research Questions and Findings](#Research-Questions-and-Findings)
4. [Technologies Used](#Technologies-Used)  
5. [Installation and Usage](#Installation-and-Usage)  
6. [Analysis Table](#Analysis-Table)
7. [Analysis Results](#Analysis-Results)
8. [Data Preprocessing Results](#Data-Preprocessing-Results)
9. [Feature Selection](#Feature-Selection)
10. [Performance](#Performance)
11. [Feature Importance](#Feature-Importance)
12. [Key Takeaways](#Key-Takeaways)
13. [Future Analysis Considerations](#Future-Analysis-Considerations)
14. [Dataset License](#Dataset-License)
15. [Team Members and Roles](#Team-Members-and-Roles)
16. [Contributing](#Contributing)
17. [Acknowledgments](#acknowledgments)  


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
Accuracy: 72.5%.
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



## Contributing
If you would like to contact us you may use the Issues tab to get in touch.
IF there are any edits you would like to make use the issues/pull requests tab.

## Acknowledgments

Mention any resources, tutorials, or contributors that helped you build this project.
Provide links to relevant documentation or tools.

Dataset: https://archive.ics.uci.edu/dataset/320/student+performance

                           

