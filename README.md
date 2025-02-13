[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/IYE4ssuc)
# Unidad No. 
## Información del estudiante  
Nombre del estudiante:  
Id.:
---
version 2 

*En la Figura 2 se muestran los diferentes estados que se pueden representar usando una palabra binaria de 3 bits. Responde la pregunta de la imagen: ¿Cuántos estados diferentes se pueden representar usando N bits?

El número de estados diferentes que se pueden representar con \( N \) bits se calcula con la fórmula:  
\[{Total de estados} = 2^N\]
Esto se debe a que cada bit tiene dos posibles valores (0 o 1), y al combinar \( N \) bits, se generan todas las combinaciones posibles de estos valores.
Por ejemplo:  
- Para **3 bits**, los estados posibles son \( 2^3 = 8 \).  
- Para **4 bits**, los estados posibles son \( 2^4 = 16 \).  
- Para **N bits**, los estados posibles son \( 2^N \).  
Entonces, la respuesta a la pregunta es: **Con \( N \) bits se pueden representar \( 2^N \) estados diferentes.**

*Escribe un párrafo explicando, en tus propias palabras, cómo se representan los datos en una computadora. Por ejemplo, ¿cómo se ingresan números, letras, imágenes a una computadora?

En una computadora, los datos se representan mediante el sistema binario, que utiliza solo dos valores: 0 y 1. Cada número, letra, imagen o sonido que ingresamos se convierte en una secuencia de bits (dígitos binarios). Por ejemplo, los números se almacenan utilizando códigos binarios como el sistema de complemento a dos, las letras se codifican con estándares como ASCII o Unicode, y las imágenes se representan como conjuntos de píxeles, donde cada uno tiene valores numéricos que indican su color. Los dispositivos de entrada, como el teclado o el mouse, convierten nuestras acciones en señales eléctricas que la computadora traduce a datos binarios, los procesa y luego los muestra en la pantalla o los almacena en la memoria.

*escribe tus conclusiones acerca de la pregunta planteada en la Figura 2. ¿Cuántos estados diferentes pueden ser representados por N variables binarias?

En conclusión, el número de estados diferentes que pueden ser representados por \( N \) variables binarias sigue la fórmula \( 2^N \). Esto significa que, a medida que aumenta el número de bits, la cantidad de combinaciones posibles crece exponencialmente. Por ejemplo, con 3 bits se pueden representar 8 estados diferentes, mientras que con 4 bits se pueden representar 16. Esta propiedad es fundamental en la computación, ya que permite almacenar y procesar grandes cantidades de información de manera eficiente. Gracias a esta representación binaria, las computadoras pueden manejar números, texto, imágenes y otros tipos de datos utilizando combinaciones de ceros y unos.
 _________________________________________________________________                                                               
|Unidad   |	Abreviatura| Equivalencia en Bytes                    |
|Bit	  |     (b)    |1 bit (mínima unidad de información)        |
|Byte	  |     (B)	   |8 bits                                      |
|KiloByte |	   (KB)	   |1,024 Bytes(2^10)                         |
|MegaByte |	   (MB)	   |1,024 KB Bytes (2^20 Bytes)               | 
|GigaByte |	   (GB)	   |1,024 MB (2^30 Bytes)                     |
|TeraByte |	   (TB)	   |1,024 GB (2^40 Bytes)                     |
|PetaByte |	   (PB)	   |1,024 TB (2^50 Bytes)                     |
|ExaByte  |    (EB)    |1,024 PB (2^60 Bytes)                     |
|ZettaByte|	   (ZB)	   |1,024 EB (2^70 Bytes)                     |
|YottaByte|	   (YB)	   |1,024 ZB (2^80 Bytes)                     |
|_________|____________|__________________________________________|

*Incluye un pequeño resumen, de un par de renglones, donde menciones la importancia del trabajo de George Bool en este tópico.

El trabajo de **George Boole** fue fundamental en la computación, ya que desarrolló el **Álgebra de Boole**, un sistema matemático basado en valores binarios (0 y 1). Su lógica es la base de los circuitos digitales y la representación de datos en computadoras, permitiendo la creación de sistemas de almacenamiento y procesamiento de información.

*Ahora es tu turno de intentar usar el método. Te voy a proponer varios números binarios y tú vas a convertirlos a decimales utilizando la `tabla 3`. Recuerda que el subíndice 2 significa que el número es binario (base 2)

- 1010101010_2
- 11111_2
- 10000000_2
- 100100100_2
- 111000_2$

Resumen de los resultados:
1010101010_2= 682^10
11111_2= 32^10
10000000_2 =128^10
100100100_2=292^10
111000_2=5610^10

*## Ejercicio 2 - Resuelve y deja evidencia en la bitácora

Ahora es tu turno. Vas a convertir los siguientes  números decimales a binarios. Recuerda que el subíndice 10 significa que el número es decimal (`base 10`)

- $127_10
- $246_10
- $1025_10
- $354_10
- 187_10

Conversión de los números a binario:

127_10

127 ÷ 2 = 63, residuo 1
63 ÷ 2 = 31, residuo 1
31 ÷ 2 = 15, residuo 1
15 ÷ 2 = 7, residuo 1
7 ÷ 2 = 3, residuo 1
3 ÷ 2 = 1, residuo 1
1 ÷ 2 = 0, residuo 1
resultado 1111111_2

246_10

246 ÷ 2 = 123, residuo 0
123 ÷ 2 = 61, residuo 1
61 ÷ 2 = 30, residuo 1
30 ÷ 2 = 15, residuo 0
15 ÷ 2 = 7, residuo 1
7 ÷ 2 = 3, residuo 1
3 ÷ 2 = 1, residuo 1
1 ÷ 2 = 0, residuo 1
Resultado: 
246_10=11110110_2

1025_10

1025 ÷ 2 = 512, residuo 1
512 ÷ 2 = 256, residuo 0
256 ÷ 2 = 128, residuo 0
128 ÷ 2 = 64, residuo 0
64 ÷ 2 = 32, residuo 0
32 ÷ 2 = 16, residuo 0
16 ÷ 2 = 8, residuo 0
8 ÷ 2 = 4, residuo 0
4 ÷ 2 = 2, residuo 0
2 ÷ 2 = 1, residuo 0
1 ÷ 2 = 0, residuo 1
Resultado: 
1025_10=10000000001_2
 

354_10

354 ÷ 2 = 177, residuo 0
177 ÷ 2 = 88, residuo 1
88 ÷ 2 = 44, residuo 0
44 ÷ 2 = 22, residuo 0
22 ÷ 2 = 11, residuo 0
11 ÷ 2 = 5, residuo 1
5 ÷ 2 = 2, residuo 1
2 ÷ 2 = 1, residuo 0
1 ÷ 2 = 0, residuo 1
Resultado: 
354_10=101100010_2

187_10

187 ÷ 2 = 93, residuo 1
93 ÷ 2 = 46, residuo 1
46 ÷ 2 = 23, residuo 0
23 ÷ 2 = 11, residuo 1
11 ÷ 2 = 5, residuo 1
5 ÷ 2 = 2, residuo 1
2 ÷ 2 = 1, residuo 0
1 ÷ 2 = 0, residuo 1
 
187_10=10111011_2

## **Actividad de investigación (para la bitácora)**

*Investiga los diferentes tipos de datos que se utilizan en varios lenguajes de programación (por ejemplo, C, Java, Python). Ten en cuenta cómo cada lenguaje define los números enteros, los decimales (o flotantes), las letras del alfabeto, las cadenas de texto, valores booleanos, entre otros. Investiga qué nombres se asignan y qué abreviaciones se utilizan en cada lenguaje.

Tipos de Datos en Diferentes Lenguajes de Programación
Los lenguajes de programación utilizan distintos tipos de datos para representar información como números, texto y valores lógicos. A continuación, se describen los principales tipos de datos en C, Java y Python.

1. Números Enteros (Integer)
Los números enteros son aquellos que no tienen parte decimal.

En C, el tipo de dato int se usa para enteros estándar, mientras que long int o long permiten valores más grandes. También existe short int o short para números más pequeños.
En Java, el tipo int es el estándar para enteros, mientras que long se usa para valores más grandes y short para números más pequeños.
En Python, solo existe el tipo int, pero se maneja de forma dinámica, permitiendo representar enteros de cualquier tamaño sin necesidad de especificar un límite.
2. Números Decimales (Flotantes o de Punto Flotante)
Estos números tienen una parte decimal y se representan con diferentes niveles de precisión.

En C, el tipo float almacena números de punto flotante de precisión simple y double de precisión doble.
En Java, el tipo float también es de precisión simple, mientras que double ofrece mayor precisión.
En Python, solo existe el tipo float, pero maneja automáticamente la precisión doble.
3. Caracteres y Cadenas de Texto
Los caracteres representan una sola letra, mientras que las cadenas son secuencias de caracteres.

En C, se usa char para caracteres individuales y los arreglos de char[] para cadenas, aunque también se pueden manejar con la biblioteca string.h.
En Java, el tipo char se usa para caracteres individuales y String para cadenas de texto.
En Python, no existe un tipo char, ya que los caracteres se representan como cadenas (str).
4. Valores Booleanos (Verdadero/Falso)
Estos valores solo pueden ser True o False y se usan en condiciones lógicas.

En C, antes de C99 se usaban int (donde 0 representa falso y cualquier otro número representa verdadero). Desde C99, se puede usar stdbool.h con el tipo bool.
En Java, el tipo boolean se usa para representar valores lógicos.
En Python, se usa el tipo bool, donde True y False son equivalentes a los valores 1 y 0, respectivamente.
5. Tipos de Datos Especiales
Algunos lenguajes incluyen tipos adicionales para manejar estructuras de datos más complejas.

En C, existen los tipos unsigned int para valores enteros sin signo (solo positivos) y los arreglos (int arr[]) para manejar listas de elementos del mismo tipo.
En Java, se pueden usar arreglos (int[]), listas dinámicas (ArrayList<>), y conjuntos (Set<>). Para estructuras clave-valor, se usa Map<>.
En Python, las listas (list) son estructuras dinámicas que pueden almacenar cualquier tipo de dato, los conjuntos (set) permiten elementos únicos, y los diccionarios (dict) permiten almacenar pares clave-valor.
Conclusión
Cada lenguaje maneja los tipos de datos de manera diferente. C es más rígido y eficiente, pero requiere más control del programador. Java ofrece mayor seguridad y organización en la gestión de datos. Python es flexible y dinámico, permitiendo trabajar sin preocuparse por los límites de tamaño o tipo de datos de manera estricta.

## **rganización de resultados**

Con la información recolectada, organiza los datos en una tabla que incluya:

- **Nombre de la variable**
- **Abreviación (si existe)**
- **Características principales** (rango, tipo de valor, etc.)

Nombre de la Variable	Abreviación	Características Principales
Número Entero	int	Representa valores enteros sin decimales. En C y Java tiene un tamaño fijo (C: 2 o 4 bytes, Java: 4 bytes). En Python, el tamaño es dinámico.
Entero Largo	long	Almacena números enteros más grandes. En C y Java ocupa más memoria (C: 4 u 8 bytes, Java: 8 bytes). No existe en Python.
Entero Corto	short	Usa menos memoria que int. En C y Java ocupa 2 bytes. No está disponible en Python.
Número Flotante	float	Representa números con decimales. En C y Java ocupa 4 bytes con precisión simple. En Python, float equivale a double.
Número Doble Precisión	double	Mayor precisión que float. En C y Java ocupa 8 bytes. En Python, float ya tiene esta precisión.
Caracter Individual	char	Representa un solo carácter. En C y Java ocupa 1 o 2 bytes (Java usa Unicode). No existe en Python, se usa str.
Cadena de Texto	String (Java), char[] (C), str (Python)	Almacena secuencias de caracteres. En C se usa un arreglo de caracteres (char[]). En Java se usa String. En Python, str maneja cadenas dinámicamente.
Booleano	bool	Representa valores true o false. En C se usa int o stdbool.h. En Java y Python se usa boolean y bool, respectivamente.
Entero sin Signo	unsigned int	Solo almacena valores positivos en C. No existe en Java ni en Python.
Arreglo (Lista de Datos)	int arr[] (C), int[] (Java), list (Python)	Almacena múltiples valores del mismo tipo. En C y Java tienen tamaño fijo, en Python son dinámicas.
Lista Dinámica	No tiene en C, ArrayList<> (Java), list (Python)	En Java y Python permite cambiar el tamaño dinámicamente. No existe en C sin usar estructuras más avanzadas.
Conjunto de Valores Únicos	No tiene en C, Set<> (Java), set (Python)	Almacena valores sin duplicados. No existe en C, pero se puede simular.
Diccionario (Clave-Valor)	No tiene en C, Map<> (Java), dict (Python)	Permite almacenar pares clave-valor. No existe en C sin estructuras avanzadas.

*## **5. Ejercicio de cálculo de espacio en memoria**

Imagina que necesitas almacenar la siguiente información en un programa:

- Un identificador numérico (número entero)
- Una temperatura (valor de punto flotante)
- Un valor lógico (dato booleano)
- Un texto con 10 caracteres.

Se almacena la información cada 10 segundos durante 24 horas. Calcula cuánto espacio total se requiere en memoria para almacenar estos datos. Describe el procedimiento y muestra el resultado final.

Ejercicio de Cálculo de Espacio en Memoria
Vamos a calcular el espacio total necesario para almacenar los datos durante 24 horas.

1. Datos a almacenar por registro
Cada conjunto de datos contiene:

Un identificador numérico (entero) → int (4 bytes)
Una temperatura (punto flotante) → float (4 bytes)
Un valor lógico (booleano) → bool (1 byte en C y Python, 1 byte en Java)
Un texto de 10 caracteres → char[10] (10 bytes, ya que cada carácter ocupa 1 byte)

2. Tamaño total de un registro
Sumamos los tamaños de cada dato:

2. Tamaño total de un registro
Sumamos los tamaños de cada dato:

4 (int)+4 (float)+1 (bool)+10 (char[10])=19 bytes

3. Número de registros almacenados en 24 horas
Se almacena información cada 10 segundos durante 24 horas.
Calculamos cuántos registros se generan en un día:

24×60×60/10=8640 registros

4. Cálculo del espacio total requerido
Multiplicamos el tamaño de cada registro por la cantidad de registros

8640×19=164,160 bytes

Convertimos a kilobytes (KB)
164,160/1024=160.31 KB

Convertimos a megabytes (MB):
160.31/1024 KB =0.156 MB

Resultado Final
Se necesitan aproximadamente 160.31 KB (0.156 MB) de memoria para almacenar estos datos durante 24 horas.

## **6. Conclusión**
Finalmente, explica con tus propias palabras el resultado de esta actividad y qué aprendiste acerca de la representación de datos en las computadoras.

Conclusión*  

A través de esta actividad, aprendí cómo los datos se representan y almacenan en la memoria de una computadora. Cada tipo de dato tiene un tamaño específico en bytes, lo que influye en el espacio total que ocupa un programa. Al calcular el almacenamiento necesario para registrar información durante 24 horas, pude ver la importancia de optimizar el uso de memoria, especialmente en aplicaciones que manejan grandes volúmenes de datos.  

También comprendí que diferentes lenguajes de programación manejan los tipos de datos de distintas maneras. Algunos, como **C y Java**, requieren definir tamaños de datos específicos, mientras que **Python** maneja los tipos de forma dinámica. Esta diferencia puede afectar el rendimiento y la eficiencia en el manejo de datos.  

En conclusión, la representación de datos en las computadoras es clave para la optimización del almacenamiento y el procesamiento eficiente de la información. Esta actividad me ayudó a visualizar cómo pequeños datos pueden acumularse y requerir una cantidad significativa de memoria con el tiempo.
 
peguntas solo paralos curiosos
## Resuelve y deja evidencia en la bitácora

Es tu turno de practicar. Realiza las siguientes sumas usando binarios. Debes convertir a binario los números decimales y luego realizar la suma binaria. Vas a utilizar datos de 8 bits. Por lo tanto, resalta aquellos casos donde haya

45_10 + 96_10

45 _10=00101101_2
​96_10=01100000_2

  00101101
+ 01100000
=10001101  (141_{10})

95 _10+84_10

95_10​ =01011111_2
​84_10=01010100_2
​
  01011111
+ 01010100
------------
  10110011  (179_{10})

124_10+63_10

124_10=01111100_2
​63_10=00111111_2
​
  01111100
+ 00111111
------------
  10111011  (187_{10})

## Ejercicio 5 - Resuelve y deja evidencia en la bitácora

Convierte a binarios los siguientes decimales. Utiliza complemento a 2 y los datos debes representarlos con 12 bits.

1. 253_10
2. 365_10
3. 145_10

253_10=000011111101_2
plicamos complemento a 2:
Invertimos los bits:

111100000010_2
​Sumamos 1:
111100000011_2

Resultado: 
−
253_10=111100000011_2(12 bits)

365_10=000101101101_2

Aplicamos complemento a 2:
Invertimos los bits:
111010010010_2

Sumamos 1:
111010010011_2

 Resultado: 
−
36510=111010010011_2(bits)

 145_10=000010010001_2
 Aplicamos complemento a 2:
Invertimos los bits:
111101101110_2
Sumamos 1:
111101101111_2

 Resultado: 
−
145_10=111101101111_2(bits)

## Ejercicio 1.

Investiga cuáles son los símbolos que se utilizan para representar cada operación de un algorimo con un diagrama de flujo. Asegúrate de que la fuente es confiable, discute lo que encontraste con tus compañeros y con el profe. Cuando estés seguro/a de tener los símbolos correctos, consigna la información en la bitácora.

Los diagramas de flujo utilizan símbolos estandarizados para representar las diferentes operaciones en un algoritmo. Estos símbolos permiten visualizar la lógica y el flujo del proceso de manera clara. Aquí están los principales símbolos utilizados:

1. **Óvalo (Inicio/Fin)**: Representa el inicio o el fin del diagrama de flujo. Se coloca al principio y al final del algoritmo.  
   - **Ejemplo:** "Inicio" o "Fin"

2. **Paralelogramo (Entrada/Salida)**: Representa una operación de entrada (leer datos) o salida (mostrar resultados).  
   - **Ejemplo:** "Leer X" o "Imprimir resultado"

3. **Rectángulo (Proceso o Acción)**: Representa una operación o proceso, como un cálculo o una asignación de valores.  
   - **Ejemplo:** "Suma = A + B"

4. **Rombo (Decisión o Condición)**: Representa una decisión o bifurcación en el flujo, basada en una condición lógica (Sí/No, Verdadero/Falso).  
   - **Ejemplo:** "¿X > 10?"

5. **Flechas (Flujo del proceso)**: Indican la dirección en la que fluye el algoritmo entre los diferentes símbolos.











