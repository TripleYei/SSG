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
