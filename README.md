# Data Analyst Project: Employee Retention & Attrition

Welcome to the **Employee Retention & Attrition** repository! This project explores data-driven solutions to key business challenges in [Human Resources]. Follow along as we uncover insights and deliver actionable recommendations.

---

## Table of Contents

- [Background & Business Problem](#background--business-problem)
- [Project Objectives](#project-objectives)
- [Data Collection & Understanding](#data-collection--understanding)
- [Data Cleaning & Preprocessing](#data-cleaning--preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Key Findings & Insights](#key-findings--insights)
- [Solutions & Recommendations](#solutions--recommendations)
- [How to Reproduce](#how-to-reproduce)

---

## Background & Business Problem

Any company has employees that monitor their perfomance and work through different departements and roles and not only that, A company tries to keep their employees satisfied so:
  - How do Employees churn and what are the factors affecting churn?
  - is attrition high or low?, which departments with high attrition rate?
  - what are the factors affecting high attrition?

## Project Objectives

Clearly state the goals of the project.
- identifying factors affecting both churn and attrition.
- departments with high attrition/churn and what factors affecting attrition/churn to that department the most.
- offer recommendations and suggested actions to help minimizing the effect of that factors.

## Data Collection & Understanding

| file | type |
| ------- | ----------- |
| Employee | .csv |
| EducationLevel | .csv |
| PerformanceRating | .csv |
| RatingLevel | .csv |
| SatisifiedLevel | .csv |

Employee Table Columns

| columnName | Description |
| -----------| ------------|
| EmployeeID | employee unique id.|	
| FirstName	 | employee first name |
| LastName	 | employee last name |
| Gender	   | employee gender |
| Age	       | employee age  |
| BusinessTravel	|  frequency travel category for employee |
| Department	    | department where the employee works  |
| DistanceFromHome (KM)	| calculated distance in kilometers from employee home to company`s site |
| State	  | employee`s state |
| Ethnicity	| employee`s ethnicity |
| Education	 | employee level of education id |
| EducationField	| the field of employee`s education |
| JobRole	  | employee job role  |
| MaritalStatus	| employee marital status (single, married, etc..) |
| Salary	| employee`s salary |
| StockOptionLevel	| unknown |
| OverTime	| does the employee take over night? |
| HireDate	| the date the employee was hired |
| Attrition	| is the employee attritioned?  |
| YearsAtCompany	| full working years of the employee at the company |
| YearsInMostRecentRole	| years of working in most recent role |
| YearsSinceLastPromotion	| how many years since last promotion? |
| YearsWithCurrManager  | how many years does that employee worked with his/her current manager? |

EducationLevel Table Columns

| columnName | Description |
| -----------| ------------|
| EducationLevelID | education level unique id.|	
| EducationLevel	 | actual education level (high school, bachelor, etc...) |

PerformanceRating Table Columns

| columnName | Description |
| -----------| ------------|
| PerformanceID | performance record unique identifyer |	
| EmployeeID	 | employee unique id. |
| ReviewDate   | the date when the employee was reviewed |
| EnvironmentSatisfaction	| environment satisfaction of the employee (range: 1-5) |
| JobSatisfaction	   | job satisfaction of the employee (range: 1-5) |
| RelationshipSatisfaction	| relationship satisfaction of the employee (range: 1-5) |
| TrainingOpportunitiesWithinYear	| number of training opportunities with in year |
| TrainingOpportunitiesTaken	| number of training opportunities taken |
| WorkLifeBalance	| work life balance of the employee (range: 1-5) |
| SelfRating	| employee self rating (range: 1-5) |
| ManagerRating | employee manager rating (rating: 1-5) |

RatingLevel Table Columns

| columnName | Description |
| -----------| ------------|
| RatingID | rating unique identifier |	
| RatingLevel	 | value of the rating level (e.g: Meets Expectation) |

SatisfiedLevel Table Columns

| columnName | Description |
| -----------| ------------|
| SatisfactionID | satisfaction unique identifyer |	
| SatisfactionLevel	 | value of the Satisfaction level (e.g: Satisfied) |



## Data Cleaning & Preprocessing

Not much cleaning was introduced

## Exploratory Data Analysis

- there were 1470 employees as total, 237 of them were inActiveEmployees (labeled with "Yes" as attrition)
- the attrition rate was 16.1% which is relatively high
- 2016 & 2020 had the most attrition rate may be for the latter is covid-19 where people had to stay home and work from, them made them lose a lot communication benefits and just doing tasks
- employees with just one year at the company are more likely to churn

## Sample Report:

https://github.com/user-attachments/assets/eab76ee0-7b15-416f-b6c3-b29628d122a9




## Key Findings & Insights

1- Attrition:

  By Department & Job Role:
    - Sales Representatives and Human Resources Recruiters have the highest attrition rates (nearly 40%), meaning these positions are particulary volatile
    - Technology roles (e.g. Software Engineers) have moderate attrition but make up the majority of the workforce

  By Travel Frequency:
    - Employees categorized as "Frequent Travellers" have the highest attrition rates.
    - "No Travel" employees have the lowest, suggesting travel demands may be a retention risk.

  By Overtime:
    - Staff who work overtime have a significantly higher attrition rate (~31%) than those who do not (~10%)

  By Education Level:
    - No formal Qualifications & Lower education levels correlate with higher attrition rates than advanced degrees

  By Years at Company:
    - Highest attrition is observed within the first 1-2 years of tenure, sharply declining as length of service increases


2- Demographics:

  - Most employees are white, aged 20-29 and married.
  - highest average salaries are for white and native hawaiian.
  - age and gender distributions show the bulk of employees in their 20s and 30s.

3- Organizational Structure:

  - The technology department is the largest, but the attrition`s biggest pain points are in sales and HR.
  - Out of 1470 employees, 1233 are active, and 237 are inactive with notable spike in attrition in recent years

4- Individual Performance and Satisfaction is left for discovery


## Solutions & Recommendations

1- Investigate High-Risk Roles and Departments

  - Conduct targeted interviews/surveys for Sales Representatives and HR Recruiters to understand specific pain points.
  - Enhance onboarding/training for new hires in the first two years.

2- Address Overtime and Travel

  - Review overtime policies, add good bonuses for overtime and promote work-life balance.
  - consider options to reduce travel or support frequent travelers with additional resources.

3- Improve Retention for Early Tenure Employees

  - Focused mentoring for new hires, especially those in first 1-2 years.

4- Monitor and Boost Employee Satisfaction 

  - Pay attention to manager ratings and work-life balance in performance reviews.
  - Offer development paths to employees with lower education, possibly integrating upskilling programs.

5- Track Demographic Trends

  - Stay alert for underrepresented or high-risk demographic groups (age, ethnicity, marital status) that may require tailored retention strategies.


## How to Reproduce

Step-by-step instructions for running the analysis:
1. Just download the report and dataset needed

