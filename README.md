# Deber Arboles - Biblioteca FISEI
Catalogo con arbol general (Biblioteca > Areas > Estantes) y ABB de libros por estante.

## Compilar y ejecutar
javac -encoding UTF-8 -d out (Get-ChildItem -Path src -Recurse -Filter *.java).FullName
java -cp out app.Main
java -cp out app.PruebasBiblioteca
