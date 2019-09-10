# BrainFluxTest

Implement a web project with Spring Boot which comprises two components:

## First Page
•	A webpage containing a button to load a time-series CSV file introduced here(https://archive.ics.uci.edu/ml/datasets/Air+Quality) into a local InfluxDB instance.
a.	The CSV file can be placed on your hard drive and it’s okay to hardcode the directory of the file into your Java program;
b.	You should use the influxdb-java package found here (https://github.com/influxdata/influxdb-java).

## Second Page
•	Another webpage to display a query result, which is the mean value of “CO(GT)” and the mean value of “NO2(GT)” for every day in 2004 along with the query you wrote to get this result.
a.	You can find an interactive data table framework at https://datatables.net/. This is NOT required, a plain table without interaction is completely accepted.


## Hints:
a.	The project should be runnable on a local machine;
b.	Check InfluxDB docs at https://docs.influxdata.com/influxdb/v1.7/;
c.	The purpose of this task is to test your familiarity with Java, general knowledge with SQL-like databases and your ability to learn unfamiliar technologies;
d.	Don’t waste your time on how the webpages looks. It would be fine as long as they are shown properly;
e.	There is no strict deadline, but it’s preferred that you can finish it during the weekend;
f.	Please upload your project to GitHub once finished so I can look at it.
