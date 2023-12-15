---
layout: post
title:  "Retos y Ejercicios de Programación"
date:   2023-1-13
categories: jekyll update
---

# Vamos a empezar

Voy a jugar con diferentes ejercicios y retos.

## JSchallenger <a href="https://www.jschallenger.com/"> Ir a la web</a>

JavaScript Practice : JavaScript fundamentals 

Suma de dos numeros : sum two numbers

~~~~
function myFunction(a, b) {

   return a + b ;
}

~~~~

Comparación de operadores : Comparison operators, strict equality
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

Get type of value : obtener el tipo del valor

~~~~

function myFunction(a)
{

   return typeof a;
}
~~~~

## Practicar SQL online : <a href="https://www.sql-practice.com/"> Ir a la web</a>

Show first name and last name of patients who does not have allergies. (null)

Mostrar el nombre y apellido de los pacientes, quién no tiene alergias.

~~~~
SELECT first_name,last_name FROM patients WHERE allergies IS NULL;
~~~~


Show first name of patients that start with the letter 'C'

Mostrar el nombre del paciente que empiece con la letra C

~~~~
SELECT first_name from patients WHERE first_name LIKE "C%";
~~~~

Show first name, last name, and gender of patients who's gender is 'M'

Mostrar nombre, apellido, y genero del paciente, genero es M

~~~~
SELECT first_name,last_name,gender from patients WHERE gender="M";
~~~~

Show first name and last name of patients that weight within the range of 100 to 120 (inclusive)

Mostrar nombre y apellido del paciente, el peso sea entre 100 y 120
~~~~
SELECT first_name,last_name from patients WHERE weight between 100 AND 120;
~~~~

Update the patients table for the allergies column. If the patient's allergies is null then replace it with 'NKA'

Actualizar la tabla pacientes, columna alergias. Si el paciente alérgico es nulo reemplza con "NKA"
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

Resuelto en PHP :  sum of two integers

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

Consulta de todas las columnas de las ciudades americanas en la tabla ciudad , con población mayor a 100000. El código del país americano es USA

~~~~
SELECT * FROM CITY WHERE POPULATION > 100000 AND COUNTRYCODE = "USA";
~~~~


Revising the Select Query II

Query the NAME field for all American cities in the CITY table with populations larger than 120000. The CountryCode for America is USA. 

Consulta del campo nombre de todas las ciudades de américa en la tabla ciudad con mayor población 120000. El código del pais para américa es USA
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

Consulta de todos los atributos para ciudad Japonsa de la tabla ciudad. El código postal para Japón es JPN

~~~~
SELECT * FROM CITY WHERE COUNTRYCODE = "JPN";
~~~~


Query the names of all the Japanese cities in the CITY table. The COUNTRYCODE for Japan is JPN. 

Consulta de los nombres de todas las ciudades japonesas de la tabla ciudad. El Código del pais para Japón es JPN

~~~~
SELECT NAME FROM CITY WHERE COUNTRYCODE = "JPN";
~~~~



Query a list of CITY and STATE from the STATION table. 

Cosulta de una lista de ciudad y estado de la tabla estación

~~~~
SELECT CITY,STATE FROM STATION ;
~~~~


Query a list of CITY names from STATION for cities that have an even ID number. Print the results in any order, but exclude duplicates from the answer.

Consulta de nombres de ciudades de cada ciudad de un estacion con ID positivo, muestra los resultados en orden y excluye duplicados.

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

Leer por teclado y mostrar, un string, integer y double.

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



Java OOP : orientado a objetos

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


## Codict. App programación.

Sum two Numbers.
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
