```text
Algoritmo validar_contrasena
    Definir clave Como Caracter
    Definir intentos Como Entero
    Definir acceso Como Logico

    intentos <- 0
    acceso <- Falso

    Mientras intentos < 3 Y acceso = Falso Hacer
        Escribir "Escribe la contrasena"
        Leer clave

        Si clave = "1234" Entonces
            acceso <- Verdadero
        SiNo
            intentos <- intentos + 1
            Escribir "Contrasena incorrecta"
        FinSi
    FinMientras

    Si acceso = Verdadero Entonces
        Escribir "Acceso permitido"
    SiNo
        Escribir "Se acabaron los intentos"
    FinSi
FinAlgoritmo
```
