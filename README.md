
This is a copy of a shared ChatGPT conversation

Report conversation
Uploaded a file
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


Sources

Uploaded a file
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

Uploaded a file
5. Write programs in Java to create three-tier applications using servlets for conducting 
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

Uploaded a file
 Redo the previous task using JSP by converting the static web pages into dynamic web 
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


Sources

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


Sources

10. XML, DTD, XML Schema and XSL for Book Information 
 
 
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


Sources

