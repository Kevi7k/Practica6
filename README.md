# Práctica 6
# *TEOREMA DE THÉVENIN*
## *PLANTEAMIENTO DEL PROBLEMA*

## *OBJETIVOS:*
# Objetivo general
- Diseñar un circuito electrico mediante la simulación en laboratorios virtuales para comprobar la validez del teorema de Thévenin

# Objetivos específico
- Comprender la metodología del teorema de Thévenin para reafirmar los conocimientos previamente adquiridos.
- Analizar los resultados teóricos con los prácticos mediante la comparación de los mismos para la obtención de porcentajes de error respectivos.


## *LISTA DE MATERIALES:*


| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 2  | Fuente de voltaje de C.D. |
| 2  | Multímetros digitales |
|  1 | Resistor de 560  |
|  1 | Resistor de 4.7k  |
|  1 | Resistor de 330  |
|  1 | Resistor de 100 |
|  1 | Resistor de 1k  |
|  1 | Potenciómetro de precisión de 1k|
|  1 | Protoboard      |

## *MARCO TEÓRICO*


## *PROCEDIMIENTO*


## *TABULACIÓN DE DATOS*

|Tipo de dato |VTH (V) |RTH (Ω)| 
| ------------- | ------------- | ------------- | 
| Calculado     | 5.056     |  298.8558    | 
| Medido     | 5.06         |      299    |    


TABLA I. Valores del Circuito Equivalente de Thévenin

|                      |  Circuito | Original |  Circuito | Thévenin |
|:--------------------:|:---------:|:--------:|:---------:|:--------:|
| Parámetro  eléctrico | Calculado |  Medido  | Calculado |  Medido  |
|      Voltaje (V)     |   3.8926  |   3.89   |   5.056   |   5.06   |
|    Corriente (mA)    |   3.8926  |   3.89   |  15.3212  |   15.3   |

TABLA II. Comprobación del Teorema de Thévenin

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

|Voltaje (VTh)| Resultados Analíticos |Resultados Experimentales|%Error|
| ------------- | ------------- | ------------- | ------------- |
| Circuito Original | 3.8926 [V] | 3.89 [V] | 0,067%|
| Circuito equivalente de Thévenin | 5.056 [V] | 5.06 [V] | 0,0001% |

TABLA III. Cálculo de errores en mediciones de voltaje


## *CONCLUSIONES*



## *RECOMENDACIONES*



## *CRONOGRAMA*


## *BIBLIOGRAFÍA*

Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.

## *ANEXOS*

![alt text]()

Figura 5. Medición de voltaje y corriente en el circuito original.


