# Data Science Jobs Analysis

## Understanding Salary Trends in different Data Science Roles

Since I am transitioning my career to data analyst, I got intrigued by data jobs salary dataset when I found it on github. The lack of accessible knowledge on the best-paying jobs and the most in-demand skills in the data science market was little confusing. So I decided to bridge that gap by analyzing what top employers look for and how certain skills impact salary potential. 

### 🔍Key Questions Explored

To better understand the data science job market, I explored:

**1. Which Data Jobs are paid more?**
**2. What's the fair salary: Yearly Salary or Hourly Salary?**
**3. What are the top skills among data professionals?**
**4. What’s the salary for the top 10 most in-demand skills?**

### 📊 Excel Skills Used

For this analysis, I leveraged the following Excel capabilities:

- **📊 Pivot Tables:** for summarizing data
- **📈 Pivot Charts:** for visual insights
- **🧮 DAX (Data Analysis Expressions):** for calculations
- **🔍 Power Query:** for data transformation


### 📂 Data Jobs Dataset

The dataset used for this project contains real-world data science job information from the year 2023. The dataset is available via [Github Public Dataset](https://github.com/lukebarousse/Excel_Data_Analytics_Course/tree/main/0_Resources/Datasets) by Luke Barousse, which provides a foundation for analyzing data using Excel. 

It includes detailed information on:

- **👷‍♂️ Job titles**
- **💰 Salaries**
- **🌎 Locations**
- **🛠️ Skills**

## 1. Which Data Jobs are paid more?

### 🔍 Skill: Power Query (ETL)
#### 📥 Extract
   I used Power Query to extract data from the dataset file, creating two distinct queries:
    🗃️ A query containing all job-related data.
    🔧 A query listing skills associated with each job ID.

#### 🔄 Transform
  Transformed both queries by:
  - Adjusting column types.
  - Removing unnecessary columns.
  - Cleaning text to remove specific terms.
  - Trimming extra whitespace.
  - Transformed Data:

📊 data_jobs_salary
![image](https://github.com/user-attachments/assets/dd20c3f1-e262-4425-be1c-c46d64692948)

#### 🔗 Load
Loaded the transformed queries into the workbook, laying the groundwork for further analysis.

Loaded Data:

📊 data_jobs_salary
![image](https://github.com/user-attachments/assets/4fdc7968-49a1-452c-880a-6353a01e2409)

### 📊 Analysis

#### 💡 Key Insights

📈 The chart strongly encourages individuals to invest in developing data science, engineering, and machine learning skills to capitalize on the lucrative job market. Aspiring for leadership or senior roles can significantly boost earning potential in the data field.

## 2. What's the fair salary: Yearly Salary or Hourly Salary?




