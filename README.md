# E-Commerce Delivery & Logistics Performance Analysis

## Project Overview
An end-to-end data analytics project analyzing delivery and logistics performance using the Brazilian Olist E-Commerce dataset.

## Technologies Used
- Python
- Pandas and NumPy
- SQL (SQLite)
- Power BI
- Jupyter Notebook

## Key Business KPIs

| KPI | Result |
|---|---:|
| Total Orders | 99,441 |
| Cancelled Orders | 625 |
| Cancellation Rate | 0.63% |
| Eligible Delivered Orders | 96,470 |
| On-Time Orders | 88,644 |
| On-Time Delivery Rate | 91.89% |
| Average Delivery Duration | 12.56 days |
| Average Late Delay | 9.55 days |
| Purchase-to-Carrier Time | 3.23 days |

## Customer Satisfaction

| Delivery Type | Average Rating |
|---|---:|
| On Time | 4.29 |
| Late | 2.57 |

Late deliveries are associated with lower customer review scores in this dataset.

## Project Modules
1. Data cleaning and preprocessing using Python.
2. Delivery KPI calculations.
3. SQL validation of Python results.
4. Regional delivery performance analysis.
5. Customer rating comparison.
6. Interactive Power BI dashboard.

## SQL Validation
SQL calculations were compared with Python results. The main delivery KPIs, regional rates, and customer-rating comparisons were successfully validated.

## Business Insights
- Overall on-time delivery rate is 91.89%.
- Late orders have an average delay of 9.55 days.
- Late deliveries have a lower average review score than on-time deliveries.
- Regional delivery performance varies across states.

## Dataset
Brazilian Olist E-Commerce Public Dataset.

## Project Structure
- data/ — Dataset files
- notebooks/ — Python analysis notebooks
- sql/ — SQL validation queries
- olist_logistics.db — SQLite database

## Project Objective
To identify delivery performance gaps and provide data-driven insights that can support better logistics operations and customer satisfaction.
