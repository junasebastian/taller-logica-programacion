```text
Algoritmo calculadora
    Definir num1 Como Real
    Definir num2 Como Real
    Definir resultado Como Real
    Definir operacion Como Caracter

    Escribir "Escribe el primer numero"
    Leer num1
    Escribir "Escribe el segundo numero"
    Leer num2
    Escribir "Escribe la operacion (+, -, *, /)"
    Leer operacion

    Segun operacion Hacer
        "+":
            resultado <- num1 + num2
            Escribir "El resultado de la suma es: ", resultado
        "-":
            resultado <- num1 - num2
            Escribir "El resultado de la resta es: ", resultado
        "*":
            resultado <- num1 * num2
            Escribir "El resultado de la multiplicacion es: ", resultado
        "/":
            Si num2 <> 0 Entonces
                resultado <- num1 / num2
                Escribir "El resultado de la division es: ", resultado
            SiNo
                Escribir "No se puede dividir entre cero"
            FinSi
        De Otro Modo:
            Escribir "La operacion no es valida"
    FinSegun
FinAlgoritmo
```
