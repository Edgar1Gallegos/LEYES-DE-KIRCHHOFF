# LEYES-DE-KIRCHHOFF


1. PLANTEAMIENTO DEL PROBLEMA 

En el siguiente informe de laboratorio se va a emplear los conocimientos aprendidos en la teoría de la materia de Fundamentos de Circuitos eléctricos. En el cuál determinaremos los valores teóricos y experimentales en un circuito, para lo cual usaremos un software que nos permite emular el laboratorio. 


2. OBJETIVOS

* Explicar y demostrar experimentalmente la Ley de Kirchhoff de Voltajes y la Ley de
Kirchhoff de Corrientes.

* Determinar el cumplimiento de las leyes de Kirchoff en un circuito eléctrico 

* Medir las corrientes y los voltajes que circulan por el circuito

* Familiarizarse con el uso del multímetro en modo de voltímetro y amperímetro.

* Estudiar y analizar mallas y así tener un mejor entendimiento sobre el tema de circuitos eléctricos.


3. ESTADO DEL ARTE

A inicios del presente año Josh Bongard experto en informática y robótica de la Universidad de Vermont (EE UU) y coautor de la nueva investigación que se publica en la revista PNAS junto al estudiante Sam Kriegman han empleado células madres de embriones de ranas para crear unas ‘máquinas vivas’ a las cuales bautizaron como ‘xenobots’. 
Los creadores afirman que no son robots tradicionales sino se trata de un organismo vivo y programable, los cuales se pueden utilizar para transportar algún objeto, buscar compuestos desagradables o de contaminación radiactiva, recolectar microplásticos en los océanos o viajar por las arterias para raspar placa. Estos xenobots son totalmente biodegradables, ya que una vez que mueren después de 7 días de funcionamiento se convierten en células muertas de la piel.

4. MARCO TEÓRICO 


##### Mallas eléctricas

En un circuito eléctrico, una malla es un camino cerrado formado por elementos de eléctricos. Podemos visualizar que existen 4 mallas en el circuito. 

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/Mallas.jpeg)

Segun la ley de voltajes Kirchhoff establece que la sumatatoria de los voltajes en una malla es igual a cero.

##### Código de colores para obtener el valor de las resistencias.

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/Colores%20resistencias.jpeg)

##### Leyes De Kirchhoff

Las leyes de Kirchhoff fueron formuladas por el físico Gustav Kirchhoff en 1845. Es responsable de 2 leyes fundamentales en teoría clásica de circuitos eléctricos. Estas leyes nos permiten resolver los circuitos electrónicos utilizando un sistema de ecuaciones que a menudo bastante usadas en ingeniería eléctrica e ingeniería electrónica. Además estas leyes indican que las corrientes que entran a un nodo son igual a la suma de corrientes que salen, y por otro lado la ley de las mallas que dice que la suma de voltajes en una malla o rama cerrada es igual a cero, entonces al comparar con los valores medidos se puede notar un porcentaje de error bajo.



##### Enunciado de la primera ley de Kirchhoff

En un circuito eléctrico, es común que se generen nodos de corriente. Un nodo es el punto del circuito donde se unen más de un terminal de un componente eléctrico.La razón por la cual se cumple esta ley se entiende perfectamente en forma intuitiva si uno considera que la corriente eléctrica es debida a la circulación de electrones de un punto a otro del circuito.
Mas científicamente se puede decir, que siempre se debe cumplir una ley de la física que dice que la energía no se crea ni se consume, sino que siempre se transforma. La energía eléctrica que entrega la batería se subdivide en el nodo de modo que se transforma en iguales energías térmicas entregadas al ambiente por cada uno de los resistores. Si los resistores son iguales y están conectados a la misma tensión, deben generar la misma cantidad de calor y por lo tanto deben estar recorridos por la misma corriente; que sumadas deben ser iguales a la corriente entregada por la batería, para que se cumpla la ley de conservación de la energía.
En una palabra, que la energía eléctrica entregada por la batería es igual a la suma de las energías térmicas disipadas por los resistores.

##### Enunciado de la segunda ley de Kirchhoff 

Cuando un circuito posee mas de una batería y varios resistores de carga ya no resulta tan claro como se establecen la corrientes por el mismo. En ese caso es de aplicación la segunda ley de Kirchhoff, que permite resolver el circuito con una gran claridad.
La segunda ley de Kirchhoff indica que la suma algebraica de todos los voltajes en una malla o bucle cerrado debe ser igual a cero.
El hecho de que se refiera a la suma algebraica implica el cuidado de las polaridades de las fuentes de energía, así como los signos de las caídas de tensión sobre cada componente eléctrico del circuito.
Por ende, al momento de aplicar esta ley hay que ser muy precavidos en el sentido de circulación de la corriente y, en consecuencia, con los signos de los voltajes contenidos dentro de la malla.











5. DIAGRAMAS 

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/Diagrama2.jpg) 


6. LISTA DE COMPONENTES 

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/Tabla%20de%20Componentes.jpg) 

7. EXPLICACIÓN DEL CÓDIGO FUENTE 

Se conecta una fuente en este caso de 10 voltios al protoboard, el positivo y el negativo. Luego se conectan las resistencias siguiendo el diagrama, que en este caso son 5 de valores de 1.5k, 2.2k (2), 3.9k y 1.8k. Siguiendo el esquema mediante cables se unen los elementos y luego con multímetro se mide los valores pedidos. 

8. APORTACIONES 

* Alrededor de 1857, Kirchhoff descubrió que la velocidad de una corriente eléctrica en un cable altamente conductor es independiente de la naturaleza del cable y es prácticamente igual a la velocidad de la luz; aunque Kirchhoff asumió que era una coincidencia y no una ley de la Naturaleza, como Maxwell estableció 5 años más tarde al demostrar que la luz es una radiación electromagnética.

* Las leyes de Kirchhoff resultan de vital importancia ya que requerimos el manejo de técnicas que nos permitieron resolver circuitos complejos de manera rápida y efectiva, además, estas leyes nos permitieron analizar dichos problemas por medio de dos técnicas: Mallas y Nodos.

* En 1845 enunció las denominadas leyes de Kirchhoff aplicables al cálculo de tensiones, intensidades y resistencias en el sí de una malla eléctrica, entendidas como una extensión de la ley de la conservación de la energía, basándose en la teoría del físico Georg Simon Ohm, según la cual la tensión que origina el paso de una corriente eléctrica es proporcional a la intensidad de la corriente.

* Una corriente eléctrica, puesto que se trata de un movimiento de cargas, produce un campo magnético, un fenómeno que puede aprovecharse en el electroimán

9. CONCLUSIONES 

* Las leyes de Kirchhoff resultan de vital importancia ya que requerimos el manejo de técnicas que nos permitieron resolver circuitos complejos de manera rápida y efectiva, además, estas leyes nos permitieron analizar dichos problemas por medio de dos técnicas: Mallas y Nodos. Por otra parte, este laboratorio resulto ser de gran provecho, ya que pudimos armar circuitos con más de una resistencia colocándola en serie y paralelo, lo que hace que los laboratorios resulten de mayor interés para ampliar más nuestros conocimientos en el armamento de circuitos en el protoboard.

* Esta práctica de laboratorio, aunque fue hecha de manera virtual, resulto de mucha ayuda ya que ofrece la mayoría de disposiciones a ocupar de manera física, nos sorprendió los valores tan exactos que arrojo aun siendo gratuito además de que pudimos comprobar las leyes de Kirchoff entre otras cosas.

* Los valores de corriente y voltaje determinados por leyes de Kirchhoff son muy aproximados a los valores experimentales, con errores menores al 0.5% en su mayoría.

10. RECOMENDACIONES 


11. CRONOGRAMA 

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/CRONOGRAMA.jpg) 

12. BIBLIOGRAFÍA 

* Matthew N.O.Sadiku, C. K. (2006). Fundamentos de circuitos eléctricos. McGraw-Hill Interamericana.
radio electronica. (s.f.). Recuperado el 01 de Junio de 2020, de http://www.radioelectronica.es/articulos-teoricos/200-las-leyes-de-kirchhoff
* Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega.
* Alcalde San Miguel, P. (2010). Electrónica general: equipos electrónicos de consumo. Madrid: Thomson/Paraninfo.
* William H.Hayt,Jr; Jack E. Kemmerly; Steven M. Durbin. Análisis de ciruitos en ingeniería.
* Electrónica completa. (s.f.). Recuperado el 01 de Junio de 2020, de http://electronicacompleta.com/lecciones/leyes-de-kirchhoff/
* Khan Academy. (s.f.). Khan Academy. Recuperado el 01 de Junio de 2020, de https://es.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/ee-kirchhoffs-laws
* Sánchez, A. S. (s.f.). EDUCACIÓN Y TECNOLOGIA. (weebly) Recuperado el 01 de Junio de 2020, de https://www.educoteca.com/tinkercad.html
* wikipedia. (20 de Noviembre de 2018). Wikipedia. (Fundación Wikimedia, Inc) Recuperado el 01 de Junio de 2020, de https://es.wikipedia.org/wiki/Leyes_de_Kirchhoff


13. ANEXOS 

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/C%C3%A1lculos3.jpeg)
![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/C%C3%A1lculos2.jpeg)
![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/C%C3%A1lculos.jpeg)
![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/C%C3%A1lculos1.jpeg)


14. MANUAL DE USUARIO 

##### Que es TinkerCAD y cómo funciona 

Tinkercad es una herramienta online ofrecida por Autodesk. Se utiliza de forma gratuita y sólo requiere crearse una cuenta de usuario. De entre sus utilidades, probablemente la más conocida es la de diseñar piezas en 3D. Sin embargo, ofrece también una posibilidad realmente interesante y es la de montar, programar y simular circuitos con Arduino.
Para ello, deberemos crearnos una cuenta de usuario y acceder. Seleccionando la opción “Circuits” podremos empezar a crear nuestros circuitos clicando sobre “Create new Circuit”:

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/Manual%20de%20usuario.jpg)

Tinkercad asignará a nuestro nuevo proyecto un nombre por defecto (Tremendous Turing) y ofrece una serie de componentes en la parte derecha de la pantalla.

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/Manual%20de%20usuario%202.jpg)


El cuadro de selección nos ofrece las opciones “Basic” y “All”, según queramos componentes elementales o de uso más común como pulsadores, Leds, resistencias fijas, potenciómetros, baterías, transistores, placas de prototipado etc. u opciones más avanzadas como circuitos integrados, osciloscopios, control remoto o tiras de Leds.

Sea cual sea la opción, clicando sobre el componente y arrastrándolo al área de trabajo podremos ir ensamblando nuestros circuitos. Además, podremos nombrar cada componente y cambiar ciertas características, tales como valores, color etc.


![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/Manual%20de%20usuario%203.jpg)






