# Water Quality and Infrastucture Analysis

This project aligns with United Nation's Sustainable Development Goal 6 (Clean Water and Sanitation), analyzing water quality and infrastructure improvement across seven provinces over a span of five years.
The project uses SQL to filter,transform and join data across multiple tables,identify challenges and monitor project progress. Also, it uses PowerBI to create engaging dashboard to drive decision making among stakeholders.
 various water sources analyzed including :
-Rivers
-Wells
-Shared taps
-Taps within homes
-Broken or non-functional taps

![vd mcq 2 3](https://github.com/user-attachments/assets/9f9906d5-8d0c-4d72-86e7-1eb9b5745168)

![water crisis 1](https://github.com/user-attachments/assets/e2ff9caf-91fe-4c0f-8846-e3d932514b8f)

## Project overview
The analysis is centered on:
-Identifying infrasturcture needs for various water source types
-Evaluating water sources based on pollution result
-Tracking employee data to assess improvment efforts and possible fraudulate activities
-Generating recommendations for improvement (e.g installing filters, installing taps,diagnosing infrastructure issues, etc)

## Database Structure
The project uses the following tables:
-**'Visits'**: Contains information on visits to each water source,including queue times, visit_count and assigned employees.

-**'Location'**: Stores location-specific information such as town,address and province.

-**'Water_source'**: Contains detailed information about different water source,the water type and population served.

-**'Well_pollution'**:Tracks pollution results for well water sources.

-**'Project_progress'**:Shows improvement on projects for each sources, status and comments.

## Key features
1. **Project Tracking**: Automatically updates improvrment recommendations based on water quality results and queue times.
2. **Employee Performance**: Monitors employee performance by tracking discrepancies between auditor and surveyor assessments.
3. **Infrastructure Recommendations**: Generates specific infrastructure improvment actions based on data (e,g.,installing UV filters in polluted wells)

## Technologies used
-**SQL**: For data extraction,cleaning,transformation, and advanced querying from related databases.

-**Power BI**: For interactive data visualization,dashboards and storytelling.

-**Git**: Version control and collaboration.
