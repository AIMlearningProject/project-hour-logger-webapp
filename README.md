# project-hour-logger-webapp
Webapp for logging in hours with a short summary. Calculates hours and outputs a CSV-file.


## Project read-me work in progress.

## How to use the app

Select start date to automatically populate the date fields, fill in start time and end time for each day of week. Click on lunch breack if you had one. Write a short summary of your work on the days you have worked. Lastly add the project code into its own field.
In monthly version, simply select start week and fill in weekly hours and short summary. In both cases, download the CSV and follow the steps below.


1. Dowload the CSV-file. 
2. Open Excel
3. Navigate to "Data" in Excel
4. Select "From text/CSV"
5. Locate your file, most likely in dowloads folder...
6. Select "import"
7. Select "custom" in separator, find the separator used in the preview window, should be just random character inbetween words.
8. Click "load" and your data will be shown in Excel sheet.
9. Wo-hoo! Your hours have beem logged into excel-file and you may save the excel file for later use.'

or.

1. Fill the form as per.
2. Click on save button.
3. Server redirects you to confirmation page where you can navigate back or sign out.
4. If instead error message pops up, fix the error and try to save again.

## Functions

- Rudimentary session handling
- Automatic field population
- Automatic hour calculation and conversion
- 5-days of logging, and
- monthly logging by the week
- Based on weeks, works over month borders
- Lunch break deduction
- lunch break length option
- file name field
- summary field
- weekly logging for whole month added
- total weekly hours
- total overall weekly hours for all weeks
- project partner logos
- separator change made in code, marked clearly for further changes. currently "£"
- database system functional
- login works
- sign out works
- weekly logs save works
- monthly logs save works
- 

## To-Do list

add or improve the following:
- Combining weekly and monthly datas
- security measures

