# Data Science Salary Analysis

## Introduction
This Data Jobs Salary Dashboard was created to help job seekers explore salary trends in data analytics and ensure they are fairly compensated for their roles.  
The dataset comes from Github public dataset by Luke Barousse. It includes detailed information on job titles, salaries, locations, and essential skills, all of which are presented in this dashboard.  
## Analysis Dashboard
The final dashboard can be checked in [Excel_Project_1_data_jobs_analysis_dashbaoard.xlsx](Excel_Project_1_data_jobs_analysis_dashbaoard.xlsx)
## Dataset Used
The dataset for this project features real-world data science job listings from 2023. It is available through [Github public dataset](https://github.com/lukebarousse/Excel_Data_Analytics_Course/tree/main/0_Resources/Datasets) by Luke Barousse. This dataset provides in-depth insights into:  
**:construction_worker: Job Titles**  
**:round_pushpin: Job Location**  
**:money_with_wings: Yearly and Hourly Salaries**  
**:wrench: Job Skills**  
## Excel Skills Used  
**:bookmark_tabs: Formulas And Functions**  
**:chart_with_upwards_trend: Charts**  
**:ballot_box_with_check: Data Validation**  

## Dashboard  
### :bookmark_tabs: Formulas And Functions
**💰 Median Salary Based on Title**
```
=MEDIAN(
    IF(
        (Data!$A$2:$A$32673=title)*
        (Data!$M$2:$M$32673<>0)*
        (Data!$K$2:$K$32673=country)*
       (ISNUMBER(SEARCH($E2,Data!$E$2:$E$32673))),
       Data!$M$2:$M$32673
      )
)
```
    Advanced Data Filtering & Analysis  
   **🔍 Multi-Criteria Filtering:** Applies filters based on job title, country, schedule type, while excluding entries with missing salary data.  
   **📊 Dynamic Array Formula:** Leverages the MEDIAN() function with nested IF() statements to analyze salary distributions across multiple conditions.  
   **🎯 Targeted Insights:** Delivers precise salary insights tailored to specific job titles, locations, and work schedules.  
   **🔢 Formula Functionality:** Automatically populates the table below by calculating the median salary based on the selected job title, country, and schedule type.  

**Table:**  
![image](https://github.com/user-attachments/assets/366b9e51-203b-43cd-8c88-b4489e48d2eb)

**⏰ Job Schedule Type**  

` FILTER(A2:A28,NOT(B2:B28)*(A2:A28<>0)) `  
    **🔍 Unique List for Job Schedule Type:** The Excel formula below uses the FILTER() function to remove entries containing "and" or commas while also excluding zero values.  
    **🔢 Formula Functionality:** This formula populates the table below, providing a distinct list of job schedule types.  

**Table:**   
![image](https://github.com/user-attachments/assets/7e8353d6-a5ee-485c-bb3c-2ba1b822395a)

### :chart_with_upwards_trend:Charts
**Data Science Jobs Salary Dashboard**

![image](https://github.com/user-attachments/assets/c2d6c255-73d2-41ec-bd34-426988eee6b0)
#### Excel Enhancements & Insights  
**📉 Chart Utilization:** Implemented a formatted bar chart to visually represent salary data with clarity.  
**🎨 Design Choice:** Chose a horizontal bar chart for easy comparison of median salaries across roles.  
**💡 Key Insights:** Quickly identifies salary trends, highlighting that Senior roles and Engineering positions tend to offer higher pay than Analyst roles.  

### :ballot_box_with_check: Data Validation

**🔍 Refined Data Selection**  
**🔒 Improved Data Validation:** Integrating the drop down list as a data validation rule for Job Title, Country, and Job Schedule Type in the Data tab ensures:  
  - 🎯 Users can only select from predefined, validated schedule types  
  - 🚫 Prevents errors and inconsistencies in data entry  
  - 👥 Enhances the dashboard’s usability and accuracy  

![DV  MConverter eu](https://github.com/user-attachments/assets/92c51e80-456a-40f3-9b93-305664b3c1ac)


## Conclusion

This dashboard was designed to get insights of salary trends across various data science related job roles.
Using public github dataset, it helps to make informed career decisions. Check the functionalities to find out how location and job type impact salaries.
