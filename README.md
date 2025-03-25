# Patient Waiting List Report Power BI

This project focuses on analyzing the total patient waiting list based on various case types (Outpatient, Inpatient, Day Cases), specialties, and patient age. The primary goal is to identify which specialties have the longest waiting times and how waiting times vary by patient age.

## High-Level Tasks Performed
-	Collected and integrated data from multiple source files to enhance understanding.
-	Performed data transformation and modeling using Power Query.
-	Designed initial sketches for data visualization.
-	Developed the dashboard layout and design.

## Objective
-	Track the current month's patient waiting list and compare it with the previous year.
-	Analyze the average and median wait times based on age and case type.
-	Identify historical trends in waiting lists by case type.
-	Provide detailed insights into the waiting list concerning age profile, time, and date.

## Data Scope
-	Time frame: 2018 to 2021

## Data Transformation and Modeling
-	Collected data from different source files (Outpatient and Inpatient for each year) and combined them in Power Query for data cleansing.
-	Applied data cleansing steps, including changing data types, trimming data, and removing unnecessary columns.
-	Standardized table structures by adding extra columns to the Outpatient table to ensure consistency before appending both queries for better analysis.

## Data Model
The structured data model includes:
-	**Fact Table:** Stores all patients' wait list details.
-	**Dimension Tables:** Contains details on specialty groups.
-	**Key Metrics & Calculations:** Utilized DAX formulas to measure total waiting lists for the current month, the same month in the previous year, and average wait times

![image](https://github.com/user-attachments/assets/95284707-392a-4906-9873-20e16bdff661)


## Dashboard Layout and Design

-	**Summary Page:** Displays key insights using card visuals, an interactive chart showing average or median wait times based on user selection, and a trend visual of the wait list over time. Three slicers are included, synchronized with the Detail Page.
-	**Detail Page:** Provides a matrix for deeper analysis, with additional slicers compared to the Summary Page for granular insights.

  ![image](https://github.com/user-attachments/assets/236d96fd-c23d-44c8-a62c-eab651ecf476)

  ![image](https://github.com/user-attachments/assets/e48a881d-4b44-48e4-9e1c-18aa3b235b1e)



## Key Insights & Takeaways 
-	The patient waiting list in March 2021 is higher compared to March 2020.
-	Outpatient wait lists have increased from 2018 to 2021, while Inpatient wait lists have shown less growth.
-	Total Outpatient Wait List: 21.7 million patients.
-	Total Inpatient Wait List: 2.9 million patients.
-	Specialty with the longest average wait list: Accident & Emergency, with an average wait list of 111 days.
 
## Link
https://www.loom.com/share/acd9c1b4050c4021b22cf758d2dcce4f?sid=925e4675-f46d-42bf-8b63-3161c9323e6b 
