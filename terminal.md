# TERMINAL

## REDIRECCIONES

&gt; : redirección de salida. Crea un fichero nuevo.


&gt;&gt; : doble redirección de S. Anexa un fichero.

&lt; : Redirigir la entrada

&lt;&lt; : Here document

&lt;&lt;&lt; : Here string.

## VARIABLES




##Metacaracteres

$: Dime el valor de una variable
~: Directorio home
.: Directorio actual
..: Directorio de arriba
\* Cualquier secuencia de caracteres
?: Cualquier caracter
[]: Conjunto de selección
' ': Partir en palabras
-- (A veces el fichero que representa)
\\: Secuencia de escape => Criptonita de los metacaracteres
"": QUitar el poner a casi todos los meta menos al $vin opcione
'': quita el poder a todos los metacaracteres.
\#: Comentario


## Otros

#! Shebang: Intérprete con el que hay que ejecutar el archivo
!!: El último comando/mohicano
!\*: Los últimos parámetros
&&: AND
||: OR
!: NOT





#! /bin/bash 

[[ $# -lt 2 ]] && echo "Mete más parámetros" && exit 1
echo $# # Cantidad e parámetros
echo $@ # Todos los parámetros como uno
echo $* # Todos los parámetros por separado.
echo $1
echo $0

echo $(basename $0)




