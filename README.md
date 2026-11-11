# School Data Analysis with Power BI

Power BI analysis of Australian school data from 2009 to 2018. The report looks at
students, schools and staff across states and territories, school sectors
(Government, Catholic, Independent), school levels and gender.

## Repository contents

| Path | Description |
|------|-------------|
| `School Data Analysis.pbix` | Main Power BI report |
| `School.pbix` | Earlier/alternate version of the Power BI report |
| `School Data Analysis.pdf` | PDF export of the report |
| `School Data/Schools/` | Number of schools per year (`2009_schools.csv` … `2018_schools.csv`) |
| `School Data/Students/` | Student counts per year (`2009_students.csv` … `2018_students.csv`) |
| `School Data/Staff/` | Staff counts per year (`2009_staff.csv` … `2018_staff.csv`) |

## Datasets

**Schools** — `State/territory, School sector, School level, Schools`

**Students** — `Full-time/part-time status, State/territory, School sector, Sex, School level, Indigenous status, Students`

**Staff** — `State/Territory, Sector, Sex, School Level, Function, Staff`

## Report highlights

- Total students by year (2009–2018) and by state (NSW, VIC, QLD, WA, SA, TAS, ACT, NT)
- Students by sector: Government (~65%), Catholic (~20%), Independent (~14%)
- Students by year and sector, by state and school level, and by sector and gender
- Map of students by state

## How to use

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Windows).
2. Clone this repository.
3. Open `School Data Analysis.pbix`.
4. If the data does not load, go to **Transform data → Data source settings** and point
   the source folder to the `School Data` folder in your local copy, then click **Refresh**.

To view the report without Power BI, open `School Data Analysis.pdf`.

## Tools

- Power BI Desktop
- Power Query (combining yearly CSV files)
- DAX measures
