# 📊 HR Analytics Dashboard – Power BI  

---

## 🧠 The Story Behind This Project  

While exploring datasets to build my first Power BI project, I came across an HR dataset containing employee details such as age, salary, job roles, departments, and attrition status.  

Instead of just creating visualizations, I wanted to solve a real-world problem:  

👉 **Why do employees leave a company?**  

Employee attrition is a major challenge for organizations as it leads to increased hiring costs, productivity loss, and disruption in workflow.  
Through this project, I aimed to analyze employee data and uncover meaningful patterns that can help organizations understand workforce behavior and improve retention strategies.  

This project marks my step into the world of **data analytics and storytelling using data**.  

---
## 📌 Steps followed:

[Download the dataset from here](YOUR_DATASET_LINK)

### 1. Data Gathering:

- Importing raw data (.csv file) into Power BI and transforming it using Power Query Editor for cleaning and data processing.

### 2. Data Cleaning:

- Removing empty columns, duplicates, and errors.  
- Replacing incorrect or inconsistent values with proper naming conventions.  
- Detecting and correcting data types using the auto-detect feature in Power Query Editor.  

### 3. Data Processing:
 - In the Power Query editor, creating new column called "AttritionCount" by using conditional column feature in add column which is created on the basis of certain condition like (IF attrition = 'Yes' then 1, Else 0).
  - This new column is further used for creating different KPI's and charts.Then creating the Attrition Rate by applying DAX queries, adding new measure (Attrition Rate = SUM([AttritionCount]))/SUM([Employeecount])) in %.
          
### 4. Data Analysis:
  - Analysis involves the creation of a range of visual representations, including bar charts, key performance indicators (KPIs), line charts, pie and donut charts, and other relevant visualizations.
  - These tools are utilized to gain insights and present data in a comprehensive and easily understandable manner.
    
---
## 🔍 What This Dashboard Explores  

This dashboard focuses on analyzing employee data to identify patterns behind attrition and workforce distribution.  

Some of the key questions explored in this project include:  

- How many employees are currently working in the company?  
- What percentage of employees leave the organization?  
- Which age group has the highest attrition?  
- Which salary range experiences the most employee turnover?  
- Which job roles and departments have the highest attrition?  
- How does education background impact attrition?  
- Do employees leave more in the early years of their career?

---

## 📊 Key Insights Summary:

1. **Total Employees:**  
   The organization has a total of **1470 employees**, representing the overall workforce size.

2. **Attrition Analysis:**  
   A total of **237 employees left the organization**, resulting in an attrition rate of **16.1%**.  
   Male attrition is higher compared to female employees.

3. **Departmental Attrition:**  
   The **Research & Development department** experienced the highest attrition, indicating a need for improved retention strategies.

4. **Education Field Impact:**  
   Employees from the **Life Sciences field** show the highest attrition, highlighting a key area of concern.

5. **Job Role Affected:**  
   Roles such as **Laboratory Technician and Sales Executive** have the highest attrition rates.

6. **Education-wise Attrition:**  
   Employees with **High School education** show the highest attrition rate among all education levels.

7. **Attrition by Age Group:**  
   The age group **26–35 years** has the highest attrition (116 employees), indicating higher job-switching in early career stages.

8. **Salary Impact:**  
   Employees earning **≤ 5K salary** show the highest attrition, suggesting salary is a major factor.

9. **Tenure Insight:**  
   Most employees leave within the **first 2 years**, indicating early dissatisfaction or better opportunities elsewhere.


## 🛠️ Tools & Technologies Used  

- Power BI  
- Power Query (Data Cleaning & Transformation)  
- DAX (Data Analysis Expressions)  
- Data Visualization Techniques  
- HR Dataset (CSV)  

---

## 📷 Dashboard Preview  

![Dashboard](YOUR_IMAGE_LINK_HERE)

---

## 📚 What I Learned From This Project  

Working on this project helped me understand that data analytics is not just about building dashboards, but about **telling meaningful stories with data**.  

Through this project, I learned:  

- How to clean and transform raw data  
- How to build interactive dashboards in Power BI  
- How to derive insights from data  
- How to present findings using visual storytelling  

This project strengthened my interest in the field of **data analytics**.  
 

---

## 💬 Feedback  

If you have any suggestions or feedback on how this dashboard can be improved or what additional insights can be explored, feel free to share your thoughts.  

Constructive feedback is always appreciated 🙌  

---

## ⭐ Support  

If you found this project helpful, consider giving it a ⭐ on GitHub!  
