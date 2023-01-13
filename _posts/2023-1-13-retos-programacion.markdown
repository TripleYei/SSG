---
layout: post
title:  "Retos y Ejercicios de Programacion"
date:   2023-1-13
categories: jekyll update
---

# Vamos a empezar

Voy a empezar a jugar con diferentes ejercicios y retos.

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

Mostrar el nombre y apellido de los paciente, quien no tiene alergias.

~~~~
SELECT first_name,last_name FROM patients WHERE allergies IS NULL;

~~~~


Show first name of patients that start with the letter 'C'

Mostrar el nombre del paciente que empiece con la letra C

~~~~

SELECT first_name from patients WHERE first_name LIKE "C%";


~~~~

