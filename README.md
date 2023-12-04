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

## Steps

The project will include a full data life cycle with 5 main steps: 
a. Data Cleaning and Transformation
b. Descriptive analysis
c. Diagnostic analysis
d. Predictive analysis
e. Prescriptive analysis.
![image](https://github.com/MarkPhamm/Adventureworks-Analytics/assets/99457952/f51e16de-879d-4317-9ba5-f6cb0101cd85)

## Appendix
* **a. Data Cleaning and Transformation:** (SQL Server)
  * Assumptions
  * Transformation
  * New Star Schema
* **b. Descriptive Analysis:** (Python, Azure, and SQL)
  * Key Metrics Analysis
  * Time Series Analysis
  * Product Analysis
  * Customer Analysis
* **c. Diagnostics Analysis:** (Dashboard with PowerBI)
  * Time Series Dashboard
  * Geographical Dashboard
  * Demographic Dashboard
  * Product Selection Dashboard
* **d. Predictive Analysis:** (Machine Learning/Deep Learning using Python)
  * ARIMA Model
  * LSTM Model
  * Model evaluation
* **e. Prescriptive Analysis:** (Recommendation for the next year)
  * To-be Business model with Actionable Insight

# Analysis
## a. Data Cleaning and Transformation:
  * Assumptions
  * Transformation
  * New Star Schema

## b. Descriptive

### 1. Key Metrics
#### 1.1: Metrics
 - Total Revenue: $29
 - Total Profit: $9M
 - Total Tax Amount: $2,4M
 - Total Freight Cost: $734K
 - AVG Profit Margin: 42.84%
#### 1.2: Takeaways:
 - 

### 2. Time Series Analysis (Only 2011, 2012, 2013, Exclude Dec 2010 and Jan 2014)
#### 2.2: Takeaways: 
- **Yearly**
    - 2011: 7 Millions
    - 2012: 6 Millions
    - 2013: 14 Millions
    - 2014 and 2010: 2 Millions (December 2010 and January 2011)
- **Quarterly**
    - Better in the 2nd quarter than in the first quarter
- **Monthly**
    - Best: June, October, November, December
    - Worst: January, February, April
  
  #### 2.1: Graphs:
   * **2.1.1: Cumulative trends**
   ![image](https://github.com/MarkPhamm/Adventureworks-Analytics/assets/99457952/c938cd70-c199-4f1d-bdf2-30ea2344b556)
   * **2.1.2: Monthly Trends (by year)**
  ![image](https://github.com/MarkPhamm/Adventureworks-Analytics/assets/99457952/36c4edb9-a2b3-42e7-971d-7a71f5b2af92)
   * **2.1.3: Monthly BreakDown (Part as whole)**
  ![image](https://github.com/MarkPhamm/Adventureworks-Analytics/assets/99457952/7959357f-a15c-4c19-ba68-2c742374b3d3)
   * **2.1.4: Monthly (%) Comparison (By Years)**
  ![image](https://github.com/MarkPhamm/Adventureworks-Analytics/assets/99457952/1ba5c55e-a057-47b1-8269-1de03058fe0f)
### 3. Product Analysis
* Top Selling Product
### 4. Customer Analysis
* Customer Demographic
* Top 5 customer

## c. Diagnostics
### Geographical Dashboard
### Demographic Dashboard
### Product Selection Dashboard


## d. Predictive:
### ARIMA Model
### LSTM Model 
### Model evaluation

## e. Prescriptive:**
### Business Proposal (To-be​)Actionable Insight:
* Focus on Mountain bikes, especially the Model 200
* Focus on selling Accessories and Clothing for a higher Profit Margin
* Use the Machine Learning Model to Predict the demand for the next month for better preparation
* Deliver marketing campaign for the first half of the year (from January to May) with the customer Persona information Above

