Esquemas planteados con 'MongoDB'. Los archivos .txt contienen las instrucciones para construir las BBDD línea
a línea. Los directorios homónimos ('Optica', 'Pizzeria', 'YouTube' y 'Spotify') contienen el volcado de datos
de sendas bases de datos ya construidas. Este volcado se realizó desde la línea de comandos (directorio 'bin')
mediante la instrucción
  'mongodump -d <database_name> -o <directory_backup>'
Pueden importarse las bases de datos, también desde la línea de comandos en 'bin', con la instrucción
  'mongorestore -d <database_name> <directory_backup>'