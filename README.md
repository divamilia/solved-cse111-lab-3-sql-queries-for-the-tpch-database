Download Link: https://assignmentchef.com/product/solved-cse111-lab-3-sql-queries-for-the-tpch-database
<br>
In this Lab session you will write 15 SQL queries for the TPCH database. You will execute the queries for the data loaded in Lab 2 and check the results.

Write SQL statements for the following queries on the TPCH database (1 pt. per query):

<ol>

 <li>What is the address and phone number of “Customer#000000227”?</li>

 <li>What are the names of the suppliers with the smallest account balance? Print the name and thebalance.</li>

 <li>Find all the items with the returnflag set to “N” shipped on September 25, 1995. Print only the quantity and the extended price.</li>

 <li>What is the maximum completion time for a lineitem? (from commit date to ship date)</li>

 <li>What is the minimum and maximum account balance among the customers in the “BUILDING” market segment?</li>

 <li>What are the distinct countries of customers who ordered items in “December 1996”?</li>

 <li>What is the receipt date and the total number of items per that date ordered by “Customer#000000118”?</li>

 <li>Find the suppliers from “ASIA” who have at least “$1000” on account balance. Print their name and the account balance.</li>

 <li>Find the average account balance of the suppliers from countries with 5 or more suppliers. Print thecountry, the number of suppliers, and the average account balance.</li>

 <li>Find the total price of orders made by customers from “EUROPE” in 1996.</li>

 <li>How many distinct customers received at least a 4% discount at least one time?</li>

 <li>Find the total number of finished orders for customers from each region and print the result in decreasing order of these numbers. (see orderstatus; F stands for finished)</li>

 <li>Find the average account balance of all the customers from “EUROPE” in the “MACHINERY” market segment.</li>

 <li>Find how many “1-URGENT” priority orders have been posted by customers from “Brazil” between 1994 and 1997, included.</li>

 <li>Find the total number of “3-MEDIUM” priority orders supplied by suppliers in each country each year. Print the country, the year, and the number of orders.</li>

</ol>

<strong>Instructions. </strong>You are required to execute the queries on the TPCH database you populated in Lab 2. We provide you the correct answers for this database. We will check the correctness of your queries on a different database. Folder Lab3 under Lab contains an archive lab3-results.zip with the correct answers. There is a file for each query, e.g., 1.out for query 1, 2.out for query 2, etc. You are required to turn in an archive containing a file with the SQL statement for every query. The name of the files have to be 1.sql for query 1, 2.sql for query 2, and so on. There should be exactly 15 files in the archive file. The name of the archive file has to be firstname-lastname-lab3.zip where firstname and lastname are your first and last names, respectively. The type of the archive file has to be zip.