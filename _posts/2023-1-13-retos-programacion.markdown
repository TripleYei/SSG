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
	    if(arr[i] == "John)
		return true
		return false 
}
~~~~
