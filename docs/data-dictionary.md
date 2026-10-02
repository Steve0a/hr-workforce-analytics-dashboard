# Data Dictionary

This document describes the major field groups used in the HR Workforce Analytics Dashboard. Exact field names may vary slightly between the source files and Tableau workbook.

## Employee and Workforce Fields

| Field group | Example fields | Use in analysis |
|---|---|---|
| Employee identifier | Employee ID | Identifies individual employee records |
| Employment status | Hired, Terminated, Status | Supports workforce activity and termination views |
| Hire and termination dates | Hire Date, Term Date | Supports time, tenure, and employment-duration analysis |
| Department and job role | Department, Job Title | Supports departmental and role-level comparisons |
| Location | Location, City, State, HQ/Branch | Supports organizational and geographic distribution views |

## Demographic Fields

| Field group | Example fields | Use in analysis |
|---|---|---|
| Gender | Female, Male | Supports gender composition and comparison views |
| Birth date / age | Birthdate, Age | Supports age-group and compensation views |
| Education level | High School, Bachelor, Master, PhD | Supports workforce education analysis |

## Compensation and Performance Fields

| Field group | Example fields | Use in analysis |
|---|---|---|
| Salary | Salary, Average Salary | Supports compensation comparisons by demographic and role |
| Salary band | Low, Medium, High, Very High | Supports grouped pay analysis |
| Performance | Performance Rating, High Performer indicator | Supports performance-related segmentation |

## Derived Fields

| Derived field | Description |
|---|---|
| Age | Calculated from birth date and the analysis date |
| Employment duration | Calculated from hire date to termination date or reference date |
| Salary band | Categorizes salary values into analysis ranges |
| High-performance indicator | Flags records meeting the selected performance threshold |

## Data Use Notice

The project uses fictional/synthetic data for portfolio and learning purposes. Do not substitute or upload confidential employee data to a public repository or Tableau Public.
