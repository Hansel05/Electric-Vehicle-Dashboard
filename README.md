# Electric Vehicle Dashboard

## Project Overview
 A comprehensive analysis of the electric vehicle (EV) market in India, focusing on trends, challenges, and opportunities for growth.

## Data Source
The dataset used in this project is stored in **electric_vehicle_sales_by_makers**, **electric_vehicle_sales_by_state**, **dim_date**.

Column description for **electric_vehicle_sales_by_makers**:
- **date**: The date on which the sales data was recorded. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- **vehicle_category**: The category of the vehicle, specifying whether it is a 2-Wheeler or a 4-Wheeler.
- **maker**: The name of the manufacturer or brand of the electric vehicle.
- **electric_vehicles_sold**: The number of electric vehicles sold by the specified maker in the given category on the given date.
***
Column description for **electric_vehicle_sales_by_state**:
- **date**: The date on which the data was recorded. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- **state**: The name of the state where the sales data is recorded. This indicates the geographical location within India.
- **vehicle_category**: The category of the vehicle, specifying whether it is a 2-Wheeler or a 4-Wheeler.
- **electric_vehicles_sold**: The number of electric vehicles sold in the specified state and category on the given date.
- **total_vehicles_sold**: The total number of vehicles (including both electric and non-electric) sold in the specified state and category on the given date.
***
Column description for **dim_date**:
- **date**: The specific date for which the data is relevant. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- **fiscal_year**: The fiscal year to which the date belongs. This is useful for financial and business analysis.
- **quarter**: The fiscal quarter to which the date belongs. Fiscal quarters are typically divided as Q1, Q2, Q3, and Q4.
