<p>lenguaje de programación fácil de leer que permite asignación de variables, operaciones matemáticas, condicionales y manipulaciones.</p>

-------------------------------------------------------------------------------

**Funciones y ayuda**
Las funciones son bloques de código que realizan tareas específicas cuando se llaman, mientras que la ayuda es la documentación disponible para ayudar a los programadores a entender cómo usarlas

```python
def sumar(a, b):
    return a + b

resultado = sumar(3, 5)

print("El resultado de la suma es:", resultado)

help(sumar)
```

**Boolean y condicionales**
En Python, True y False son palabras clave que representan los valores verdadero y falso en bolean. Los condicionales if-else se usan para tomar decisiones basadas en valores booleanos. Los operadores lógicos and, or y not se usan para combinar valores booleanos y crear expresiones lógicas más complejas.

```python
es_verano = True

if es_verano:
    print("Es verano, hace calor.")
else:
    print("No es verano, hace frío.")
```

**listas**
secuencias ordenadas de valores que pueden ser modificadas e indexadas tambien ofrecen funciones útiles para poder modificar o manipulas

```python
numeros = [1, 2, 3, 4, 5]
print(numeros)

primer_elemento = numeros[0]
print("Primer elemento:", primer_elemento)

ultimo_elemento = numeros[-1]
print("Último elemento:", ultimo_elemento)

numeros[2] = 10
print(numeros)

numeros.append(6)
print(numeros)
```

**Bucles y compresión**
los bucles FOR y WHILE repiten el codigo de manera determinada y las compresiones de listas permiten condensar bucles y condicionales  
**Bucles**

```python

for i in range(1, 6):
    print(i)
```


**Compresión**

```python
# Comprensión de listas para obtener los cuadrados de los primeros 5 números enteros
cuadrados = [x**2 for x in range(1, 6)]

# Imprimir la lista resultante
print(cuadrados)
```

**strings y diccionarios**
las cadenas son flexibles soportan múltiples métodos de manipulación son muy útiles para organizar datos 
```python
# Ejemplo de manipulación de strings
frase = "Hola, este es un ejemplo de string en Python!"

# Obtener la longitud de la frase
longitud = len(frase)
print("Longitud:", longitud)

# Convertir a mayúsculas
mayusculas = frase.upper()
print("Mayúsculas:", mayusculas)

# Convertir a minúsculas
minusculas = frase.lower()
print("Minúsculas:", minusculas)

# Reemplazar una parte del string
reemplazo = frase.replace("ejemplo", "caso")
print("Reemplazo:", reemplazo)

# Dividir el string en una lista usando un separador
palabras = frase.split(" ")
print("Palabras:", palabras)
```

2. Trabajando con diccionarios:

```python
# Ejemplo de diccionario
persona = {
    "nombre": "Juan",
    "edad": 30,
    "profesion": "Ingeniero",
    "ciudad": "Madrid"
}

# Acceder a un valor por clave
print("Nombre:", persona["nombre"])
print("Edad:", persona["edad"])

# Agregar una nueva clave-valor
persona["email"] = "juan@example.com"

# Verificar si una clave existe en el diccionario
if "ciudad" in persona:
    print("Ciudad:", persona["ciudad"])

# Obtener todas las claves del diccionario
claves = persona.keys()
print("Claves:", claves)

# Obtener todos los valores del diccionario
valores = persona.values()
print("Valores:", valores)
```


**trabajando con librerías externas**
Una biblioteca externa es un conjunto de código que se puede usar en un programa de Python. Las bibliotecas externas se pueden usar para agregar nuevas funciones a un programa, o para simplificar la escritura de código.
Para usar una biblioteca externa en un programa de Python, debe instalar la biblioteca primero. La mayoría de las bibliotecas externas están disponibles a través del administrador de paquetes de Python, pip. Para instalar una biblioteca con pip, use el comando `pip install <nombre de la biblioteca>.

