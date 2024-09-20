register-app
<br>
Test93

What is the use of 'between' command?
A. 'between’ can operate on any expression. Filters a record set for data matching the values in an exclusive range.
B. 'between’ can operate only on numeric, datetime, or timespan expression. Filters a record set for data matching the values in an inclusive range..
C. Option A & B
D. None of the above
2
What is the use of 'summarize' operator?
A. Return the number of rows in the result.
B. Produces a table that aggregates the content of the input table. 
C. Option A & B
D. None of them
3
Choose appropriate query to fetch data of a machine(Tom), for an Organization(Mindtree) between given time.
A. Table1 | where ReportTime between (datetime(2021-10-14 08:06:13)..datetime(2021-10-14 12:03:10)) | where OrgId == "Mindtree" | where MachineId == "Tom"
B. Table1 | where ReportTime (datetime(2021-10-14 08:06:13)..datetime(2021-10-14 12:03:10)) | where OrgId == "Mindtree" | where MachineId == "Tom"
C. Table1 | where ReportTime between(2021-10-14 08:06:13)..(2021-10-14 12:03:10)) | where OrgId == "Mindtree" | where MachineId == "Tom"
D. All of the above
4
What is the use of 'take' command?
A. 'Take' command specifies no. of columns required.
B. 'Take' command specifies no. of rows required.
C. 'Take' command specifies no. of active machines for an Org.
D. Both A & B
5
What is the use of 'count' command?
A. Count' command returns the maximum value across the group.
B. 'Count' command Produces a table that aggregates the content of the input table.
C. 'Count' command Evaluates its sole argument and returns a bool value indicating if the argument evaluates to a null value.
D. 'Count' command returns the number of records(rows) in the input record set. 
6
What is the 'Use of 'sort' command?
A. Sort the rows of the input table into order(desc/asc) by one or more columns. ​
B. Returns the first N records sorted by the specified columns.
C. Option A & B
D. None of them
7
What are Tables?
A. Tables has only Columns.
B. Tables has only Rows.
C. Tables are Entities that hold the data in form of columns and rows.
D. None of the above
8
What is KQL?
A. KQL is a Programming Language used to build system software.
B. KQL is a Kusto query language. It is read only query language. It is used to fetch or process the data from the data tables and return the result.
C. KQL is a web server where we host our websites.
D. All of the above
9
What are Clusters?
A. Clusters are entities that hold databases.
B. Clusters are referred by using a function cluster(url).
C. Both A & B
D. None of the above
10
What is the use of 'search' command?
A. Search command can only look at one table and one column for a specific text string.​
B. Search command can work by looking across one or more tables, through one or more columns for a specific text string.​
C. Both A & B
D. None of the above
11
On what basis 'take' command selects the sample rows from the result as output?
A. Selection is based on the value of Time column.
B. Selection is based on time when the record is ingested into the database.
C. Selection is affected by the use of 'sort' operator that needs to be mentioned prior to 'take'.
D. Selection is random and will change during multiple runs.
12
What is the use of 'Top' command?
A. 'Top' command returns the first N records sorted by the specified columns.
B. 'Top' command returns the random N records sorted by the specified columns.
C. 'Top' command returns the last N records sorted by the specified columns.
D. None of the above
13
From the list , select the one that can be used with summarize command.
A. sort
B. where
C. count()
D. count
14
What is the use of 'ago' command?
A. Filters based on the time range passed as arguments.
B. Subtracts the given timespan from the current UTC clock time.
C. Option A & B
D. None of the above
15
What is the  purpose of 'join' operator?
A. 'Join' command merge the columns of two tables to form a new table by matching values of the specified columns from each table.
B. 'Join' command merge the rows of two tables to form a new table by matching values of the specified rows from each table.
C. 'Join' command merge the rows of two tables to form a new table by matching values of the specified columns from each table.
D. All of the above
16
'let' command is
A. An alias to 'extend'.
B. used to bind expression to names.
C. used to filter the rows.
D. None of them
17
Which of the following statements are TRUE?
A. Using 'project' we can choose which columns we need to see in the output
B. Using 'project-away' we can choose which columns to include in the output
C. Using 'project' we can choose which columns to exclude from the result
D. Using 'project-away' we can choose which columns to exclude from the result.
18
'isnull' command is
A. An alias to 'isempty' command
B. checks whether a value is null
C. checks whether the value is an empty string
D. All of them
19
What is the difference between 'where' and 'search'?
A. 'where' and 'search' can be used interchangeably at all times(theoretically).
B. 'where' command filters on a specific predicate while 'search' command look for matching strings.
C. Both A & B
D. None of the above
20
What is the use of 'extend' command?
A. Appends a table to another table.
B. Merge two tables into one.
C. Create calculated columns and append them to the result set.​
D. None of the above
