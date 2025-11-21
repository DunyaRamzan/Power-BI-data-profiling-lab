# Power BI data profiling lab
![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Analytics-F2C811?logo=Power%20BI)
![SQL Server](https://img.shields.io/badge/SQL%20Server-Database-CC2927?logo=microsoft-sql-server)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-217346?logo=microsoft-excel)
![Skillable](https://img.shields.io/badge/Skillable-Virtual%20Lab-2E7DFF)

# 📝 Project Overview
This project is based on a Power BI lab completed entirely inside the Skillable virtual environment as part of the data bootcamp i completed. 
####  📌 The lab focused on:
#### 📌 Connecting Power BI Desktop to a SQL Server database
#### 📌 Importing multiple tables and CSV files
#### 📌 Exploring and profiling data using Power Query
#### 📌 Identifying missing values, inconsistencies, and potential key fields
#### 📌 All work was completed inside the virtual machine so the source datasets cannot be shared externally. This repository contains the completed PBIX file and a screenshot of the final lab.

# 🚀 Objectives
#### 📌 Load and explore data in Power BI Desktop
#### 📌 Use Power Query to assess column quality, distribution and profile
#### 📌 Identify missing, inconsistent or unreliable values
#### 📌 Verify key columns for relationships
#### 📌 Combine multiple data sources in a structured way
This mirrors the early stages of a real world analytics workflow.
# 🔌 Connecting to SQL Server
Inside the Skillable VM:
#### 📌 Connected Power BI to a local SQL Server instance (localhost)
#### 📌 Imported tables from the AdventureWorksDW2020 dataset including:
#### 📌 DimEmployee
#### 📌 DimProduct
#### 📌 DimReseller
#### 📌 FactResellerSales
These tables were explored and profiled using Power Query.

# 🔍 Data Exploration in Power Query
Power Query’s built in profiling tools helped identify potential issues and understand data structure:
## ✔ Column Quality
#### 📌  Checked percentages of valid, error, and empty values
#### 📌  Example: Position column in DimEmployee had a high number of blank entries
## ✔ Column Distribution
#### 📌  Checked distinct and unique values for potential key columns
#### 📌 Example: EmployeeKey had 296 distinct and 296 unique values — reliable for relationships
## ✔ Column Profile
#### 📌  Identified inconsistencies like variations in the BusinessType field in DimReseller
These steps ensure data is clean and ready for modelling or reporting.

# 🗂 Importing CSV Data
Two CSV files were included in the lab and imported into Power BI Desktop:
#### 📌 ResellerSalesTargets.csv – monthly sales targets
#### 📌 ColorFormats.csv HEX codes for conditional formatting
Missing values were represented with hyphens which would normally be cleaned in later steps.

# 🖥️ Tools Used
#### 📌  Power BI Desktop (Skillable virtual machine)
#### 📌  Power Query
#### 📌  SQL Server (Skillable VM)
#### 📌  CSV files included with the lab

# 📁 Repository Contents
As the datasets only exist inside the Skillable virtual lab the repository includes:
#### ✔ Completed PBIX file
#### ✔ Final lab completion screenshot
No raw SQL or CSV data is included.

# 📝 Key Takeaways
Completing this lab strengthened my skills in:
#### 📌  Connecting Power BI to SQL Server in a virtual environment
#### 📌  Exploring and profiling data before analysis
#### 📌  Spotting missing, inconsistent, or unreliable data
#### 📌  Reviewing potential key columns for relationships
#### 📌  Working with multiple data sources in a structured workflow
These are foundational skills for professional analytics projects.

# 🏁 Summary
This Skillable virtual lab gave me practical experience in data preparation and quality assessment within Power BI. It reinforced the importance of understanding and cleaning data before building any dashboards or models an essential step in any real world analytics workflow.

<img width="379" height="236" alt="image" src="https://github.com/user-attachments/assets/00029a63-47f6-4034-97fa-68b1f2199d5d" />

