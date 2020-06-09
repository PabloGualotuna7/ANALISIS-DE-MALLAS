# ANÁLISIS DE MALLAS


1. PLANTEAMIENTO DEL PROBLEMA 

En el siguiente informe de laboratorio se va a emplear los conocimientos aprendidos en la teoría de la materia de Fundamentos de Circuitos eléctricos, estudiaremos el análisis de las mallas en los circuitos eléctricos para tener una facilidad en la aplicación y resolución de ejercicios. Así como también podemos comparar los resultados tantos calculados y medidos con el programa (TINKERCAD, PROTEUS, ETC.)

2. OBJETIVOS

* Medir circuitos de c.d. de varias mallas con múltiples fuentes de voltajes y múltiples resistores.

* Determinar la tensión o la corriente de cualquier elemento de un circuito plano.

* Resolver un circuito eléctrico generando un sistema de ecuaciones simultáneas que se obtienen aplicando las leyes de Kirchhoff y las relaciones i-v (corriente-voltaje) de los elementos del circuito en la o las mallas del circuito.

* Analizar los pasos que se debe seguir para poder resolver mediante el análisis de mallas.

3. MARCO TEÓRICO 

Un circuito de varias mallas es el que tiene dos o mas mallas, esto significa que tiene diferentes trayectorias cerradas de elementos. Los elementos de las mallas están en serie o paralelo y éstos conducen la misma corriente. Para resolver estos circuitos se determina de forma facil haciendo uso de las Leyes de Kirchoff mas especificamnete la Ley de Voltajes, se calcula la corriente total de la malla y ya con este dato se determinan los voltajes y las potencias de cada resistor. El voltaje de la fuente equivalente se calcula usando la ley de voltaje de Kirchhoff siguiendo la dirección de las manecillas del reloj usando el flujo de corriente convencional.

¿Qué es una malla?

![](https://github.com/PabloGualotuna7/ANALISIS_DE_MALLAS/blob/master/img/1.jpg)

En un circuito eléctrico, una malla es un camino cerrado formado por elementos de circuitos. En este caso hay 4 mallas, formadas por 4 caminos cerrados. Si no hay una fuente de voltaje o de corriente en una malla entonces asumimos que la corriente fluye en un sentido horario. Se podría asumir en el sentido anti horario, lo cual no interesa mucho ya que si se escoge un sentido incorrecto la corriente que nos resultará al hacer nuestros cálculos tendrá signo negativo. Esto lo podremos apreciar al final cuando obtengamos nuestra respuesta.

Las corrientes las debemos representar en nuestro diagrama se la siguiente manera:

![](https://github.com/PabloGualotuna7/ANALISIS_DE_MALLAS/blob/master/img/2.jpg)

Vemos que en la malla 1 se asume que la corriente va en sentido horario ya que sale del positivo de la fuente. En las mallas 2 y 3 no hay fuente, así que se asume libremente (preferiblemente en sentido horario). En la malla 4 la corriente va en sentido anti horario por salir del positivo de la fuente de voltaje.

* Ley de Ohm: sean V el voltaje, R la resistencia e I la corriente del elemento resistivo óhmico, en el cual el voltaje y la corriente son directamente proporcionales, siendo la resistencia la constante de proporcionalidad: V = I.R

* Ley de Kirchhoff del voltaje (LKV): en cualquier trayectoria cerrada recorrida en una sola dirección, la suma algebraica de los voltajes es cero. Esto incluye los voltajes debidos a fuentes, resistores, inductores o capacitores: ∑ E = ∑ Ri. I

* Ley de Kirchhoff de la corriente (LKC): en cualquier nodo, la suma algebraica de las corrientes es cero, teniendo en cuenta que a las corrientes que entran se les asigna un signo y a las que salen otro. De esta forma: ∑ I = 0.

El análisis de mallas es una técnica empleada para resolver circuitos eléctricos planos. Este procedimiento también puede aparecer en la literatura con el nombre de método de las corrientes de malla (o lazo). Además, es un método general que sirve para resolver circuitos cuyos elementos están conectados en serie, en paralelo o de forma mixta, es decir, cuando no se distingue claramente el tipo de conexión. El circuito debe ser plano, o al menos debe ser posible re-dibujarlo como tal.

Pasos a seguir en un análisis por mallas:

* Paso 1. Asignar una corriente de malla a cada malla (sentido cualquiera) y asignar una polarización a cada elemento del circuito.
* Paso 2. Establecemos un sentido de circulación siguiendo el cual aplicamos KVL a cada malla. Tendremos tantas ecuaciones como mallas.
* Paso 3. Usamos las relaciones V/I (Ley de Ohm) para expresar las tensiones en función de las corrientes en las ecuaciones de 2.
* Paso 4. Sustituimos las ecuaciones del paso 3 en 2.
* Paso 5. Obtenemos las corrientes de malla.

4. DIAGRAMAS

Circuito Electrico

![](https://github.com/PabloGualotuna7/ANALISIS_DE_MALLAS/blob/master/img/DIAGRAMA-2.jpg)

Circuito Electrico hecho en Tinkercad

![](https://github.com/PabloGualotuna7/ANALISIS_DE_MALLAS/blob/master/img/Circuito_Armado.png)

Circuito Elecrtico con mediciones hecho en Proteus 

![](https://github.com/PabloGualotuna7/ANALISIS_DE_MALLAS/blob/master/img/Circuito_Proteus.png)

5. LISTAS DE COMPONENTES

Para la descripción de los equipos empleados véase hojas técnicas.

6. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

* Abrimos el sitio web "tinkercad" y creamos una cuenta.

* Hacemos clic izquierdo en "Circuits" y comenzamos con la practica.

* Seleccionamos una placa de pruebas pequeñas (Protoboard).

* Se seleccicona y se conecta al protoboard los sumistros de energia asignandole el valor de 5 y 18 V.

* Escogemos cinco resistencias y las conectamos siguiendo el diagrama visto en el archivo de la practica, que en este caso son 5 de valores de 820 Ohm, 1.2k Ohm, 390 Ohm, 1K Ohm y 2.2k Ohm. 

* Hacinedo clic izquierdo en los pines del protoboard conectamos con cables las resistencias y pasamos corriente a donde haga falta.

* Colocamos un multimetro y realizamos las mediciones de voltaje y de corriente el color negro es el negativo mientras que el colo rojo es el positivo.

* Cambiamos la configuracion de multimetro en voltaje y conectamos en paralelo con las resistencias.

* Ahora dentro del mismo multimetro seleccionamos amperaje y conectamos en serie con las resistencias.

* Anotamos los valores obtenidos en las tablas de la guia de laboratorio.

* Guardamos y salimos.

7. TABLAS DE MEDICIONES Y CÁLCULOS 

8. ANÁLISIS DE RESULTADOS

9. CONCLUSIONES 

10. RECOMENDACIONES 

11. CRONOGRAMA

Actividadades desarrolladas a lo largo de la practica de laboratorio.

![](https://github.com/PabloGualotuna7/ANALISIS_DE_MALLAS/blob/master/img/Cronograma.png)

12. BIBLIOGRAFÍA 

2015 Educatina LLC. (2015). educatina. Recuperado el 11 de Diciembre de 2015, de http://www.educatina.com/buscar?q=circuitos+el%C3%A9ctricos+

Alexander, C. 2006. Fundamentos de Circuitos Eléctricos. 3ra. Edición. Mc Graw Hill.

Boylestad, R. 2011. Introducción al Análisis de Circuitos.2da. Edición. Pearson.

Matthew N.O.Sadiku, C. K. (2006). Fundamentos de circuitos eléctricos. McGraw-Hill Interamericana. radio electronica. (s.f.). Recuperado el 01 de Junio de 2020, de http://www.radioelectronica.es/articulos-teoricos/200-las-leyes-de-kirchhoff

Dorf, R., & Svoboda, J. (2011). Circuitos eléctricos. México: Alfaomega.
