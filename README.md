# metro-rail
An implementation of a database for a metro railways system on Oracle RDBMS.

<h3>Background</h3>
The project was made as a submission for the subject DBMS in the 5th semester of BE. The project was made keeping in mind scalability and automation (no need for a DBA to look after it daily). The project is far away from achieving proper automation but lays the basis for it.

<h3>Files in Repository</h3>
<b>METRO.sql</b>: file contains the SQL code to create tables, triggers, procedures and functions.

<b>Metro Rail Management System.pdf</b>:  PDF file containing a Requirement Analysis, ER diagram and other stuff.

<h3>Details and Limitations of the project</h3>
<ul>
<li>The function to calculate the price of travel between two stations can currently only work if the stations are on the same line or on two intersecting lines. Otherwise it throws an error saying the calculation is beyond the scope of the system.</li>
<li>A metro line cannot be a loop and cannot fork anywhere. It is just a curvy line.</li>
<li>Two metro lines can intersect only once and a intersection station can only be a crossing for two lines.</li>
<li>A train can run on routes and routes can only exist on one line.</li>
<li>The source and destination of a route can be any stations as long as they are on the same line.</li>
</ul>
