# General Overview
This analytics project aims to boost AdventureWorks Cycles' revenue by analyzing company data. The process includes accessing the data warehouse, data cleaning, and transformation, followed by a detailed examination to extract valuable insights for strategic decision-making.

**Goal**: 
* **Interactive:** Discover trends and make informed decisions in their respective roles.
* **Dynamic, Real-time Update:**  Our charts and dashboards dynamically update in real-time as data

## About AdventureWorks Cycles
AdventureWorks Cycles, headquartered in Bothell, Washington, is a major multinational manufacturer of metal and composite bicycles. With a strong presence in North America, Europe, and Asia, the company employs 500 individuals and strategically deploys regional sales teams to serve its diverse market base.

![image](https://github.com/MarkPhamm/Adventureworks-Analytics/assets/99457952/677fbdee-9968-4ad1-b424-100208ade77e)


## Tools
**Tools used:** SQL Server, Python notebook, PowerBI, Azure Data Studio

## Appendix
![image](https://github.com/MarkPhamm/Adventureworks-Analytics/assets/99457952/f51e16de-879d-4317-9ba5-f6cb0101cd85)
* **a. Data Cleaning and Transformation:** (SQL Server)
  * Assumptions
  * Transformation
  * New Star Schema

   
* **b. Descriptive Analysis:** (Python, Azure, and SQL)
  * Step 1: Key Metrics Analysis
  * Step 2: Time Series Analysis
  * Step 3: Product Analysis
  * Step 4: Customer Analysis
 
* **c. Diagnostics Analysis:** (Dashboard with PowerBI)
  * Step 5: Time Series Dashboard
  * Step 6: Geographical Dashboard
  * Step 7: Demographic Dashboard
  * Step 8: Product Selection Dashboard
  
* **d. Predictive Analysis:** (Machine Learning/Deep Learning using Python)
  * Step 9: ARIMA Model
  * Step 10: LSTM Model
  * Step 11: Model evaluation
  
* **e. Prescriptive Analysis:** (Recommendation for the next year)
  * Step 12: To-be Business model with Actionable Insight

# Analysis
## a. Data Cleaning and Transformation:
  * **Assumptions**
  * **Transformation:** Given that we don't require all the columns from the table, it is advisable to cherry-pick only the essential ones. Additionally, we plan to:
    * Data cleaning by standardized datetime values for improved consistency.
    * Eliminate unnecessary columns
    * Apply more reader-friendly names.
    * Introduce new calculated columns, including Profit, Profit Margin, ShipStatus, TimeToArrive, TimeToShip, Model Name, and Customer Age for enhanced analytical insights.
  * **New Star Schema:**
     ![image](https://github.com/MarkPhamm/Adventureworks-Analytics/assets/99457952/ea06b28f-57af-4e2f-8ca8-ea94243f9495) 

## b. Descriptive Analysis

### 1. Key Metrics
 - Total Revenue: $29M
 - Total Profit: $9M
 - Total Tax Amount: $2.4M
 - Total Freight Cost: $734K
 - Profit Margin: 42.84%

### 2. Time Series Analysis (Only 2011, 2012, 2013, Exclude Dec 2010 and Jan 2014)
- **Yearly**

![image](https://github.com/MarkPhamm/Adventureworks-Analytics/assets/99457952/ea6be652-d5bf-4c36-aebe-c8fb8c1c5147)

    - 2011: 7 Millions
    - 2012: 6 Millions
    - 2013: 14 Millions
    - 2014 and 2010: 2 Millions (December 2010 and January 2011
  
- **Monthly**

![image](https://github.com/MarkPhamm/Adventureworks-Analytics/assets/99457952/7d7a5735-85c7-4e03-8e73-9160c59b46b1)

    - Best: June, October, November, December
    - Worst: January, February, April

### 3. Product Analysis
- **Overview**
  - Bikes (95% Profits) (Clothing for 4%) and (Accessories for 1%)
  - Best Selling: Model 200 (mountain bikes)
- **Cutting/Reintroduction**
  - Model Mountain 100 has been cut, in replaced with Mountain 400-500, with relatively low revenue (first year).
  - 2011: Mountain 100,  2012: Mountain 200, 2013 Mountain: 200, 400, 500
  - 

- **Specific**
### 4. Customer Analysis
#### Takeaways: 

## c. Diagnostics Analysis
### 5. Time Series Dashboard (Why was 2013 Revenue so high?)
- Mountain Bikes Sales increase
- Accessories and Clothing was introduced
- Touring Bikes was introduced (Generating 3.7 million dollars).
### 6. Geographical Dashboard
### 7. Demographic Dashboard
### 8. Product Selection Dashboard


## d. Predictive Analysis:
### 9. ARIMA Model
### 10. LSTM Model 
### 11. Model evaluation

## e. Prescriptive Analysis:
### 12. Business Proposal (To-be​) Actionable Insight:
* Shift focus from Road bikes to Mountain Bikes
* Focus on Mountain bikes, especially the Model 200
* Focus on selling Accessories and Clothing for a higher Profit Margin
* Use the Machine Learning Model to Predict the demand for the next month for better preparation
* Deliver marketing campaign for the first half of the year (from January to May) with the customer Persona information Above

