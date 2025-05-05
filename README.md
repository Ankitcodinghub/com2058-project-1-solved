# com2058-project-1-solved
**TO GET THIS SOLUTION VISIT:** [COM2058 Project 1 Solved](https://www.ankitcodinghub.com/product/com2058-project-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99943&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COM2058 Project 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (4 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Within the scope of this project, you are expected to get used to the use of PostgreSQL, open source object-relational database system. In addition, it is expected that you will be able to query all possible SQL commands and create your own queries according to the desired output.

In the project, Task A part is given for you to install and get used to the programs (You do not need to put a screenshot in the document.).The main part you need to do is Task B, Task C and Task D. For Task B, there should be full screenshots of each query in the document. Projects of those who write the query on paper or cut the image will not be evaluated. The query and the output of the query should be clearly visible inside the image. For Task C, the queries should be handwritten on a piece of paper and the photograph should be attached to the document. And lastly, for Task D you must upload the updated Project_1.py as StudentNumber_Project_1.py and add the output images to the document.

You must submit the project as a single file in the “StudentNumber.pdf” format and StudentNumber_Project_1.py file. The project is individual and each student is expected to do it himself. In projects that are taken from each other or that are understood to be duplicates, all projects sent by the student will not be evaluated and the student’s overall lab grade will be considered “0”.

Task A: Getting Set Up

Before starting, you need to download PostgreSQL program from the “https://www.postgresql.org/download/” and install it on your computer. For more detailed information, the documents in the “https://www.postgresql.org/docs/” file can be examined.

After installing, you can access the program from the command prompt as shown in Figure 1.

Important Note: If you have not added the path of the PostgreSQL program to the system paths, you must work in the file location of the “bin” folder the program when running it at the command prompt.

For connection, you need to type the following command.  psql –U postgres –h localhost

After running that command, the password you specified during installation will be asked. After this process, your database connection is made and you can see that you are currently running “postgres=#”. Now it’s time to create the database you will be working on.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
 create database mydb;

The “\l” command shows the existing databases, the “\c” command shows which user is connected to the database, the “\d” command shows the properties of the table. The “\q” command logs out of the system.

You can also use the pgAdmin 4 program that comes by default in the installation instead of the command prompt. If it was not installed by default during installation, you can download it from the “https://www.pgadmin.org/download/” page. Of course, the pgAdmin program will also ask you for the password you set during installation for the connection. As you can see in Figure 2, all database operations on the command prompt screen are automatically detected by the pgadmin program. To run a query in the pgAdmin program, you must press the “Query Tool” button marked in blue in Figure 2.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1. PostgreSQL database connection example with command promt

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Task B: Querying – SQL!

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 2. Example of PgAdmin 4

</div>
</div>
<div class="layoutArea">
<div class="column">
Now, after getting a little familiar with the program, we come to the part where you have to do it!!! In this part, you need to import the attached northwind.sql. You can perform the queries on the command screen or in pgAdmin. This choice is up to you!

You can see the database structure in Figure 3. You must examine the recorded data in each table before performing the queries. The given database is widely used. You can search the internet for your questions about the database.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Attention!!! Each student should make the database name they create as their student number. Also, each student should create a schema named StudentNumber_Project1 and import the given .sql file in there.

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Figure 3. Nortwind Database

Write standard SQL queries to answer the following questions:

1. By finding the total price (unit_price*quantity) and discounted total prices (unit_price*quantity*(1-discount)) of the products, search for the top 10 when you sort them from high to low based on the discounted price calculation.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Attention!!! In order to get full marks, you need to obtain the same query outputs (pay attention to the column names and order). You are requested to specify the tables that you should use for queries. Therefore, it is expected that each student’s query will be unique.

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Figure 4. Question-1 Output

2. Query the total price of the products whose shipped_date value is between 1997-12-30 and 1998-1-5, and the data whose shipped_date value is null and the total price is greater than 4000.

Figure 5. Question-2 Output

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
3. Query the data whose discontinued value is “0” and whose reorder_level value is higher than 20 and units_on_order value is 0.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 6. Question-3 Output

4. In the specified columns, query the data that ends with “y” for Ship_country, starts with “M” for customer_id, and whose freight value is greater than 70.

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Figure 7. Question-4 Output

5. Write a query that calculates the total discounted price of all products by years (if there is no product, the value “0” will be written) and shows them by creating columns according to the years, with product_id less than 5 and customer_id starting with “E”.

Figure 8. Question-5 Output

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
6. Combine the Customers and Suppliers tables and query the data containing the letter “w” in the contact_name in the costumer table and the letter “g” in the suppliers contact_name.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 9. Question-6 Output

<ol start="7">
<li>Show the first 5 products with the highest unit_price value and the first 5 products with the lowest, in order by unit_price.Figure 10. Question-7 Output</li>
<li>Query to sum of the sales made since June-1997 on a yearly basis according to the category_name. (Set to write two digits after the dot.)</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
Figure 11. Question-8 Output

Task C: Relational Algebra – SQL!

Now, you are expected to rewrite the SQL queries you wrote in Task B using relational algebra. As mentioned before, you are expected to write the solutions manually on a piece of paper and attach the photo to the document. Queries should be clearly visible.

Task D: Connect the Database in Python

In this part, you are expected to connect to the database you have created using python and execute the queries you have written. To connect to the database, you must first have python installed on your system. Then, you should then run the following command.

 python -m pip install psycopg2-binary

After the installation is complete, you need to run the Project_1.py file given to you by filling in the required places and add the screen outputs you received as in the image to your document (Figure 12). You need to save the updated Project_1.py file as StudentNo_Project_1.py and upload it to the system.

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
Figure 12. Question-1 Output with Python

</div>
</div>
</div>
