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

**Aclaración**:  En las siguientes gráficas el eje x utiliza la cantidad de días a partir del día en que se confirmo el primer caso de COVID-19 reportado en Guatemala (13-03-2020). 

#### Casos Acumulados:
![Screenshot]({{site.url}}/resources/Casos_Acumulados.png)
En esta gráfica se muestra la evolución de la cantidad **acumulada** de casos. Se puede observar como solamente los casos activos no presentan un crecimiento constante. 

#### Casos Diarios:
![Screenshot]({{site.url}}/resources/Casos_Diarios.png)
Esta gráfica nos muestra la cantidad de casos **nuevos diarios** de cada categoria. Valores negativos indican que ese día en particular se reportaron más recuperados que casos confirmados.  

### Casos Confirmados y Pruebas Diarias
![Screenshot]({{site.url}}/resources/Razon_confirmados_pruebas_diario.png)
En esta gráfica se observa la relación entre la cantidad de pruebas realizadas y casos confirmados para cada día, la formula utilizada es: 

Porcentaje = 100*(CasosConfirmados/Pruebas Realizadas)

Un valor más alto nos indíca que las pruebas que se realizaron fueron efectivas, es decir, que se identificaron más casos positivos. 

Ojo: El día **2020-07-13** se reportaron 1221 confirmados y solamente 1089 pruebas, por lo que se observa un pico que se sale del 100%. 

### Pruebas Acumuladas y Diarias
![Screenshot]({{site.url}}/resources/Resumen_Pruebas_semilogy.png)
Esta gráfica consiste de dos partes: La cantidad de pruebas realizadas diarias y la cantidad de pruebas acumuladas. 

### Evolución de Casos
![Screenshot]({{site.url}}/resources/Evolucion_Porcentaje_Casos.png)
En esta gráfica se muestra la evolución del porcentaje de casos **activos, fallecidos** y **recuperados** respecto al total de casos. 

![Screenshot]({{site.url}}/resources/Evolucion_Porcentaje_Casos_Detalle.png)
Esta es la misma gráfica con la evolución de cada tipo de caso por separado con su respectivo eje. Cabe mencionar que al inicio no se contaba con casos recuperados, por eso los primeros días no se observa la variable. 

### Evolución de Casos Cerrados
Un cierre de caso se da cuando un caso activo se recupera o fallece, esta gráfica muetra como esta proporción a cambiado a lo largo de la pandemia. 

![Screenshot]({{site.url}}/resources/Evolucion_Casos_Cerrados.png)

Se puede observar como en dos ocasiones, alrededor del día 40 y 75, se reportaron más casos fallecidos que recuperados. 