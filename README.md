# TEOREMA DE SUPERPOSICIÓN

1. OBJETIVOS

Generales

* Analizar el circuito  y justificar el uso de la teoría del teorema de superposición para los diferentes cálculos. 

Especificos

* Demostrar la funcionalidad del teorema de superposición y revisar los valores medidos con los valores teóricos mediante el uso de simuladores. 
* Explicar los datos obtenidos en las tablas, mediante las formulas establecidas.
* Practicar la resolucion de ejercicios usando el teorema de superposición.

2. MARCO TEÓRICO 

Uno de los metodos al momento de analizar circuitos es el Teorema de Superposición, al igual que hemos visto analisis de mallas y leyes de Kirchhoff. Este teorema nos dice que el voltaje o corriente a través de cualquier elemento de un circuito puede obtenerse sumando todos los voltajes o corrientes generados por cada fuente. La palabra superposición es una manera elegante de decir suma, por ejemplo si tenemos una resitencia R_3, estamos usando el principio de superposición cuando decimos que las corrientes de lazo, I_1 e I_2, se suman en la corriente existente en el resistor, I_{R_3}.

<p align="center">
  <img src="https://github.com/Dillanj2/Informe3/blob/main/Im%C3%A1genes/Ejemplo%20Teoria..png">
</p>
<p align="center">
  Figura 2.1: Ejemplo del Teorema de Superposición.
</p>

Las dos corrientes de lazo se superponen (se suman) para formar la corriente a través de R_3.

3. DIAGRAMAS

<p align="center">
  <img src="https://github.com/Dillanj2/Informe3/blob/main/Im%C3%A1genes/Circuito%20para%20comprobar%20el%20Teorema%20de%20Superposici%C3%B3n.png">
</p>
<p align="center">
  Diagrama 3.1: Circuito para comprobar el Teorema de Superposición.
</p>

4. LISTA DE COMPONENTES

* 2 Fuente de Voltaje de C.D.
* 2 Multimetros Digitales.
* 1 Resistor de 1kΩ
* 1 Resistor de 2.2kΩ
* 1 Resistor de 820Ω
* 1 Resistor de 470Ω
* 1 Protoboard

5. PROCEDIMIENTO

5.1 Arme el circuito que se muestra en el diagrama 3.1.

5.2 Con las dos fuentes conectadas, mida el voltaje V_A y la corriente I_x, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 5.1 y 5.2 respectivamente.

5.3 Haga "cero" la fuente de voltaje de 12 V (V_2) y mida el voltaje V_A y la corriente I_x, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 5.1 y 5.2 respectivamente.

5.4 Haga "cero" la fuente de voltaje de 20 V (V_1) y mida el voltaje V_A y la corriente I_x, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en la tabla 5.1 y 5.2 respectivamente.

<p align="center">
  Tabla 5.1: Medición de voltaje aplicando superposición.
</p>
<p align="center">
  <img src="https://github.com/Dillanj2/Informe3/blob/main/Im%C3%A1genes/Medici%C3%B3n%20de%20voltaje%20aplicando%20superposici%C3%B3n.png">
</p>

<p align="center">
  Tabla 5.2: Medición de corriente aplicando superposición.
</p>
<p align="center">
  <img src="https://github.com/Dillanj2/Informe3/blob/main/Im%C3%A1genes/Medici%C3%B3n%20de%20corriente%20aplicando%20superposici%C3%B3n.png">
</p>

5.5 Verifique el cumplimiento del Teorema de Superposición y compare los resultados obtrenidos prácticamente con los obtenidos analíticamente. Realice sus conclusiones.

El procedimiento lo puede observar entrando al siguiente enlace:

<p><a href="https://github.com/Dillanj2/Informe3/blob/main/C%C3%B3digo%20fuente/Procedimiento_de_Laboratorio_3.pdf">Procedimiento</a>

6. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

* Tinkercad: Es una herramienta online de Autodesk, que permite la simulacion de circuitos, al igual que permite dibujar esquemas circuitales de forma sencilla.
* LTspice: Es un simulador de alto rendimiento en el que pueden armarse diagramas esquemáticos de reguladores de alimentación conmutados o Convertidores DC-DC. Permite la simulacion de circuitos.

7. CONCLUSIONES

* El teorema de superposicion nos ayuda de gran manera en el analisis de circuitos, especialmente cuando queremos encontrar la corriente que se forma en un resistor. 
* Al aplicar el teorema de superposición en conjunto con los temas aprendidos anteriormente, el análisis de circuitos se hace mas facil de operar. 

8. BIBLIOGRAFÍA

McAllister, W. (S/F). El método de la corriente de malla. Khan Academy. Obtenido de: https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-mesh-current-method

9. ANEXOS

<p align="center">
  <img src="https://github.com/Dillanj2/Informe3/blob/main/Im%C3%A1genes/Circuito%20en%20TINKERCAD.jpeg">
</p>
<p align="center">
  Figura 9.1: Circuito en Tinkercad.
</p

<p align="center">
  <img src="https://github.com/Dillanj2/Informe3/blob/main/Im%C3%A1genes/Circuito%20en%20LTspice.jpeg">
</p>
<p align="center">
  Figura 9.1: Circuito en LTspice.
</p

<p align="center">
  <img src="https://github.com/Dillanj2/Informe3/blob/main/Im%C3%A1genes/Circuito%20con%20V_1%20cero.jpeg">
</p>
<p align="center">
  Figura 9.3: Circuito con V_12 cero.
</p
  
<p align="center">
  <img src="https://github.com/Dillanj2/Informe3/blob/main/Im%C3%A1genes/Circuito%20con%20V_2%20cero.jpeg">
</p>
<p align="center">
  Figura 9.4: Circuito con V_20 cero.
</p


