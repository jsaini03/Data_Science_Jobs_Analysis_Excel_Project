# Data Science Jobs Analysis

## Understanding Salary Trends in different Data Science Roles

Since I am transitioning my career to data analyst, I got intrigued by data jobs salary dataset when I found it on github. The lack of accessible knowledge on the best-paying jobs and the most in-demand skills in the data science market was little confusing. So I decided to bridge that gap by analyzing what top employers look for and how certain skills impact salary potential. 

### 🔍Key Questions Explored

To better understand the data science job market, I explored:

**1. Which Data Jobs are paid more?**  
**2. What's the fair salary for Data Science Roles: Yearly Salary vs Hourly Salary?**  
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

### 🧮 Skills: PivotTables 

#### 📈Pivot Table
- Edited the data table using the Power Query Editor.
- Then added new measure to calculate the Hourly salary adjusted where I multiplied hourly rate with 2080 to find out the yearly compensation based on hourly rate.
- Moved the `job_title_short` to the rows area and `salary_year_avg` & 'hourly_slary_adjusted' into the values area to make a comparison.

![image](https://github.com/user-attachments/assets/6348b8d0-7c77-4931-b5c9-e39c7d1169da)

### 📊 Analysis

#### 💡 Insights

- 💰 The salary disparity between yearly and hourly is quite noticeable in high-tech jobs, which shows that the yearly salary jobs are well compensated as compared to hourly salary based jobs.
- Conversely in Hourly Based Salary, Senior roles in data science are well paid amongst all. Data Analyst and Business Analyst are on lower end but still very competitive. The variation depicts the different workload expectations.

![image](https://github.com/user-attachments/assets/17bf65c5-8d12-4402-a1d9-70bc770d697a)

## 3. What are the top skills among data professionals?

### 🔧 Skill: Power Query

#### 💪 Power Query

- 🔗 Created a reference table by extracting `data_jobs_skills` from the `data_jobs_salary`.
- 🧹 Data was cleaned using Power Query; Loaded it to generate the skill count pivot table and chart

![image](https://github.com/user-attachments/assets/3b25a3c9-0f72-4a13-ae35-e1230f1c9d92)

### 📊Analysis

#### 💡Insights

- 💻 SQL and Python remain the cornerstone skills for data-related roles, emphasizing their critical role in data processing and analysis.
- ☁️ The growing prominence of AWS and Azure highlights the industry's rapid transition toward cloud computing and big data solutions.

![image](https://github.com/user-attachments/assets/e638d21c-8b64-413e-bc80-0ead1fde3e37)


## 4. What’s the salary for the top 10 most in-demand skills?

### 📊 Skill: Pivot Chart

#### 📈 PivotChart

- Created a combo PivotChart to plot median salary and skill job count from my PivotTable.
    - 🪙 **Primary Axis:** Median Salary (as a Clustered Column)
    - 👍 **Secondary Axis:** Skill Job Count (as a Line with Markers)

### 📊 Analysis

#### 💡Insights

- 💰 Skills like Python and SQL ahve higher job counts, suggesting their critical role in high-paying tech jobs and offering fairly paid salaries.
- 📉 Spark, AWS, Azure skills yield high median salaries but Python and SQL are the most in-demand, making them essential for data roles.

   ![image](https://github.com/user-attachments/assets/af086574-38af-44ae-bcd7-4bd613a46878)

- This chart highlights the importance of investing time in learning high-value skills like Python and SQL, which are evidently tied to higher paying roles, especially for those looking to maximize their salary in the tech industry.

## Conclusion

As an aspiring Data Analyst, I worked on this Excel-based project to gain valuable insights into the data science job market. Using a curated dataset from real-world job postings(thanks to Luke Barousse), I analyzed job titles, salaries, locations, and essential skills. By utilizing Excel tools such as Power Query, PivotTables and charts, I identified key correlations between various skills and higher salaries, with Python, SQL, and cloud technologies standing out as top contributors. 






