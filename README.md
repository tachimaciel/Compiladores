# Compiladores

Autores:
  * Eduardo Maciel
  * Juan Pablo Martinez
  
Analizador Léxico, Sintáctico y traducción al XML para archivos JSON hecho en el lenguaje C

# Windows
Compilación y Ejecución AnLex:
  * gcc anlex.c tablaSimbolos.c -o salida
  * salida.exe fuente.txt
  
Compilación y Ejecución AnSin:
  * gcc ansin.c -o salida
  * salida.exe fuente.txt

Compilación y Ejecución Traductor:
  * gcc trad.c -o salida
  * salida.exe fuente.txt
  
# Linux
Compilación y Ejecución AnLex:
  * gcc anlex.c tablaSimbolos.c -o salida
  * ./anlex fuente.txt

Compilación y Ejecución AnSin:
  * gcc ansin.c -o salida
  * ./salida fuente.txt
  
Compilación y Ejecución Traductor:
  * gcc trad.c -o salida
  * ./salida fuente.txt
