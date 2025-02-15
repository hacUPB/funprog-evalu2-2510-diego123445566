Ejercisio 1.
Inicio
    Escribir "Ingrese el numero de lapices que va comprae"
    Leer lapices
    Si lapices >= 1000 
        costo = 85 * lapices
    Si no
        costo = 90 * lapices
    Fin Si
    Escribir "el valor total es: ", costo
Fin

Ejercisio 2.
Inicio
    Escribir "Ingrese el valor total de la compra:"
    Leer compra

    Si compra > 250000 
        descuento ← compra * 0.15
    Sino
        descuento ← compra * 0.08
    FinSi

    precio_final ← compra - descuento

    Escribir "El descuento aplicado es: ", descuento
    Escribir "El precio final a pagar es: ", precio_final
Fin

Ejercisio 3.
Inicio
    Escribir "Ingrese la cantidad de alumnos:"
    Leer alumnos

    Si alumnos >= 100 Entonces
        costo_por_alumno ← 65
        total_a_pagar ← alumnos * costo_por_alumno
    Sino Si alumnos >= 50 Entonces
        costo_por_alumno ← 70
        total_a_pagar ← alumnos * costo_por_alumno
    Sino Si alumnos >= 30 Entonces
        costo_por_alumno ← 95
        total_a_pagar ← alumnos * costo_por_alumno
    Sino
        total_a_pagar ← 4000
        costo_por_alumno ← total_a_pagar / alumnos
    FinSi

    Escribir "El costo por alumno es: ", costo_por_alumno
    Escribir "El total a pagar a la compañía de viajes es: ", total_a_pagar
Fin
