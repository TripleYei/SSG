---
layout: post
title:  "Retos y Ejercicios de Programación"
date:   2023-1-13
categories: jekyll update
---

# Retos y ejercicios

¡Empezamos!

## JSchallenger <a href="https://www.jschallenger.com/"> Ir a la web</a>

JavaScript Practice: JavaScript fundamentals 

Suma de dos numeros: sum two numbers.

~~~~
function myFunction(a, b) {

   return a + b ;
}

~~~~

Comparación de operadores: Comparison operators, strict equality.
~~~~
  function  myFunction(a, b)
  {
      if( a === b) 
      {
         return true;
       }  else 
       {
         return false;
        }
   }

~~~~

Get type of value: obtener el tipo del valor.

~~~~

function myFunction(a)
{

   return typeof a;
}
~~~~

Hello World

To complete this exercise, type console.log('Hello World'); and run the code.

~~~~
console.log('Hello World');
~~~~


Reassign a value to a variable
Assign a new value to the variable num. The code will not work the way it is. Find the mistake and fix it. Execute the corrected code.

~~~~
let num = 1;
num = 2;
console.log(num);
~~~~

Assign a value to a variable
Here, we declare the variable num. But, it has no value yet. Assign a value to it and run the code.

~~~~
let num;
num = 5;
console.log(num);
~~~~


Assign the value of another variable
Here, we have two variables numOne and numTwo. numOne already has a value. Assign numTwo the value of numOne and run the code.

~~~~
let numOne = 5;
let numTwo = numOne;
console.log(numTwo);
~~~~


Create the missing variable
Below, we attempt to assign the value of a variable named numOne to the variable numTwo. But, that variable has not been declared yet. Declare a variable named numOne and run the code.

~~~~
let numOne = 5;
let numTwo = numOne;
console.log(numTwo);
~~~~


Accessing a variable (1)
In this simple exercise we declare a variable called num and assign it a value of 5. Then we try to log the value of the variable using the console.log() method.
But, the console.log() method contains a small mistake. If you try to run the code, you will see an error message.
Fix the mistake and run the code again.


~~~~
const num = 5;
console.log(num);
~~~~


Accessing a variable (2)
This exercise is very similar to the previous one. We declare a variable called num, assign it a value of 5, and try to log it. But again, we introduced a small mistake.
Fix the code and run it.

~~~~
const num = 5;
console.log(num);
~~~~



Declare a variable and assign a number
In this exercise we practice how to declare a new variable and how to assign it a number. The console.log() statement below attempts to log a variable named num.
Declare a variable with this name and assign it a number of your choice. Run the code to see if the number is being logged.


~~~~
const num = 5;
console.log('The value of num is: ' + num);
~~~~


Reassign a value to a variable (2)
The code below first declares a variable named num with value 1. Then, a new value 2 is assigned. Finally, the variable is logged.
But, the code will not work like that. Find the mistake and fix it. Execute the corrected code.

~~~~
let num = 1;
num = 2;
console.log(num);
~~~~


Uncomment to Assign a Number
As you can see, the code is trying to print the value of x, but it's not working because the variable is commented out.

In JavaScript, comments are used to add notes to your code or to disable lines of code.
You can create a single-line comment by adding // in front of a line. JavaScript will ignore that line when running the code.

Your task:
Uncomment the line that declares the variable so that the code prints the value of x.


~~~~
const x = 7;
console.log(x);
~~~~


Time to Uncomment
This time, the variable declaration is still commented out, but in a slightly different way — the comment appears inline.

In JavaScript, comments can also be placed after code on the same line. These are called inline comments and also start with //.

Your task:
Fix the variable declaration so the code prints the value of x.


~~~~
const x = 100;
console.log(x);
~~~~


Time to comment
In this challenge, the variable x is reassigned to a new value, but we want to prevent this change.

To do this, you can use a comment to "disable" the line of code that reassigns x. Comments can be used to stop specific code from running without deleting it.

Your task:
Comment out the reassignment of x so that the code still prints the value 100.


~~~~
let x = 100;

// x = 0


console.log(x);
~~~~






# JavaScript w3schools

Create a variable called carName, assign the value Volvo to it.

~~~~
let carName = "Volvo";
~~~~

Create a variable called x, assign the value 50 to it.

~~~~
let x = 50
~~~~

Display the sum of 5 + 10, using two variables: x and y.

~~~~
let x = 5;
let y = 10;
document.getElementById("demo").innerHTML = x +y;
~~~~

Create a variable called z, assign x + y to it, and display the result in an alert box.

~~~~
let x = 5;
let y = 10;
let z = x + y;
alert(z);
~~~~

On one single line, declare three variables with the following names and values:

firstName = "John"
lastName = "Doe"
age = 35

~~~~
let firstName = "John", lastName = "Doe", age = 35;
~~~~

Multiply 10 with 5, and alert the result:

~~~~
alert(10 *5);
~~~~

Divide 10 by 2, and alert the result:

~~~~
alert(10 /2);
~~~~

Alert the remainder when 15 is divided by 9.

~~~~
alert(15 % 9);
~~~~

Use the correct assignment operator that will result in x being 15 (same as x = x + y).

~~~~
x = 10;
y = 5;
x += y;
~~~~

Use the correct assignment operator that will result in x being 50 (same as x = x * y).

~~~~
x = 10;
y = 5;
x *= y;
~~~~

Use comments to describe the correct data type of the following variables:

~~~~
let length = 16;          // Number


let lastName = "Johnson"; // String


const x = {
  firstName: "John",
  lastName: "Doe"
};                        // Object
~~~~

Execute the function named myFunction.

~~~~
function myFunction() {
  alert("Hello World!");
}
myFunction();
~~~~

Create a function called "myFunction".

~~~~

function myFunction() {
   alert("Hello World!");
}
~~~~

Make the function return "Hello".

~~~~
function myFunction() {
  return "Hello";
}
document.getElementById("demo").innerHTML = myFunction();
~~~~

Make the function display "Hello" in the inner HTML of an element with the ID "demo".

~~~~
function myFunction() {
  document.getElementById("demo").innerHTML = "Hello";
}
~~~~

Alert "John" by extracting information from the person object.

~~~~
const person = {
  firstName: "John",
  lastName: "Doe"
};

alert(person.firstName);
~~~~

Add the following property and value to the person object: country: Norway.

~~~~
const person = {
  firstName: "John",
  lastName: "Doe",
  country: "Norway"
};
~~~~

Create an object called person with name = John, age = 50.
Then, access the object to alert("John is 50").

~~~~
const person = {
  name:"John", age:50
};
alert( person.name + " is " + person.age);
~~~~

The <button> element should do something when someone clicks on it. Try to fix it!

~~~~
<button onclick="alert('Hello')">Click me.</button>
~~~~

When the button is clicked, the function "myFunction" should be executed.

~~~~
<button onclick ="myFunction()">Click me.</button>
~~~~

The <div> element should turn red when someone moves the mouse over it.

~~~~
<div onmouseover ="this.style.backgroundColor='red'">myDIV.</div>
~~~~

Use the length property to alert the length of txt.

~~~~
let txt = "Hello World!";
let x = txt.length;
alert(x);
~~~~

Use escape characters to alert We are "Vikings".

~~~~
let txt = " We are \"Vikings\" ";
alert(txt);
~~~~


Concatenate the two strings to alert "Hello World!".

~~~~
let str1 = "Hello ";
let str2 = "World!";
alert(str1 + str2);
~~~~

Convert the text into an UPPERCASE text:

~~~~

let txt = "Hello World!";
txt = txt.toUpperCase();
~~~~

Use the slice method to return the word "bananas".

~~~~
let txt = "I can eat bananas all day";
let x = txt.slice(10, 17);
~~~~

Use the correct String method to replace the word "Hello" with the word "Welcome".

~~~~
let txt = "Hello World";
txt = txt.replace("Hello", "Welcome");
~~~~

Convert the value of txt to upper case.

~~~~
let txt = "Hello World";
txt = txt.toUpperCase();
~~~~

Convert the value of txt to lower case.

~~~~
let txt = "Hello World";
txt = txt.toLowerCase();
~~~~

Get the value "Volvo" from the cars array.

~~~~
const cars = ["Saab", "Volvo", "BMW"];
let x = cars[1];
~~~~

Change the first item of cars to "Ford".

~~~~
const cars = ["Volvo", "Jeep", "Mercedes"];
cars[0] = "Ford";
~~~~

Alert the number of items in an array, using the correct Array property.

~~~~

const cars = ["Volvo", "Jeep", "Mercedes"];
alert(cars.length);
~~~~

Use the correct Array method to remove the last item of the fruits array.

~~~~
const fruits = ["Banana", "Orange", "Apple"];
fruits.pop();
~~~~

Use the correct Array method to add "Kiwi" to the fruits array.

~~~~
const fruits = ["Banana", "Orange", "Apple"];
fruits.push("Kiwi");
~~~~

Use the splice() method to remove "Orange" and "Apple" from fruits.

~~~~
const fruits = ["Banana", "Orange", "Apple", "Kiwi"];
fruits.splice(1, 2);
~~~~

Use the correct Array method to sort the fruits array alphabetically.

~~~~
const fruits = ["Banana", "Orange", "Apple", "Kiwi"];
fruits.sort();
~~~~

Create a Date object and alert the current date and time.

~~~~
const d = new Date();
alert(d);
~~~~

Use the correct Date method to extract the year (four digits) out of a date object.

~~~~
const d = new Date();
year = d.getFullYear()
~~~~

Use the correct Date method to get the month (0-11) out of a date object.

~~~~
const d = new Date();
month = d.getMonth();
~~~~

Use the correct Date method to set the year of a date object to 2020.

~~~~
const d = new Date();
d.setFullYear(2020);
~~~~

Use the correct Math method to create a random number.

~~~~
let r = Math.random();
~~~~

Use the correct Math method to return the largest number of 10 and 20.

~~~~
let x = 
Math.max(10, 20);
~~~~

Use the correct Math method to round a number to the nearest integer.

~~~~
let x = Math.round(5.3);
~~~~

Use the correct Math method to get the square root of 9.

~~~~
let x = Math.sqrt(9);
~~~~

Choose the correct comparison operator to alert true, when x is greater than y.

~~~~
x = 10;
y = 5;
alert(x > y);
~~~~

Choose the correct comparison operator to alert true, when x is equal to y.

~~~~

x = 10;
y = 10;
alert(x ==y);
~~~~

Choose the correct comparison operator to alert true, when x is NOT equal to y.

~~~~
x = 10;
y = 5;
alert(x != y);
~~~~

Choose the correct conditional (ternary) operator to alert "Too young" if age is less than 18, otherwise alert "Old enough".

~~~~
var age = n;
var voteable = (age < 18) ? "Too young" : "Old enough";
alert(voteable);
~~~~

Fix the if statement to alert "Hello World" if x is greater than y.

~~~~
if (x > y){
  alert("Hello World");
}
~~~~

Fix the if statement to alert "Hello World" if x is greater than y, otherwise alert "Goodbye".

~~~~

if(x > y) {
  alert("Hello World");
} 
else
 {
  alert("Goodbye");
}
~~~~

Create a switch statement that will alert "Hello" if fruits is "banana", and "Welcome" if fruits is "apple".

~~~~

switch (fruits) {
  case "Banana":
    alert("Hello")
    break;
  
case "Apple":
    alert("Welcome")
    break;    
}
~~~~

Add a section that will alert("Neither") if fruits is neither "banana" nor "apple".

~~~~

switch(fruits) {
  case "Banana":
    alert("Hello")
    break;
  case "Apple":
    alert("Welcome")
    break;
  
default:
  alert("Neither");
}
~~~~

Create a loop that runs from 0 to 9.

~~~~
let i;
for(i= 0; i< 10; i++) {
  console.log(i);
}
~~~~

Create a loop that runs through each item in the fruits array.

~~~~
const fruits = ["Apple", "Banana", "Orange"];
for (x of fruits) {
  console.log(x);
}
~~~~

Create a loop that runs as long as i is less than 10.

~~~~
let i = 0;
while (i <10) {
  console.log(i);
  i++
}
~~~~

Create a loop that runs as long as i is less than 10, but increase i with 2 each time.

~~~~
let i = 0;
while (i < 10) {
  console.log(i);
  i =  i + 2;
}
~~~~

Make the loop stop when i is 5.

~~~~
for (i = 0; i < 10; i++) {
  console.log(i);
  if (i == 5) {
    break;
  }
}
~~~~

Make the loop jump to the next iteration when i is 5.


~~~~
for (i = 0; i < 10; i++) {
  if (i == 5) {
    continue;
  }
  console.log(i);
}
~~~~

Use the getElementById method to find the <p> element, and change its text to "Hello".

~~~~
<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "Hello";
</script>
~~~~

Use the getElementsByTagName method to find the first <p> element, and change its text to "Hello".

~~~~
<p id="demo"></p>

<script>
document.getElementsByTagName("p")[0].innerHTML= "Hello";
</script>
~~~~

Change the text of the first element that has the class name "test".

~~~~
<p class="test"></p>
<p class="test"></p>

<script>
document.getElementsByClassName("test")[0].innerHTML = "Hello";
</script>
~~~~

Use HTML DOM to change the value of the image's src attribute.

~~~~
<img id="image" src="smiley.gif">

<script>
document.getElementById("image").src = "pic_mountain.jpg";
</script>
~~~~

Use HTML DOM to change the value of the input field.

~~~~
<input type="text" id="myText" value="Hello">

<script>
document.getElementById("myText").value= "Have a nice day!";
</script>
~~~~

Change the text color of the <p> element to "red".

~~~~
<p id="demo"></p>

<script>
document.getElementById("demo").style.color = "red";
</script>
~~~~

Change the font size of the p element to 40 pixels.

~~~~
<p id="demo"></p>

<script>
document.getElementById("demo").style.fontSize = "40px";
</script>
~~~~

Use the CSS display property to hide the p element.

~~~~
<p id="demo"></p>

<script>
document.getElementById("demo").style.display = "none";
</script>
~~~~

Use the eventListener to assign an onclick event to the <button> element.

~~~~
<button id="demo">Click me1</button>

<script>
document.getElementById("demo").addEventListener("click", myFunction);
</script>
~~~~



## Practicar SQL online : <a href="https://www.sql-practice.com/"> Ir a la web</a>

Show first name and last name of patients who does not have allergies (null).

Mostrar el nombre y apellido de los pacientes, quién no tiene alergias.

~~~~
SELECT first_name,last_name FROM patients WHERE allergies IS NULL;
~~~~


Show first name of patients that start with the letter 'C'.

Mostrar el nombre del paciente que empiece con la letra C.

~~~~
SELECT first_name from patients WHERE first_name LIKE "C%";
~~~~

Show first name, last name, and gender of patients who's gender is 'M'.

Mostrar nombre, apellido, y genero del paciente, genero es M.

~~~~
SELECT first_name,last_name,gender from patients WHERE gender="M";
~~~~

Show first name and last name of patients that weight within the range of 100 to 120 (inclusive).

Mostrar nombre y apellido del paciente, el peso sea entre 100 y 120.
~~~~
SELECT first_name,last_name from patients WHERE weight between 100 AND 120;
~~~~

Update the patients table for the allergies column. If the patient's allergies is null then replace it with 'NKA'.

Actualizar la tabla pacientes, columna alergias. Si el paciente alérgico es nulo reemplza con "NKA".
~~~~
UPDATE patients SET  allergies = "NKA" where allergies is NULL;
~~~~

## SQL  W3schools

Insert the missing statement to get all the columns from the Customers table.

~~~~
SELECT * FROM Customers;
~~~~

Write a statement that will select the City column from the Customers table.

~~~~
SELECT city FROM Customers;
~~~~


Select all the different values from the Country column in the Customers table.


~~~~
SELECT DISTINCT Country FROM Customers;
~~~~

Select all records where the City column has the value "Berlin".

~~~~
SELECT * FROM Customers WHERE CITY = "BERLIN";
~~~~

Use the NOT keyword to select all records where City is NOT "Berlin".

~~~~
SELECT * FROM Customers WHERE NOT CITY = 'BERLIN';
~~~~

Select all records where the CustomerID column has the value 32.

~~~~
SELECT * FROM Customers WHERE CustomerID = 32;
~~~~

Select all records where the City column has the value 'Berlin' and the PostalCode column has the value 12209.

~~~~
SELECT * FROM Customers WHERE City = 'Berlin' AND postalcode = 12209;
~~~~

Select all records where the City column has the value 'Berlin' or 'London'.

~~~~
SELECT * FROM Customers WHERE City = 'Berlin' OR city = 'London';
~~~~

Select all records from the Customers table, sort the result alphabetically by the column City.

~~~~
SELECT * FROM Customers ORDER BY city;
~~~~

Select all records from the Customers table, sort the result reversed alphabetically by the column City.

~~~~
SELECT * FROM Customers ORDER BY city DESC;
~~~~

Select all records from the Customers table, sort the result alphabetically, first by the column Country, then, by the column City.

~~~~
SELECT * FROM Customers ORDER BY country, city;
~~~~

Insert a new record in the Customers table.

~~~~
INSERT INTO
 Customers 
(

CustomerName, 
Address, 
City, 
PostalCode,
Country
)

VALUES
 
(

'Hekkan Burger',
'Gateveien 15',
'Sandnes',
'4306',
'Norway'
);
~~~~

Select all records from the Customers where the PostalCode column is empty.

~~~~
SELECT * FROM Customers WHERE PostalCode IS NULL;
~~~~


Select all records from the Customers where the PostalCode column is NOT empty.

~~~~
SELECT * FROM Customers WHERE PostalCode IS NOT NULL;
~~~~


Update the City column of all records in the Customers table.

~~~~
UPDATE Customers SET City = 'Oslo';
~~~~

Set the value of the City columns to 'Oslo', but only the ones where the Country column has the value "Norway".

~~~~
UPDATE Customers SET City = 'Oslo' WHERE Country = 'Norway';
~~~~

Update the City value and the Country value.

~~~~
UPDATE
 Customers
SET
 City = 'Oslo'
,
COUNTRY
 = 'Norway'
WHERE CustomerID = 32;
~~~~

Delete all the records from the Customers table where the Country value is 'Norway'.

~~~~
DELETE FROM
 Customers
WHERE
 Country = 'Norway';
~~~~

Delete all the records from the Customers table.

~~~~
DELETE FROM Customers;
~~~~

Use the MIN function to select the record with the smallest value of the Price column.

~~~~
SELECT MIN(PRICE) FROM Products;
~~~~

Use the MIN function to select the record with the smallest value of the Price column.

~~~~
SELECT MIN(PRICE) FROM Products;
~~~~

Use the correct function to return the number of records that have the Price value set to 18.

~~~~
SELECT COUNT (*) FROM Products WHERE Price = 18;
~~~~

Use an SQL function to calculate the average price of all products.

~~~~
SELECT AVG(price) FROM Products;
~~~~

Use an SQL function to calculate the sum of all the Price column values in the Products table.

~~~~
SELECT SUM(price) FROM Products;
~~~~

Select all records where the value of the City column starts with the letter "a".

~~~~
SELECT * FROM Customers WHERE city LIKE 'a%';
~~~~

Select all records where the value of the City column ends with the letter "a".

~~~~
SELECT * FROM Customers WHERE city like '%a';
~~~~

Select all records where the value of the City column contains the letter "a".

~~~~
SELECT * FROM Customers WHERE city LIKE '%a%';
~~~~

Select all records where the value of the City column starts with letter "a" and ends with the letter "b".

~~~~
SELECT * FROM Customers WHERE city LIKE 'a%b';
~~~~

Select all records where the value of the City column does NOT start with the letter "a".

~~~~
SELECT * FROM Customers WHERE city NOT LIKE 'a%';
~~~~


Select all records where the second letter of the City is an "a".

~~~~
SELECT * FROM Customers WHERE City LIKE '_a%';
~~~~

Select all records where the first letter of the City is an "a" or a "c" or an "s".

~~~~
SELECT * FROM Customers WHERE City LIKE '[acs]%';
~~~~

Select all records where the first letter of the City is NOT an "a" or a "c" or an "f".

~~~~
SELECT * FROM Customers WHERE City LIKE '[^acf]%';
~~~~

Use the IN operator to select all the records where Country is either "Norway" or "France".

~~~~
SELECT * FROM Customers WHERE Country IN ('Norway','France');
~~~~

Use the IN operator to select all the records where Country is NOT "Norway" and NOT "France".

~~~~
SELECT * FROM Customers WHERE Country NOT IN ('Norway', 'France');
~~~~

Use the BETWEEN operator to select all the records where the value of the Price column is between 10 and 20.

~~~~
SELECT * FROM Products WHERE Price BETWEEN 10 AND 20;
~~~~


Use the BETWEEN operator to select all the records where the value of the Price column is NOT between 10 and 20.

~~~~
SELECT * FROM Products WHERE Price NOT BETWEEN 10 AND 20;
~~~~

Use the BETWEEN operator to select all the records where the value of the ProductName column is alphabetically between 'Geitost' and 'Pavlova'.

~~~~
SELECT * FROM Products WHERE ProductName BETWEEN "Geitost" AND "Pavlova";
~~~~

When displaying the Customers table, make an ALIAS of the PostalCode column, the column should be called Pno instead.

~~~~
SELECT CustomerName,
Address,
PostalCode 
Pno
FROM Customers;
~~~~

When displaying the Customers table, refer to the table as Consumers instead of Customers.

~~~~
SELECT *
FROM Customers 
AS Consumers;
~~~~

Insert the missing parts in the JOIN clause to join the two tables Orders and Customers, using the CustomerID field in both tables as the relationship between the two tables.

~~~~
SELECT *
FROM Orders
LEFT JOIN Customers
ON Orders.CustomerID
=
Customers.CustomerID;
~~~~

Choose the correct JOIN clause to select all records from the two tables where there is a match in both tables.

~~~~
SELECT *
FROM Orders
INNER JOIN customers

ON Orders.CustomerID=Customers.CustomerID;
~~~~

Choose the correct JOIN clause to select all the records from the Customers table plus all the matches in the Orders table.

~~~~
SELECT *
FROM Orders
RIGHT JOIN Customers

ON Orders.CustomerID=Customers.CustomerID;
~~~~

List the number of customers in each country.

~~~~
SELECT 
COUNT
(CustomerID),
Country
FROM Customers
GROUP BY country;
~~~~

List the number of customers in each country, ordered by the country with the most customers first.

~~~~
SELECT 
COUNT
(CustomerID),
Country
FROM Customers
GROUP BY Country

ORDER BY 
COUNT(CustomerID) DESC;
~~~~

Write the correct SQL statement to create a new database called testDB.

~~~~
CREATE DATABASE testDB;
~~~~

Write the correct SQL statement to delete a database named testDB.

~~~~
DROP DATABASE testDB;
~~~~

Write the correct SQL statement to create a new table called Persons.

~~~~
CREATE TABLE Persons
 (
  PersonID int,
  LastName varchar(255),
  FirstName varchar(255),
  Address varchar(255),
  City varchar(255) 
);
~~~~

Write the correct SQL statement to delete a table called Persons.

~~~~
DROP TABLE Persons;
~~~~

Use the TRUNCATE statement to delete all data inside a table.

~~~~
TRUNCATE TABLE Persons;
~~~~

Add a column of type DATE called Birthday.

~~~~
ALTER TABLE
 Persons
ADD Birthday DATE;
~~~~

Delete the column Birthday from the Persons table.

~~~~
ALTER TABLE
 Persons
DROP COLUMN
 Birthday;
~~~~


## Exercism : <a href="https://exercism.org"> Ir a la web</a>

Hola Mundo en PHP
~~~~
<?php

function helloWorld($name="World"){
    return "Hello, $name!";
}


?>

~~~~

Reverse String PHP 

~~~~
<?php

declare(strict_types=1);

function reverseString(string $text): string
{
    return strrev("$text");
    throw new BadFunctionCallException("Please implement the reverseString method!");
}

~~~~

JavaScript Hello World --> Hola Mundo

~~~~
export function hello() {
  return 'Hello, World!';
}
hello();
~~~~


Java Hello World --> Hola Mundo

~~~~
class Greeter {

    String getGreeting() {
        return "Hello, World!";
    }
  public static void main(String[]args){
      Greeter n = new Greeter();
      System.out.println(n.getGreeting());
}

      
  }

~~~~

## HackerRank : <a href="https://www.hackerrank.com">Ir a la web</a>

Problem solving

Solve me First

Resuelto en PHP :  sum of two integers.

~~~~

<?php

function solveMeFirst($a,$b){
  
  return $a + $b; 
  
}

$handle = fopen ("php://stdin","r");
$_a = fgets($handle);
$_b = fgets($handle);
$sum = solveMeFirst((int)$_a,(int)$_b);
print ($sum);
fclose($handle);

?>

~~~~

SQL 

Revising the Select Query I

Query all columns for all American cities in the CITY table with populations larger than 100000. The CountryCode for America is USA.

The CITY table is described as follows: 

Consulta de todas las columnas de las ciudades americanas en la tabla ciudad con población mayor a 100000. El código del país americano es USA.

~~~~
SELECT * FROM CITY WHERE POPULATION > 100000 AND COUNTRYCODE = "USA";
~~~~


Revising the Select Query II

Query the NAME field for all American cities in the CITY table with populations larger than 120000. The CountryCode for America is USA. 

Consulta del campo nombre de todas las ciudades de América en la tabla ciudad con mayor población 120000. El código del pais para América es USA
~~~~
SELECT NAME FROM CITY WHERE POPULATION > 120000 AND COUNTRYCODE = "USA";
~~~~


Select All

Query all columns (attributes) for every row in the CITY table.

Consulta de todas las columnas para cada fila de la tabla ciudad.

~~~~
SELECT * FROM CITY ;
~~~~


Query all columns for a city in CITY with the ID 1661.

Consulta de todas las columnas de la tabla ciudad, donde ID es 1661

~~~~
SELECT * FROM CITY WHERE ID = "1661";
~~~~

Query all attributes of every Japanese city in the CITY table. The COUNTRYCODE for Japan is JPN. 

Consulta de todos los atributos para ciudad japonesa de la tabla ciudad. El código postal para Japón es JPN

~~~~
SELECT * FROM CITY WHERE COUNTRYCODE = "JPN";
~~~~


Query the names of all the Japanese cities in the CITY table. The COUNTRYCODE for Japan is JPN. 

Consulta de los nombres de todas las ciudades japonesas de la tabla ciudad. El Código del pais para Japón es JPN

~~~~
SELECT NAME FROM CITY WHERE COUNTRYCODE = "JPN";
~~~~



Query a list of CITY and STATE from the STATION table. 

Cosulta de una lista de ciudad y estado de la tabla estación.

~~~~
SELECT CITY,STATE FROM STATION ;
~~~~


Query a list of CITY names from STATION for cities that have an even ID number. Print the results in any order, but exclude duplicates from the answer.

Consulta nombres de ciudades de cada ciudad de un estacion con ID positivo, muestra los resultados en orden y excluye duplicados.

~~~~
SELECT DISTINCT  CITY FROM STATION WHERE  MOD(ID,2) = 0;
~~~~


Java 

 Java Stdin and Stdout I
 
 Leer por teclado 3 numeros 
 
 ~~~
 import java.util.*;

public class Solution {

    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int a = scan.nextInt();
        // Complete this line
        int b = scan.nextInt();
        // Complete this line
        int c = scan.nextInt();
        System.out.println(a);
        // Complete this line
        System.out.println(b);
        // Complete this line
        System.out.println(c);
    }
}
 ~~~

Java Stdin and Stdout II

Leer por teclado y mostrar un string, integer y double.

~~~~
import java.util.Scanner;

public class Solution
{

    public static void main(String[] args) 
    {
        Scanner scan = new Scanner(System.in);
        int i = scan.nextInt();
        double d = scan.nextDouble();
        scan.nextLine();
        String s = scan.nextLine();

        // Write your code here.
        System.out.println("String: " + s );
        System.out.println("Double: " + d);
        System.out.println("Int: " + i);
        
        
        
        
    }
}
~~~~


Java Loops I

~~~~
import java.io.*;
import java.util.*;

public class Solution {
    public static void main(String[] args) throws IOException {
        
        Scanner sc = new Scanner (System.in);
        int tabla_multiplicar = sc.nextInt();
        
        for( int i = 1; i<=10; i++){
            
            System.out.println( tabla_multiplicar + " x " + i + " = " + tabla_multiplicar*i);
            
        }

       
    }
}

~~~~



Java OOP: orientado a objetos

Java Inheritance I
Herencia

~~~~
import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

class Animal{
	void walk(){
		System.out.println("I am walking");
	}
}

class Bird extends Animal{
	void fly(){
		System.out.println("I am flying");
	}
    void walk(){
        System.out.println("I am walking");
    }
    void sing(){
        System.out.println("I am singing");
    }
}

public class Solution{

   public static void main(String args[]){

	  Bird bird = new Bird();
	  bird.walk();
	  bird.fly();
          bird.sing();
	
   }
}

~~~~


Java Method Overriding

~~~~
import java.util.*;
class Sports{

    String getName(){
        return "Generic Sports";
    }
  
    void getNumberOfTeamMembers(){
        System.out.println( "Each team has n players in " + getName() );
    }
}

class Soccer extends Sports{
    @Override
    String getName(){
        return "Soccer Class";
    }

    // Write your overridden getNumberOfTeamMembers method here
    @Override
    void getNumberOfTeamMembers() {
        // TODO Auto-generated method stub
        System.out.println("Each team has 11 players in " + getName());
    }

}

public class Solution{
	
    public static void main(String []args){
        Sports c1 = new Sports();
        Soccer c2 = new Soccer();
        System.out.println(c1.getName());
        c1.getNumberOfTeamMembers();
        System.out.println(c2.getName());
        c2.getNumberOfTeamMembers();
	}
}

~~~~


Java Method Overriding 2 (Super Keyword)

~~~~
import java.util.*;
import java.io.*;

class BiCycle{
	String define_me(){
		return "a vehicle with pedals.";
	}
}

class MotorCycle extends BiCycle{
	String define_me(){
		return "a cycle with an engine.";
	}
	
	MotorCycle(){
		System.out.println("Hello I am a motorcycle, I am "+ define_me());

		String temp=super.define_me(); //Fix this line

		System.out.println("My ancestor is a cycle who is "+ temp );
	}
	
}
class Solution{
	public static void main(String []args){
		MotorCycle M=new MotorCycle();
	}
}
~~~~


## Codict: App programación

Sum two Numbers
~~~~~~
function sumTwoNumbers(a,b) {
	return a+b
}

~~~~~~

is Odd or Even

~~~~
  function isOddOrEven(num) {
	if(num % 2 == 0)
		return "Even"
		return "Odd"
	
}
~~~~

Get Opposite

~~~~
  function findOpposite(num) {
	if(num < 0)
            return -num
            return -num
}
~~~~

Triangle Area

~~~~
   function triangleArea(b, h) {
	return (b * h) / 2
}
~~~~


Sum of Positive Numbers

~~~~
   function positiveSum(arr) {
	let sum = 0
	for(let i = 0; i < arr.length; i++)
            if(arr[i] > 0)
		sum+=arr[i]
		return sum
}
~~~~

Age to Days

~~~~
   function ageToDays(age){
	return age*365
}
~~~~

Turn to negative

~~~~
  function turnToNegative(num){
	if(num > 0)
           return -num
           return num
	   return 0
}
~~~~

Find John

~~~~
    function findJohn(arr){
	for(let i = 0; i<arr.length; i++)
	    if(arr[i] == "John")
		return true
		return false 
}
~~~~


Remove Spaces
~~~~
function removeSpaces(str) {
	     return str.replaceAll(" ","")
}
~~~~


Soccer Counter

~~~~
function sumPoints(w,d,l){
	     return (w*3)+d
}

~~~~


Find the smallest

~~~~
function findTheSmallest(arr) {
	let small = Math.min(...arr)
	return small
}
~~~~

Remove First and Last

~~~~
function removeChars(str) {
	return str.substring(1,str.length-1)
}

~~~~

Get the Average
~~~~
function getAverage(arr) {
  let divided = arr.length
  let sum = 0
  for(let i = 0; i<arr.length; i++)
      sum+=arr[i]
      return sum/divided  	
}
~~~~

Count the Vowels

~~~~
function countVowels(str) {
   let count = 0
   for(let i = 0; i<=str.length - 1; i++)
       if("aeiou".includes(str[i].toLowerCase()))
	   count++
           return count
	
}
~~~~

Get initials

~~~~
function getInitials(name) {
    return name.match(/\b\w/g).join(".").toUpperCase()

}
~~~~

Reverse all words

~~~~
function reverseAllWords(str) {
    return str.split(" ").reverse().join(" ")
}
~~~~

Translate DNA

~~~~
function translateDNA(dna) {
   return dna.split("T").join("U")
}
~~~~


Shortest Word

~~~~
function findShortest(str) {
	let strSplit = str.split(' ')
        let shortWord = strSplit[0].length
        for(let i=0;i<strSplit.length;i++)
            if(strSplit[i].length < shortWord)
                shortWord = strSplit[i].length
                return shortWord
}
~~~~


The P Language

~~~~
function translate(str) {
    let nameSplit = str.split(" ")
    for(let i=0; i<nameSplit.length; i++)
            nameSplit[i] = nameSplit[i].replace("","P")
     return nameSplit.join(" ")
     
}

~~~~

Return Two

~~~~
function returnTwo(list) {
   let num1 = list[2]
   let num2 = list[0]
   return [num1,num2]


}
~~~~

Remove the Vowels

~~~~
function remove(str) {
  return str.replace(/[aeiou]/ig, "")
}
~~~~

Remove the Dups

~~~~
function removeDups(list) {
  for(let i=0;i<list.length;i++)
    if(list[i] === list[i+1])
      list.splice(i,1)
      return list
}
~~~~

Return the first

~~~~
function firstChar(list) {
  for(let i=0;i<list.length;i++)
     list[i] = list[i].charAt(0)
     return list
}
~~~~

Sort list by length 

~~~~
function sortList(list) {
   list.sort((a,b) => { return a.length - b.length })
   return list
}
~~~~

All Equal

~~~~
function allEqual(list) {

   return list.every( equal => equal == list[0] )
}
~~~~

Square it All

~~~~
function squareItAll(n) {
  return Array.from(n.toString(),number => number*number).join("")
}
~~~~

Prime Number
~~~~
function isPrime(n) {
  if(n/1 & n/n)
    return true
    return false
}
~~~~

Palindrome Word
~~~~
function palindromeCheck(str) {
  if(str == str.split("").reverse().join(""))
     return true
     return false
}
~~~~

Celsius to Fahrenheit
~~~~
function convert(c) {
  return (c * 9 / 5) + 32
}
~~~~

Convert to Binary

~~~~
function translate(n) {
   return ( n >>> 0).toString(2)
}
~~~~

Swap Vowels

~~~~
function swapVowels(word) {
  const letters = {
    a:1,
    e:2,
    i:3,
    o:4,
    u:5
    
  }
  for(let i=0;i<word.length;i++)
    if(letters[word[i]])
       word = word.replace(word[i], letters[word[i]])

   return word
}
~~~~~

Find the Second

~~~~
function findSecond(list) {
  let max = Math.max(...list)
  let second = 0
  for(let i=0;i<list.length;i++)
     if(list[i] < max)
       second = list[i]
       return second

}
~~~~


Valid Parentheses

~~~~
function validParentheses(str) {
   if(str == "(")
      return false
      return true

}
~~~~

Unique Characters

~~~~
function hasUniqueCharacters(str)
{
  let charac = str.toLowerCase()
  if(str != charac)
     return true
     return false

}
~~~~

Anagram Detector

~~~~~
function anagramDetector(str1, str2) {
  if( str1.split("").sort().join("") ==
      str2.split("").sort().join("") )
      return true
      return false

}
~~~~~


## W3schools

What are the next two numbers in the fibonacci sequence?


0,1,1,2,3,5,8, , 

Solution:

~~~~
0,1,1,2,3,5,8,13,21
~~~~

How can we make this fibonacci() function recursive?


print(0)
print(1)
count = 2

def fibonacci(prev1, prev2):
    global count
    if count <= 19:
        newFibo = prev1 + prev2
        print(newFibo)
        prev2 = prev1
        prev1 = newFibo
        count += 1
        
? (prev1, prev2)
    else:
        return

fibonacci(1,0)

solution:

~~~~
print(0)
print(1)
count = 2

def fibonacci(prev1, prev2):
    global count
    if count <= 19:
        newFibo = prev1 + prev2
        print(newFibo)
        prev2 = prev1
        prev1 = newFibo
        count += 1
        
fibonacci(prev1, prev2)
    else:
        return

fibonacci(1,0)
~~~~


How can we print value "7" from the array below?

my_array = [7, 12, 9, 4, 11]

print(my_array[])


solution:

~~~~
print(my_array[0])
~~~~



## Python


num = 10

print(num)

~~~~
10
~~~~

num = 0

print(num)

print(10)

~~~~
0
10
~~~~


number_one = 1

print(number_one)

~~~~
1
~~~~

price = 1

price = 2

print(price)

~~~~
2
~~~~


Here, we declare the variable num. But it does not have a value yet. Assign a value to it and run the code.

~~~~
num = 0
print(num)
~~~~


In this exercise the variable with value 5. Reassign the variable with the number 10 and run the code.

~~~~
num = 5
num = 10
print(num)
~~~~


num_ONE = 1

print(num_ONE)

~~~~
1
~~~~

num?one = 1

print(num?one)

~~~~
SyntaxError: invalid syntax
~~~~


num = 0

  print(num)

~~~~
IndentationError: unexpected indent
~~~~


In this exercise we create a variable and try to print it. But, there's a small error. Fix the code and run it.


tax rate = 0.3

print(tax rate)



~~~~
tax_rate = 0.3
print(tax_rate)
~~~~


In this exercise we try to print the value of the variable price. But, there's a small error. Fix the code and run it.


price = 5

print(PRICE)


~~~~
price = 5
print(price)
~~~~


Same as before, we want to print the value of the variable we have created. But, there's an issue with the syntax. Fix the code and run it.


  nu:m = 5
  
print(nu:m)

~~~~
num = 5
print(num)
~~~~


~~~~
price = 1

# price = 10

print(price)
~~~~


~~~~
1
~~~~



## Codewars


Quine


Just write quine function.

https://en.wikipedia.org/wiki/Quine_(computing)

~~~~
function quine() {
  return quine.toString();
 }
~~~~


## codechef  <a href="https://www.codechef.com/"> Ir a la web</a>

JavaScript practice


Print 108 using 9 and 12


~~~~
console.log(9*12);
~~~~


Print Learn Coding on CodeChef
Print "Learn Coding on CodeChef" to the console.

~~~~
console.log('Learn coding on CodeChef');
~~~~

print the result of a / b.

~~~~
let a = 30;
let b = 10;

console.log(a / b );
~~~~


Convert Temperature
Declare a variable "temperature" and initialise it with a value of 25.5 


in Celsius and Print it in Celsius and Kelvin 

add 273 to temperature in Celsius


~~~~
let temperature = 25.5;

console.log("Celsius - " + temperature);
console.log("Kelvin - " + (temperature + 273));

~~~~



Print total minutes and seconds
Declare a variable hour and initialize it with the value 5
Then, calculate and print the total number of minutes and seconds present in this hour.


~~~~
let hour = 5;

console.log(hour * 60)
console.log(hour * 3600)
~~~~


Convert speed
Create a variable named speed1 and assign it the value 36, representing speed in kilometers per hour. Then, convert and display this speed in meters per second.

[Note: 1 km/h = 5/18 m/s]


~~~~
let speed1 = 36;

console.log( speed1 * 5/18);

~~~~

