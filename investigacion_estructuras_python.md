Listas

Las listas en Python son secuencias ordenadas y mutables de elementos que pueden contener datos de diferentes tipos. Proporcionan una manera eficiente de almacenar y manipular datos, permitiendo realizar operaciones como acceder a elementos por índice, agregar, eliminar o modificar elementos.

Principales características de las listas en Python

- Mutabilidad
- Acceso por indice
- Diversidad de tipos

Métodos para las listas

Las listas tienen métodos propios para facilitarte el manejo de ellas mismas.


Tuplas

Las tuplas son secuencias ordenadas e inmutables de elementos, lo que significa que una vez creadas, sus elementos no pueden ser modificados. A pesar de esta limitación, las tuplas son útiles cuando se requiere mantener un conjunto de datos estático o cuando se desea evitar cambios accidentales en la estructura de los datos. 

Principales características de las tuplas en Python

- Características clave de los diccionarios
Inmutabilidad
- Acceso por indice
- Diversidad de tipos
- Datos duplicados
- Resumen

Lección 3 - Colecciones (Parte 2)

Diccionarios

Continuando con la lección de colecciones, ahora nos centraremos en los diccionarios ya que ellos son colecciones no ordenadas de pares clave-valor. A diferencia de las listas y tuplas, que se acceden por índice numérico, los diccionarios utilizan claves únicas para acceder a sus valores.

Dict = {

"clave": valor,

"clave": valor,

"clave": valor...

}

Es fundamental que los domines porque su estructura es muy similar al manejo de objetos en otros lenguajes de programación, por ejemplo, imagina que quieres guardar tu información personal en Python, tu nombre, edad, dirección, etc. Puedes usar un diccionario para esto.

Características clave de los diccionarios

Claves Únicas:

Cada clave en un diccionario debe ser única. Si intentas usar la misma clave más de una vez, el valor más reciente sobrescribirá al anterior.

Claves Inmutables

Las claves deben ser de un tipo de datos inmutable, como cadenas, números o tuplas (con elementos inmutables). Esto se debe a que las claves deben ser únicas y no pueden cambiarse una vez establecidas.

Valores Mutables

Los valores en un diccionario pueden ser de cualquier tipo de datos, incluyendo listas, otros diccionarios, etc. 

Métodos útiles

Cada uno de esos métodos puede utilizar un ciclo for para iterar sobre ellos. dándote una facilidad en el manejo de los diccionarios.

keys()

Devuelve todas las claves del diccionario en un dict_keys, para facilitar su posterior manejo te recomiendo convertirlo en una lista

Item()

Devuelve una dict_items ,esta colección contiene una lista con tuplas que contienen el par clave-valor, como ya sabes la tupla no puede ser modificada 

Values()

Devuelve todos los valores del diccionario en un dict_values

get(clave, valor_por_defecto)

Retorna el valor asociado a la clave si existe, de lo contrario retorna valor_por_defecto, es muy útil ya que cuando intentamos acceder a una clave que no existe nos arroja una excepción, en cambio con este método controlamos dicha excepción
