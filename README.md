# HR Analytics

## Backstory

A company which is active in Big Data and Data Science wants to hire data scientists among people who successfully pass some courses conducted by the company. Many people signup for their training. Company wants to know which of these candidates really wants to work for the company after training or looking for a new employment because it helps to reduce the cost and time as well as the quality of training or planning the courses and categorization of candidates. Information related to demographics, education, experience are in hands from candidates signup and enrollment.

## Impact

Immediate impact for the company is reducing the time and cost for reaching out to/interviewing candidates. In the long run, the model prediction can help with retaining talent by analyzing factors which may identify employees which may start looking for employment elsewhere.

## Data

 * **source**: [Kaggle, HR Analytics](https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists)

## Target
<ins>*Is the candidate looking for a new job?*</ins>

* Yes
* No

## Features

<ins>*Current Status*</ins>
  - Gender
  - City
  - City development index

<ins>*Education*</ins>
  - Major
  - Education level

<ins>*Current Company*</ins>
  - Company type
  - Company size
  
<ins>*Credentials*</ins>
  - Enrolled courses
  - Training hours
  - Relevant experience
  - Experience (years)

## Tools

 * `numpy`, `pandas`
 * `statsmodels`, `scikit-learn`
 * `matplotlib`, `seaborn`

#### Classification Models

 * Logistic Regression
 * kNN
 * Decision Trees
 * Random Forests