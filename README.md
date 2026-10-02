# Chicago Social & Educational Data Analysis (SQL)

## Project Overview
This project explores the relationship between socioeconomic indicators, school performance, and crime rates in Chicago. By integrating three distinct datasets, I used SQL to uncover how a community's environment influences health, education, and public safety.

## Technical Skills Demonstrated
* **Database Management:** Loading raw CSV data into a **SQLite** database using Python and the `sql` magic extension.
* **Advanced SQL:** Utilizing `JOINs`, `GROUP BY`, and `Subqueries` to aggregate data across multiple tables.
* **Data Integration:** Connecting the `CENSUS_DATA`, `CHICAGO_PUBLIC_SCHOOLS`, and `CHICAGO_CRIME_DATA` tables.

## Key Insights
* Found a direct correlation between high **Hardship Index** scores and lower school safety ratings.
* Identified the specific communities with the highest crime rates relative to their per capita income.
* Mapped schools that are "beating the odds" in high-hardship neighborhoods.

## How to Run
1. Clone the repo: [GitHub repository](https://github.com/almustafaomer-debug/Chicago-Urban-Data-Analysis-SQL)
2. Install dependencies: `pip install pandas sqlalchemy ipython-sql`
3. Open `Chicago_Data_Analysis.ipynb` in Jupyter or VS Code.
