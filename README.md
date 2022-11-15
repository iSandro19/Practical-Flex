# Practical-Flex | Óscar Alejandro Manteiga Seoane

## Desarrollo, funcionamiento y peculiaridades

### Desarrollo en 3 etapas

La primera de ellas será la composición del código de la práctica. En esta parte se edita el fichero practica1.l, que es el centro del propio ejercicio. Para hacer el desarrollo lo que se hizo fue buscar que nos proporcionase un correcto comportamiento ante tests básicos que se pasaban por terminal para cada uno de los 6 apartados de implementación. Lo primero que se hizo fue el reconocimiento de caracteres y palabras, para después incorporar el reconocimiento de frases (algo sencillo al solo tener que contar los puntos). Finalmente se desarrolló el reconocimiento de palabras que están completamente en minúscula, mayúscula o números. Esto se hizo a la vez ya que solo se tuvo que incorporar la misma idea pero cambiando los rangos de caracteres dentro de la regla.

La segunda parte del desarrollo fue la implementación de test más complejos que se centrasen en partes clave. Se hicieron 9 tests con un script que compila la práctica, ejecuta los test y muestra por terminal si han sido satisfactorios o no. Esto permitió encontrar fallos en la implementación (como por ejemplo, contar "!!!" como palabra) y arreglarlos fácilmente a la vez que se aseguraba que no se rompía nada de lo que funcionaba con anterioridad.

La última fase fue la redacción de esta pequeña memoria para ilustrar el desarrollo de la práctica.

### Funcionamiento

El funcionamiento de la misma es sencillo. Con el programa en FLEX detectamos todos los caracteres de una cadena de texto o fichero (excluyendo los espacios en blanco, tabulaciones y retornos de carro), todas las palabras (letras en minúscula, mayúscula o números separadas entre si), todas las palabras que sean 100% en minúscula, mayúscula y numéricas y todas las frases (contabilizamos los puntos que existen en el fichero).
Para ejecutarla basta con ejecutar make all y se compilará el programa para después ejecutar todos los test. Si queremos ejecutarlo uno por uno y ver el input del programa tendremos que hacer make runX (siendo X el número de test a ejecutar).

### Contenido

- practica1.l: programa en flex.
- practica1.txt: memoria (este archivo).
- Makefile: archivo para compilar el programa.
- test: carpeta con los archivos de testeo.
  - test/testX.txt: texto para procesar con el programa.
  - test/testXrtdo: resultado del programa.
  - test/testXrtdo.txt: resultado esperado.
  
---

Óscar Alejandro Manteiga Seoane | PL 2022/2023
