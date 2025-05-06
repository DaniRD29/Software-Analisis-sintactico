# Software-Analisis-sintactico

Hola, el objetivo del siguiente software es lograr comprender como funciona un analizador léxico utilizando la librería PLY con la herramienta lex, se utiliza para dividir el texto de entrada en una colección de tokens especificados por una colección de expresiones regulares reglas.
Para ejecutar el programa, deberemos tener Python y la extensión PLY, y si queremos utilizar un editor de texto como Visual Studio Code, esto con el fin de visualizar y editar el código fuente, en mi caso yo lo ejecutare desde CMD. Entrare a la carpeta y ejecutare el archivo, en mi caso la ruta de mi archivo no está muy lejos por lo que es más sencillo de escribir. 
Cd /WorkPython
/WorkPython py PLY.py
Ya una vez que lo hayamos ejecutado, observaremos que en la salida de la terminal tenemos la clasificación de números, identificadores, palabras claves entre otros elementos, la finalidad de estos es como la librería actúa en dividir los caracteres gracias a las reglas de las expresiones regulares y a los tokens que se han establecido en el código, permitiendo al programa reconocer de forma más fácil lo que está establecido en la variable data. 
Quiero redactar cómo funciona la identificación de palabras clave, la variable constante RESERVED, contiene dichas palabras que son “reservadas para el lenguaje”, por otro lado, la función t_ID(), con ayuda de la expresión regular puede determinar las palabras clave que han sido determinadas anteriormente y los agrega a la lista para su impresión en la pantalla. 

Link de presentación: 
https://youtu.be/zOuEvGqHaAc?si=aAsZb6UQGJo4G_n6 
