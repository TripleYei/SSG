---
layout: post
title:  "Data Visualization"
date:   2023-11-15
categories: jekyll update
---

# Data Visualization

## Ejercicios D3 

 Add Document Elements with D3

~~~~
<body>
  <script>
 
    const anchor = d3.select("body").append("h1").text("Learning D3");
  </script>
</body>
~~~~

Select a Group of Elements with D3

~~~~
<body>
  <ul>
    <li>Example</li>
    <li>Example</li>
    <li>Example</li>
  </ul>
  <script>
    const anchors = d3.selectAll("li").text("list item");
  </script>
</body>
~~~~

Work with Data in D3

~~~~
<body>
  <script>
    const dataset = [12, 31, 22, 17, 25, 18, 29, 14, 9];
    
    d3.select("body").selectAll("h2")
    .data(dataset)
    .enter()
    .append("h2")
    .text("New Title");

  </script>
</body>
~~~~



## Chart.js


Pie Charts
~~~~
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
	
  <canvas id="myChart"></canvas>
  <style>
  	canvas{
  		width: 100%;
  		max-width: 700px;
  	}
  </style>

   <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

<script>
  const ctx = document.getElementById('myChart');

  new Chart(ctx, {
    type: 'pie',
    data: {
      labels: ['HTML', 'CSS', 'JS'],
      datasets: [{
        label: '# of Votes',
        data: [12, 19, 3],
        borderWidth: 1
      }]
    },
    options: {
      scales: {
        y: {
          beginAtZero: true
        }
      }
    }
  });
</script>
</body>
</html>
~~~~


Bar Charts

~~~~
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
	
  <canvas id="myChart"></canvas>
  <style>
  	canvas{
  		width: 100%;
  		max-width: 700px;
  	}
  </style>

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

<script>
  const ctx = document.getElementById('myChart');

  new Chart(ctx, {
    type: 'bar',
    data: {
      labels: ['HTML', 'CSS', 'JS'],
      datasets: [{
        label: '# of Votes',
        data: [12, 19, 3],
        borderWidth: 1
      }]
    },
    options: {
      scales: {
        y: {
          beginAtZero: true
        }
      }
    }
  });
</script>
</body>
</html>
~~~~

Line Graphs 

~~~~

<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
	
  <canvas id="myChart"></canvas>
  <style>
  	canvas{
  		width: 100%;
  		max-width: 700px;
  	}
  </style>

  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

<script>
  const ctx = document.getElementById('myChart');

  new Chart(ctx, {
    type: 'line',
    data: {
      labels: ['HTML', 'CSS', 'JS'],
      datasets: [{
        label: '# of Votes',
        data: [12, 19, 3],
        borderWidth: 1
      }]
    },
    options: {
      scales: {
        y: {
          beginAtZero: true
        }
      }
    }
  });
</script>
</body>
</html>
~~~~

## Looker Studio

Crear gráfico desde Looker Studio desde una Hoja de cálculo de Google



Clic en Crear  --> Fuente de datos

Seleccionar Hojas de cálculo de Google

Se selecciona la hoja de cálculo

Opciones :

Quitar : Usar la primera fila como encabezado

Clic en Conectar

Tenemos las dimensiones : A,B Y C --> Como la hoja de Cálculo


Clic en Crear Informe, Añadir al Informe

Añadir un gráfico: Barras,Circula,Lineas

¡Enhorabuena, ya tienes un gráfico!

