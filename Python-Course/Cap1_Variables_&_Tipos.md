# Variables y tipos de datos
## Variables
En Python, una variable es un contenedor que almacena un valor. A diferencia de otros lenguajes de programación, no es necesario declarar el tipo de variable en Python,
ya que el tipo se infiere automáticamente según el valor asignado. Para asignar un valor a una variable, utilizamos el signo de igual (=). 

**_Ejemplo:_**
```python
# Asignación de valores a variables
nombre = "Juan"
edad = 25
altura = 1.75
```
En el ejemplo anterior, hemos creado tres variables: `nombre`, `edad` y `altura`. La variable nombre es de tipo `str` (cadena de caracteres) porque hemos asignado un valor entre comillas dobles. 
La variable edad es de tipo `int` (entero) y la variable altura es de tipo `float` (número de punto flotante).

## Tipos de datos en Python
Python proporciona varios tipos de datos incorporados. A continuación, se enumeran los tipos de datos más comunes:

### 1. Enteros (int):
Los enteros son números sin parte decimal. Pueden ser positivos o negativos. Ejemplo:
```python
edad = 25
```
### 2. Números de punto flotante (float):
Los números de punto flotante son números con una parte decimal. Ejemplo:
```python 
altura = 1.75
```
### 3. Cadenas de caracteres (str):
Las cadenas de caracteres son secuencias de caracteres encerradas entre comillas (simples o dobles). Ejemplo:
```python
nombre = "Juan"
```
### 4. Booleanos (bool):
Los booleanos son valores que representan verdadero (True) o falso (False). Ejemplo:
```python
es_mayor_de_edad = True
```
### 5. Listas (list):
Las listas son colecciones ordenadas y modificables de elementos. Pueden contener diferentes tipos de datos. Ejemplo:
```python
numeros = [1, 2, 3, 4, 5]
```
### 6. Tuplas (tuple):
Las tuplas son colecciones ordenadas e inmutables de elementos. Al igual que las listas, pueden contener diferentes tipos de datos. Ejemplo:
```python
coordenadas = (10, 20)
```
### 7. Conjuntos (set):
Los conjuntos son colecciones no ordenadas de elementos únicos. Ejemplo:
```python
colores = {"rojo", "verde", "azul"}
```
### 8. Diccionarios (dict):
Los diccionarios son colecciones de pares clave-valor. Cada valor se accede a través de una clave única. Ejemplo:
```python
persona = {"nombre": "Juan", "edad": 25, "altura": 1.75}
```
Estos son solo algunos de los tipos de datos más comunes en Python. Hay otros tipos de datos especializados y también se pueden crear tipos de datos personalizados.



