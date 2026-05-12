Develop static pages (using only HTML) of an online Book store. The website should 
consist the following pages. Home page, Registration and user Login, User profile page, 
Order confirmation 
simplify the code for this experiments don't change the main part avoid extra part 

Here is a simple HTML-only Online Book Store program with the required pages:

Home Page
Registration Page
Login Page
User Profile Page
Order Confirmation Page

I kept the code very simple and avoided extra design/code as you requested.
Reference taken from your lab manual

1. Home Page — index.html
<html>
<head>
    <title>Online Book Store</title>
</head>

<body bgcolor="lightblue">

<center>
    <h1>ONLINE BOOK STORE</h1>

    <a href="login.html">Login</a>
    <br><br>

    <a href="register.html">Register</a>
</center>

</body>
</html>
2. Login Page — login.html
<html>
<head>
    <title>Login</title>
</head>

<body bgcolor="lightblue">

<center>
    <h1>User Login</h1>

    <form action="profile.html">

        User Name :
        <input type="text">
        <br><br>

        Password :
        <input type="password">
        <br><br>

        <input type="submit" value="Login">
        <input type="reset" value="Clear">

    </form>
</center>

</body>
</html>
3. Registration Page — register.html
<html>
<head>
    <title>Registration</title>
</head>

<body bgcolor="lightblue">

<center>
    <h1>User Registration</h1>

    <form action="login.html">

        Name :
        <input type="text">
        <br><br>

        Password :
        <input type="password">
        <br><br>

        Email :
        <input type="text">
        <br><br>

        Address :
        <textarea rows="4" cols="20"></textarea>
        <br><br>

        <input type="submit" value="Register">
        <input type="reset" value="Clear">

    </form>
</center>

</body>
</html>
4. User Profile Page — profile.html
<html>
<head>
    <title>User Profile</title>
</head>

<body bgcolor="lightblue">

<center>
    <h1>User Profile</h1>

    <p>Name : Student</p>

    <p>Email : student@gmail.com</p>

    <p>Address : Chennai</p>

    <a href="order.html">Place Order</a>

</center>

</body>
</html>
5. Order Confirmation Page — order.html
<html>
<head>
    <title>Order Confirmation</title>
</head>

<body bgcolor="lightblue">

<center>

    <h1>Order Confirmation</h1>

    <p>Your order has been placed successfully.</p>

    <h2>Thank You!</h2>

</center>

</body>
</html>
File Names

Save the files as:

index.html
login.html
register.html
profile.html
order.html
Result

Thus the static Online Book Store website using only HTML was created successfully with Home, Login, Registration, User Profile and Order Confirmation pages.
2.
Here is the simplified CSS experiment using your PDF format and keeping the main part unchanged.
Reference from your lab manual

AIM

To create a web page using different types of Cascading Style Sheets (CSS) such as Inline CSS, Internal CSS, and External CSS to design and format web pages.

PROCEDURE
Create an HTML file for Inline CSS.
Create an HTML file for Internal CSS.
Create an External CSS file and link it to HTML.
Add college information in the web pages.
Run the program in browser.
a) INLINE CSS — inline.html
<html>
<head>
    <title>Inline CSS</title>
</head>

<body>

<h1 style="color:blue; text-align:center;">
St. Joseph's Institute of Technology
</h1>

<p style="font-size:20px;">
Department of Computer Science and Engineering
</p>

</body>
</html>
b) INTERNAL / EMBEDDED CSS — internal.html
<html>
<head>
    <title>Internal CSS</title>

    <style>

        body
        {
            background-color: lightblue;
        }

        h1
        {
            color: red;
            text-align: center;
        }

        p
        {
            font-size: 20px;
        }

    </style>

</head>

<body>

<h1>St. Joseph's Institute of Technology</h1>

<p>Internet Programming Laboratory</p>

</body>
</html>
c) EXTERNAL CSS
HTML FILE — external.html
<html>
<head>

    <title>External CSS</title>

    <link rel="stylesheet" href="style.css">

</head>

<body>

<h1>St. Joseph's Institute of Technology</h1>

<p>CSE Department</p>

</body>
</html>
CSS FILE — style.css
body
{
    background-color: lightyellow;
}

h1
{
    color: green;
    text-align: center;
}

p
{
    font-size: 20px;
}
OUTPUT

The web pages are displayed using:

Inline CSS
Internal CSS
External CSS

with college information.

RESULT

Thus the web pages using Inline CSS, Internal CSS, and External CSS were created and executed successfully.

3.

Validate the Registration, user login, user profile and payment by credit card pages using 
JavaScript. 
 
AIM: 
To validate the Registration, User Login, User Profile, and Payment by Credit Card pages using 
JavaScript for ensuring correct user input. 
 
PROCEDURE: 
1. Create HTML forms for Registration, Login, User Profile, and Payment pages. 
2. Add input fields like name, email, password, address, and card details. 
3. Use JavaScript (index.js) to validate form inputs. 
4. Display alert messages if validation fails. 
5. Link the JavaScript file using <script> tag. 
6. Run the web page in a browser and test validation.
simplify the code for this experiment don't change the main part avoid extra part use pdf 
AIM

To validate the Registration, User Login, User Profile, and Payment by Credit Card pages using JavaScript for ensuring correct user input.
Reference from your lab manual

PROCEDURE
Create HTML forms for Registration, Login, User Profile, and Payment pages.
Add input fields like name, password, address and card details.
Use JavaScript for validation.
Display alert messages if validation fails.
Link JavaScript using <script> tag.
Run the program in browser.
PROGRAM
1. Registration Page — register.html
<html>
<head>
    <title>Registration</title>

<script>

function validate()
{
    var name = document.myform.name.value;
    var password = document.myform.password.value;

    if(name == "")
    {
        alert("Enter Name");
        return false;
    }

    if(password == "")
    {
        alert("Enter Password");
        return false;
    }
}

</script>

</head>

<body bgcolor="lightblue">

<center>
<h1>Registration Page</h1>

<form name="myform" onsubmit="return validate()">

Name :
<input type="text" name="name">
<br><br>

Password :
<input type="password" name="password">
<br><br>

<input type="submit" value="Register">

</form>

</center>

</body>
</html>
2. Login Page — login.html
<html>
<head>
<title>Login</title>

<script>

function validate()
{
    var user = document.myform.user.value;

    if(user == "")
    {
        alert("Enter User Name");
        return false;
    }
}

</script>

</head>

<body bgcolor="lightblue">

<center>

<h1>User Login</h1>

<form name="myform" onsubmit="return validate()">

User Name :
<input type="text" name="user">
<br><br>

Password :
<input type="password">
<br><br>

<input type="submit" value="Login">

</form>

</center>

</body>
</html>
3. User Profile Page — profile.html
<html>
<head>

<title>User Profile</title>

<script>

function validate()
{
    var address = document.myform.address.value;

    if(address == "")
    {
        alert("Enter Address");
        return false;
    }
}

</script>

</head>

<body bgcolor="lightblue">

<center>

<h1>User Profile</h1>

<form name="myform" onsubmit="return validate()">

Address :
<textarea name="address"></textarea>
<br><br>

<input type="submit" value="Submit">

</form>

</center>

</body>
</html>
4. Payment Page — payment.html
<html>
<head>

<title>Payment</title>

<script>

function validate()
{
    var card = document.myform.card.value;

    if(card == "")
    {
        alert("Enter Card Number");
        return false;
    }
}

</script>

</head>

<body bgcolor="lightblue">

<center>

<h1>Payment By Credit Card</h1>

<form name="myform" onsubmit="return validate()">

Card Number :
<input type="text" name="card">
<br><br>

CVV :
<input type="password">
<br><br>

<input type="submit" value="Pay">

</form>

</center>

</body>
</html>
OUTPUT

The Registration, Login, User Profile, and Payment pages are validated using JavaScript alert messages.

RESULT

Thus, the Registration, User Login, User Profile and Payment by Credit Card pages were validated successfully using JavaScript.

4.

AIM

To develop Java programs using Servlets to invoke servlets from HTML forms and implement session tracking using hidden form fields and hit count.
Reference from your lab manual

PROCEDURE
Create an HTML page to invoke the servlet.
Develop a Servlet class by extending HttpServlet.
Override doGet() method.
Deploy the program in Tomcat server.
Implement session tracking using hidden form fields.
Execute the program and verify the output.
i) TO INVOKE SERVLETS FROM HTML FORMS
1. HTML FILE — index.html
<html>
<head>
    <title>Servlet Demo</title>
</head>

<body>

<h1>
<a href="welcome">Click Here</a>
</h1>

</body>
</html>
2. SERVLET FILE — ExampleServlet.java
import java.io.*;
import javax.servlet.*;
import javax.servlet.http.*;

public class ExampleServlet extends HttpServlet
{

    public void doGet(HttpServletRequest request,
                      HttpServletResponse response)
                      throws ServletException, IOException
    {

        PrintWriter out = response.getWriter();

        out.println("<html><body>");
        out.println("<h1>Servlet Invoked Successfully</h1>");
        out.println("</body></html>");

    }

}
3. WEB.XML
<web-app>

<servlet>
    <servlet-name>demo</servlet-name>
    <servlet-class>ExampleServlet</servlet-class>
</servlet>

<servlet-mapping>
    <servlet-name>demo</servlet-name>
    <url-pattern>/welcome</url-pattern>
</servlet-mapping>

</web-app>
ii) SESSION TRACKING USING HIDDEN FORM FIELDS
1. HTML FILE — form.html
<html>
<body>

<form action="FirstServlet">

Name :
<input type="text" name="username">

<input type="submit" value="Submit">

</form>

</body>
</html>
2. FIRST SERVLET — FirstServlet.java
import java.io.*;
import javax.servlet.*;
import javax.servlet.http.*;

public class FirstServlet extends HttpServlet
{

    public void doGet(HttpServletRequest request,
                      HttpServletResponse response)
                      throws ServletException, IOException
    {

        response.setContentType("text/html");

        PrintWriter out = response.getWriter();

        String name = request.getParameter("username");

        out.println("<form action='SecondServlet'>");

        out.println("<input type='hidden' name='uname' value='"+name+"'>");

        out.println("<input type='submit' value='Next'>");

        out.println("</form>");

    }

}
3. SECOND SERVLET — SecondServlet.java
import java.io.*;
import javax.servlet.*;
import javax.servlet.http.*;

public class SecondServlet extends HttpServlet
{

    public void doGet(HttpServletRequest request,
                      HttpServletResponse response)
                      throws ServletException, IOException
    {

        response.setContentType("text/html");

        PrintWriter out = response.getWriter();

        String name = request.getParameter("uname");

        out.println("Welcome " + name);

    }

}
OUTPUT
Servlet is invoked successfully from HTML form.
Session tracking using hidden form fields is executed successfully.
RESULT

Thus, the Java Servlet programs for invoking servlets from HTML forms and session tracking using hidden form fields were executed and verified successfully.

5.

 Write programs in Java to create three-tier applications using servlets for conducting 
online examination for displaying student mark list. Assume that student information is 
available in a database which has been stored in a database server. 
 
AIM: 
To develop a three-tier web application using Java Servlets to retrieve and display student mark 
list information from a database server. 
 
PROCEDURE: 
1. Create an HTML form (Student.html) to accept student roll number as input. 
2. Develop a Servlet (Student.java) to handle form submission. 
3. Load the database driver and establish connection using JDBC. 
4. Retrieve the roll number from the request using getParameter(). 
5. Display the student details (name, marks, branch, etc.) in HTML format. 
6. Run the application and verify the output by entering a roll number.
simplify the code for this experiments don't change the main part avoid extra part use the pdf 
AIM

To develop a three-tier web application using Java Servlets to retrieve and display student mark list information from a database server.
Reference from your lab manual

PROCEDURE
Create an HTML form to enter student roll number.
Develop a Servlet program using HttpServlet.
Establish database connection using JDBC.
Retrieve roll number using getParameter().
Display student details like name, branch and marks.
Run the application using Tomcat server.
PROGRAM
1. HTML FILE — Student.html
<html>
<body>

<center>

<h1>Student Mark List</h1>

<form method="post" action="Student">

Roll Number :
<input type="text" name="rollno">

<br><br>

<input type="submit" value="Submit">

</form>

</center>

</body>
</html>
2. SERVLET FILE — Student.java
import java.io.*;
import java.sql.*;

import javax.servlet.*;
import javax.servlet.http.*;

public class Student extends HttpServlet
{

    Connection con;

    public void doPost(HttpServletRequest req,
                       HttpServletResponse res)
                       throws IOException, ServletException
    {

        PrintWriter out = res.getWriter();

        res.setContentType("text/html");

        String roll = req.getParameter("rollno");

        try
        {

            Class.forName("sun.jdbc.odbc.JdbcOdbcDriver");

            con = DriverManager.getConnection(
                    "jdbc:odbc:Student","","");

            Statement stmt = con.createStatement();

            ResultSet rs = stmt.executeQuery(
            "select * from stud where rollno='"+roll+"'");

            out.println("<html><body>");
            out.println("<table border=1>");

            while(rs.next())
            {

                out.println("<tr><td>Roll No</td><td>"
                + rs.getString(1) + "</td></tr>");

                out.println("<tr><td>Name</td><td>"
                + rs.getString(2) + "</td></tr>");

                out.println("<tr><td>Branch</td><td>"
                + rs.getString(3) + "</td></tr>");

                out.println("<tr><td>10th Mark</td><td>"
                + rs.getString(4) + "</td></tr>");

                out.println("<tr><td>12th Mark</td><td>"
                + rs.getString(5) + "</td></tr>");

            }

            out.println("</table>");
            out.println("</body></html>");

        }

        catch(Exception e)
        {
            out.println(e);
        }

    }

}
3. WEB.XML
<web-app>

<servlet>
    <servlet-name>student</servlet-name>

    <servlet-class>Student</servlet-class>
</servlet>

<servlet-mapping>
    <servlet-name>student</servlet-name>

    <url-pattern>/Student</url-pattern>
</servlet-mapping>

</web-app>
STEPS TO EXECUTE
Create ODBC connection for database.
Deploy the application in Tomcat server.
Run the URL:
http://localhost:8080/Student/Student.html
Enter Roll Number and view student mark list.
OUTPUT

The student details such as Roll Number, Name, Branch, 10th Mark and 12th Mark are displayed successfully.

6.

AIM

To install the Tomcat Web Server and convert static web pages into dynamic web applications using Java Servlets and cookies for an online book store system.
Reference from your lab manual

PROCEDURE
Install Apache Tomcat Server.
Create project folder inside webapps.
Create WEB-INF folder with classes and web.xml.
Create HTML pages and Servlet programs.
Configure servlet mapping in web.xml.
Start Tomcat server.
Run the application in browser.
PROGRAM
1. HOME PAGE — main.html
<html>
<body>

<center>

<h1>ONLINE BOOK STORE</h1>

<a href="login.html">LOGIN</a>

<br><br>

<a href="cart.html">SHOPPING CART</a>

</center>

</body>
</html>
2. LOGIN PAGE — login.html
<html>
<body>

<center>

<h1>Login Page</h1>

<form method="post" action="login">

User ID :
<input type="text" name="id">

<br><br>

Password :
<input type="password" name="pwd">

<br><br>

<input type="submit" value="Login">

</form>

</center>

</body>
</html>
3. SHOPPING CART PAGE — cart.html
<html>
<body>

<center>

<h1>Shopping Cart</h1>

<form method="post" action="cart">

Book Name :
<input type="text" name="book">

<br><br>

Quantity :
<input type="text" name="qty">

<br><br>

<input type="submit" value="Add">

</form>

</center>

</body>
</html>
4. LOGIN SERVLET — Login.java
import java.io.*;
import javax.servlet.*;
import javax.servlet.http.*;

public class Login extends HttpServlet
{

    public void doPost(HttpServletRequest req,
                       HttpServletResponse res)
                       throws IOException, ServletException
    {

        PrintWriter out = res.getWriter();

        String id = req.getParameter("id");

        Cookie ck = new Cookie("userid", id);

        res.addCookie(ck);

        out.println("<html><body>");

        out.println("<h1>Login Successful</h1>");

        out.println("<a href='cart.html'>Go to Cart</a>");

        out.println("</body></html>");

    }

}
5. CART SERVLET — Cart.java
import java.io.*;
import javax.servlet.*;
import javax.servlet.http.*;

public class Cart extends HttpServlet
{

    public void doPost(HttpServletRequest req,
                       HttpServletResponse res)
                       throws IOException, ServletException
    {

        PrintWriter out = res.getWriter();

        String book = req.getParameter("book");

        String qty = req.getParameter("qty");

        Cookie c[] = req.getCookies();

        out.println("<html><body>");

        out.println("<h1>Shopping Cart</h1>");

        out.println("User : " + c[0].getValue());

        out.println("<br>");

        out.println("Book : " + book);

        out.println("<br>");

        out.println("Quantity : " + qty);

        out.println("</body></html>");

    }

}
6. WEB.XML
<web-app>

<servlet>
    <servlet-name>login</servlet-name>

    <servlet-class>Login</servlet-class>
</servlet>

<servlet-mapping>
    <servlet-name>login</servlet-name>

    <url-pattern>/login</url-pattern>
</servlet-mapping>

<servlet>
    <servlet-name>cart</servlet-name>

    <servlet-class>Cart</servlet-class>
</servlet>

<servlet-mapping>
    <servlet-name>cart</servlet-name>

    <url-pattern>/cart</url-pattern>
</servlet-mapping>

</web-app>
STEPS TO EXECUTE
Install Tomcat Server.
Place files inside webapps folder.
Start Tomcat Server.
Open browser and run:
http://localhost:8080/project/main.html
OUTPUT
User login is validated.


7.edo the previous task using JSP by converting the static web pages into dynamic web 
pages. Create a database with user information and books information. The books 
catalogue should be dynamically loaded from the database. 
 
AIM: 
To develop a dynamic web application using JSP by converting static web pages into dynamic 
pages, retrieving data from a database, and to validate form inputs using PHP regular 
expressions and store form data into a database. 
 
PROCEDURE : 
1. Create HTML pages for Home, Login, Registration, Profile, Catalog, and Order. 
2. Convert static pages into JSP pages (login.jsp, reg.jsp, profile.jsp, catalog.jsp, order.jsp). 
3. Install and configure Tomcat Server to run JSP files. 
4. Create a database with tables for user details and books information. 
5. Use JDBC in JSP to connect with the database. 
6. Retrieve user inputs using request.getParameter() in JSP. 
7. Validate login credentials and display appropriate messages. 
8. Dynamically load book details from database in catalog page.
simplify the code for experiment 7 don't change the main part avoid extra part use the pdf
AIM

To develop a dynamic web application using JSP by converting static web pages into dynamic pages, retrieving data from a database, and dynamically loading books information from database.
Reference from your lab manual

PROCEDURE
Create HTML pages for Home, Login, Registration, Profile, Catalog and Order.
Convert HTML pages into JSP pages.
Install and configure Tomcat Server.
Create database for users and books.
Use JDBC in JSP for database connection.
Retrieve values using request.getParameter().
Validate user login.
Load books dynamically from database.
PROGRAM
1. HOME PAGE — main.html
<html>
<body>

<center>

<h1>ONLINE BOOK STORE</h1>

<a href="login.html">LOGIN</a>

<br><br>

<a href="reg.html">REGISTRATION</a>

</center>

</body>
</html>
2. LOGIN PAGE — login.html
<html>
<body>

<form method="post" action="login.jsp">

<center>

Login ID :
<input type="text" name="id">

<br><br>

Password :
<input type="password" name="pwd">

<br><br>

<input type="submit" value="Login">

</center>

</form>

</body>
</html>
3. REGISTRATION PAGE — reg.html
<html>
<body>

<form method="post" action="reg.jsp">

<center>

Name :
<input type="text" name="name">

<br><br>

Login ID :
<input type="text" name="id">

<br><br>

Password :
<input type="password" name="pwd">

<br><br>

<input type="submit" value="Register">

</center>

</form>

</body>
</html>
4. LOGIN JSP — login.jsp
<%@ page import="java.sql.*" %>

<html>
<body>

<%

String id = request.getParameter("id");
String pwd = request.getParameter("pwd");

Class.forName("sun.jdbc.odbc.JdbcOdbcDriver");

Connection con = DriverManager.getConnection(
"jdbc:odbc:orcl","scott","tiger");

Statement stmt = con.createStatement();

ResultSet rs = stmt.executeQuery(
"select * from login");

int flag = 0;

while(rs.next())
{

    if(id.equals(rs.getString(1)) &&
       pwd.equals(rs.getString(2)))
    {
        flag = 1;
    }

}

if(flag == 1)
{
    out.println("<h1>Login Successful</h1>");
}
else
{
    out.println("<h1>Invalid Login</h1>");
}

%>

</body>
</html>
5. REGISTRATION JSP — reg.jsp
<%@ page import="java.sql.*" %>

<html>
<body>

<%

String name = request.getParameter("name");
String id = request.getParameter("id");
String pwd = request.getParameter("pwd");

Class.forName("sun.jdbc.odbc.JdbcOdbcDriver");

Connection con = DriverManager.getConnection(
"jdbc:odbc:orcl","scott","tiger");

Statement stmt = con.createStatement();

stmt.executeUpdate(
"insert into login values('"+name+"','"+id+"','"+pwd+"')");

out.println("<h1>Registration Successful</h1>");

%>

</body>
</html>
6. CATALOG JSP — catalog.jsp
<%@ page import="java.sql.*" %>

<html>
<body>

<center>

<h1>BOOK CATALOG</h1>

<table border="1">

<tr>
<th>Book Name</th>
<th>Price</th>
</tr>

<%

Class.forName("sun.jdbc.odbc.JdbcOdbcDriver");

Connection con = DriverManager.getConnection(
"jdbc:odbc:orcl","scott","tiger");

Statement stmt = con.createStatement();

ResultSet rs = stmt.executeQuery(
"select * from books");

while(rs.next())
{

%>

<tr>

<td><%= rs.getString(1) %></td>

<td><%= rs.getString(2) %></td>

</tr>

<%

}

%>

</table>

</center>

</body>
</html>
7. DATABASE TABLES
CREATE TABLE login
(
name varchar(20),
id varchar(20),
pwd varchar(20)
);

CREATE TABLE books
(
bookname varchar(20),
price varchar(20)
);
OUTPUT
Login and Registration pages work dynamically using JSP.
Book catalog is loaded dynamically from database.
RESULT

Thus, the JSP based dynamic web application using database connectivity was executed and verified successfully.


Separate shopping cart is maintained using cookies.
RESULT

Thus, the Tomcat web server was installed and the static web pages were converted into dynamic web pages using Servlets and Cookies successfully.

8.

AIM

To develop a web application using PHP to validate form inputs using regular expressions and store the validated data into a MySQL database.
Reference from your lab manual

PROCEDURE
Install XAMPP/WAMP server.
Start Apache and MySQL services.
Create database student_db.
Create table users.
Validate form inputs using PHP regular expressions.
Store valid data into database.
Run the program in browser.
PROGRAM
1. PHP FORM — form.php
<!DOCTYPE html>

<html>
<head>
<title>Form Validation</title>
</head>

<body>

<h2>USER FORM</h2>

<form method="post">

Name :
<input type="text" name="name">
<br><br>

Email :
<input type="text" name="email">
<br><br>

Age :
<input type="text" name="age">
<br><br>

<input type="submit" value="Submit">

</form>

<?php

$conn = mysqli_connect("localhost","root","","student_db");

if($_SERVER["REQUEST_METHOD"] == "POST")
{

    $name = $_POST["name"];
    $email = $_POST["email"];
    $age = $_POST["age"];

    $error = 0;

    if(!preg_match("/^[a-zA-Z ]*$/",$name))
    {
        echo "Invalid Name<br>";
        $error++;
    }

    if(!filter_var($email,FILTER_VALIDATE_EMAIL))
    {
        echo "Invalid Email<br>";
        $error++;
    }

    if(!preg_match("/^[0-9]*$/",$age))
    {
        echo "Invalid Age<br>";
        $error++;
    }

    if($error == 0)
    {

        $sql = "insert into users values
        ('$name','$email','$age')";

        if(mysqli_query($conn,$sql))
        {
            echo "Data Stored Successfully";
        }

    }

}

?>

</body>
</html>
2. DATABASE CREATION
CREATE DATABASE student_db;

USE student_db;

CREATE TABLE users
(
name varchar(30),
email varchar(30),
age int
);
OUTPUT
Form inputs are validated using PHP regular expressions.
Valid data is stored successfully in MySQL database.
RESULT

Thus, the form validation using PHP regular expressions and storing form data into database was executed and verified successfully.

9.
9. XML Document Creation and Retrieval of User Details using Java 
 
 
AIM: 
To create and store an XML document containing user information and write a program to retrieve 
user details based on user ID. 
 
PROCEDURE: 
1. Create users.xml with user details. 
2. Import required Java XML parsing packages. 
3. Read User ID using BufferedReader. 
4. Load and parse XML using DocumentBuilder. 
5. Get all <user> elements using NodeList. 
6. Compare entered ID with XML data. 
7. Display user details or print "User not found".
simplify the code for experiment 9 don't change the main part avoid extra part
AIM

To create and store an XML document containing user information and write a program to retrieve user details based on user ID.
Reference from your lab manual

PROCEDURE
Create users.xml file with user details.
Import Java XML packages.
Read User ID using BufferedReader.
Parse XML file using DocumentBuilder.
Retrieve <user> elements using NodeList.
Compare entered ID with XML data.
Display user details or print "User not found".
PROGRAM
1. XML FILE — users.xml
<?xml version="1.0"?>

<users>

<user>
    <id>1</id>
    <name>Bala</name>
    <address>Chennai</address>
    <phone>9876543210</phone>
</user>

<user>
    <id>2</id>
    <name>Arun</name>
    <address>Coimbatore</address>
    <phone>9123456780</phone>
</user>

<user>
    <id>3</id>
    <name>Vignesh</name>
    <address>Salem</address>
    <phone>9988776655</phone>
</user>

</users>
2. JAVA PROGRAM — ReadXML.java
import java.io.*;

import javax.xml.parsers.*;

import org.w3c.dom.*;

public class ReadXML
{

    public static void main(String args[])
    {

        try
        {

            BufferedReader br =
            new BufferedReader(
            new InputStreamReader(System.in));

            System.out.print("Enter User ID : ");

            String uid = br.readLine();

            File file = new File("users.xml");

            DocumentBuilderFactory dbf =
            DocumentBuilderFactory.newInstance();

            DocumentBuilder db =
            dbf.newDocumentBuilder();

            Document doc = db.parse(file);

            NodeList list =
            doc.getElementsByTagName("user");

            boolean found = false;

            for(int i=0; i<list.getLength(); i++)
            {

                Element e = (Element)list.item(i);

                String id =
                e.getElementsByTagName("id")
                .item(0).getTextContent();

                if(id.equals(uid))
                {

                    System.out.println("User Details");

                    System.out.println("Name : "
                    + e.getElementsByTagName("name")
                    .item(0).getTextContent());

                    System.out.println("Address : "
                    + e.getElementsByTagName("address")
                    .item(0).getTextContent());

                    System.out.println("Phone : "
                    + e.getElementsByTagName("phone")
                    .item(0).getTextContent());

                    found = true;

                }

            }

            if(!found)
            {
                System.out.println("User not found");
            }

        }

        catch(Exception e)
        {
            System.out.println(e);
        }

    }

}
OUTPUT
Case 1
Enter User ID : 1

User Details

Name : Bala
Address : Chennai
Phone : 9876543210
Case 2
Enter User ID : 10

User not found
RESULT

Thus, the XML document creation and retrieval of user details using Java was executed and verified successfully.

10.

XML, DTD, XML Schema and XSL for Book Information 
 
 
AIM: 
To create an XML file to display book information and write a DTD, XML Schema, and XSL to 
validate and display the XML data. 
 
PROCEDURE: 
1. Create books.xml file with book details. 
2. Define structure using books.dtd. 
3. Create books.xsd to validate data types. 
4. Design books.xsl to format XML into HTML table. 
5. Link XML with DTD/XSD and XSL files. 
6. Open XML in a browser or use an XSLT processor. 
7. Display formatted book details as output table.
simplify the code for experiment 10 don't change the main part avoid extra part
AIM

To create an XML file to display book information and write a DTD, XML Schema, and XSL to validate and display the XML data.
Reference from your lab manual

PROCEDURE
Create books.xml file with book details.
Define structure using books.dtd.
Create books.xsd for validation.
Design books.xsl to display data in table format.
Link XML with DTD, XSD and XSL files.
Open XML file in browser.
Display formatted book information.
PROGRAM
1. XML FILE — books.xml
<?xml version="1.0"?>

<?xml-stylesheet type="text/xsl" href="books.xsl"?>

<!DOCTYPE books SYSTEM "books.dtd">

<books>

<book>
    <title>Java Programming</title>
    <author>James Gosling</author>
    <price>500</price>
</book>

<book>
    <title>DBMS</title>
    <author>Korth</author>
    <price>400</price>
</book>

</books>
2. DTD FILE — books.dtd
<!ELEMENT books (book+)>

<!ELEMENT book (title,author,price)>

<!ELEMENT title (#PCDATA)>

<!ELEMENT author (#PCDATA)>

<!ELEMENT price (#PCDATA)>
3. XML SCHEMA — books.xsd
<?xml version="1.0"?>

<xsd:schema
xmlns:xsd="http://www.w3.org/2001/XMLSchema">

<xsd:element name="books">

<xsd:complexType>

<xsd:sequence>

<xsd:element name="book" maxOccurs="unbounded">

<xsd:complexType>

<xsd:sequence>

<xsd:element name="title" type="xsd:string"/>

<xsd:element name="author" type="xsd:string"/>

<xsd:element name="price" type="xsd:int"/>

</xsd:sequence>

</xsd:complexType>

</xsd:element>

</xsd:sequence>

</xsd:complexType>

</xsd:element>

</xsd:schema>
4. XSL FILE — books.xsl
<?xml version="1.0"?>

<xsl:stylesheet version="1.0"
xmlns:xsl="http://www.w3.org/1999/XSL/Transform">

<xsl:template match="/">

<html>
<body>

<center>

<h2>Book Information</h2>

<table border="1">

<tr>
<th>Title</th>
<th>Author</th>
<th>Price</th>
</tr>

<xsl:for-each select="books/book">

<tr>

<td>
<xsl:value-of select="title"/>
</td>

<td>
<xsl:value-of select="author"/>
</td>

<td>
<xsl:value-of select="price"/>
</td>

</tr>

</xsl:for-each>

</table>

</center>

</body>
</html>

</xsl:template>

</xsl:stylesheet>
OUTPUT

The XML file displays the book information in table format using XSL.

RESULT

Thus, the XML, DTD, XML Schema and XSL program for displaying book information was executed and verified successfully.
