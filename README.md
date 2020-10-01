# Proyecto001

**Prueba sobre TypeScript**

Hemos creado una carpeta del Proyecto donde hemos instalado el git init.
Una vez instalado tenemos el  archivo README.MD y hemos creado
el tsconfig.json del typescript con tsc --init.
Después hemos creado una carpeta doc donde estarán los ejercicios
del proyecto cuyo archivo son .ts(typescript).
A continuación creamos otra carpeta llamada dist que es donde estarán
los archivos .js (javascript). Después creamos el archivo .gitignore
donde estarán las carpetas ocultas en nuestro caso escribiremos en ese
archivo el nombre de la carpeta dist que es la que estará oculta.
A continuación nos iremos al archivo tsconfig.json y descomentamos y 
escribimos  "outDir": "./dist",  a tsconfig.json para controlar los 
archivos  transpilados de ts a js, que para compilar usaré: tsc -w.
Para ejecutar un archivo js: node dist/ejercicio001