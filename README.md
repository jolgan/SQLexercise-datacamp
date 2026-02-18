# Exploring London’s Travel Network (SQL on Snowflake & Databricks)

This repository contains a brief, guided SQL exercise completed as part of a micro-project on DataCamp, to practise querying data within **Snowflake** and **Databricks** environments using SQL. This learning artefact represents a documentation of my first hands-on exposure to **Snowflake and Databricks** environments, with the dataset already prepared and structured for querying.

## Data
The dataset is based on public transport journey volumes in London, originally published by **Transport for London (TfL)**. The data was loaded into both Snowflake and Databricks databases (titled `TFL`) (CSV file attached).

## Objectives
Three SQL queries were written to answer the following questions:

1. **Most popular transport types**  
   Aggregated total journeys by transport mode.

2. **Most popular months for the Emirates Airline cable car**  
   Identified the five highest-volume months, with results rounded to two decimal places.

3. **Least popular years for Underground & DLR journeys**  
   Found the five years with the lowest total journey volume.

## Key takeaways
- First exposure to **Snowflake** and **Databricks** cloud-based platforms for querying data
- Practiced core SQL fundamentals:
  - Aggregation and grouping (`SUM`, `GROUP BY`)
  - Filtering data using `WHERE`, `LIKE`, and null checks
  - Sorting and ranking results with `ORDER BY` and `LIMIT`
  - Using built-in functions such as `ROUND()`
  - Aliasing columns

Link to [DataCamp guided project](https://app.datacamp.com/learn/projects/exploring_londons_travel_network/guided/Snowflake)

