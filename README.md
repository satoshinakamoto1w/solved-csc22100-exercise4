Download Link: https://assignmentchef.com/product/solved-csc22100-exercise4
<br>
<ol>

 <li>Consider the Student database and Listing 25.2 in Chapter 25 of the textbook. Your tasks are:</li>

 <li>Amend the database to include the following Tables:</li>

</ol>

Students(<u>studentID</u>, firstName, lastName, email, sex)

Courses(<u>courseID</u>, courseTitle, department)

Classes(<u>courseID</u>, <u>studentID</u>, <u>section</u>, year, semester, GPA)

The underlined attributes are the primary keys of theirs corresponding tables.  The value of attribute sex may be either ‘F’ or ‘M’.  The Only GPAs allowed in the database are A, B, C, D, F, and W.

<ol start="25">

 <li>Amend Listing 25.2 to build and test a Java application that connects to the amended database, creates and populates the Students, Courses, and Classes Tables.</li>

 <li>Amend Listing 25.2 to return and display the number of students enrolled in CSc 22100 in the Spring 2020 semester for each letter grade.</li>

 <li>Utilize the Java class PieChart in Exercise 3 to build and display a pie chart showing the proportion of students for each GPA. In the pie chart:</li>

</ol>




<ol>

 <li>Each segment has a different color;</li>

 <li>Each segment has a legend showing the corresponding GPA and number of students;</li>

</ol>

<ul>

 <li>The segments for the GPAs are displayed in alphabetical order.</li>

</ul>

<ol start="2">

 <li>Your report should include the full Java code including all DDL and SQL statements used. In addition, the report should have all DDL and SQL scripts used in a separate section with appropriate heading.</li>

 <li>The report should show the output tables of the given query and corresponding pie chart for a sufficient amount of input data.</li>

 <li>Your application should utilize JavaFX graphics and “PreparedStatement” objects for the execution of SQL statements/queries.</li>

 <li>You may use any Relational Database Management System (RDBMS) of your choice.</li>

</ol>


