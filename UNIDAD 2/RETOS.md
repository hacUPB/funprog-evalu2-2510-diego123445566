🔍 Para cada ejercicio, realice un análisis detallado y registre sus conclusiones en una tabla donde clasifique las variables de entrada, salida y las constantes. Enuncie las ecuaciones involucradas y explique el enfoque analítico que utilizará para plantear la solución.

1. Se requiere obtener la distancia entre dos puntos en el plano cartesiano,
tal y como se muestra en la figura 1. Realice un diagrama de flujo y pseudocódigo
que representen el algoritmo para obtener la distancia entre
esos puntos.

2. Una modista, para realizar sus prendas de vestir, encarga las telas al extranjero.
Para cada pedido, tiene que proporcionar las medidas de la tela
en pulgadas, pero ella generalmente las tiene en metros. Realice un algoritmo
para ayudar a resolver el problema, determinando cuántas pulgadas
debe pedir con base en los metros que requiere. Represéntelo mediante un
diagrama de flujo y pseudocódigo (1 pulgada = 0.0254 m).
3. Se requiere determinar la hipotenusa de un triángulo rectángulo. ¿Cómo sería el diagrama de flujo y el pseudocódigo que representen el algoritmo para obtenerla? 
Recuerde que por Pitágoras se tiene que: $C^2 = A^2 + B^2$.
4. Se requiere determinar la edad actual de una persona basándose en su fecha de nacimiento. Además, es necesario establecer si la persona ya ha cumplido años en el año en curso, si aún no lo ha hecho, o si hoy es su cumpleaños, para celebrarlo. La fecha de nacimiento y la fecha actual estarán representadas mediante tres variables: día, mes y año.
    
    **Pasos a seguir:**
    
    - Diseñe un algoritmo que permita calcular la edad de la persona.
    - Determine si la persona ya celebró su cumpleaños este año o si aún no lo ha hecho.
    - Verifique si la fecha actual corresponde al día de su cumpleaños. De ser así, imprima el mensaje “Feliz Cumpleaños”.
    - Represente la solución utilizando pseudocódigo claro y estructurado.
5. Realice un algoritmo que permita determinar el sueldo semanal de un trabajador con base en las horas trabajadas y el pago por hora, considerando que a partir de la hora número 41 y hasta la 45, cada hora se le paga el doble, de la hora 46 a la 50, el triple, y que trabajar
más de 50 horas no está permitido. Represente el algoritmo mediante pseudocódigo.
6. Se requiere un algoritmo para determinar, de N cantidades, cuántas son cero, cuántas son menores a cero, y cuántas son mayores a cero. Realice el pseudocódigo para representarlo, utilizando el ciclo apropiado.
7. Se requiere un algoritmo para determinar cuánto ahorrará en pesos una persona diariamente, y en un año, si ahorra 3¢ el primero de enero, 9¢ el dos de enero, 27¢ el 3 de enero y así sucesivamente todo el año. Represente la solución mediante pseudocódigo.
8. Realice el algoritmo para determinar cuánto pagará una persona que adquiere N artículos, los cuales están de promoción. Considere que si su precio es mayor o igual a $200 se le aplica un descuento de 15%, y si su precio es mayor a $100, pero menor a $200, el descuento es de
12%; de lo contrario, solo se le aplica 10%. Se debe saber cuál es el costo y el descuento que tendrá cada uno de los artículos y finalmente cuánto se pagará por todos los artículos obtenidos. Represente la solución mediante pseudocódigo.
9. Realice un algoritmo y represéntelo mediante pseudocódigo para obtener una función exponencial, la cual está dada por:
 e^x = 1 + x/1! + x^2/2! + x^3/3! + ...
10. Realice un algoritmo para obtener el seno de un ángulo y represéntelo mediante pseudocódigo. Utilice la siguiente ecuación:
Sen x = x - x^3/3! + x^5/5! - x^7/7! + ...

SOLUCION

pseurocodigo

1. Algoritmo Distancia_de_dos_puntos
	escribir "ingresa las coordenadas de los puntos"
	Escribir "ingresa coordenada X1"
	Leer coordenadaX1
	Escribir "ingresa coordenada Y1"
	Leer coordenadaX2
	Escribir "ingresa coordenada X2"
	Leer coordenadaY1
	Escribir  "ingresa coordenada Y2"
	Leer coordenadaY2
	DISTANCIA=rc(coordenadaX2-coordenadaX1)+ (coordenadaY2-coordenadaY1)

	Imprimir DISTANCIA
FinAlgoritmo


2. Algoritmo METROS_A_PULGADAS
	Escribir "ingrese la cantidad de tela en metros"
	Leer metros
	pulgadas <- metros / 0.0254
	ESCRIBIR "Debe pedir", pulgadas, "pulgadas de tela."
	
FinAlgoritmo


3. Algoritmo TRIANGULO_RECTANGULO
	Escribir "ingrese el valor del cateto A"
	Leer A
	ESCRIBIR "Ingrese el valor del cateto B"
    LEER B
	C <- Rc(A^2 + B^2)
	ESCRIBIR "La hipotenusa es" C
FinAlgoritmo

``
4.  Algoritmo EDAD_ACTUAL_DE_UNA_PERSONA
		ESCRIBIR "Ingrese el día de nacimiento"
		LEER diaNAC
		ESCRIBIR "Ingrese el mes de nacimiento"
		LEER mesNac
		ESCRIBIR "Ingrese el año de nacimiento"
		LEER añoNac
		ESCRIBIR "Ingrese el día actual"
		LEER diaAct
		ESCRIBIR "Ingrese el mes actual"
		LEER mesAct
		ESCRIBIR "Ingrese el año actual"
		LEER añoAct
		edad <- añoAct - añoNac
		
		SI (mesAct < mesNac) O (mesAct = mesNac Y diaAct < diaNac) ENTONCES
			edad <- edad - 1
			ESCRIBIR "Aún no ha cumplido años este año."
		SiNo
			ESCRIBIR "Ya cumplió años este año."
		FIN SI
		SI (mesAct = mesNac Y diaAct = diaNac) ENTONCES
			ESCRIBIR "Feliz Cumpleaños!"
		FinSi
		Imprimir "edad actual" edad
	
FinAlgoritmo


5. Algoritmo horad de trabajo
    ESCRIBIR "Ingrese las horas trabajadas en la semana:"
    LEER horasTrabajadas
    ESCRIBIR "Ingrese el pago por hora:"
    LEER pagoHora
    SI horasTrabajadas > 50 ENTONCES
        ESCRIBIR "No está permitido trabajar más de 50 horas."
    SINO
        sueldo <- 0
	FinSi
        SI horasTrabajadas <= 40 ENTONCES
            sueldo <- horasTrabajadas * pagoHora
        SINO SI horasTrabajadas <= 45 ENTONCES
				sueldo <- (40 * pagoHora) + ((horasTrabajadas - 40) * pagoHora * 2)
			SINO SI horasTrabajadas <= 50 ENTONCES
					sueldo <- (40 * pagoHora) + (5 * pagoHora * 2) + ((horasTrabajadas - 45) * pagoHora * 3)
				FIN SI
				
				ESCRIBIR "El sueldo semanal es:", sueldo
			FIN SI
		FinSi
FinAlgoritmo

``
6.   Algoritmo triangulo_rectangulo
	ESCRIBIR "Ingrese la cantidad de números a evaluar (N):"
    LEER N
    contadorCeros <- 0
    contadorPositivos <- 0
    contadorNegativos <- 0
    PARA i <- 1 HASTA N HACER
        ESCRIBIR "Ingrese un número:"
        LEER num
        SI num = 0 ENTONCES
            contadorCeros <- contadorCeros + 1
        SINO SI num > 0 ENTONCES
				contadorCerosPositivos <- contadorCerosPositivos + 1
			SINO
				contadorCerosNegativos <- contadorCerosNegativos + 1
			FIN SI
		FinSi
	FinPara
	Imprimir  "Cantidad de números iguales a cero:", contadorCeros
	Imprimir "Cantidad de números positivos:", contadorCerosPositivos
	Imprimir  "Cantidad de números negativos:", contadorCerosNegativos
FinAlgoritmo

``
7. Algoritmo Ahorro_anual
	Definir ahorro_diario como real
    Definir ahorro_total como real
    Definir dia como entero
    ahorro_diario <- 0.03  // Primer día se ahorran 3 centavos
    ahorro_total <- 0
    Para dia <- 1 hasta 365 Hacer
        Mostrar "Día ", dia, ": ahorró ", ahorro_diario, " pesos"
        ahorro_total <- ahorro_total + ahorro_diario
        ahorro_diario <- ahorro_diario * 3 // Se triplica el ahorro cada día
    Fin Para
    Mostrar "Total ahorrado en el año: ", ahorro_total, " pesos"
FinAlgoritmo

``
8. Algoritmo promocion
    Escribir "Ingrese el precio de los articulos comprados" 
    Leer precio
		Si precio >= 200 Entonces
            descuento <- precio * 0.15
        Sino Si precio >= 100 Entonces
				descuento <- precio * 0.12
			Sino
				descuento <- precio * 0.10
			FinSi
		FinSi
			precio_final <- precio - descuento
			total_pago <- total_pago + precio_final
			Escribir "Descuento aplicado: ", descuento
			Escribir "Precio final del artículo ", i, ": ", precio_final
		Escribir "Total a pagar por todos los artículos: ", total_pago
FinAlgoritmo

``
9. Algoritmo funcion_exponencial
    Escribir "Ingrese el valor de x:"
    Leer x
    Escribir "Ingrese el número de términos (precisión):"
    Leer n
    suma <- 1
    termino <- 1
    Para i desde 1 hasta n-1 hacer
        termino <- (termino * x) / i
        suma <- suma + termino
    Fin Para
    Escribir "El valor aproximado de e^x es: ", suma
FinAlgoritmo

``
10. Algoritmo angulo
	Escribir "Ingrese el valor de x en radianes"
	Leer x 
	Escribir "Ingrese el numero de te?rminos que desea imprimir"
	Leer n
	Sen(x) = x  
    termino = x  
    i = 1  
    si i < n hacer
        termino = termino * (-1) * x * x / ((2 * i) * (2 * i + 1))  
        Sen(x) = Sen(x) + termino  
        i = i + 1  
    FinSi
	Escribir "El valor aproximado de Sen(x) es: ", Sen(x)
FinAlgoritmo
