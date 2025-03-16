---
title: "Análisis de robos en CDMX"
author: "Alan Jrz"
date: "2025-03-16"
draft: false
image: img/banner/blog1.jpg
layout: post
description: "Analicé el perfil de las víctimas de robo con violencia a cuentahabientes, enfocándome en la cantidad, edad, sexo, horarios y ubicaciones de mayor incidencia. También identifiqué los cajeros e instituciones bancarias con mayor riesgo por su cercanía a zonas de alta concentración de robos."
tags: ["Robo a cuentahabientes", "Inseguridad", "R", "Hotspot"]
chunk_output_type: inline
---
## Total de víctimas

Entre 2019 y 2024 , la cantidad de víctimas de robos a cuentahabiente al
salir de cajero con violencia ha mostrado una clara tendencia
descendente, destacando algunos momentos clave. En 2019, se registraron
los valores más altos, con un pico máximo de 74 robos en julio. Sin
embargo, en abril de 2020, con el inicio de la pandemia por COVID-19, se
produjo una caída drástica, reduciendo los robos a menos de 15
incidentes mensuales. A partir de 2021 y 2022, hubo una recuperación
moderada, pero sin alcanzar los niveles pre-pandemia. Desde 2023, la
tendencia continuó a la baja, y en 2024 se registraron los mínimos
históricos, con solo 8 robos en abril y septiembre, reflejando un cambio
significativo en el comportamiento del delito.

<div class="iframe-container">
<iframe title="Robos a cuentahabiente saliendo del cajero" aria-label="Interactive line chart" id="datawrapper-chart-WQyVk" src="https://datawrapper.dwcdn.net/WQyVk/3/" scrolling="no" frameborder="0" style="width: 100%; min-width: 100% !important; border: none;" height="525" data-external="1">
</iframe>
</div>

## Características

La ocurrencia de los delitos está vinculada con el horario de operación
de los bancos comerciales, ya que de lunes a viernes entre las 09:00 y
las 16:00 hrs. se cometieron 73.8% de los robos (1 496). Asimismo, el
día viernes concentró mayor proporción, con 21% del total. De tal forma,
fue identificado el día viernes como el de mayor riesgo de sufrir un
robo violento al salir del cajero.

El análisis de robos a cuentahabientes muestra una clara concentración
en horario bancario (09:00 a 16:00 hrs.), donde ocurre el 73.8% de los
incidentes. El viernes es el día de mayor riesgo, con el 21% del total
de robos y un pico máximo a las 13:00 hrs. (68 robos), lo que sugiere
que los delincuentes aprovechan el aumento de transacciones previo al
fin de semana.


<div class="iframe-container">
<h4 style="font-family: 'Inter', sans-serif; font-size: 21px; font-weight: 700; text-align: left; margin-bottom: 10px;">
    Ocurrencia por día y hora de la semana
</h4>
<h6 style="font-family: 'Inter', sans-serif; font-size: 14px; font-weight: 500; text-align: left; margin-top: 2px;">
    Total acumulado del periodo
</h6>
<iframe src="/js/G2.html" width="100%" height="500px" style="width:100%; min-width: 100% !important; border: none; overflow: hidden; display: block;" height="100">
</iframe>
<h6 style="font-family: 'Inter', sans-serif; font-size: 10px; font-weight: 600; text-align: left;  font-style: italic; margin-bottom: 10px;">
    Nota: No se consideran los registros para los que no se especificó el día y hora de ocurrencia.<br>
    Gráfico: Alan Jrz Fuente: FGJ-CDMX
</h6>
</div>


Las características de las víctimas señalan que los cuentahabientes
entre 30 y 39 años de edad fueron los de mayor riesgo, en especial los
hombres ya que 32.4% de las víctimas de se situaron en ese rango de
edad, al igual que 28.7% de las mujeres. A medida que aumenta la edad,
la proporción de víctimas disminuye, siendo menor en los grupos de 50 a
59 años y 60 y más, lo que sugiere que los delincuentes prefieren atacar
a personas en edad productiva. Es importante mencionar que, del total de
víctimas, 7 de cada 10 fueron hombres, lo que remarca el riesgo
enfrentado.
<div style="height: 40px;"></div>
<div class="iframe-container">
<iframe title="Distribución de víctimas por rango de edad y sexo" aria-label="Gráfico de rangos" id="datawrapper-chart-KRbX1" src="https://datawrapper.dwcdn.net/KRbX1/4/" scrolling="no" frameborder="0" style="width: 100%; min-width: 100% !important; border: none;" height="350" data-external="1">
</iframe>
</div>

## Distribución Geográfica
<div style="height: 40px;"></div>

<div class="iframe-container">
<h4 style="font-family: 'Inter', sans-serif; font-size: 21px; font-weight: 700; text-align: left; margin-bottom: 10px;">
    Identificación de hotspot y cajeros en riesgo
</h4>
<h6 style="font-family: 'Inter', sans-serif; font-size: 14px; font-weight: 500; text-align: left; margin-top: 2px;">
    
</h6>
<iframe src="/js/M1.html" width="100%" height="500px" style="border: none; overflow: hidden; display: block;"></iframe>
<h6 style="font-family: 'Inter', sans-serif; font-size: 10px; font-weight: 600; text-align: left;  font-style: italic; margin-bottom: 10px;">
    Nota: No se consideran los registros para los que no se especificó longitud y latitud.<br>
    Fue utilizado el algoritmo DBSCAN con proximidad de ~150 metros y un minimo de 5 delitos.<br>
    Gráfico: Alan Jrz Fuente: FGJ-CDMX y Banxico
</h6>
</div>
