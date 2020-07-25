---
title: '3 - Moldeo y Fundición'
date: 2020-06-17T19:30:08+10:00
draft: false
weight: 6
summary: Video Tutoriales del módulo de Desbaste CNC.
---

Ejemplo de moldeo y fundición mediante la técnica de desbaste en CNC. 

---

## Tutorial: Desbaste CNC


{{< video-local src="http://pgarreton.com/pgarreton.com/mid2020/Mecanizado25D.mp4" >}}

Tutorial de desbaste por distintas profundidades utilizando el respaldo de la silla Fresia.

#### Modelo 3d

{{< iframe-skfb>}}

###### Archivo grasshopper para diseño de molde

{{< boton-descargar src="gh_palmeta.gh" >}}

###### Archivo .STEP (solido) para abrir en Fusion360

{{< boton-descargar src="palmeta.stp" >}}

#### Trayectoria con RhinoCam

![rhinocam1](/img/desbaste/RHI4.png)

Después de abrir el modelo 3d, se debe cocinar la geometría y convertirla en objeto tipo "NURBS"

![rhinocam2](/img/desbaste/RHI6.png)

Luego de insertar el objeto en relación al eje de coordenadas, se debe generar un stock de cuadro delimitador, simulando el material a desbastar.

![rhinocam3](/img/desbaste/RHI2.png)

Siempre delimitando el área de corte para que la máquina no salga del sector deseado.

![rhinocam4](/img/desbaste/RHI5.png)

Primer desbaste horizontal para eliminar el exceso del material, ya que las maderas suelen tener variabilidad en el grosor.

![rhinocam5](/img/desbaste/RHI3.png)

El desbaste comienza fresando la superficie en los tres ejes.

![rhinocam6](/img/desbaste/RHI1.png)

Acabado.

{{< video-local src="/img/desbaste/rough.mp4" >}}

Este video muestra la trayectoria que hará el desbaste horizontal.

{{< video-local src="/img/desbaste/FeFini.mp4" >}}

Este video simula la trayectoria creada, se puede ver la fresa de 6 mm.

{{< video-local src="/img/desbaste/SimuPro.mp4" >}}

Simulación total de desbastes horizontales y luego acabado final.

#### Fresando el molde

![fresado1](/img/desbaste/cnc/mold1.jpg)
\
\
![fresado2](/img/desbaste/cnc/mold2.jpg)
\
\
{{< video-local src="/img/desbaste/cnc/molding.mp4" >}}

![fresado3](/img/desbaste/cnc/mold3.jpg)

![fresado4](/img/desbaste/cnc/mold4.jpg)

![fresado5](/img/desbaste/cnc/mold5.jpg)

![fresado6](/img/desbaste/cnc/mold6.jpg)

Una vez obtenido el modelo desde la CNC, este se lija y se le agrega una capa de aceite para facilitar la extracción de la silicona.

![fresado8](/img/desbaste/cnc/mold8.jpg)

![fresado7](/img/desbaste/cnc/mold7.jpg)

Se confecciona una caja abierta para incorporar la silicona y que esta quede en el lugar deseado.


![fresado9](/img/desbaste/cnc/mold9.jpg)

Luego de 24 horas de reposo se remueve la caja.

![fresado10](/img/desbaste/cnc/mold10.jpg)

En este caso se realizó el positivo del molde con yeso, material que demora aproximadamente una hora en fraguar.

![fresado11](/img/desbaste/cnc/mold11.jpg)
\
\
Al final del proceso tenemos el molde de madera (positivo), el molde de silicona (negativo) y la pieza final en yeso (positivo).
\
\
![fresado12](/img/desbaste/cnc/mold12.jpg)
\
\
Ejemplos de otros moldes.
\
\
{{< gallery dir="/img/desbaste/cnc" />}} {{< load-photoswipe >}}