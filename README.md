# Analysis_on_Bicycle_purchase

![image](https://github.com/user-attachments/assets/82aca801-7515-457b-bb50-7b3827bd9895)

This is an excel data analysis using CRISP-DM framework. This is a refresher project for me in excel to analyze and understand bicycle purchases with respect to gender, distance of commute, and age. I extract data, clean, manipulate, use pivort tables, and create charts to clearly show trends we can make inferences from. 

## Business Understanding

The main objective of this analysis is to understand how various factors influence a customer’s decision to purchase a bicycle. The conclusion from this project could be used to plan restocking based on customer demand. Also, it could be important in terms of location of stores and the demographics in these locations. 

## Data Understanding

The dataset is an excel sheet with data on factors that may have influenced a customer’s decision to purchase a bicycle. It includes demographic attributes such as marital status, gender, age, education level, and income.
Also, it covers lifestyle indicators like occupation, home ownership, number of children, number of cars owned, and commute distance. The dataset also specifies whether an individual purchased a bike or not, allowing for deeper insights into purchasing behavior.

## Data Preparation

After downloading the data and understanding it, we begin by data cleaning. I created 3 additional sheets namely working sheets, pivot table, and dashboard. This is because I didn’t want to interfere with the raw data and also give me the chance to experiment more with the raw data. Copying the raw data unto the working sheet, I first checked for duplicate data and removed 26 duplicates. Then moving from column after column, I cleansed and manipulated the data. As can be seen when compared, in the Marital Status column ‘M’ and ‘S’ were replace with ‘Married’ and ‘Single’. Gender column F and M were replace with ‘Female’ and ‘Male’. 10 + Miles was replaced with ‘More than 10 Miles’. Decimal places in the income column were removed. Another column, Age Brackets’ was created out of the ‘Age’ column, and using the IFS(), ‘Senior’, ‘Middle Age’, and ‘Young Adult’ were created for different age groups. 

## Pivot Tables and Graphs

On the Pivot table sheets, 3 pivot tables were created. 
### Table 1: Average Income Per Purchase

![image](https://github.com/user-attachments/assets/385bbf80-bf73-495b-b004-e3e578da1138)

### Graph1: 
![image](https://github.com/user-attachments/assets/36388567-238d-4b83-a901-c4fda675334f)

### Table 2: Count of Purchased by commute distance

![image](https://github.com/user-attachments/assets/342304c6-8d6c-43b6-a087-4cbc49f93ef9)

### Graph 2:
![image](https://github.com/user-attachments/assets/4c41c423-9ee6-4e4a-957a-8741f2a2c92e)

### Table 3: Count of purchase by age group

![image](https://github.com/user-attachments/assets/1eab3ba4-4cbf-433f-a7d6-7d96f6b890cf)

### Graph 3: 
![image](https://github.com/user-attachments/assets/0c1935d0-2e28-49c0-b1d6-3afe46b09911)

