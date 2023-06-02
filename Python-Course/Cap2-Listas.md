# Listas en Python
## Introducción a las listas en Python
Las listas son una estructura de datos importante en Python. Se utilizan para almacenar colecciones ordenadas de elementos. 
Las listas son muy versátiles y permiten almacenar diferentes tipos de datos, como números, cadenas de texto e incluso otras listas. 
En este tutorial, aprenderemos sobre la creación, manipulación y acceso a los elementos de una lista.

### Creación de una lista
En Python, una lista se representa mediante corchetes (`[]`) y los elementos se separan por comas. Aquí tienes un ejemplo de cómo crear una lista simple:
````python
# Creación de una lista vacía
lista_vacia = []

# Creación de una lista con elementos
numeros = [1, 2, 3, 4, 5]
nombres = ["Juan", "María", "Luisa"]
mezclada = [1, "dos", 3.0, [4, 5]]
````
En el primer ejemplo, hemos creado una lista vacía llamada lista_vacia. En los siguientes ejemplos, hemos creado listas con diferentes tipos de elementos.

### Acceso a los elementos de una lista
Puedes acceder a los elementos de una lista utilizando índices. Los índices en Python comienzan en 0, lo que significa que el primer elemento tiene un índice de 0,
el segundo tiene un índice de 1, y así sucesivamente. Aquí tienes algunos ejemplos:
````python
numeros = [1, 2, 3, 4, 5]
print(numeros[0])  # Imprime el primer elemento: 1
print(numeros[2])  # Imprime el tercer elemento: 3

nombres = ["Juan", "María", "Luisa"]
print(nombres[1])  # Imprime el segundo elemento: María

mezclada = [1, "dos", 3.0, [4, 5]]
print(mezclada[3])  # Imprime la lista [4, 5]
````

### Modificación de elementos en una lista
Las listas en Python son mutables, lo que significa que puedes modificar sus elementos después de haber creado la lista. Para modificar un elemento específico,
simplemente asigna un nuevo valor a ese elemento utilizando su índice. Aquí tienes un ejemplo:
```Python
numeros = [1, 2, 3, 4, 5]
numeros[2] = 10
print(numeros)  # Imprime [1, 2, 10, 4, 5]
```
En este ejemplo, hemos modificado el tercer elemento de la lista numeros y le hemos asignado el valor 10.

### Operaciones comunes con listas
Existen muchas operaciones útiles que puedes realizar con las listas en Python. Aquí hay algunos ejemplos:

#### Obtener la longitud de una lista
Puedes usar la función `len()` para obtener la longitud de una lista, es decir, el número de elementos que contiene.
```python
numeros = [1, 2, 3, 4, 5]
print(len(numeros))  # Imprime 5
```
#### Agregar elementos a una lista
Puedes agregar elementos a una lista utilizando el método `append()`. Este método agrega un elemento al final de la lista.
````python
numeros = [1, 2, 3]
numeros.append(4)
print(numeros)  # Imprime [1, 2, 3, 4]
````
#### Eliminar elementos de una lista
Existen diferentes formas de eliminar elementos de una lista en Python. Aquí hay dos métodos comunes:
- El método `remove()` elimina la primera aparición de un elemento específico en la lista.
```python
numeros = [1, 2, 3, 4, 5]
numeros.remove(3)
print(numeros)  # Imprime [1, 2, 4, 5]
```
- El método `pop()` elimina el elemento en un índice específico y devuelve su valor. Si no se proporciona un índice, elimina el último elemento de la lista.
```python
numeros = [1, 2, 3, 4, 5]
elemento = numeros.pop(2)
print(numeros)  # Imprime [1, 2, 4, 5]
print(elemento)  # Imprime 3
```
#### Ordenar una lista
Puedes ordenar una lista en orden ascendente utilizando el método `sort()`.
````python
numeros = [5, 2, 4, 1, 3]
numeros.sort()
print(numeros)  # Imprime [1, 2, 3, 4, 5]
````
Si deseas ordenar la lista en orden descendente, puedes utilizar el argumento `reverse=True` en el método `sort()`.

#### Concatenar listas
Puedes combinar dos listas utilizando el operador de concatenación `(+)`.
```python
numeros1 = [1, 2, 3]
numeros2 = [4, 5, 6]
concatenada = numeros1 + numeros2
print(concatenada)  # Imprime [1, 2, 3, 4, 5, 6]
```

### Ejercicios
- Escribe un programa que solicite al usuario ingresar una lista de números separados por comas. Luego, imprime el número más grande de la lista.
- Escribe una función llamada eliminar_duplicados que reciba una lista como parámetro y devuelva una nueva lista que contenga los elementos de la lista original sin duplicados. Prueba tu función con diferentes listas.
- Escribe un programa que tome una lista de palabras y devuelva una lista que contenga las mismas palabras, pero en orden inverso. Por ejemplo, si la lista original es ["Hola", "mundo", "Python"], la lista invertida sería ["Python", "mundo", "Hola"].
- Escribe una función llamada contar_elementos que reciba una lista como parámetro y devuelva un diccionario que contenga cada elemento de la lista como clave y su conteo como valor. Por ejemplo, si la lista es ["a", "b", "a", "c", "b", "a"], el diccionario resultante sería {"a": 3, "b": 2, "c": 1}.
- Escribe una función llamada suma_elementos que reciba una lista de números como parámetro y devuelva la suma de todos los elementos. Prueba tu función con diferentes listas.
- Escribe un programa que tome una lista de nombres y los ordene alfabéticamente de forma ascendente. Imprime la lista ordenada.
- Escribe una función llamada buscar_elemento que reciba una lista y un elemento como parámetros, y devuelva True si el elemento se encuentra en la lista, o False en caso contrario.

Estos ejercicios te ayudarán a practicar diferentes operaciones con listas y fortalecer tu comprensión de los conceptos abordados. ¡No dudes en preguntar si tienes alguna duda o necesitas más ejemplos!

