# Credit_Card-_Case_study-Data-Analysis-

<p align="center">
     <img width="400" height="200" src="https://user-images.githubusercontent.com/119164734/210168620-9a04f558-cb25-484a-9686-9c135fce4812.jpg">
</p>

# Promblem Statement:
A manager at the bank is disturbed with more and more customers leaving their credit card services. They would really appreciate if one could analyics for them who is gonna get churned so they can proactively go to the customer to provide them better services and turn customers' decisions in the opposite direction.
Now, this dataset consists of 500 customers mentioning their age, salary, marital_status, credit card limit, credit card category, etc. There are nearly 18 features.
 
Case Study:

1. No of customer Existing and Attrited by **Age wise, Salary, Marital_status, Education, Gender**?

2. Average utilization of Credit card by Existing and Attrited Customers?

3. Month on Booking data of the Existing and Attrited Customers customers?

4. Average transcation between the Existing and Attrition customers?

# Data Description:

| Features | Description |
|---|---|
|Attrition_Flag|Details about Existing/Attrited customers|
|Customer_Age|Details of the customers Age|
|Gender|Details of the Gender|
|Education|Status of the customer education|
|Marital_status|Single/Married/Divorced datails|
|Income_status| Customer salary status|
|Card_Category|Blue/Silver/Gold|
|Total_tran_Amount|Total amount transcation by credit card customer|
|Months_on_book|Booking of credit card by monthwise|

# Data Analysis:
**The process of examining data sets in order to find trends and draw conclusions about the information they contain**.

## 1.No of Customer Existing and Attrited  by Age wise, Salary, Marital_status, Education, Gender?

## Agewise Customers Attrited details:-

- Import the dataset into **MySQL** RDBM tool 
- Create a query :

<p align="center">
     <img width="800" height="200" src="https://user-images.githubusercontent.com/119164734/210177152-784468fc-2a6b-44a3-8c82-5015dc1cea08.png">
</p>

- Import the queries to POWER BI- Data Visualization Tool

<p align="center">
     <img width="800" height="400" src="https://user-images.githubusercontent.com/119164734/210177171-7949c398-412b-40f0-838c-d461691a4c53.png">
</p>

## Result:

- The number of customer attriting in **the age range of 40-50 years is the highest,followed by 50-60 years**.

- The possibility of customers attriting between **the age range 40-50 is the highest followed by 50-60 years**.

## Gender - Existing and Attrited Contribution:

- Create a query based on Gender - Existing and Attrited Contribution using MY SQL

<p align="center">
     <img width="800" height="200" src="https://user-images.githubusercontent.com/119164734/210177510-d1aa8f93-ac8f-4d3e-95ca-5628349d6fa2.png">
</p>

- Import the queries to POWER BI- Data Visualization Tool.

<p align="center">
     <img width="800" height="400" src="https://user-images.githubusercontent.com/119164734/210177523-2c80edf4-b253-4aec-863d-be119ceee8e1.png">
</p>

## Result:

- The number of Males is higher amongst both the attrited and existing customers.
- **The possibility of a Male customer attrited is higher than that of a Female customer**.

## Education- Existing and Attrited Customers:

- Create a query based on Education - Existing and Attrited Contribution using MY SQL

<p align="center">
     <img width="800" height="200" src="https://user-images.githubusercontent.com/119164734/210178064-0ed8fd38-8270-4d13-b9c2-b11c92fc30fa.png">
</p>

- Import the queries to POWER BI- Data Visualization Tool.

<p align="center">
     <img width="800" height="400" src="https://user-images.githubusercontent.com/119164734/210178062-511d1d1c-767e-4df7-85a0-a2662487327c.png">
</p>

## Result:
- The percentage of attrired customers to Existing Customers is fairly uniform amongst the different Educational level,however the attrited customer who are mostly **Doctorates and Post-graduate**.
- In other hand, existing customers are mostly from **Graduates and Higher school**.

## Income_Status - Existing and Attrited Customer:

Create a query based on Income_Status - Existing and Attrited Contribution using MY SQL

<p align="center">
     <img width="800" height="200" src="https://user-images.githubusercontent.com/119164734/210179017-4af25952-30bf-4fc1-843a-f6315949ed09.png">
</p>

- Import the queries to POWER BI- Data Visualization Tool.

<p align="center">
     <img width="800" height="400" src="https://user-images.githubusercontent.com/119164734/210179034-8e690218-31c8-45ed-8fc6-5c2c195029c4.png">
</p>

## Result:
- There is hardly any difference in the precentage of attrited to existing customers as per their income category.Its range between 17% - 20% across the difference level,hence we cannot predict the possibility of leaving customes based on their Income_Status.

## 2. Average utilization of Credit card by Existing and Attrited Customers?

The average use of credit card by Attrited and existing customers,analyst by MYSql

<p align="center">
     <img width="800" height="150" src="https://user-images.githubusercontent.com/119164734/210179544-440c18c8-557c-48df-8948-691f3406af52.png">
</p>

- Import the queries to POWER BI- Data Visualization Tool.

<p align="center">
     <img width="800" height="400" src="https://user-images.githubusercontent.com/119164734/210179674-c869025f-8bf2-4435-8849-f6e80f4baed5.png">
</p>

## Result:

- The average utilization of Attrited customers is 31.1% as comparing to 68.8% of existing customers,**hence we can summarize that the lesser the utilization on the credit card, the higher the chance of attrited**.

## 3. Month on Booking data of the Existing and Attrited customers?

Tenure of relationship with bank:

<p align="center">
     <img width="800" height="300" src="https://user-images.githubusercontent.com/119164734/210180083-f69e20dd-643c-4708-83dc-29188fcc96a1.png">
</p>

- Import the queries to POWER BI- Data Visualization Tool.

<p align="center">
     <img width="800" height="400" src="https://user-images.githubusercontent.com/119164734/210180093-71666a7e-bb23-415d-b138-aba336a1efaf.png">
</p>

## Result:
- The precentage of customer attrited is the highest,who have been with the bank for 30-40 months,foolowed by 40-50 months and 20-30 months.
- **We should concentrate the renge of 20-50 months customers with the bank**.

## 4. Average transcation between the Existing and Attrition customers?

Analysis the total transcation between the Existing and Attrition customers

<p align="center">
     <img width="800" height="200" src="https://user-images.githubusercontent.com/119164734/210180586-385c7ca9-3fb6-4c6d-9d5f-6e524066eb1a.png">
</p>

- Import the queries to POWER BI- Data Visualization Tool.

<p align="center">
     <img width="800" height="400" src="https://user-images.githubusercontent.com/119164734/210180587-c9dab038-e2d9-45ac-b864-6e7003b31d9d.png">
</p>

## Result:
- The average transcation of the attrited customers has the highest value than that of the existing customer.
- **We can conformed that the lesser transcation is directly illustrate the existing customers**

# Conclusion:

- The possibility of customer churning between the age range of 40-50 years is the highest,followed by 50-60 years.
- The possibility of a Male customers attrited is higher than that of a female customers.
- The risk of attrited is higher for the customer,who are Graduate and Higher school as comparing to the others.
- The precentage of customer attrited is the highest,who have been with the bank for 30-40 months,foolowed by 40-50 months and 20-30 months.**We should concentrate the renge of 20-50 months customers with the bank**.
- The lesser the utilization of credit card the higher the chance of attrition.









