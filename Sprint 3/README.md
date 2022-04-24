# Sprint 3 - Data Preparation, Modeling, Evaluation

# Data Preparation Phase 
## 3.1 Task: Select Data
### Rationale for Inclusion/Exclusion: 
→ Columns that did not have relevance to the analysis were dropped (**Developer Email, Privacy Policy, and Developer Website**)

  - Columns with extra information like Developer contact info is extra data that could be removed

→ Columns with numeric values and columns that provided insights into potential app KPIs were kept in the analysis in order to explore further how to evaluate app performance (**Price, Rating, Rating Count, etc.**)

→ Even though there are many features remaining, we wanted to keep a substantial number of features in order to have enough variables to construct meaningful dashboards


## 3.2 Task: Clean Data 
### Data Cleaning Report: 
→ Even though the data pulled from Kaggle was fairly clean, we needed to conduct some additional cleaning

1. Null values needed to be accounted for 

    - Blanks and values that represented missing values were interpolated or coerced to np.nan in order to allow for calculations
  
2. The date values needed updating and cleaning

    - Original date format is in Unix date time and it needed to be converted to a more easily understood datetime format

## 3.3 Task: Construct Data
### Data Exploration Report: 
→ As mentioned above, date formats needed to be changed to be more useful and easy to understand in the analysis

  - Changed from Unix format to a standard date time format

→ Minimum installs and maximum install values were provided in the data, but to get an approximate and more specific installs number we created a new value to interpolate the values and create an estimated installs field that we can use in our analysis

  - Originally we tried creating an estimated value by taking min+max / 2, but after further consideration we determined interpolating the values would be a more accurate and appropriate way to represent estimates.


## 3.4 Task: Integrate Data
### Merged Data:
→ Main tables in the database are:
  - applications
  - food_delivery_reviews
  - app_reviews


## 3.5 Task: Format Data
### Reformatted Data: 
→ **AWS RDS database connection details**: aws_rds_db.txt file in Github
→ **Data Preparation Python Code**: data_preparation.ipynb file in Github

**Exploratory SQL using AWS Postgres Database**

1. Explore tables

        SELECT *
        FROM applications
        ;

        SELECT *
        FROM app_reviews
        ;

        SELECT *
        FROM food_delivery_reviews
        ;


2. Demonstrate JOINS 

  - JOIN applications with food_delivery_reviews (using doordash as an example)
      
        SELECT *
        FROM applications a 
        LEFT JOIN food_delivery_reviews f
          ON a.app_id = f.app_id
        WHERE a.app_id = 'com.dd.doordash'
        ;

  - JOIN applications with app_reviews (using com.anydo as an example)
      
        SELECT *
        FROM applications a 
        LEFT JOIN app_reviews r 
          ON a.app_id = r.app_id
        WHERE a.app_id = 'com.anydo'
        ;


# Modeling Phase 
## 4.1 Task: Selecting Modeling Techniques
### Modeling Technique and Assumptions: 
→ 

## 4.2 Task: Generate Test Design
### Test Design: 
→ 

## 4.3 Task: Build Model 
### Parameter Settings, Models and Descriptions: 
→ 

## 4.4 Task: Assess Model
### Model Assessment and Revisions: 
→ 

# Evaluation Phase 
## 5.1 Task: Evaluate Results 
### Assessment of Results in terms of Business Success Criteria: 
### Approved Model(s)
→ 

## 5.2 Task: Review Process
### Review of Process: 
→ 

## 5.3 Task: Determine Next Steps
### Possible Actions:
### Decisions: 
→ 
