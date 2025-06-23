# Dataset Information - Bank Marketing

## Source

This dataset is from the UCI Machine Learning Repository:  
[Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)

## Description

The Bank Marketing dataset contains data related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The goal of the marketing campaign is to predict whether a client will subscribe (yes/no) to a term deposit.

## Dataset Characteristics

- Number of Instances: 45,211
- Number of Attributes: 17 (plus the target variable)
- Attribute Types: Numeric, Categorical
- Missing Values: None (some attributes have 'unknown' as category)

## Attributes Overview

| Attribute          | Description                                         |
|--------------------|-----------------------------------------------------|
| age                | Age of the client (numeric)                         |
| job                | Type of job (categorical)                           |
| marital            | Marital status (categorical)                        |
| education          | Education level (categorical)                       |
| default            | Has credit in default? (categorical: 'yes','no')   |
| housing            | Has housing loan? (categorical: 'yes','no')        |
| loan               | Has personal loan? (categorical: 'yes','no')       |
| contact            | Contact communication type (categorical)           |
| month              | Last contact month of year (categorical)            |
| day_of_week        | Last contact day of week (categorical)              |
| duration           | Last contact duration, in seconds (numeric)        |
| campaign           | Number of contacts performed during this campaign  |
| pdays              | Days passed since last contact (-1 means not contacted) |
| previous           | Number of contacts performed before this campaign  |
| poutcome           | Outcome of previous campaign (categorical)         |
| emp.var.rate       | Employment variation rate - quarterly indicator     |
| cons.price.idx     | Consumer price index - monthly indicator            |
| cons.conf.idx      | Consumer confidence index - monthly indicator       |
| euribor3m          | Euribor 3 month rate - daily indicator              |
| nr.employed        | Number of employees - quarterly indicator           |

## Target Variable

- **y**: Has the client subscribed a term deposit? ('yes','no')

## Usage

This dataset is widely used for classification tasks, customer profiling, and marketing campaign effectiveness studies.

## Notes

- The attribute `duration` highly affects the output target (e.g., if duration=0 then y='no'). Usually, this attribute should be discarded when building predictive models.
- Some attributes contain 'unknown' values which represent missing or undisclosed information.

---

For more information, refer to the original [UCI Dataset Page](https://archive.ics.uci.edu/ml/datasets/bank+marketing).