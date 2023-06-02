# Introducción a los operadores básicos en Python
Los operadores en Python son símbolos especiales que realizan operaciones en uno o más operandos y devuelven un resultado. Python proporciona varios tipos de operadores, entre ellos los operadores aritméticos, de asignación, de comparación, lógicos y de pertenencia. En este tutorial, nos enfocaremos en los operadores aritméticos, de asignación y de comparación.

### Operadores aritméticos
Los operadores aritméticos se utilizan para realizar operaciones matemáticas básicas. Los operadores aritméticos en Python incluyen la suma, resta, multiplicación, división y módulo. Aquí tienes una lista de operadores aritméticos:

- Suma (+): Se utiliza para sumar dos valores.
- Resta (-): Se utiliza para restar un valor de otro.
- Multiplicación (*): Se utiliza para multiplicar dos valores.
- División (/): Se utiliza para dividir un valor entre otro.
- Módulo (%): Devuelve el resto de una división.

A continuación, se muestra un ejemplo de código que utiliza operadores aritméticos:
```python
# Ejemplo de operadores aritméticos
a = 10
b = 3

suma = a + b
resta = a - b
multiplicacion = a * b
division = a / b
modulo = a % b

print("Suma:", suma)
print("Resta:", resta)
print("Multiplicación:", multiplicacion)
print("División:", division)
print("Módulo:", modulo)
```
salida:
```bash
Suma: 13
Resta: 7
Multiplicación: 30
División: 3.3333333333333335
Módulo: 1
```

## Operadores de asignación
Los operadores de asignación se utilizan para asignar valores a variables. El operador de asignación más común es el signo igual (=). Aquí tienes un ejemplo de código que utiliza operadores de asignación:
```python
# Ejemplo de operadores de asignación
a = 10  # Asigna el valor 10 a la variable 'a'
b = 5   # Asigna el valor 5 a la variable 'b'

# Operadores compuestos de asignación
a += b  # Equivalente a: a = a + b
print("a =", a)  # Salida: a = 15

a -= b  # Equivalente a: a = a - b
print("a =", a)  # Salida: a = 10

a *= b  # Equivalente a: a = a * b
print("a =", a)  # Salida: a = 50

a /= b  # Equivalente a: a = a / b
print("a =", a)  # Salida: a = 10.0

a %= b  # Equivalente a: a = a % b
print("a =", a)  # Salida: a = 0.0
```

## Operadores de comparación
Los operadores de comparación se utilizan para comparar dos valores y devuelven un valor booleano (True o False) según se cumpla o no la condición. Aquí tienes una lista de operadores de comparación en Python:

- Igual (==): Comprueba si dos valores son iguales.
- Distinto (!=): Comprueba si dos valores son diferentes.
- Mayor que (>): Comprueba si el valor de la izquierda es mayor que el de la derecha.
- Menor que (<): Comprueba si el valor de la izquierda es menor que el de la derecha.
- Mayor o igual que (>=): Comprueba si el valor de la izquierda es mayor o igual que el de la derecha.
- Menor o igual que (<=): Comprueba si el valor de la izquierda es menor o igual que el de la derecha.

A continuación, se muestra un ejemplo de código que utiliza operadores de comparación:
```python
#Ejemplo de operadores de comparación
a = 5
b = 10

print("a == b:", a == b)  # Salida: False
print("a != b:", a != b)  # Salida: True
print("a > b:", a > b)    # Salida: False
print("a < b:", a < b)    # Salida: True
print("a >= b:", a >= b)  # Salida: False
print("a <= b:", a <= b)  # Salida: True
```

## Ejercicios prácticos
Ahora que hemos cubierto los operadores básicos en Python, aquí tienes algunos ejercicios prácticos para que los completes:

- Escribe un programa que tome dos números ingresados por el usuario y muestre la suma, resta, multiplicación, división y módulo de esos números.
- Escribe un programa que tome un número ingresado por el usuario y verifique si es par o impar. Muestra un mensaje adecuado en cada caso.
- Escribe un programa que tome el radio de un círculo ingresado por el usuario y calcule el área y la circunferencia del círculo. Muestra los resultados redondeados a dos decimales.
- Escribe un programa que tome tres números ingresados por el usuario y determine el número más grande de los tres.

Te animo a que intentes resolver estos ejercicios por ti mismo. Si tienes alguna pregunta o necesitas ayuda, estaré aquí para ayudarte. ¡Buena suer




