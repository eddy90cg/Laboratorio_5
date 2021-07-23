# TEOREMA DE THEVENIN

#### INTEGRANTES: EDISON CADENA - STEVEN FLORES - WILLIAM MOSQUERA

# 1.	OBJETIVOS

OBJETIVO GENERAL:

* Demostrar experimentalmente el teorema de Thevenin  para resolver un circuito.

OBJETIVOS ESPECÍFICOS: 

* Aplicar la teoria de Thevenin  para conseguir un circuito mas sencillo de resolver.

* Comparar los calculos con los resultados practicos y determinar  cual es el error entre los datos ontenidos en la practica y los valores calculados


# 2.	MARCO TEÓRICO

# TEOREMA DE THEVENIN

* Resumen: 

El teorema de Thevenin establece que un circuito lineal de dos terminales puede sustituirse por un circuito equivalente
Es decir, el teorema de Thevenin proporciona una técnica para sustituir la parte fija por un circuito equivalente sencillo.

* Introducción:

Si el circuito original posee muchas resistencias, y se desea calcular intensidad, tensión o potencia de alguna de estas, o que se ubique entre los puntos A y B de un circuito grande, se puede simplificar el proceso a través del teorema de Thevenin. Se establece que es posible construir un circuito equivalente más pequeño, comprendido por una resistencia y una fuente de tensión dispuestos en serie. Los valores asignados a cada uno de estos se conoce como resistencia de Thevenin y tensión de Thevenin, que serán equivalentes al valor de la resistencia entre A y B, conocida como resistencia de carga.

![Circuito-de-Thevenin](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Circuito%20de%20Thevenin%20-%20Ejemplo.png)

* Mentefacto:

--------------------------------
---------------------------------
------------------------------------
---------------------------------
![]( )

# 3. EXPLICACIÓN DEL PROCEDIMIENTO

Para poder aplicar este teorema: 

Es necesario tener conocimiento varios métodos estudiados previamente como lo son: resolución de circuitos por medio de mallas y nodos, superposición, resistencia equivalente, divisor de corriente devisor de voltaje, conexiones en serie paralelo, etc.

* Cuando se construye un circuito equivalente de Thevenin, es posible realizar cálculos más sencillos y en menos tiempo que al trabajar con el circuito completo original. Para lograr aplicar el teorema correctamente, se deben realizar estos pasos:

* Al eliminar las fuentes de alimentación del circuito original, será posible encontrar la resistencia de Thevenin. Luego se deberá calcular el valor de la resistencia total que existe entre los punto A y B donde se encuentre conectada la resistencia de carga.

* Para el caso de hallar la tensión de Thevenin, se elimina la resistencia de carga, y se calcula el voltaje de los puntos de conexión abiertos donde esta se encontraba.

* Construye el circuito equivalente utilizando la tensión de Thevenin y la resistencia de Thevenin en serie. 

* Conecta la resistencia de carga entre los puntos de conexión abiertos de este circuito.

* Utilizando las reglas de circuitos en serie, se analiza la tensión y corriente de la resistencia de carga.

* Equipos y Materiales necesarios: 

| **Cantidad** | **Elemento** |
| :---: | :---: |
| 2 | Fuente de Voltaje de C.D.  |
| 2 | Multímetros Digitales |
| 1 | Resistor de <img src="https://latex.codecogs.com/svg.latex?560\Omega" title="560\Omega" /> |
| 1 | Resistor de <img src="https://latex.codecogs.com/svg.latex?4.7k\Omega" title="4.7k\Omega" /> |
| 1 | Resistor de <img src="https://latex.codecogs.com/svg.latex?330\Omega" title="330\Omega" /> |
| 1 | Resistor de <img src="https://latex.codecogs.com/svg.latex?100\Omega" title="100\Omega" /> |
| 1 | Resistor de <img src="https://latex.codecogs.com/svg.latex?1k\Omega" title="1k\Omega" /> |
| 1 | Potenciómetro de precisión de <img src="https://latex.codecogs.com/svg.latex?1k\Omega" title="1k\Omega" /> |
| 1 | Protoboard |

* Figura, Circuito Teórico para comprobar el Teorema de Thévenin:

![](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Circuito%20Esquemático.jpeg)

* Circuito Experimental Armado

![](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Circuito%20Experimental%20Armado.jpeg)

* Circuito Experimental con mediciones de Voltaje y Corriente

![](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Circuito%20Armado%20-%20Medición%20de%20V%20e%20I.jpeg)

* Circuito sin R5 y con medición de voltaje

![](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Circuito%20sin%20R5%20-%20V.jpeg)

* Circuito sin R5, sin efecto de las fuentes de voltaje y con medición de la resistencia equivalente

![](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Circuito%20sin%20R5%20-%20Req.jpeg)

* Circuito equivalente de Thévenin con R5 y con mediciones de Corriente y Voltaje

![](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Circuito%20de%20Thévenin%20-%20Medición%20de%20V%20e%20I.jpeg)

# 4. RESPUESTA A INTERROGANTES Y CÁLCULO DEL ERROR

Tabla de Registro de datos tomados para el Circuito Equivalente de Thévenin :

| <img src="https://latex.codecogs.com/svg.latex?V_{TH}" title="V_{TH}" /> | <img src="https://latex.codecogs.com/svg.latex?(V)" title="(V)" /> | <img src="https://latex.codecogs.com/svg.latex?R_{TH}" title="R_{TH}" /> | <img src="https://latex.codecogs.com/svg.latex?(\Omega)" title="(\Omega)" /> |
| :---: | :---: | :---: | :---: |
| **Calculado** | 5.049 | **Calculado** | 298.86 |
| **Medido** | 5.06 | **Medido** | 299 |

Porcentaje de Error Obtenido

|      | <img src="https://latex.codecogs.com/svg.latex?V_{TH}" title="V_{TH}" /> | <img src="https://latex.codecogs.com/svg.latex?R_{TH}" title="R_{TH}" /> |
| :---: | :---: | :---: |
| **Error** | <img src="https://latex.codecogs.com/svg.latex?-0.21%" title="-0.21%" /> | <img src="https://latex.codecogs.com/svg.latex?-0.04%" title="-0.04%" /> |      

Tabla de Registro de datos tomados para la Comprobación del Teorema de Thévenin  :

| **Parámetro Eléctrico** | **Circuito Original** || **Circuito Equivalente de Thévenin**||
| :---: | :---: | :---: | :---: | :---: |
|| **Calculado** | **Medido** | **Calculado** | **Medido** |
| **Voltaje (V)** | 3.89 | 3.89 | 3.89 | 3.90 |
| **Corriente (mA)** | 3.89 | 3.89 | 3.89 | 3.90 |

Porcentaje de Error Obtenido para el **Circuito Original**

| **Circuito Original** | **Error** |
| :--: | :---: |
| **Voltaje (V)** | <img src="https://latex.codecogs.com/svg.latex?0%" title="0%" /> |
| **Corriente (mA)** | <img src="https://latex.codecogs.com/svg.latex?0%" title="0%" /> |

Porcentaje de Error Obtenido para el **Circuito Equivalente de Thévenin**

| **Circuito Original** | **Error** |
| :--: | :---: |
| **Voltaje (V)** | <img src="https://latex.codecogs.com/svg.latex?-0.26%" title="-0.26%" /> |
| **Corriente (mA)** | <img src="https://latex.codecogs.com/svg.latex?-0.26%" title="-0.26%" /> |


![WhatsApp Image 2021-03-23 at 2 49 25 PM](https://user-images.githubusercontent.com/76057459/112209045-099e2f00-8be7-11eb-87d1-d4586bf28c03.jpeg)

Para poder encontrar los valores y comprobar el Teorema de Thévenin se realizaron los siguientes cálculos:

![img046](https://user-images.githubusercontent.com/76057459/112208608-8bda2380-8be6-11eb-9d4b-45e1bb7425d6.jpg)

![WhatsApp Image 2021-03-23 at 2 35 16 PM](https://user-images.githubusercontent.com/76057459/112208663-998fa900-8be6-11eb-8812-8d9294e1f445.jpeg)

![WhatsApp Image 2021-03-23 at 2 38 44 PM](https://user-images.githubusercontent.com/76057459/112208668-9b596c80-8be6-11eb-94b7-071afdcddb67.jpeg)

![WhatsApp Image 2021-03-23 at 2 44 26 PM](https://user-images.githubusercontent.com/76057459/112208675-9d233000-8be6-11eb-936e-ff508412de2e.jpeg)

 ![img046](https://user-images.githubusercontent.com/76057459/112203594-b75a0f80-8be0-11eb-9b94-666fb5353f63.jpg)


* Formula a aplicar para el calculo del ERROR: 

<img src="https://latex.codecogs.com/gif.latex?\mathrm{Porcentaje\&space;de\&space;Error\&space;en\&space;el\&space;Voltaje:}&space;\\&space;\\&space;%\&space;Error&space;=&space;\frac{V_T(Teorico)-V_T(Practico)}{V_T(Teorico)}\times&space;100" title="\mathrm{Porcentaje\ de\ Error\ en\ el\ Voltaje:} \\ \\ %\ Error = \frac{V_T(Teorico)-V_T(Practico)}{V_T(Teorico)}\times 100" />

<img src="https://latex.codecogs.com/gif.latex?\mathrm{Porcentaje\&space;de\&space;Error\&space;en\&space;la\&space;Corriente:}&space;\\&space;\\&space;%\&space;Error&space;=&space;\frac{I_T(Teorico)-I_T(Practico)}{I_T(Teorico)}\times&space;100" title="\mathrm{Porcentaje\ de\ Error\ en\ la\ Corriente:} \\ \\ %\ Error = \frac{I_T(Teorico)-I_T(Practico)}{I_T(Teorico)}\times 100" />

# 5. VIDEO

* aca ira el link del video de youtube


# 6.	CONCLUSIONES

* El teorem de Thevenin nos permite obtener un circuito equivalente , se puede calcular en menos tiempo el valor de voltajes, la corriente o hasta la potencia de un circuito una vez que se conecta una carga lo cual facilita la resolucion del circuito

* Es aplicable a cualquier elemento del circuito, siempre que este cuente con una fuente independiente

* Se comprueba que podemos obtener voltaje y corriente aplicando los métodos en análisis de circuitos eléctricos que cuentan
con varias conexiones sin importar cuales las conexiones solo teniendo una resitencia independiente  con el Teorema de Thevenin.

* Obervamos que las fuentes de voltaje igualadas a cero equivalen a un corto circuito, mientras que
las fuentes de corriente igualadas a cero equivalen a un circuito abierto.

# 7.	BIBLIOGRAFÍA

Rodríguez, H. (19 de Octubre de 2017). lifeder. Obtenido de

     https://www.lifeder.com/leyes-kirchhoff/

Pérez, A. (12 de enero de 2015). Electrónica Completa. Obtenido de

     https://electronicacompleta.com/leyes-de-kirchhoff/

Recuperado de:

     https://dademuch.com/2019/11/08/principio-de-superposicion-analisis-de-circuitos-electricos/

RÚBRICA

   ![](https://github.com/eddy90cg/Laboratorio_4/blob/main/Anexos/rubrica.jpg)

