# Sales-Report

### Dashboard Link : https://app.powerbi.com/groups/me/reports/44f4e622-fbf2-4504-86fa-216e2d4c08f2/ReportSection?experience=power-bi


## Business Request & User Stories

The business request for this data analyst project was an executive sales report for sales managers. Based on the request that was made from the business we following user stories were defined to fulfill delivery and ensure that acceptance criteria’s were maintained throughout the project.

![2](https://github.com/LostVayne9919/Sales-Report/assets/117676583/5916ccc9-0f9d-40c1-966a-d591666ef6c0)


## Data Cleansing & Transformation (SQL)
To create the necessary data model for doing analysis and fulfilling the business needs defined in the user stories the following tables were extracted using SQL.

One data source (sales budgets) were provided in Excel format and were connected in the data model in a later step of the process.

Below are the SQL statements for cleansing and transforming necessary data.
        

### DIM_Calendar:
![DIM_Calender](https://github.com/LostVayne9919/Sales-Report/assets/117676583/42dc2a2a-cd3b-4c36-82a2-a50f3d5dc8b8)

### DIM_Customers:
![DIM_Customers](https://github.com/LostVayne9919/Sales-Report/assets/117676583/ad27ea4c-61bc-4dcd-8047-8d8a99f95ea3)

### DIM_Products:
![Dim_Products](https://github.com/LostVayne9919/Sales-Report/assets/117676583/a95fe431-675b-42ed-a92e-af61aecdc604)
## FACT_InternetSales:
![Facts_Sales](https://github.com/LostVayne9919/Sales-Report/assets/117676583/1121738b-8048-4f6a-8889-2901919557cf)
# Data Model
Below is a screenshot of the data model after cleansed and prepared tables were read into Power BI.

This data model also shows how FACT_Budget hsa been connected to FACT_InternetSales and other necessary DIM tables.

![Datamodel](https://github.com/LostVayne9919/Sales-Report/assets/117676583/2253e2bb-a037-4a3f-a3ac-23f1c514ee09)

# Sales Management Dashboard    
The finished sales management dashboard with one page with works as a dashboard and overview, with two other pages focused on combining tables for necessary details and visualizations to show sales over time, per customers and per products.

![pro](https://github.com/LostVayne9919/Sales-Report/assets/117676583/bb9a90ca-46fd-4995-ae75-88727d5cd77e)
