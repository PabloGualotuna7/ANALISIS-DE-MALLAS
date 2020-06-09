# ANÁLISIS DE MALLAS


1. PLANTEAMIENTO DEL PROBLEMA 

En el siguiente informe de laboratorio se va a emplear los conocimientos aprendidos en la teoría de la materia de Fundamentos de Circuitos eléctricos en lo que respecta a Análisis de mallas, para lo cuál se debe tener un conocimiento previo de las leyes de Kirchhoff.  


2. OBJETIVOS

* Explicar y demostrar experimentalmente la Ley de Kirchhoff de Voltajes y la Ley de
Kirchhoff de Corrientes.

* Medir las corrientes y los voltajes que circulan por el circuito.

* Identificar en un circuito eléctrico mixto los nodos y mallas.

* Elaborar un circuito mixto en el simulador "tinkercad", recoger datos de voltaje y de corrriente en cada resistencia.

3. MARCO TEÓRICO 

##### Conceptos previos de las leyes de Kirchhoff

Antes de empezar con las leyes de Kirchhoff es necesario conocer conceptos previos para tener un mejor entendimiento.

Elementos activos: Son los elementos de un circuito capaces de suministrar energía al circuito. Las fuentes de tensión son elementos activos.

Elementos pasivos: Son los elementos de un circuito que consumen energía. Son elementos pasivos las resistencias, las inductancias y los condensadores.

Nudo: Punto de un circuito donde concurren más de dos conductores

Rama: Conjunto de todos los elementos comprendido entre dos nodos consecutivos

Malla: Conjunto de ramas que forman un camino cerrado en un circuito, que no puede subdividirse en otros ni pasar dos veces por la misma rama

En el siguiente circuito diferenciaremos:

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/Circuito.jpeg)

Los elementos activos son los generadores: E1 - E2 - E3

Los elementos pasivos son las resistencias: R1 -R2 - R3 - R5 - R6 - R7 

Los nodos del circuito: a - b - c - d

Las ramas: ab, bd,  bc, ad, dc y ac

Las mallas: abda, dbcd y adca

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

4. DIAGRAMAS

Circuito Electrico

![](https://github.com/PabloGualotuna7/ANALISIS_DE_MALLAS/blob/master/img/DIAGRAMA-2.jpg)

Circuito Electrico hecho en Tinkercad

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/Circuito%20acabado.png)

5. LISTAS DE COMPONENTES

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/Tabla%20de%20Componentes.jpg) 

Para la descripción de los equipos empleados véase hojas técnicas.

6. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

* Abrimos el sitio web "tinkercad" y creamos una cuenta.

* Hacemos clic izquierdo en "Circuits" y comenzamos con la practica.

* Seleccionamos una placa de pruebas pequeñas (Protoboard)

* Se seleccicona y se conecta al protoboard un sumistro de energia asignandole un valor de 10 voltios.

* Escogemos cinco resistencias y las conectamos siguiendo el diagrama visto en el archivo de la practica, que en este caso son 5 de valores de 1kOhm.5kOhm, 2.2kOkm (2), 3.9kOkm y 1.8kOhm. 

* Hacinedo clic izquierdo en los agujeros del prtoboard conectamos con cables las resistencias y pasamos corriente a donde haga falta.

* Colocamos un multimetro y realizamos las mediciones de voltaje y de corriente el colo negro es el negativo mientras que el colo rojo es el positivo.

* Cambiamos la configuracion de multimetro en volatje y conectamos en paralelo con las resistencias.

* Ahora dentro del mismo multimetro seleccionamos amperaje y conectamos en serie con las resistencias.

* Anotamos los valores obtenidos en las tablas de la guia de laboratorio.

* Guardamos y salimos.


7. TABLAS DE MEDICIONES Y CÁLCULOS 

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/Resultados.jpg)

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/Resultados2.jpg)

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/Resultados3.jpg)

8. ANÁLISIS DE RESULTADOS

* Según los datos de la Tabla 1, es clara la similitud entre los valores de intensidad de corriente y voltaje experimentales y teóricos. * El error entre ambas cantidades oscila entre el 0% y el 0.5% este último del voltaje de los resistores. Esta congruencia entre los valores medidos y teóricos nos sugiere que las leyes de Kirchhoff, efectivamente, nos permiten determinar la corriente y voltaje de elementos en un circuito eléctrico difícil de reducir. 
* Como se había dicho, la diferencia relativa entre los valores teóricos y experimentales se debe a números de decimales trabajados ya en la teoría usamos un máximo de dos decimales mientras que el simulador se desconoce los decimales trabajado. Aun así, la determinación de la corriente y voltaje de resistores por este medio es una excelente aproximación a los valores reales, por el bajo error que presentan. En cuanto a las mediciones, mucho influye la lectura correcta de las mismas y la imprecisión de los instrumentos empleados para registrarlas.

9. CONCLUSIONES 

* Las leyes de Kirchhoff resultan de vital importancia ya que requerimos el manejo de técnicas que nos permitieron resolver circuitos complejos de manera rápida y efectiva, además, estas leyes nos permitieron analizar dichos problemas por medio de dos técnicas: Mallas y Nodos. Por otra parte, este laboratorio resulto ser de gran provecho, ya que pudimos armar circuitos con más de una resistencia colocándola en serie y paralelo, lo que hace que los laboratorios resulten de mayor interés para ampliar más nuestros conocimientos en el armamento de circuitos en el protoboard.

* Esta práctica de laboratorio, aunque fue hecha de manera virtual, resulto de mucha ayuda ya que ofrece la mayoría de disposiciones a ocupar de manera física, nos sorprendió los valores tan exactos que arrojo aun siendo gratuito además de que pudimos comprobar las leyes de Kirchoff entre otras cosas.

* Los valores de corriente y voltaje determinados por leyes de Kirchhoff son muy aproximados a los valores experimentales, con errores menores al 0.5% en su mayoría.

10. RECOMENDACIONES 

* Se requiere tener bien hecho las conexiones sino los elementos se queman, pero en este caso podemos simular en el laboratorio online DCAC-LAB algo similar a la vida real. En tinkercad se deben realizar los cambios siempre y cuando la simulaciín este detenida.

* Verificar los datos de todos los elementos antes de realizar las medidas para poder cuadrar con los valores calculados en el cuaderno.

* Percartarse al momento de medir ya que el multimetro tiene las magnitudes de voltaje y amperios además tener en cuenta de las escalas que se mide.

* Colocar de manera correcta los elementos en los pines de la protoboard para no interferir en los calculos, diferencias los cables tanto positivo y negativo en color rojo y negro respectivamente.

11. CRONOGRAMA

Actividadades desarrolladas a lo largo de la practica de laboratorio.

![](https://github.com/Edgar1Gallegos/LEYES-DE-KIRCHHOFF/blob/master/img/Cronograma.png)

12. BIBLIOGRAFÍA 

* Matthew N.O.Sadiku, C. K. (2006). Fundamentos de circuitos eléctricos. McGraw-Hill Interamericana.
radio electronica. (s.f.). Recuperado el 01 de Junio de 2020, de http://www.radioelectronica.es/articulos-teoricos/200-las-leyes-de-kirchhoff
* Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega.
* Electrónica completa. (s.f.). Recuperado el 01 de Junio de 2020, de http://electronicacompleta.com/lecciones/leyes-de-kirchhoff/
* Khan Academy. (s.f.). Khan Academy. Recuperado el 01 de Junio de 2020, de https://es.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/ee-kirchhoffs-laws
* Sánchez, A. S. (s.f.). EDUCACIÓN Y TECNOLOGIA. (weebly) Recuperado el 01 de Junio de 2020, de https://www.educoteca.com/tinkercad.html
* wikipedia. (20 de Noviembre de 2018). Wikipedia. (Fundación Wikimedia, Inc) Recuperado el 01 de Junio de 2020, de https://es.wikipedia.org/wiki/Leyes_de_Kirchhoff

