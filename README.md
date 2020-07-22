# Práctica 6
# *TEOREMA DE LA MÁXIMA TRANSFERENCIA DE POTENCIA.*
## *PLANTEAMIENTO DEL PROBLEMA*

Como ya lo sabemos cómo estudio previo a la realización de nuestra práctica, la potencia suministrada en un elemento de nuestro circuito, es la energía eléctrica transferida o absorbida en un momento determinado. Para lo cual nosotros nos preguntaremos, como calcular y como medir dicha energía eléctrica. Nuestra respuesta a dicha pregunta la tendremos en este informe. 

Como respuesta, tenemos primero planteado nuestro teorema de máxima transferencia de potencia, el cual nos ayudara a calcular los valores que ya lo hemos establecido. Luego por medio de nuestra medición de los valores necesarios para la aplicación de nuestra formula de potencia máxima, o en su mejor caso, utilizando un vatímetro el cual nos permita calcular la potencia en nuestra resistencia. Y al final, nosotros tendremos que realizar nuestros cálculos teóricos, comparándolos y revisando si estamos realizando de manera correcta nuestro procedimiento.


## *OBJETIVOS*
# Objetivo general
- Diseñar un circuito eléctrico mediante la simulación en laboratorios virtuales para comprobar la validez del teorema de la máxima transferencia de potencia.

# Objetivos específico
- Comprender la metodología del teorema de la máxima transferencia de potencia para reafirmar los conocimientos previamente adquiridos.
- Encontrar la resistencia aproximada en la cual se obtiene la mayor transferencia de potencia.
- Analizar los resultados teóricos con los prácticos mediante la comparación de los mismos para la obtención de porcentajes de error respectivos.


## *LISTA DE MATERIALES*


| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 1  | Fuente de voltaje de C.D. |
| 1  | Multímetro digital |
|  1 | Resistor de 220  |
|  1 | Resistor de 470 |
|  1 | Resistor de 680  |
|  1 | Resistor de 820 |
|  1 | Resistor de 1k  |
|  1 | Resistor  de 1.5k    |
|  1 | Resistor  de 1.8k      |
|   1 | Resistor  de 2.2k     |
|  1  | Resistor  de  3.9k    |
|  1  | Resistor  de  4.7k   |
|  1  | Protoboar      |

Tabla 1. Materiales
## *MARCO TEÓRICO*

Para poder lograr transferir la máxima potencia a una carga  en un circuito este consiste en hacer que dicha carga absorba al máximo a la fuente de energía del circuito, es decir que consuma lo que mas pueda de potencia que es generada por la fuente. Como se sabe, un circuito, respecto a dos puntos (a,b) este se puede reducir mediente el teorema de thevenin ya antes visto, como ya sabemos este es reducido a una fuente (Vth) en serie con una resistencia (Rth), para poder determinar de como se obtiene la máxima transferencia de potencia dirigida hacia una carga, lo que debemos de hacer es reducir la red que existe a los terminales de dicha carga mediante el teorema ya mencionado, valga la redundancia , de modo que el circuito al final se reduce solamente en una malla entonces ahí encontramos la potencia transferida.

![alt text](https://github.com/Kevi7k/Practica6/blob/master/Imagenes/Diagrama%201.jpg)

Fig 1. Circuito simplificado

Donde para poder encontrarla, debemos seguir los siguientes pasos:

1. Encuentra la resistencia interna, RI. Esta es la resistencia que se encuentra al mirar hacia atrás en los dos terminales de carga de la fuente. sin carga conectada. Como hemos demostrado en el Teorema de Thevenin y Teorema de norton En los capítulos, el método más sencillo es reemplazar las fuentes de voltaje por cortocircuitos y las fuentes de corriente por circuitos abiertos, luego encontrar la resistencia total entre los dos terminales de carga.

2. Encuentre la tensión de circuito abierto (Vth) o la corriente de cortocircuito (In) de la fuente entre los dos terminales de carga, sin carga conectada.

Aplicando Teorema de thevenin 

![alt text](https://github.com/Kevi7k/Practica6/blob/master/Imagenes/diagrama%202.png)

Fig 2.  Teorema de thevenin 

 o aplicando Teorema de Norton

![alt text](https://github.com/Kevi7k/Practica6/blob/master/Imagenes/diagrama%203.png)

Fig 3.  Teorema de Norton 

Una vez que hemos encontrado RI, Sabemos la resistencia óptima a la carga (Rth = RL). Finalmente, se puede encontrar la potencia máxima con el siguiente modelo matemático.

![alt text](https://github.com/Kevi7k/Practica6/blob/master/Imagenes/Formula.png)

Fig 4.  Formula de la potencia máxima.




## *PROCEDIMIENTO*

1.-Arme el circuito que se muestra en la figura.
 
 ![alt text](https://github.com/Kevi7k/Practica6/blob/master/Imagenes/diagrama%204.png)
 
 Fig 5.   Circuito a ser simulado.

2.- Mida el voltaje y la corriente para cada valor de RL que se indica en la fig 5, anote los resultados medidos.

3.- Calcule las potencia consumida por RL, para cada valor dado y anote los resultados en la tabla 2.


## *TABULACIÓN DE DATOS*


|  RL(Ω)   |  Corriente medida (mA) | Voltaje medido (V)   | Potencia calculada Experimentalmente (W)|Potencia calculada teoricamente (W)  |
|:--------:|:---------:|:--------:|:---------:|:--------:|
|  220      | 10,6 |  2,32  | 0,02459  |  0,02455   |
|  470      | 8,98  |  4,22    |  0,0379    |   0,03792    |
|  680      |  7,98  |  5,43    |  0,04331   |   0,04328    |
|  820      | 7,43 | 6,09  | 0,04524 |  0,04521 |
|  1000      |   6,82  |  6,82   |   0,04651    |  0,04648    |
|  1500      |   5,56  | 8,33  |  0,04631   |   0,04629    |
|  1800      | 5 |  9 | 0,045|  0,045 |
|  2200      |   4,1  |   9,71  |   0,04282 |   0,04282    |
|  3900      |   2,94  |  11,5   |  0,03381 |   0,03374    |
|  4700      | 2,54 |  11,9   | 0,03023  |  0,03038  |

TABLA II. Comprobación de la máxima transferencia de potencia.


## *Ecuaciones*

Las ecuaciones que vamos a utilizar para este tema, prácticamente son las mismas de temas anteriores.

Lo que hay que tomar en cuenta que para comprobar este teorema o realizar ejercicios de este mismo, lo que debemos saber son , las metodologías del teorema de thevenin y el de Norton , por lo que de ahi, las ecuaciones que estariamos utilizando, practicamente serían las mismas pero añadiendole estas formulas que son las de la potencia o potencia máxima.


![alt text](https://github.com/Kevi7k/Practica6/blob/master/Imagenes/Formula.png)

Fig 7.  Formula de la potencia máxima.

La resistencia de Thévenin es la resultante de todas las resistencia en el circuito pero apagado las fuentes y se denomina como (Rth)

El voltaje de Thévenin esta denominado con (Vth):

Vth=In.Rth

Donde In vendría ser la intensidad de donde quitamos la resistencia , cumpliendose Ley de Ohm y las unidades son las mismas.

Intensidad=Amperio (A)

Voltaje=Voltio (V)

Resistencia= Ohmio (omega)

Para encontrar las corrientes necesarias para el calculo de voltajes, tanto en el circuito original como en el circuito de Thévenin será necesario hacer uso de las leyes de Kirchoff. De manera que:

V1+V2+V3+V4+...Vn=0

Esta ecuación se cumple siempre y cuando sea de solamente una malla, es decir la sumatoria de voltajes dentro de una malla es igual a cero, afirmando esto, se cumple otra ley que nos habla sobres las corrientes. Es muy útil si para el cálculo realizaramos un análisis nodal

I(salida)=I(entrada)

## *PREGUNTAS*

1.- ¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente su respuesta

El teorema de la máxima transferencia de potencia  estuvo a poco de cumplirse ya que hay dos resistencias muy cercanas a la resistencia de thevenin , pero no iguales por lo que en esta práctica no se pudo comprobar el teorema de la máxima transferencia de potencia. 

2.- ¿Cuál fue la potencia máxima en RL?

La máxima potencia obtenida en RL  fue de 0,04651 (W) correspondiente a una resistencia de 1000(Ω) que es la más cercana a la resistencia de thevenin de 1200.

3.- ¿Para qué valor de RL se obtiene la MTP?

Para obtener la máxima transferencia de potencia , las resistencias Rth y Rl correspondientes deben tener el mismo valor , por lo que esta para ser igual debe tener el valor de 1200.


## *DIAGRAMA*

![alt text](https://github.com/Kevi7k/Practica6/blob/master/Imagenes/Circuito%20implementado.png)

Figura 6. Circuito propuesto simulado en TinkerCAD junto a sus componentes de medición.

## *EXPLICACIÓN DEL CIRCUITO*

Como podemos evidenciar, tenemos un circuito el cual simula un circuito resuelto sacando una fuente de voltaje thevenin y una resistencia thevenin, esto para poder aplicar nuestra formula de máxima potencia, que está en función de nuestra fuente de voltaje thevenin, nuestra resistencia thevenin y nuestra resistencia en la cual vamos a sacar la potencia.


Tenemos nuestra fuente de voltaje de 15 volteos, y nuestra primera resistencia de 1200 ohmios. Nuestra tercera resistencia variara de acuerdo a los datos de la resistencia que queramos calcular. Nuestros valores para nuestra segunda resistencia tendremos: 220, 470, 680, 820, 1000, 1500, 1800, 2200, 3900 y 4700 ohmios. Dichas resistencias como ya lo mencionamos las añadiremos una por una, para obtener nuestra potencia en dicha resistencia. Como ya lo estudiamos en nuestra teoría, dicha potencia calculada o medida, con la ayuda de un vatímetro, estará dada en Watts.


## *ANÁLISIS DE RESULTADOS*
En general los resultados de las mediciones nunca serán exactas, a pesar del máximo cuidado que se tenga en el momento de realizar cada una de ellas, no es posible expresar el reultado como exacto, es por esto que a continuación se ralizará una tabla donde se muestre  el error relativo de cada valor obtenido:

Resistencia(Ω)|Potencia (W) con resultados Analíticos | Potencia (W) con resultados Experimentales|%Error|
|---------------- | ------------- | ------------- |-----------|
| 220      |  0,02455 | 0,02459 | 0,02%|
| 470      | 0,03792| 0,03789 | 0,05% |
| 680     | 0,04328| 0,04331 | 0,06% |
| 820      | 0,04521| 0,04525 | 0,06% |
| 1000      | 0,04648| 0,04651 | 0,06% |
| 1500     | 0,04629| 0,04631 | 0,04% |
| 1800     | 0,045| 0,045 | 0.00% |
| 2200      | 0,04282| 0,04282 | 0,00% |
| 3900      | 0,03374| 0,03381 | 0,21% |
| 4700     | 0,03038| 0,03023 | 0,49% |

TABLA III. Cálculo de errores en la potencia


## *CONCLUSIONES*

- Al realizar los cálculos correspondientes de potencia en forma experimental y analítica se ha determinado la máxima transferencia de potencia se obtiene en un rango donde la resitencia de carga llega a tener un valor desde 1000Ω hasta 1500Ω.

- Luego de observar el rango donde se obtiiene la mayor potencia, se puede afirmar que el teorema de máxima transferencia de potencia es válido, ya que teóricamente se obtiene la máxima transferencia de potencia cuando la resistencia de carga tiene el mismo valor que la resistencia de Thévenin y en nuestro caso el rango se aproxima a la resistenica de 1200Ω.

- Durante la práctica se han obtenido errores, debido a la variación de datos, tanto experimentales como teóricos. Como sabemos las potencias obtenidas son medidas indirectas y esta es la razón por la cual no se puede llegar al valor exacto.

- Los errores obtenidos no superan el 1%, lo que nos garantiza la efectividad de la práctica y la precisión con la cual se realizó el cálculo de cada dato. Para nuestro estudio estos errores se los puede pasar por alto ya que no se ve afectado el comportamiento de parámetros eléctricos dentro del circuito.

## *RECOMENDACIONES*
1.- Para realizar una práctica exitosa se debe tener conocimiento previo adquirido, principalmente el teorema de Thévenin, para poder relacionar la teoría aprendida con la simulación.

2.- Tener en cuenta que en esta práctica el dato teórico con el que comparamos nuestros resultados es calculado a partir de otras mediciones, a menos que se utilice un simulador de laboratorio que pueda medir potencia.

3.- Tener cuidado al momento de aproximar los valores que calculamos teóricamente ya que si lo hacemos mal , nos dará un porcentaje de error más alto de lo esperado.

4.- Realizar paso a paso la práctica, siguiendo en orden el prodecimiento ya establecido en las guías de laboratorio, para así no cometer errores. 


## *CRONOGRAMA*

![alt text](https://github.com/Kevi7k/Practica6/blob/master/Cronograma/Cronograma1.jpg)

## *BIBLIOGRAFÍA*

Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.

## *ANEXOS*

![alt text](https://github.com/Kevi7k/Practica6/blob/master/Imagenes/mediciones1.jpg)
![alt text](https://github.com/Kevi7k/Practica6/blob/master/Imagenes/mediciones2.jpg)

Figura 5. Medición de voltaje y corriente en la resistencia de carga del circuito.


![alt text](https://github.com/Kevi7k/Practica6/blob/master/Imagenes/calculos.jpg)

Figura 5. Cálculos experimentales, teóricos y error porcentual.
