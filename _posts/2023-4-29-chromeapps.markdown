---
layout: post
title:  "Creación de extensiones en Chrome"
date:   2023-04-29
categories: jekyll update
---


## Crear Extensiones con HTML y JavaScript

# Vamos a necesitar un manifest.json

~~~~
{

  "name": "nombre aplicación",
   "description": "Descripción de la aplicación",
   "version": "1.0",
   "app": {
       "background": {
       
            "scripts": ["script.js"]
        }
   
   }

}

~~~~

# Se crea un script.js

~~~~
chrome.app.runtime.onLaunched.addListener(function() {
  
    chrome.app.window.create('index.html' , {
    
          'outerBounds' : {
              'width': 400,
               'height': 500
          }
      });


});

~~~~


# Se crea código HTML

~~~~
<!DOCTYPE html>
<head>
    <title>Creación de una extensión</title>
</head>
<body>
  <h1>Felicidades</h1>
</body>
</html>
~~~~


## Chrome

Entramos en el menú, Más herrramientas, extensiones.


Cargar descomprimida, subimos la carpeta, donde hemos creado los anteiores archivos.
