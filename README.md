# Motor Vehicle Collisions/Crashes Analysis through Data Warehouse

This repository contains the final project for DAMG 7370: Designing Advanced Data Architectures for Business Intelligence at Northeastern University. The project involves analyzing motor vehicle collision data from three major cities: New York, Chicago, and Austin.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Project Phases](#project-phases)
  - [Part 1: Data Profiling and Staging](#part-1-data-profiling-and-staging)
  - [Part 2: Staging to Integration](#part-2-staging-to-integration)
  - [Part 3: Visualizations](#part-3-visualizations)
- [Reports and Analyses](#reports-and-analyses)
- [Author](#author)

## Project Overview

The project aims to analyze motor vehicle collision data from three cities to extract meaningful insights and present them through various reports and visualizations. The analysis will cover the number of accidents, areas with the highest accident rates, the involvement of pedestrians, temporal patterns, and factors contributing to accidents.

## Data Sources

The data for this project is obtained from the Department of Transportation for each city, available through the following links:
- [New York City Motor Vehicle Collisions](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data)
- [Austin Crash Report Data](https://data.austintexas.gov/Transportation-and-Mobility/Austin-Crash-Report-Data-Crash-Level-Records/y2wy-tgr5/about_data)
- [Chicago Traffic Crashes](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if/about_data)

## Project Phases

### Part 1: Data Profiling and Staging
- **Data Profiling**: Using tools like Alteryx or ydata profile.
- **Analysis Document**: Detailed document of the analysis.
- **Data Staging**: Staging tables created using Talend for ETL jobs.
- **Dimensional Model**: Creation of facts and dimensions with mapping documents explaining source to target transformations.

  ![image](https://github.com/yugallakhyani11/Motor_Vehicle_Collision_DW/assets/145067889/727679e8-d715-418d-a250-80a3b7d9a5ce)

### Part 2: Staging to Integration
- **ETL Jobs**: Talend ETL jobs for staging to integration.
- **Validation**: Query dimensional models to validate data and explain any row rejections.
- **Business Questions**: SQL queries to address provided business questions.
- **Dimensional Model**: Adding SCDs and Factless Fact to accomodate additional business requirements.
  ![image](https://github.com/yugallakhyani11/Motor_Vehicle_Collision_DW/assets/145067889/8f749071-d6bd-4b89-9ad4-800e0cb5d98f)

### Part 3: Visualizations
- **Tools**: Tableau and Power BI.
- **Reports**: Time-based analysis, fatality analysis, and common factors in accidents.
- **Uploads**: Screenshots and source workbooks.

## Reports and Analysis

The following key analysis based on Business Requirements will be performed:
- Number of accidents in each city.
- Top 3 areas in each city with the highest number of accidents.
- Reports on accidents resulting in injuries.
- Involvement of pedestrians in accidents.
- Temporal analysis of accidents (time of day, day of the week, seasonality).
- Motorists' injury and fatality statistics.
- Areas with the most fatal accidents.
- Common factors contributing to accidents.



## Author

Yugal Bharat Lakhyani
