# infs1200-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [INFS1200 Assignment 3 Solved](https://www.ankitcodinghub.com/product/infs1200-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118781&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;INFS1200 Assignment 3  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
INFS1200 Module 3 Assignment

Group Member 1

(This person should submit on Gradescope) Cao Quoc Thang Hoang 47594876

Group Member 2 Hoang Viet Nguyen 46769659

1. Overview

The purpose of this assignment is to test your ability to use and apply SQL concepts to complete tasks in a real-world scenario. Specifically, this assessment will examine your ability to use SQL Data Manipulation Language to return specific subsets of information which exist in a database and Data Definition Language to create new relational schema.

This assignment can be completed in group of two or individually. If done in a group, your partner must be enrolled in the same course.

2. Submission

All submissions must be made through an electronic marking tool called Gradescope, which will also be used for providing feedback and automated marking. You will need to submit two types of files to the autograder:

• Query Files: For each question in sections A, B and C, you are required to submit a .sql or .txt file which contains your SQL query solution for that question (only one of these files, if you submit both, the .sql file will be graded). The file should only contain the SQL query(s), no additional text. The file should be named as per the description in the question. Additionally, the number of queries allowed to be run per question is also specified in each question’s description.

When submitting to the autograder, please select all your .txt or .sql individually instead of uploading a zip file. Additionally, for student working in a group, only one group member should submit via Gradescope. The student submitting on behalf of their group must add their group member to their submission via Gradescope.

3. Marking

Brisbane QLD 4072 Australia CRICOS PROVIDER NUMBER 00025B

Grading and autograder feedback

Note that solutions to each question will be limited to contain a maximum of 3 queries.

When you submit your code, the autograder will provide you with two forms of immediate feedback:

• Simple instance data tests: The autograder will return your degree of success on the simple data instance, so that you can judge your progress (i.e. 90% of simple instance tests passed). Individual test results will not be revealed, and your submission’s performance on the more difficult instances will remain hidden until grades are released. Final weightings on the different test instances will also remain hidden until grades are released.

More details will be provided regarding how you can interpret the results of these tests and what it means for your assignment grade during practicals.

Materials provided:

You will be provided with the DB schema and the simple data instance. Because the autograder uses the same DBMS as your zones, you are encouraged to use your zones to develop your assignment answers.

The task is described on the next page

5. Task

For this assignment you will be presented with the simplified schema of an online movie streaming service. You will be required to write a combination of SQL DML and DDL queries which answer higher level questions about the data constrained in the database or perform operations against the database’s schema and instance data.

Assignment Specification

“Duration” refers to the time in seconds a customer has spent streaming a particular movie after the “Timestamp”.

Relational Schema

Customer [id, name, dob, bestFriend, subscriptionLevel]

Customer.bestFriend references Customer.id

Customer.subscriptionLevel references Subscription.level

Movie [prefix, suffix, name, description, rating, releaseDate]

Previews [customer, moviePrefix, movieSuffix, timestamp]

Previews.customer references Customer.id

Previews.{moviePrefix, movieSuffix} reference Movie.{prefix, suffix}

Streams [customer, moviePrefix, movieSuffix, timestamp, duration]

Streams.customer reference Customer.id

Streams.{moviePrefix, movieSuffix} reference Movie.{prefix, suffix}

Subscription [level, price]

A file containing this schema and a small data instance are included on Blackboard. For this assignment you will be required to write SQL queries to complete the following questions. Please use the submission boxes provided to record your answers, but do not forget to submit to the autograder as well!

Section A – SQL DDL

Example

Task The company has decided to stop recording and tracking how many customers preview movies. Write an SQL query to reflect this change in the database schema.

Explanation This change implies that the Previews table will no longer be needed.

SQL Solution DROP TABLE Previews;

Question 1

Task Write a SQL DDL query to implement the following relational schema and associated foreign keys.

Explanation The relational schema for this the new table is as follows:

Table: MovieEmployee

Column Data Type Allow Nulls? Primary Key?

moviePrefix VARCHAR(4) No Yes

movieSuffix VARCHAR(4) No Yes

employeeName VARCHAR(100) No Yes

role {“Actor”, “Production”, “Other”} No Yes

Additionally, no employee should be able to start two roles in the same or different movies on the same day.

The foreign keys for this new table are as follows:

MovieEmployee.{moviePrefix, movieSuffix} references Movie.{prefix, suffix}

Foreign key constraints should be implemented such that:

• Updates to a Movie’s prefix and/or suffix are automatically updated in MovieEmployee as well.

• A Movie cannot be deleted if there is an employee recorded as having worked on that movie.

File Name a1.txt or a1.sql

SQL Solution CREATE TABLE MovieEmployee ( moviePrefix VARCHAR(4) NOT NULL, movieSuffix VARCHAR(4) NOT NULL,

employeeName VARCHAR(100) NOT NULL,

role ENUM(‘Actor’,’Production’,’Other’) NOT NULL,

PRIMARY KEY(moviePrefix, movieSuffix, employeeName, role),

FOREIGN KEY (moviePrefix, movieSuffix) REFERENCES Movie(prefix, suffix) ON

UPDATE CASCADE ON DELETE RESTRICT

);

Question 2

Task The Company has decided to keep track of the country of origin for each movie. Write an SQL query(s) to capture this change.

Explanation This query should add an attribute “CountryOfOrigin”, which captures the country of origin via a country code of a maximum of three letters (e.g., AUS for Australia).

The attribute should be null for existing tuples.

File Name a2.txt or a2.sql

SQL Solution ALTER TABLE Movie

ADD CountryOfOrigin VARCHAR(3) NULL;

Section B – SQL DML (UPDATE, DELETE, INSERT)

Note: Modification made to the database schema made in previous questions are not persisted.

Example

Task Set the content rating of all movies called “Bad Day” to be “PG”.

Explanation The rating for each movie is captured using the rating attribute in the Movie table.

SQL Solution UPDATE Movie SET rating = “PG”

WHERE name = “Bad Day”

Question 1

Task In an effort to purge the system of fake customer accounts the Chief Information Officer of SurfTheStream has authorised all customer accounts to be removed that meet either (or both) of the following conditions:

• The account id has less than 3 characters. (e.g., “AA”)

• The customer is older than 110 or younger than 10 years old.

File Name b1.txt or b1.sql

SQL Solution DELETE FROM Customer C

WHERE CHAR_LENGTH(C.id) &lt; 3

OR YEAR(CURRENT_DATE) – YEAR(C.dob) &gt; 110

OR YEAR(CURRENT_DATE) – YEAR(C.dob) &lt; 10;

Question 2

Task Make the necessary modification to the database so that previews of “Harry Potter” movies are not shown to current customers.

Explanation The system will not show a movie preview if the customer has already previewed the movie. Therefore, for all movies with “Harry Potter” in the title create a fake preview record with the timestamp being the current time the query is run.

File Name b2.txt or b2.sql

SQL Solution INSERT INTO Previews (customer, moviePrefix, movieSuffix, timestamp)

SELECT C.id, M.prefix, M.suffix, NOW()

FROM Movie M, Customer C

WHERE M.name LIKE ‘%Harry Potter%’ AND NOT EXISTS (

SELECT *

FROM Previews P

WHERE P.customer = C.id

AND P.moviePrefix = M.prefix

AND P.movieSuffix = M.suffix

)

Section C – SQL DML (SELECT)

Example

Task Return the prefix and suffix of all movies with a rating of “M”.

Explanation This query should return a table with two columns. The first column should correspond to the movie’s prefix and the second column to the movie’s suffix.

SQL Solution SELECT prefix, suffix

FROM Movie

WHERE rating = “M”

Question 1

Task Return the id and name of all costumers that hold a ‘basic” subscription level in ascending order by age.

Explanation This query should return a table with two columns, the first containing the id of a customer and the second their name.

File Name c1.txt or c1.sql

SQL Solution SELECT C.id, C.name

FROM Customer C

WHERE C.subscriptionLevel LIKE ‘basic’

ORDER BY YEAR(C.dob) DESC, MONTH(C.dob) DESC, DAY(C.dob) DESC;

Question 2

Task Return the movies that have been streamed at least once during the past seven days.

Explanation This query should return a table with three columns of prefix, suffix, name of movies that have been streamed at least once. The 7-day time period is inclusive and should be correct to the second the query is run.

File Name c2.txt or c2.sql

SQL Solution

SELECT DISTINCT S.moviePrefix, S.movieSuffix, M.name

FROM Streams S

JOIN Movie M ON (M.prefix = S.moviePrefix AND M.suffix = S.movieSuffix)

Question 3

Task Return the number of movies which were released per year.

Explanation This query should return a table with two columns, the first containing a year, the second containing the number of movies released in that year. You do not need to represent years which had zero movies released.

File Name c3.txt or c3.sql

SQL Solution SELECT YEAR(M.releaseDate), COUNT(*)

FROM Movie M

GROUP BY YEAR(M.releaseDate);

Question 4

Task For each customer who has a best friend, return their id, name and age difference in comparison to their best friend.

Explanation This query should return a table with fours columns, the first for the id of the customer, the second for the name of the customer, the third for the name of their best friend and the four for the age difference (in days). The age difference should be calculated using:

Customer’s DOB – Customer’s best friend’s DOB

The MySQL documentation page for this function can be viewed here.

File Name c4.txt or c4.sql

SQL Solution SELECT C.id, C.name, F.name, DATEDIFF(C.dob,F.dob)

FROM Customer C

JOIN Customer F ON (C.bestFriend = F.id);

Question 5

Task Return the list of customer ids who have watched the same number of previews as their best friends.

File Name c5.txt or c5.sql

SQL Solution SELECT C.id, C.bestFriend, COUNT(P.customer)

FROM Customer C

JOIN Previews P ON (C.id = P.customer)

GROUP BY C.id

HAVING COUNT(P.customer) = (

SELECT COUNT(P2.customer)

FROM Previews P2

WHERE(P2.customer = C.bestFriend)

)

Question 6

Task Return a list of customers who have streamed exactly 5 distinct movies, of which at least one was streamed for over an hour.

Explanation This query should return a table with two columns, the first being customer ids and the second being customer names. Hint: Non-Correlated Subquery

File Name c6.txt or c6.sql

SQL Solution SELECT C.id, C.name

FROM Customer C

JOIN Streams S ON (S.customer = C.id)

WHERE S.duration &gt;= 3600 AND C.id IN (

SELECT S2.customer

FROM Streams S2

GROUP BY S2.customer

HAVING COUNT(S2.customer) = 5

)

GROUP BY S.customer

Question 7

Task Return the id and name of all customers who have previewed at least all the “Harry Potter” movies.

Explanation This query should return a table with two columns, the first being customer ids and the second being customer names. Any movie with “Harry Potter” in the title is considered a Harry Potter movie. Hint: Correlated Subquery

File Name c7.txt or c7.sql

SQL Solution SELECT C.id, C.name

FROM Customer C

JOIN Previews P ON P.customer = C.id

JOIN Movie M ON M.prefix = P.moviePrefix AND M.suffix = P.movieSuffix

WHERE M.name LIKE “%Harry Potter%”

GROUP BY P.customer

HAVING COUNT(*) = (SELECT COUNT(*)

FROM Movie M2

WHERE M2.name LIKE “%Harry Potter%”);

Question 8

Task For each customer, return the content rating that is most representative of the movies they have seen.

Explanation This query should return a table with two columns. The first containing the id of the customer and the second containing the content rating that is most representative of the movies they have seen. You can ignore customers who have not watched any movies. In cases that there is a tie between ratings, any would be ok to be returned.

Hint: VIEW.

File Name c8.txt or c8.sql

SQL Solution CREATE VIEW `CustomerRating` AS

SELECT S.customer, M.rating, COUNT(M.rating) AS content

FROM Streams S

JOIN Movie M ON (M.prefix = S.moviePrefix AND M.suffix = S.movieSuffix)

GROUP BY M.rating,S.customer

ORDER BY S.customer;

CREATE VIEW `result` AS

SELECT CR.customer, CR.rating

FROM CustomerRating CR

WHERE CR.content IN (

SELECT MAX(CR2.content)

FROM CustomerRating CR2

WHERE CR2.customer = CR.customer

GROUP BY CR2.customer

HAVING MAX(CR.content)

);

SELECT R1.customer, R1.rating

FROM result R1

LEFT JOIN result R2 ON (R1.customer = R2.customer AND R1.rating &lt; R2.rating)

WHERE R2.customer IS NULL;

Section D – Critical Thinking

1. In this section you will be presented with an abstract scenario(s) relating to the UoD provided in the task description.

Example

Task SurfTheStream is looking for customers who can work for the company as movie critics and write blogs on new releases. Propose two different strategies to complete the given task. Pick one of those two strategies and write an SQL query(s) that implements that strategy.

Strategies 1. Customers who watch a lot of movies are likely to meet the criterion defined in the question. We can go for customers who watched say at least 50 movies.

2. Customers who watch movies when they come out are likely to meet the criterion defined in the question. We can go for customers who watched several (say 10) movies within a week of the movie’s release.

SQL Solution SELECT C.*

FROM Customer C

JOIN Previews P ON P.customer = C.id

JOIN Movie M ON M.prefix = P.moviePrefix AND M.suffix = P.movieSuffix

WHERE DATEDIFF(P.timestamp, M.releaseDate) &lt; 8

GROUP BY C.id

HAVING COUNT(*) &gt; 9

Question 1

Task SurfTheStream wants to provide a free subscription level upgrade to loyal customers. Propose two different strategies to complete the given task. Pick one of those two strategies and write an SQL query(s) that implements that strategy.

Strategies 1. In order to be a loyal customer, a customer who watch a lot of movies in a fix and long duration (a month, a year…) and have high subscription level. We can go for customer who watch at least 10 movies in a month (approximately 2 times per week) and have.

2. Customer who has large total stream time is large. For instance, total stream time is 50 hours (equivalent to 180000 seconds) or more to have a free subscription to loyal customer.

SQL Solution SELECT C.id

FROM Customer C

JOIN Streams S ON (C.id = S.customer)

GROUP BY C.id

HAVING SUM(S.duration) &gt; 180000;

Section E – RiPPLE Task

• Resource Creation: Create one or more effective resource. For a learning resource to be considered as effective it needs to pass a moderation process which is administered by your peers and the teaching team. Teaching staff will be spot-checking to review moderations performed by just peers and change the outcome if necessary.

• Resource Moderation: Moderate 4 or more resources effectively. An effective moderation means that you have completed the moderation rubric and have provided a detailed justification for your judgement as well as constructive feedback on how the resource can be improved. Simply saying a resource is “good” does not qualify. Again, teaching staff will be spot-checking the quality of moderations and change the outcome when necessary.

• Answering Questions: Answer 10 or more questions correctly. To answer a resource correctly your first response must be correct. You can attempt as many questions as you want, and incorrect answers do not count against you. Only answers from the Practice tab are counted. Answering in-class RiPPLE activity questions does not count towards questions answers.

These tasks are to be completed individually through the RiPPLE platform, via the link available on Blackboard.

Note: For the above three activities, the resources you create, moderate and answer must be in the following categories on RiPPLE:

• SQL

• Functional-dependency

• Normalization

Creating, moderating or answering questions from other categories will not be counted towards your mark for the RiPPLE component of this assignment.
