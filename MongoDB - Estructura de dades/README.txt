Esquemas planteados con 'MongoDB'. Los archivos .txt contienen las instrucciones para construir las BBDD l�nea
a l�nea. Los directorios hom�nimos ('Optica', 'Pizzeria', 'YouTube' y 'Spotify') contienen el volcado de datos
de sendas bases de datos ya construidas. Este volcado se realiz� desde la l�nea de comandos (directorio 'bin')
mediante la instrucci�n
  'mongodump -d <database_name> -o <directory_backup>'
Pueden importarse las bases de datos, tambi�n desde la l�nea de comandos en 'bin', con la instrucci�n
  'mongorestore -d <database_name> <directory_backup>'