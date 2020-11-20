
# Linea Python y DS
## Reto: Comprensión de listas
### Descripción:
En el mundo de la ciencia de datos cuando se está trabajando con texto es muy común que sea necesario hacer una
limpieza de datos. Generalmente la limpieza de datos consiste en definir un formato estándar a todos los datos 
con los que estamos trabajando y remover datos que no representan importancia.

En este caso vamos a hacer uso de una funcionalidad muy particular de python llamada comprehension  de listas 
que nos será util para procesar todas las palabras en un texto.

### Objetivo:
Completar la función `limpiar_stop_words` para que remueva las palabras que se encuentren presentes en la 
lista`stopwords` ademas de convertir todo el texto a minúscula.

##### Input: 
Una cadena de texto con palabras a remover (stopwords) dentro de el y sin un formato estándar

#### Output:
La cadena de texto completamente en minúsculas y sin las palabras "stopwords"

### Comprobar resultados:
Para comprobar los resultados puedes ejecutar el script main.py usando:
```shell script
$ python main.py
```
Y deberías de ver los siguiente:
```shell script
Tu limpiador de texto funciona!. FELICITACIONES!!!
```