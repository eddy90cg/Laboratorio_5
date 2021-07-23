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

![](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Mentefacto-Lab5.jpeg)

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

* Tabla de Registro de datos tomados para el Circuito Equivalente de Thévenin :

| <img src="https://latex.codecogs.com/svg.latex?V_{TH}" title="V_{TH}" /> | <img src="https://latex.codecogs.com/svg.latex?(V)" title="(V)" /> | <img src="https://latex.codecogs.com/svg.latex?R_{TH}" title="R_{TH}" /> | <img src="https://latex.codecogs.com/svg.latex?(\Omega)" title="(\Omega)" /> |
| :---: | :---: | :---: | :---: |
| **Calculado** | 5.049 | **Calculado** | 298.86 |
| **Medido** | 5.06 | **Medido** | 299 |

* Porcentaje de Error Obtenido

|      | <img src="https://latex.codecogs.com/svg.latex?V_{TH}" title="V_{TH}" /> | <img src="https://latex.codecogs.com/svg.latex?R_{TH}" title="R_{TH}" /> |
| :---: | :---: | :---: |
| **Error** | <img src="https://latex.codecogs.com/svg.latex?-0.21%" title="-0.21%" /> | <img src="https://latex.codecogs.com/svg.latex?-0.04%" title="-0.04%" /> |      

* Tabla de Registro de datos tomados para la Comprobación del Teorema de Thévenin  :

| **Parámetro Eléctrico** | **Circuito Original** || **Circuito Equivalente de Thévenin**||
| :---: | :---: | :---: | :---: | :---: |
|| **Calculado** | **Medido** | **Calculado** | **Medido** |
| **Voltaje (V)** | 3.89 | 3.89 | 3.89 | 3.90 |
| **Corriente (mA)** | 3.89 | 3.89 | 3.89 | 3.90 |

* Porcentaje de Error Obtenido para el **Circuito Original**

| **Circuito Original** | **Error** |
| :--: | :---: |
| **Voltaje (V)** | <img src="https://latex.codecogs.com/svg.latex?0%" title="0%" /> |
| **Corriente (mA)** | <img src="https://latex.codecogs.com/svg.latex?0%" title="0%" /> |

* Porcentaje de Error Obtenido para el **Circuito Equivalente de Thévenin**

| **Circuito Original** | **Error** |
| :--: | :---: |
| **Voltaje (V)** | <img src="https://latex.codecogs.com/svg.latex?-0.26%" title="-0.26%" /> |
| **Corriente (mA)** | <img src="https://latex.codecogs.com/svg.latex?-0.26%" title="-0.26%" /> |

Para poder encontrar los valores y comprobar el Teorema de Thévenin se realizaron los siguientes cálculos:

Resolución por el Teorema de Thévenin

* Para Thévenin debemos retirar R5 y las fuentes de voltaje se deben reemplazar pot un cortocircuito

![](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Thévenin-Paso1.jpeg)

* Obtenemos la resistencia equivalente entre R1 y R2, y la llamamos <img src="https://latex.codecogs.com/svg.latex?R_{12}" title="R_{12}" />

![](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Thévenin-Paso2.jpeg)

<img src="https://latex.codecogs.com/svg.latex?R_{12}=\frac{(560\Omega)(4700\Omega)}{560\Omega&plus;4700\Omega}=500.30\Omega" title="R_{12}=\frac{(560\Omega)(4700\Omega)}{560\Omega+4700\Omega}=500.30\Omega" />

* Encontramos la resistencia equivalente entre <img src="https://latex.codecogs.com/svg.latex?R_{12}" title="R_{12}" /> y R3, y la llamamos <img src="https://latex.codecogs.com/svg.latex?R_{123}" title="R_{123}" />

![](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Thévenin-Paso3.jpeg)

<img src="https://latex.codecogs.com/svg.latex?R_{123}=\frac{(500.38\Omega)(330\Omega)}{500.38\Omega&plus;330\Omega}=198.86\Omega" title="R_{123}=\frac{(500.38\Omega)(330\Omega)}{500.38\Omega+330\Omega}=198.86\Omega" />

* Encontramos la resistencia equivalente entre <img src="https://latex.codecogs.com/svg.latex?R_{123}" title="R_{123}" /> y R4, que será la Resistencia de Thévenin

![](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Thévenin-Paso4.jpeg)

<img src="https://latex.codecogs.com/svg.latex?R_{TH}=198.86\Omega&plus;1000\Omega=298.86\Omega" title="R_{TH}=198.86\Omega+1000\Omega=298.86\Omega" />

* Luego encontramos el Voltaje de Thévenin realizando un análisis de mallas

![](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Thévenin-Mallas.jpeg)

<img src="https://latex.codecogs.com/svg.latex?\begin{matrix}&space;\textrm{Malla&space;1}\\&space;12-560I_1-4700(I_1-I_2)=0\\&space;-5260I_1&plus;4700I_2=-12&space;\quad&space;(1)&space;\end{matrix}" title="\begin{matrix} \textrm{Malla 1}\\ 12-560I_1-4700(I_1-I_2)=0\\ -5260I_1+4700I_2=-12 \quad (1) \end{matrix}" />

<img src="https://latex.codecogs.com/svg.latex?\begin{matrix}&space;\textrm{Malla&space;2}\\&space;2-330I_2-4700(I_2-I_1)=0\\&space;4700I_1-5030I_2=-2&space;\quad&space;(2)&space;\end{matrix}" title="\begin{matrix} \textrm{Malla 2}\\ 2-330I_2-4700(I_2-I_1)=0\\ 4700I_1-5030I_2=-2 \quad (2) \end{matrix}" />

* Obtenemos el siguiente sistema de ecuaciones

<img src="https://latex.codecogs.com/svg.latex?\begin{cases}&space;-5260I_1&plus;4700I_2=-12\\&space;4700I_1-5030I_2=-2&space;\end{cases}" title="\begin{cases} -5260I_1+4700I_2=-12\\ 4700I_1-5030I_2=-2 \end{cases}" />

* Resolvemos y encontramos <img src="https://latex.codecogs.com/svg.latex?I_1" title="I_1" />  e  <img src="https://latex.codecogs.com/svg.latex?I_2" title="I_2" />

<img src="https://latex.codecogs.com/svg.latex?I_1=0.01597A=15.97mA" title="I_1=0.01597A=15.97mA" />

<img src="https://latex.codecogs.com/svg.latex?I_2=0.0153A=15.3mA" title="I_2=0.0153A=15.3mA" />

* Ahora encontramos el <img src="https://latex.codecogs.com/svg.latex?V_{TH}" title="V_{TH}" /> que será igual al voltaje en los extremos de R3

<img src="https://latex.codecogs.com/svg.latex?\begin{matrix}&space;V_{TH}=R_3\cdot&space;I_2\\&space;\\&space;V_{TH}=330\Omega\cdot&space;15.3mA=5.049V&space;\end{matrix}" title="\begin{matrix} V_{TH}=R_3\cdot I_2\\ \\ V_{TH}=330\Omega\cdot 15.3mA=5.049V \end{matrix}" />

* Una vez obtenida la resistencia y voltaje, podemos formar el circuito equivalente de Thévenin y encontrar los equivalentes al circuito original

![](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Thévenin-Completo.jpeg)

* Para la Corriente Equivalente de Thévenin

<img src="https://latex.codecogs.com/svg.latex?\begin{matrix}&space;5.049-298.86I-1000I=0\\&space;\\&space;I=\frac{-5.049}{-1298.86}=0.00389A=3.89mA&space;\end{matrix}" title="\begin{matrix} 5.049-298.86I-1000I=0\\ \\ I=\frac{-5.049}{-1298.86}=0.00389A=3.89mA \end{matrix}" />

* Para la Voltaje Equivalente de Thévenin

<img src="https://latex.codecogs.com/svg.latex?\begin{matrix}&space;V=R_5\cdot&space;I\\&space;V=1000\Omega\cdot&space;3.89mA=3.89V&space;\end{matrix}" title="\begin{matrix} V=R_5\cdot I\\ V=1000\Omega\cdot 3.89mA=3.89V \end{matrix}" />

* Resolución del Circuito Original por Análisis de Mallas

![](https://github.com/eddy90cg/Laboratorio_5/blob/main/Laboratorio%205/Circuito%20Original-Mallas.jpeg)

<img src="https://latex.codecogs.com/svg.latex?\begin{matrix}&space;\textrm{Malla&space;1}\\&space;12-560I_1-4700(I_1-I_2)=0\\&space;-5260I_1&plus;4700I_2=-12\quad&space;(1)&space;\end{matrix}" title="\begin{matrix} \textrm{Malla 1}\\ 12-560I_1-4700(I_1-I_2)=0\\ -5260I_1+4700I_2=-12\quad (1) \end{matrix}" />

<img src="https://latex.codecogs.com/svg.latex?\begin{matrix}&space;\textrm{Malla&space;2}\\&space;2-330(I_2-I_3)-4700(I_2-I_1)=0\\&space;4700I_1-5030I_2&plus;330I_3=-2\quad&space;(2)&space;\end{matrix}" title="\begin{matrix} \textrm{Malla 2}\\ 2-330(I_2-I_3)-4700(I_2-I_1)=0\\ 4700I_1-5030I_2+330I_3=-2\quad (2) \end{matrix}" />

<img src="https://latex.codecogs.com/svg.latex?\begin{matrix}&space;\textrm{Malla&space;3}\\&space;-100I_3-1000I_3-330(I_3-I_2)=0\\&space;330I_2-1430I_3=0\quad&space;(3)&space;\end{matrix}" title="\begin{matrix} \textrm{Malla 3}\\ -100I_3-1000I_3-330(I_3-I_2)=0\\ 330I_2-1430I_3=0\quad (3) \end{matrix}" />

* Obtenemos el siguiente sistema de ecuaciones

<img src="https://latex.codecogs.com/svg.latex?\begin{cases}&space;-5260I_1&plus;4700I_2=-12\\&space;4700I_1-5030I_2&plus;330I_3=-2\\&space;330I_2-1430I_3=0&space;\end{cases}" title="\begin{cases} -5260I_1+4700I_2=-12\\ 4700I_1-5030I_2+330I_3=-2\\ 330I_2-1430I_3=0 \end{cases}" />

* Resolvemos y encontramos <img src="https://latex.codecogs.com/svg.latex?I_1" title="I_1" /> , <img src="https://latex.codecogs.com/svg.latex?I_2" title="I_2" />  e  <img src="https://latex.codecogs.com/svg.latex?I_3" title="I_3" />

<img src="https://latex.codecogs.com/svg.latex?\begin{matrix}&space;I_1=0.01735A=17.35mA\\&space;I_2=0.0687A=16.87mA\\&space;I_3=0.00389A=3.89mA\\&space;\end{matrix}" title="\begin{matrix} I_1=0.01735A=17.35mA\\ I_2=0.0687A=16.87mA\\ I_3=0.00389A=3.89mA\\ \end{matrix}" />

* <img src="https://latex.codecogs.com/svg.latex?I_3" title="I_3" /> será la Corriente de R5 y finalmente encontramos el Voltaje de la misma resistencia

<img src="https://latex.codecogs.com/svg.latex?\begin{matrix}&space;V_{R_5}=I_3\cdot&space;R_5\\&space;V_{R_5}=3.89mA(1000\Omega)=3.89V&space;\end{matrix}" title="\begin{matrix} V_{R_5}=I_3\cdot R_5\\ V_{R_5}=3.89mA(1000\Omega)=3.89V \end{matrix}" />













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

