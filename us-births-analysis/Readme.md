### Explore U.S. Births

This is the first guided project in Dataquest.io's Data Science path (Python basics course)

Both files contain US births data:

US_births_1994-2003_CDC_NCHS.csv contains U.S. births data for the years 1994 to 2003, as provided by the Centers for Disease Control and Prevention's National Center for Health Statistics

US_births_2000-2014_SSA.csv contains U.S. births data for the years 2000 to 2014, as provided by the Social Security Administration

Both files have the following structure:

Header | Definition
---|---------
`year` | Year
`month` | Month
`date_of_month` | Day number of the month
`day_of_week` | Day of week, where 1 is Monday and 7 is Sunday
`births` | Number of births

The Jupyter notebook contains some basics analysis on both datasets, including: 

- U.S. births counts by period (year, month of a year, day of a month, day of a week)
- Least and most births counts by granularity 
- Trend analysis: same values from different periods
- Difference of births counts each year between the 2 datasets (in percentage)
