### Project Title

**Author**

#### Executive summary
This project explores the data (support Ticket Data Information), employing machine learning models to predict which Product Group, Support Level, Agent Group are likely to churn based on Priority, Source of the Ticket, ... Using models like Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, Gradient Boosting, and Support Vector Machines (SVM), I identified the most accurate predictors of churn. The findings indicate key factors associated with churn and provide insights for developing retention strategies, ultimately guiding data-driven decisions to reduce churn rates.

#### Rationale
Why should anyone care about this question?
In our companies there exist many workflows and processes.  For most of this processes there is a difference between the expected and the actual process flow. That means that those processes can be optimized. 
A process is a series of actions or steps repeated in a progression from a defined or recognized 'start' to a defined or recognized 'finish'. The purpose of a process is to establish and maintain a commonly understood flow that allows a task to be completed efficiently and consistently.
Every process step you take leaves digital traces — event log data — in the transactional systems you use. Those digital traces can be collected and stored and those Event-Logs helps the companies to understand their business better. This can be visualized and also be used for Machine learning to answer some questions tied to Manpower planning.
Examples for the processes might be:
- supply change process 
- working process in an support department / call center (based on  tickets in a ticketing system)
  For all those processes you need to plan the shifts and also the employees (knowledge, …) so that the work can be done in an expected manner tied to the demand.
On some days you need more employees, on other days you need less employees (depending on the weekdays on seasonal events, …). And what is also important your employees need to have a specific certification and knowledge to do the work (solve the problems, …).
If you don’t have the necessary employees at the specific/time in your shift you might have some problems: this can lead to business disruption, financial impact, and loss of productivity.
The predictive Manpower Planning also ensure optimal resource allocation (employees with the needed and necessary certification and knowledge) and  that the processes can be optimized.
I will now choose the process/workflow in a support department/call center. Here the work has been tied to tickets in the ticketing system.


#### Research Question
What are you trying to answer?
•	Which and how many employees you need for the shifts in the next week /month ( depending on the product/product group and the knowledge which is needed  and which employees have those knowledges.)
•	If a new release / product will be supported, which employees (tied to the product/produc tgroup,.. ) and how many you need to solve this additional amount of work?


#### Data Sources
What data will you use to answer you question?
I used "Technical Support Dataset" data from 
https://www.kaggle.com/datasets/suvroo/technical-support-dataset

#### Methodology
What methods are you using to answer the question?
I followed a structured machine learning pipeline, which included:
    1.    Data Preprocessing: Data cleaning, encoding categorical variables, handling missing values, and feature scaling.
    2.    Model Selection and Training: Using Logistic Regression, K-Nearest Neighbors, Decision Tree, Gradient Boosting, and Support Vector Machines to compare their effectiveness in predicting churn.
    3.    Model Evaluation: I evaluated each model based on accuracy, precision, recall, F1-score, and AUC-ROC to identify the most predictive and reliable models.
    4.    Result Interpretation: Key metrics were analyzed to assess each model’s predictive power, helping highlight the most important factors influencing churn.
    
#### Results
What did your research find?
The machine learning models provided a range of performance metrics, with Gradient Boosting and SVM showing the highest AUC-ROC scores, indicating strong predictive power. Logistic Regression performed adequately but with lower recall, indicating it missed some churn cases. Decision Tree and KNN provided moderate precision and recall but showed lower AUC-ROC compared to Gradient Boosting and SVM. These results suggest that the top-performing models can reliably identify at-risk users based on their engagement and usage patterns.

#### Next steps
What suggestions do you have for next steps?
    1.    Model Fine-Tuning: Refine the models further through hyperparameter tuning, especially for Gradient Boosting and SVM, to improve accuracy and recall.
    2.    Feature Engineering: Experiment with additional derived features or interaction terms to capture more complex relationships within the data.
    3.    Segmented Retention Strategies: Use churn probability scores to segment users and create targeted retention strategies, such as special offers, personalized recommendations, or timely notifications.

#### Outline of project
    1.    Introduction and Background: Overview of the Support Ticket - "industry" and the importance of understanding the data.
    2.    Research Question and Objectives: Define the goals of the analysis and key questions being answered.
    3.    Data Overview: Detailed description of the dataset and features.
    4.    Exploratory Data Analysis (EDA): Insights on data trends, correlations, and initial observations.
    5.    Modeling Approach: Explanation of chosen machine learning models and the rationale behind each.
    6.    Evaluation and Results: Presentation of model evaluation metrics and comparison of performance.
    7.    Conclusions and Recommendations: Summary of findings and practical suggestions for reducing churn.
    8.    Next Steps and Future Work: Outline of potential developments and applications for ongoing churn prediction efforts.

#### additional work to be done
   1. add knowledge information
   2. add employee information
   3. with the additional data (knowledge, employee) it is possible to have not just product, product group, but also the exact emplyoee, which is needed 

##### Contact and Further Information
