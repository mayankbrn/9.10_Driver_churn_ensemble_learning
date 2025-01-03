# Driver_churn_ensemble_learning

Business Case: Ensemble Learning

# Ensemble Learning 📊

Welcome to the project! 🎉 

## About Ola
Ola is a leading ride-hailing and mobility platform based in India, founded in December 2010 by Bhavish Aggarwal and Ankit Bhati. Over the years, Ola has evolved from being a simple taxi aggregator to becoming one of the largest mobility platforms globally.

## Business Problem 📈
Recruiting and retaining drivers is seen by industry watchers as a tough battle for Ola. Churn among drivers is high and it’s very easy for drivers to stop working for the service on the fly or jump to Uber depending on the rates. 

## Problem Statement:
As the companies get bigger, the high churn could become a bigger problem. To find new drivers, Ola is casting a wide net, including people who don’t have cars for jobs. But this acquisition is really costly. Losing drivers frequently impacts the morale of the organization and acquiring new drivers is more expensive than retaining existing ones.


## Dataset/ Column Profiling:📋

The dataset at the heart of this exploration. Here are some of the key features:

## Data Dictionary

### Driver Dataset Documentation

### Description
This document outlines the structure and details of the driver dataset.

### Fields:

1. **MMMM-YY : Reporting Date (Monthly)**  
   - Represents the monthly reporting period in `MMMM-YY` format.

2. **Driver_ID : Unique ID for drivers**  
   - A unique identifier assigned to each driver.

3. **Age : Age of the driver**  
   - Age of the driver in years.

4. **Gender : Gender of the driver**  
   - Encoded values:  
     - `0` : Male  
     - `1` : Female  

5. **City : City Code of the driver**  
   - Code representing the city where the driver is based.

6. **Education_Level : Education level**  
   - Encoded values:  
     - `0` : 10+  
     - `1` : 12+  
     - `2` : Graduate  

7. **Income : Monthly average income of the driver**  
   - Represents the driver's average monthly income.

8. **Date Of Joining : Joining date for the driver**  
   - The date when the driver joined.

9. **LastWorkingDate : Last date of working for the driver**  
   - The last working date recorded for the driver.

10. **Joining Designation : Designation of the driver at the time of joining**  
    - The job title/designation when the driver started.

11. **Grade : Grade of the driver at the time of reporting**  
    - The grade level assigned to the driver.

12. **Total Business Value : Total business value acquired by the driver in a month**  
    - The business value generated by the driver in a given month:  
      - Positive value indicates revenue.  
      - Negative value indicates cancellations, refunds, or car EMI adjustments.

13. **Quarterly Rating : Quarterly rating of the driver**  
    - Ratings range from `1` to `5` (higher is better).


## 🚀 Mission 🚀

To get you started, here are some questions you might consider:

You are working as a data scientist with the Analytics Department of Ola, focused on driver team attrition. You are provided with the monthly information for a segment of drivers for 2019 and 2020 and tasked to predict whether a driver will be leaving the company or not based on their attributes like
- Demographics (city, age, gender etc.)
- Tenure information (joining date, Last Date)
- Historical data regarding the performance of the driver (Quarterly rating, Monthly business acquired, grade, Income)


## Concepts Used 
- Ensemble Learning- Bagging
- Ensemble Learning- Boosting
- KNN Imputation of Missing Values
- Working with an imbalanced dataset

## 📈 Let's Get Exploring 📊

Now that you're armed with questions and a powerful dataset, it's time to embark on your journey. Feel free to fork this repository, clone it to your local machine, and start diving into the code and data. Don't forget to share your findings and insights with the community.

Remember, the more we learn from this data, the better we can help companies like Jamboree around the world! 🌎🍿

Happy learning! 🚀👨‍💻🎬
