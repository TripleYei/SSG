---
layout: post
title:  "Uso de la API GeoPlugin"
date:   2023-3-24
categories: jekyll update
---


## Uso de GeoPlugin con JavaScript

Con esta API podemos obtener información de la ciudad, ip, país, etc.

<a href="https://www.geoplugin.com/"> Acceder a la web</a>

## Uso del Script

~~~~
<script src="http://www.geoplugin.net/javascript.gp"></script>
~~~~

## Funcion Ciudad, IP, País
~~~~
function geoplugin_city()
function geoplugin_request()
function geoplugin_countryName()
~~~~

## Ejemplo 

~~~~
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>GeoPlugin</title>
    <script src="http://www.geoplugin.net/javascript.gp"></script>
    <script>
      function geo()
	{
   	let ciudad = geoplugin_city() ,  pais = geoplugin_countryName() ,  ip = geoplugin_request();
	 capa.innerHTML = "Ciudad: " + ciudad + " Pais: " + pais + " IP: " + ip;
	}

   </script>
</head>
<body onload="geo()">
    <div id = "capa"></div>

</body>
</html>

~~~
