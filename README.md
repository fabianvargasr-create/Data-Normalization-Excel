# [Data Normalization of Netflix Titles in Excel]

## 🎯 Project Overview
This project consist in the process of Normalization of unstructured data into a Relational DB, performed in Excel. 
The project were part of the Udemy course named Data Analysis | SQL, Tableau, Power BI, Excel | Real Projects. 
This dashboard was created using a dataset downloaded from the course, but also available in Kaggle. The information is related to Netflix Titles.



---

## 🛠️ Tech Stack & Tools
* **Data Processing:** Excel, the unstructured data was converted into First Normalization form, then second and finally the third Normalization Form.
* **Dataset Source:** Kaggle / Udemy Course. I downloaded from the course files available.

---

## 🚀 Key Insights & Business Value
* **Insight 1:** This is a key factor to be able to start the analysis of the data. Unstructured data has redundancy and inconsistent dependencies which
do not allow the proper analysis of Data. Many functions were used as Trim, Unique. To unpivot columns, the Power Query option were used. Independent tables
were created for each kind of information but always having the reference of the primary key. Aditional keys were created to eliminate repeated data and to have
better dependencies.
* **Insight 2:** As mention, without this process we can say that it is almost imposible to start the analysis of data, so is something critical.


---

## 📈 Dashboard Features & Architecture
The final Tableau workbook consists of a primary dashboard:
1. The dashboard has many insights about sells and other topics, as profit, revenue, how profit changes in percentage thought the years, some products sales numbers.
As well we can see top 10 products, sub-category profits divided by gender, sales by age group and by country. All of this information
can be filtered by year and/or by country. This information is important to get insights through time and geography. 


---

## 🔧 Data Preparation Process
As mention, data was normalized. There are 3 stages to complete this:
First Normal Form, in which it was confirmed that each row is unique, each cell contains single values and not lists, and each single value can not be reduced or divided further.
Here functions as Text to columns were used to splits lists found in cells, trim was used to ensure no spaces were found before any word, 
unique is used to get distint elements of a list, then convert into table format and use power query to put all data in different columns into one but with reference.

Second Normal Form, is the second stage and in there first all requirement from first form must be completed, and then it is needed to 
ensure that all non-key attibutes are fully dependant on primary key. This is done by creating new tables related to each type of data there but include the primary key in the 
same order, so that reference always exists and is accurate. 

Third Normal Form, the last stage and again, need to confirm that the requirements of the previous form were accomplished. In this last state the goal is to ensure that all fields must be
only determinable by the primary or compose keys and no other fields. 

I included 2 files, the first one is the raw and the one named normalized is the result of the process.

---
*Developed as part of my professional transition into Data Analytics & Automation.*
