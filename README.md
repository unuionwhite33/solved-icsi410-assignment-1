Download Link: https://assignmentchef.com/product/solved-icsi410-assignment-1
<br>
Download the Access file <strong>Asg1.accdb</strong> from Blackboard, and then rename the file name from

“<strong>Asg1</strong>” to your last and first names separated by an underscore. Don’t change the extension “<strong>accdb</strong>”. For example, mine would be <strong>borys_ted.accdb</strong>. Insert one row of data into each of the seven tables. You can choose whatever data values you choose with one exception: the one row in the Employee table must contain your first and last name. Then, if you wish, you may add any additional rows in any of the tables at any time to help you debug your query syntax. Next, create 10 separate Access SQL queries, named “Query1” through “Query10”. Each query will contain a SQL statement that is your solution for the translation of a “plain English” request. Each query is worth one point. The 10 “plain English” queries are:

<ol>

 <li>Display all the columns in Invoice for those rows with an iprice value greater than $10,500.</li>

 <li>Display all the columns in Invoice and sort the output first by ascending ieid and then further sub-sorted by descending iprice.</li>

 <li>Display only the cfirst, cmi, and clast columns in Customer.</li>

 <li>Join Employee and Invoice and display all columns.</li>

 <li>Join Customer, Relationship, and Dealership and display all columns.</li>

 <li>Join Dealership and Employee and display all columns when ehire is greater than 12/31/2017.</li>

 <li>Display all the columns in Vehicle for those rows that have one or more associated rows in Invoice.</li>

 <li>Display all the columns in Employee for those rows that don’t have any associated rows in Invoice.</li>

 <li>Count the number of rows in Vehicle.</li>

 <li>Display ieid and the count of the number of rows for each ieid value. Use just the Invoice table.</li>

</ol>

(You are counting the number of invoices for each employee.)

You are responsible for creating adequate test data to prove to yourself that your queries are working correctly. Your SQL statements must be logically correct and not simply return the “correct” results based on your choice of data. Each query is a single SQL statement (but may include subselects). Do <strong><em>not</em></strong> allow the possibility of duplicate rows in your answer. Use <strong>DISTINCT</strong> when necessary, but do <strong><em>not</em></strong> specify <strong>DISTINCT</strong> when it’s not needed. All joins must be done by matching the appropriate columns in the <strong>WHERE</strong> clause. In other words, you are <strong><em>not</em></strong> to use “<strong>INNER, </strong><strong>LEFT, </strong>or <strong>RIGHT JOIN</strong>” and “<strong>ON</strong>” syntax to perform the join operation; you will get no credit for doing this. One-quarter point (0.25) will be deducted for each of the following:

<ul>

 <li>Extra / missing distinct / distinctrow</li>

 <li>Extra / missing simple condition needed to join two tables</li>

 <li>Extra / missing column in the output</li>

 <li>Each table that has no rows in it</li>

 <li>Using a table name prefix for a column that doesn’t need it</li>

 <li>Any additional error</li>

</ul>

If a SQL statement has one or more <u>syntax</u> errors, it automatically earns a score of zero. If the execution of a SQL statement generates the “Enter Parameter Value” dialog box, it automatically earns a score of zero. There may be multiple, equally correct solutions for some or all of these problems