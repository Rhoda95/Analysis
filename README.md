# Analysis

### Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)

### Project Overview
This contains what your project is all about and what you aim to achieve


[picture dashboard.xlsx](https://github.com/user-attachments/files/20361526/picture.dashboard.xlsx)


```SQL
[UploaDROP DATABASE IF EXISTS `RHODA`;
CREATE DATABASE `RHODA`;
USE `RHODA`;

CREATE TABLE FOOD_PRICE_LIST(
S_N INT,
ITEM_NAME VARCHAR (50),
QUANTITY INT,
UNIT_PRICE FLOAT (50),
TOTAL_PRICE FLOAT (50),
primary key (S_N));

INSERT INTO FOOD_PRICE_LIST(S_N, ITEM_NAME, QUANTITY, UNIT_PRICE, TOTAL_PRICE)
VALUE
(1, 'BAG OF RICE', 2, 10,000.00, 20,000.00),
(2, 'BAG OF BEANS', 2, 70,000.00, 140,000.00),
(3, 'BIG TIN MILK', 2, 12,000.00, 24,000.00),
(4, 'BIG TIN MILO', 2, 11,000.00, 22,000.00),
(5, 'TIN TOMATOES', 1, 24,000.00, 24,000.00);

SELECT FROM RHODA.FOOD_PRICE_LIST;

ding FOOD PRICELIST.sql…]()
```

### Data Source
Market data: The secondary source used for this project is the "market_data.csv" file, contains complete information about each sale made by the organization.

### Tools
- Excel - Data cleaning
  
  [Download here](Htpps//microsoft.com)
- SQL - Data analysis
- PowerBi - Creating a report

  ### Data cleaning/Preparation
In the initial data preparation phase, we performed the following task:
1. Data loading and inspection
2. Handling missing values
3. Data cleaning and formatting
   
   
### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as
- What is the overall sales trend?
- Which products are top sellers?
- What is the peak sales period?

  ### Data Analysis
  ```SQL
  SELECT * FROM table 1
  where condt. =2;
  ```

  ### Results/Findings
  The analysis results are summarized as follows:
1.	Company’s sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
2.	Product category A is the best performing category in terms of sales and revenue
3.	Customer segment with high lifetime value (LIV) should be targeted for marketing efforts. 

### Recommendation
- Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales seasons to maximize revenue
- Focus on expanding and promoting products in category A.
- Implement a customer segmentation strategy to target high LIV customers effectively.

  ### Limitations
  I had to remove all zero values from budget and revenue column because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even after the omissions but even then, we can still see that theirs is a positive correlation between both budget and number of votes with revenue.

  ### Reference

  1. SQL for Business by Mary
  2. [Stack Overflow](Https//stack.com)

     

