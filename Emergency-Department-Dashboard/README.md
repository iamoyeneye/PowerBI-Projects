# Emergency Department Operational Performance Dashboard

An interactive Power BI dashboard analysing emergency department patient volumes, waiting times and recorded patient satisfaction.

## Project Overview

The dashboard was developed to provide operational visibility into patient activity and waiting-time performance.

Users can analyse performance by:

- Reporting month
- Specialty
- Day of week
- Time period

The project demonstrates the development of an interactive reporting solution from data preparation through to data modelling, DAX measures and dashboard presentation.

## Key Insights

- Average waiting time exceeded the 30-minute practice target across several day and time combinations.
- The highest observed average waiting time in the March 2020 all-specialty view was 49 minutes on Wednesday between 12pm and 3pm.
- Patient volume increased by 17.4% compared with the previous month in the March 2020 view.
- Average waiting time decreased by 2.2% compared with the previous month despite the increase in patient volume.

## Technical Implementation

**Tools and techniques**

- Power BI
- Power Query
- DAX
- Data modelling
- Data validation and transformation
- Calendar dimension
- Time-band analysis
- Synchronized report filtering
- Conditional formatting
- Power BI Service

## Data Model

The report uses a structured data model centred on the emergency department activity dataset, supported by a dedicated calendar dimension and a time-band sorting dimension.

Dedicated DAX measures were created for:

- Patient volume
- Average waiting time
- Minimum waiting time
- Maximum waiting time
- Patient satisfaction
- Month-over-month comparisons

## Data Quality & Assumptions

Patient satisfaction is calculated from records containing a recorded satisfaction score. Blank satisfaction values are excluded from the average.

The 30-minute waiting-time threshold shown in the wait-time analysis page of the report is a practice assumption used for analytical demonstration. It should not be interpreted as an official performance standard.

The portfolio version of the dataset has been sanitised by removing direct name fields before publication.

## Portfolio

- [View the full project case study](https://iamoyeneye.github.io/emergency-department-dashboard.html)
- [View the interactive Power BI dashboard](https://app.powerbi.com/view?r=eyJrIjoiNGQ3ZTYzMWUtZDcyYy00NzgxLTkwMmYtYzMyMDc4MTA1N2JmIiwidCI6ImE5Y2E4ZmE1LWQwZWItNGFlYy1iYjAzLTZjOTljYzZlNmEwMSJ9)

## Project Status

Completed
