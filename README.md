# Employee-Retention

## Objective
•	To understand what factors contributed most to employee turnover.
•	To perform clustering to find any meaningful patterns of employee traits.
•	To create a model that predicts the likelihood if a certain employee will leave the company or not. 
•	To create or improve different retention strategies on targeted employees.

## Dataset:
The dataset contains information of employees in an organization and is present in the form of csv file with the following variables:

**satisfaction_level** – The satisfaction level of an employee
**last_evaluation** – The evaluation  score of the employee
**number_project** – The number of projects worked by the employee
**average_montly_hours** – The average number of hours worked by the employee per month
**time_spend_company** – The number of years spent by the employee in the organization
**Work_accident** – If the employee had an accident during work ( 0 – No, 1 – Yes)
**Turnover** – if the employee left the company (0 – No, 1 – Yes)
**Promotion** - if the employee got a promotion during his tenure in the organization (0 – No, 1 – Yes)
**Department** – Department of the employee
**Salary** – Salary range of the employee

 
## Jupyter Notebooks:
The Jupyter notebook HR_Analysis_EDA provides the code, explanation and information on the exploratory analysis performed on the dataset. The Jupyter notebook HR_Analytics_Modelling provides the code, explanation and information on the predictive models, predictions, the metrics  , feature importance and the insights drawn from the dataset.

## Conclusion:
**Binary Classification:** Turnover V.S. Non-Turnover
**Instance Scoring:** Likelihood of employee responding to an offer/incentive to save them from leaving.
**Need for a strategy**: Save employees from leaving
In our employee retention problem, rather than simply predicting whether an employee will leave the company within a certain time frame, we would much rather have an estimate of the probability that he/she will leave the company. 
We would rank employees by their probability of leaving, then allocate a limited incentive budget to the highest probability instances. 

Consider employee turnover domain where an employee is given treatment by Human Resources because they think the employee will leave the company within a month, but the employee actually does not. This is a false positive. This mistake could be expensive, inconvenient, and time consuming for both the Human Resources and employee but is a good investment for relational growth. 

Compare this with the opposite error, where Human Resources does not give treatment/incentives to the employees and they do leave. This is a false negative. This type of error is more detrimental because the company lost an employee, which could lead to great setbacks and more money to rehire. 
Depending on these errors, different costs are weighed based on the type of employee being treated. For example, if it’s a high-salary employee then would we need a costlier form of treatment? What if it’s a low-salary employee? The cost for each error is different and should be weighed accordingly. 
 
## Solution 1:
•	We can rank employees by their probability of leaving, then allocate a limited incentive budget to the highest probability instances.
•	OR, we can allocate our incentive budget to the instances with the highest expected loss, for which we'll need the probability of turnover.

## Solution 2: 
Develop learning programs for managers. Then use analytics to gauge their performance and measure progress. Some advice:
•	Be a good coach
•	Empower the team and do not micromanage
•	Express interest for team member success
•	Have clear vision / strategy for team
•	Help team with career development  

## Remarks:
Selection Bias:
•	One thing to note about this dataset is the turnover feature. We don't know if the employees that left are interns, contractors, full-time, or part-time. These are important variables to take into consideration when performing a machine learning algorithm to it. 

•	Another thing to note down is the type of bias of the evaluation feature. Evaluation is heavily subjective and can vary tremendously depending on who is the evaluator. If the employee knows the evaluator, then he/she will probably have a higher score.  
