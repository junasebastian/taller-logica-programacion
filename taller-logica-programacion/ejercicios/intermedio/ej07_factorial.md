```text
Algoritmo factorial
    Definir numero Como Entero
    Definir i Como Entero
    Definir resultado Como Entero

    resultado <- 1

    Escribir "Escribe un numero entero positivo"
    Leer numero

    Si numero < 0 Entonces
        Escribir "No se puede calcular el factorial de un numero negativo"
    SiNo
        Para i <- 1 Hasta numero Hacer
            resultado <- resultado * i
        FinPara

        Escribir "El factorial es: ", resultado
    FinSi
FinAlgoritmo
```
