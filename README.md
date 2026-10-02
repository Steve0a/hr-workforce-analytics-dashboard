# HR Workforce Analytics Dashboard

An interactive Tableau dashboard that turns fictional HR data into workforce insights across hiring, terminations, demographics, compensation, job roles, education, and geography.

**Live dashboard:** [View on Tableau Public](https://public.tableau.com/app/profile/steve.o.a/viz/HRDashboard_17909717904240/HRDetails)

> **Data note:** This portfolio project uses a fictional/synthetic HR dataset. It is intended to demonstrate analytics, data-visualization, and storytelling skills—not to represent a real organization or its employees.

## Dashboard Preview

![HR Workforce Analytics Dashboard](images/dashboard-overview.png)

*Add `dashboard-overview.png` to the `images/` folder to display the primary dashboard preview here. See [images/README.md](images/README.md) for all screenshot names.*

## Project Goal

This project demonstrates how HR data can be organized into an interactive decision-support dashboard. The analysis helps users explore workforce composition, hiring and termination patterns, compensation differences, performance-related views, job-title distribution, education levels, and employee location patterns.

## Business Questions

- Which departments and job titles account for the highest hiring volume?
- How do hires and terminations vary by department and workforce segment?
- How is the workforce distributed across headquarters, branches, and states?
- What workforce patterns appear across gender, age group, and education level?
- How do average salaries vary by role, age, and education level?

## Tools Used

- **Tableau** — interactive dashboard design, calculated fields, filters, mappings, and visual storytelling
- **Python / pandas** — data cleaning, missing-value checks, category standardization, and derived fields
- **Excel / CSV** — source-data review and preparation
- **GitHub** — project documentation and portfolio presentation

## Dashboard Sections

| Section | What it explores |
|---|---|
| Department analysis | Hiring and termination counts by department |
| Job-title analysis | Workforce/hiring distribution across roles |
| Location analysis | Headquarters vs. branch distribution and geographic coverage |
| Demographics | Gender, age-group, and education-level patterns |
| Compensation | Average salary by age, job title, education level, and gender |

## Project Workflow

1. Reviewed and prepared the HR source data in Excel and Python.
2. Checked for missing values in key fields such as salary, performance rating, hire date, and termination date.
3. Standardized category values and date formats.
4. Created derived analytical fields, including age, employment duration, salary bands, and performance-related indicators.
5. Built individual Tableau worksheets for departments, job titles, locations, demographics, education, and salary relationships.
6. Combined the views into an interactive Tableau dashboard and published it to Tableau Public.

## Portfolio Observations

The following observations are descriptive summaries of the published fictional dataset and should be interpreted as dashboard exploration prompts rather than conclusions about a real company:

- Operations has the largest displayed hiring volume, followed by Sales and Customer Service.
- The location view shows approximately 70% of displayed hires at branch locations and 30% at headquarters.
- The education-level view shows Bachelor’s degree holders as the largest displayed group.
- Salary patterns differ by job title, age, education level, and gender, making these useful areas for compensation review.
- Workforce activity spans several U.S. states, with the map supporting location-level exploration.

See [docs/insights-and-recommendations.md](docs/insights-and-recommendations.md) for interpretation guidance and possible HR actions.

## Repository Structure

```text
hr-workforce-analytics-dashboard/
├── data/                         # Optional fictional source/processed data
├── dashboard/                    # Tableau workbook files
├── docs/                         # Project documentation
├── images/                       # Dashboard screenshots used in this README
├── README.md
├── LICENSE
└── .gitignore
```

## Add the Tableau Workbook

Upload your workbook using one of these exact paths:

- `dashboard/HR_Workforce_Analytics_Dashboard.twb` for the Tableau workbook file
- `dashboard/HR_Workforce_Analytics_Dashboard.twbx` for the packaged workbook, if you choose to share it

Read [dashboard/README.md](dashboard/README.md) before uploading. A `.twbx` can include data extracts, so verify that it contains only fictional, shareable data.

## Add Screenshots

Add dashboard images to `images/` using the filenames in [images/README.md](images/README.md). Once added, the main preview image will automatically appear at the top of this README.

## Viewing the Project

- Use the [Tableau Public dashboard](https://public.tableau.com/app/profile/steve.o.a/viz/HRDashboard_17909717904240/HRDetails) for interactive exploration.
- Use this repository for project context, methods, documentation, dashboard screenshots, and optional files.

## Author

Steve Okyere Oduro-Amoyaw

---

If you use or adapt this project, please credit the author and retain the fictional-data disclosure.