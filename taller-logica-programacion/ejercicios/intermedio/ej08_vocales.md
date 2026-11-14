```text
Algoritmo contar_vocales
    Definir palabra Como Caracter
    Definir letra Como Caracter
    Definir i Como Entero
    Definir cantidad Como Entero

    cantidad <- 0

    Escribir "Escribe una palabra"
    Leer palabra

    Para i <- 1 Hasta Longitud(palabra) Hacer
        letra <- Minusculas(Subcadena(palabra, i, i))

        Si letra = "a" O letra = "e" O letra = "i" O letra = "o" O letra = "u" Entonces
            cantidad <- cantidad + 1
        FinSi
    FinPara

    Escribir "La cantidad de vocales es: ", cantidad
FinAlgoritmo
```
