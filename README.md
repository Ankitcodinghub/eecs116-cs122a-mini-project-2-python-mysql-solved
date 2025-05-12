# eecs116-cs122a-mini-project-2-python-mysql-solved
**TO GET THIS SOLUTION VISIT:** [EECS116_CS122A Mini-Project 2-Python + MySQL Solved](https://www.ankitcodinghub.com/product/eecs116_cs122a-mini-project-2-python-mysql-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;90984&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EECS116_CS122A Mini-Project 2-Python + MySQL Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Mini-Project 2 – Python + MySQL

In this project, we will create a database and tables using MySQL, and import the data into tables. Then you are required to write a Python program that implements a non-graphical user interface for MySQL. Your Python program should interact with the user and provide complete sentences to answer a selection of queries. Due by 5PM on Tuesday 3/9. Turn in the .py source code file to “Mini Project 2” on Canvas.

Deliverable

A .py source code file for this project.

STEP 1 – Set Up MySQL

For testing and grading purposes, you must follow the guide below to create and use a new MySQL account.

1. Open MySQL Workbench, select the “Administration” tab on the left then click “Users and Privileges”.

2. Click “Add Account” button, enter “mp2” for Login Name and “eecs116” for password. Click “Apply”. You can ignore the following warning:

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3. Keep the newly created account selected, switch to the “Schema Privileges” tab.

4. Click the “Add Entry” button, select “All Schema” then click OK. Click “Select ‘ALL’”, then Apply.

5. Click the on the top left to return to the homepage. Click to create a new connection to the “mp2” account. Enter the user name and password.

6. Once logged in, create a schema named “flights” and make it the default schema.

7. Click button and open the create_table.sql file. Click execute to create tables.

Then click again to open the import_data.sql file. Execute to import data. The flight database has 9 relations:

The relation Airport contains basic information about an airport

The relation Flight contains basic information about a complete flight route

The relation Flight Leg contains information about a flight segment within that route

The relation Leg instance contains information on a flight leg from a particular day

The relation Fare contains information on a fare for a flight

The relation Airplane type has information about different airplane models

The relation Can land has information about whether a certain type of airplane can land at a particular airport

The relation Airplane has information about a single airplane

The relation Seat reservation has information about a particular reservation for a flight

8. Now your MySQL is set up and ready to use.

STEP 2 – Install the Library

We will use PyMySQL library to connect Python to MySQL.Before we start, make sure you have MySQL 5.6 or above and Python 3.6 or above. This is the minimum requirement, you need to upgrade MySQL and Python if you do not meet this requirement.

To install PyMySQL, open your command prompt(Windows) or Terminal(macOS) and

type:

We provide some code snippets below. You can start to modify the code to do this project and provide the requested functions described at the end of this document.

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑝𝑝𝑝𝑝𝑝𝑝h𝑜𝑜𝑜𝑜3 − 𝑚𝑚 𝑝𝑝𝑝𝑝𝑝𝑝 𝑝𝑝𝑜𝑜𝑖𝑖𝑝𝑝𝑖𝑖𝑖𝑖𝑖𝑖 𝑃𝑃𝑝𝑝𝑃𝑃𝑝𝑝𝑃𝑃𝑃𝑃𝑃𝑃

OR

(If you only installed Python3) 𝑝𝑝𝑝𝑝𝑝𝑝h𝑜𝑜𝑜𝑜 − 𝑚𝑚 𝑝𝑝𝑝𝑝𝑝𝑝 𝑝𝑝𝑜𝑜𝑖𝑖𝑝𝑝𝑖𝑖𝑖𝑖𝑖𝑖 𝑃𝑃𝑝𝑝𝑃𝑃𝑝𝑝𝑃𝑃𝑃𝑃𝑃𝑃

</div>
</div>
<div class="layoutArea">
<div class="column">
(If you installed both Python2 and Python3)

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
– Sample Code –

In the beginning of the py file, import the library you need:

import pymysql

To Create a Connection with MySQL Server for the database “sample_python”:

In the host part, ‘localhost’ is the address of the server (127.0.0.1 means the localhost which is your own computer; if you want to connect to other computers just change the address), and “flight” is the database name. This code snippet uses user id “mp2” and password “eecs116” to login.

To Perform SQL Queries: To Get the Results:

To Add a Tuple into a Table:

Note that:

– “default” means to use the default value for customer_ID, which is auto-incremented.

Use db.close() to end the connection.

STEP 3 – Write the Python Program

You are about to build a demo program for an AI database capable of interacting with the user through English rather than SQL. Your Python program should interact with the user through the Python console. Your demo program will handle at least the following six queries/tasks with corresponding answers:

1. Query: Find the cheapest flight given airports and a date. Please enter the airport code for the departure airport:

</div>
</div>
<div class="layoutArea">
<div class="column">
db = pymysql.connect(host=’localhost’,

</div>
</div>
<div class="layoutArea">
<div class="column">
user=’mp2′,

</div>
</div>
<div class="layoutArea">
<div class="column">
passwd=’eecs116’,

</div>
</div>
<div class="layoutArea">
<div class="column">
db= ‘flight’)

</div>
</div>
<div class="layoutArea">
<div class="column">
cur = db.cursor()

</div>
</div>
<div class="layoutArea">
<div class="column">
sql=”SELECT * FROM customer”

</div>
</div>
<div class="layoutArea">
<div class="column">
cur.execute(sql)

</div>
</div>
<div class="layoutArea">
<div class="column">
for row in cur.fetchall(): # cur.fetchone() gets one result at a time

</div>
</div>
<div class="layoutArea">
<div class="column">
print(row)

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
sql = (“””INSERT INTO bank.customer(customer_ID, customer_name)

</div>
</div>
<div class="layoutArea">
<div class="column">
VALUES(default, %s)”””) # %s is a place holder for inserting a variable here

</div>
</div>
<div class="layoutArea">
<div class="column">
val = (cust_name) # customer name is stored in variable cust_name

</div>
</div>
<div class="layoutArea">
<div class="column">
cur.execute(sql, val)

</div>
</div>
<div class="layoutArea">
<div class="column">
cur.commit() #use commit to save the changes you made to the database

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Please enter the airport code for the destination airport:

What is the date of the flight in yyyy-mm-dd?

Result: The cheapest flight is $FlightNumber, and the cost is $FareAmount.

2. Query: Find the flight and seat information for a customer. Please enter the customer’s name:

Result: The flight number is $FlightNumber, and the seat number is $SeatNumber.

3. Query: Find all non-stop flights for an airline. What is the name of the airline?

Result: The non-stop flights are: $FlightNumber1, $FlightNumber2, $FlightNumber3…

4. Task: Add a new airplane.

Please enter the total number of seats: Please enter the airplane type:

Result: $NumAffected fares are affected. (e.g. “3 fares are affected”)

6. Remove a seat reservation.

Please enter the flight number: Please enter the customer name:

Result: Seat $SeatNumber is released.

The “$” symbol indicates a variable that you need to replace with an answer. To simplify the project, you may assume each question leads to a non-empty result(i.e., at least one tuple is returned for each question). A non-stop flights are flights with only one leg. A flight leg is a segment of a flight. For example, a flight from LAX to YYZ may have two flight legs, the first one from LAX to PHX and the second from PHX to YYZ.

Requirements:

1. Your program should show a list of queries and tasks to the user and ask the user to choose one to start with.

2. After the user has selected a query/task, collect more information from the user if needed.

3. Your Python program must communicate with the database for each query/task.

4. After reporting the result, your program should ask the user to choose another query/task or quit the program.

5. If your query involves insert, update, and delete of the database, you should commit the changes to the database.

6. Your python source code file must be named as “mp2-xxxxxxxx.py”, xxxxxxxx being your student ID.

</div>
</div>
<div class="layoutArea">
<div class="column">
Result: The new airplane has been added with id: $AirplaneID

</div>
</div>
<div class="layoutArea">
<div class="column">
5. Increase low-cost fares(≤ 200) by a factor.

Please enter a factor (e.g. 0.2 will increase all fares by 20%):

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Reference: https://gist.github.com/onzfonz/eb8025de13e67c783795

</div>
</div>
</div>
