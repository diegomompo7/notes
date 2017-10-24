# Comados

```

Comando head
Comando head
Comando head
Siempre alerta estás.

```

ls: list files = Muestraun directorio
cd: change director = Cambiar de directorio
mkdir: make dir = Crea un directorio
rm: remove = Quita un directorio
rmdir: remove directory = Quita un directorio (sólo sí está vacío)
rm -rf (**r**ecursivo **f**orce)
mv cambia el nombre o cambia de sitio

- git clone URL: Clonar un repositorio
- git status: Ver un repositorio
- git add . : añadir a repositorio local
- git commit -m "Initial commit"
- git config --global user.email "you@example.com"
- git config --global user.name "Your Name"
- git push
- git add -u (quita repositorios)


seq: secuencia de números

## Comandos para unir

cat: concatenar arcivos en la terminal

paste: unir en vertical

join: combinaciones

## Comandos que dividen

head
tail -2 archivo
tail -f (deja el fichero archivo)
cut: corta vertical : cut -d"  " -f1
split: divide horizontal

1: Herramienta terminal
2: Nucleo de aplicaciones
3: Desarrollo de aplicaciones


## Otras

wget: Descarga de Internet
tr: Translate
-s squeezee
uniq -c: deja filas funicas -c: cuenta
sort ordena -n numerico
bc: calculadora
cal: calendario
touch: crea un fichero o lo actualizafor



cat shk.txt | tr "A-Z" "a-z" | tr -s "\t \n" "\n" | tr -cd "a-z\n" | sort | uniq -c | sort -n |tr -s  " " " " | cut -f3 -d" " | curl dict://dict.org


## Para buscar

grep: Filtran
ed: editor sin ventanas
sed: lo mismo



.n: linea
-c : número de veces.n

find: busca ficheros
xargs: Ejecuta cona argumentos.
which: Donde está un ejecutable.
