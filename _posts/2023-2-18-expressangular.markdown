---
layout: post
title:  "Consumir API Express con Angular en local"
date:   2023-2-18
categories: jekyll update

---


## Consumir una API con Angular en local

Creamos el proyecto 

~~~~
ng new app
~~~~

En Routing le decimos y (yes) y con CSS

Creamos un componente

~~~~
ng generate component inicio
~~~~

En el archivo ts:

Tenemos que importar el modelo y el servicio


Creamos un servicio

~~~~
ng generate service Servicios/data
~~~~

Dentro del servicio necesitamos el HttpClient y el modelo
~~~~
Aqui es donde ponemos : api = "http://localhost:3000/yei";
~~~~

NOTA : Al conectar front con back, nos saldrá un error de CORS.

Lo solucionamos así:
~~~~
npm install cors
~~~~

<a href="https://github.com/TripleYei/angular_express/blob/main/web.js"> Acceder al código </a>





Creamos un modelo, donde ponemos:

Ejemplo: ejemplo.model.ts

Depende de la API, en este caso la API tiene los campos id,name y url
~~~~
id:string;
name:string;
url:string;
~~~~

En el app.module.ts 

Se importa el servicio y se pone en providers.

También el HttpClient se pone en imports


app.component.html

ponemos el component que creamos

~~~~
<app-inicio></app-inicio>
<router-outlet> </router-outlet>
~~~~


## Ejemplo

<a href="https://github.com/TripleYei/angular_express"> Acceder</a>

