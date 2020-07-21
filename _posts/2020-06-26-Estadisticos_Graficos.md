---
layout: post
title:  "Estadísticos y Gráficos"
date:   2020-06-26 00:00:00 +0000
categories: guatemala corona graficas estadisticas 
---


Como parte de este proyecto, originalmente se pensó en llevar registro de los datos relevantes durante la pandemia de la COVID-19 en Guatemala, y servir como repositorio de datos para que otros informaran a la población. Gracias al esfuerzo de voluntarios como [Hiram22](https://github.com/hiram22), a partir de hoy estaremos también proveyendo diaramente estadísticos y gráficas para alcanzar a un público más amplio, proveer información de forma más clara y que podría informar decisiones individuales.

Estas gráficas son generadas a partir de los datos en [nuestro repositorio](https://github.com/ncovgt2020/ncovgt2020) y gracias al esfuerzo de [Hiram22](https://github.com/hiram22).

# Estadísticos Relevantes, actualizados 19 julio 2020:

confirmados:  39039

recuperados:  25539

fallecidos:  1502

activos:  11998

pruebas realizadas:  123786


# Gráficas

**Aclaración**:  En las siguientes gráficas el eje x utiliza la cantidad de días a partir del día en que se confirmo el primer caso de COVID-19 en Guatemala (13-03-2020). 

#### Casos Acumulados:
![Screenshot]({{site.url}}/resources/Casos_Acumulados.png)
En esta gráfica se muestra la evolución de la cantidad **acumulada** de casos. Se puede observar claramente como todas se encuentran en crecimiento hasta la feccha (2020-07-10).

#### Casos Diarios:
![Screenshot]({{site.url}}/resources/Casos_Diarios.png)
Esta gráfica nos muestra la cantidad de casos **nuevos diarios** de cada categoria. 

### Casos Confirmados y Pruebas Diarias
![Screenshot]({{site.url}}/resources/Razon_confirmados_pruebas_diario.png)
En esta gráfica se observa la relación entre la cantidad de pruebas realizadas y casos confirmados para cada día, la formula utilizada es: 

$$\frac{CasosConfirmados}{Pruebas Realizadas}{x100}$$

Un valor más alto nos indíca que las pruebas que se realizaron fueron efectivas, es decir, que se identificaron más casos positivos. 

### Pruebas Acumuladas y Diarias
![Screenshot]({{site.url}}/resources/Resumen_Pruebas_semilogy.png)
Esta gráfica consiste de dos partes: La cantidad de pruebas realizadas diarias y la cantidad de pruebas acumuladas. 

### Evolución de Casos
![Screenshot]({{site.url}}/resources/Evolucion_Porcentaje_Casos.png)
En esta gráfica se muestra la evolución del porcentaje de casos **activos, fallecidos** y **recuperados** respecto al total de casos. 

![Screenshot]({{site.url}}/resources/Evolucion_Porcentaje_Casos_Detalle.png)