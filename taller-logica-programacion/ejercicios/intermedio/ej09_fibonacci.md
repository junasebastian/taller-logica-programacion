```text
Algoritmo serie_fibonacci
    Definir cantidad Como Entero
    Definir i Como Entero
    Definir primero Como Entero
    Definir segundo Como Entero
    Definir siguiente Como Entero

    primero <- 0
    segundo <- 1

    Escribir "Cuantos numeros de la serie desea mostrar?"
    Leer cantidad

    Si cantidad <= 0 Entonces
        Escribir "Debe escribir una cantidad mayor que cero"
    SiNo
        Para i <- 1 Hasta cantidad Hacer
            Escribir Sin Saltar primero, " "

            siguiente <- primero + segundo
            primero <- segundo
            segundo <- siguiente
        FinPara
        Escribir ""
    FinSi
FinAlgoritmo
```
