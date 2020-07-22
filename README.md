# Práctica 6
# *TEOREMA DE LA MÁXIMA TRANSFERENCIA DE POTENCIA.*
## *PLANTEAMIENTO DEL PROBLEMA*

## *OBJETIVOS:*
# Objetivo general
- Diseñar un circuito electrico mediante la simulación en laboratorios virtuales para comprobar la validez del teorema de la máxima transferencia de potencia.

# Objetivos específico
- Comprender la metodología del teorema de la máxima transferencia de potencia para reafirmar los conocimientos previamente adquiridos.
- Analizar los resultados teóricos con los prácticos mediante la comparación de los mismos para la obtención de porcentajes de error respectivos.


## *LISTA DE MATERIALES:*


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
 
 Fig 5.   Circuito para simular

2.- Mida el voltaje y la corriente para cada valor de RL que se indica en la fig 5, anote los resultados medidos.

3.- Calcule las potencia consumida por RL, para cada valor dado y anote los resultados en la tabla 2.


## *TABULACIÓN DE DATOS*


|  RL(Ω)   |  Corriente medida (mA) | Voltaje medido (V)   | Potencia calculada Experimentalmente (W)|Potencia calculada teoricamente (W)  |
|:--------:|:---------:|:--------:|:---------:|:--------:|
|  220      | 10,6 |  2,32  | 0,02459  |  0,02455   |
|  470      | 8,98  |  4,22    |  0,03789    |   0,03792    |
|  680      |  7,98  |  5,43    |  0,04333   |   0,04328    |
|  820      | 7,42 | 6,09  | 0,04524 |  0,04521 |
|  1000      |   6,82  |  6,82   |   0,04651    |  0,04648    |
|  1500      |   5,56  | 8,33  |  0,04631   |   0,04629    |
|  1800      | 5 |  9 | 0,045|  0,045 |
|  2200      |   4,1  |   9,71  |   0,03981 |   0,04282    |
|  3900      |   2,94  |  11,5   |  0,03381 |   0,03373    |
|  4700      | 2,54 |  11,9   | 0,03022  |  0,03037   |

TABLA II. Comprobación de la máxima transferencia de potencia.

## *PREGUNTAS*

1.- ¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente su respuesta

El teorema de la máxima transferencia de potencia  estuvo a poco de cumplirse ya que hay dos resistencias muy cercanas a la resistencia de thevenin , pero no iguales por lo que en esta práctica no se pudo comprobar el teorema de la máxima transferencia de potencia. 

2.- ¿Cuál fue la potencia máxima en RL?

La máxima potencia obtenida en RL  fue de 0,04651 (W) correspondiente a una resistencia de 1000(Ω) que es la más cercana a la resistencia de thevenin de 1200.

3.- ¿Para qué valor de RL se obtiene la MTP?

Para obtener la máxima transferencia de potencia , las resistencias Rth y Rl correspondientes deben tener el mismo valor , por lo que esta para ser igual debe tener el valor de 1200.

## *DIAGRAMA*

![alt text]()

Figura 3. Circuito propuesto simulado en TinkerCAD.

## *Ecuaciones*

Las ecuaciones que vamos a utilizar para este tema, prácticamente son las mismas de temas anteriores.Lo único que cambia es la metodología al momento de resolver, como los pasos a seguir que tenemos en el marco teórico pero tomando en cuenta lo siguiente:

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


## *EXPLICACIÓN DEL CIRCUITO*



## *ANÁLISIS DE RESULTADOS*
En general los resultados de las mediciones nunca serán exactas, a pesar del máximo cuidado que se tenga en el momento de realizar cada una de ellas, no es posible expresar el reultado como exacto, es por esto que a continuación se ralizará una tabla donde se muestre  el error relativo de cada valor obtenido:

Resistencia(Ω)|Potencia (W)| Resultados Analíticos |Resultados Experimentales|%Error|
|-------------| ------------- | ------------- | ------------- | ------------- |
| 220      |  xxx  | xxxx | xxxx | 0,067%|
| 470      | xxx | xxxx| xxxx | 0,0001% |
| 680     | xxx | xxxx| xxxx | 0,0001% |
| 820      | xxx | xxxx| xxxx | 0,0001% |
| 1000      | xxx | xxxx| xxxx | 0,0001% |
| 1500     | xxx | xxxx| xxxx | 0,0001% |
| 1800     | xxx | xxxx| xxxx | 0,0001% |
| 2200      | xxx | xxxx| xxxx | 0,0001% |
| 3900      | xxx | xxxx| xxxx | 0,0001% |
| 4700     | xxx | xxxx| xxxx | 0,0001% |

TABLA III. Cálculo de errores en la potencia


## *CONCLUSIONES*



## *RECOMENDACIONES*
1.- Para realizar una practica exitosa se debe tener conocimiento previo adquirido, para poder relacionar la teoría aprendida con la simulación.

2.- Tener cuidado al momento de aproximar mal los valores que calculamos teóricamente ya que si lo hacemos mal , nos dará un porcentaje de error mas alto de lo esperado.

3.- Realizar paso a paso la practica, siguiendo en orden el prodecimiento ya establecido en las guías de laboratorio, para así no cometer errores. 


## *CRONOGRAMA*


## *BIBLIOGRAFÍA*

Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.

## *ANEXOS*

![alt text]()

Figura 5. Medición de voltaje y corriente en el circuito original.


