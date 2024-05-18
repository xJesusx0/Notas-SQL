# Notas-SQL

## Tipos de datos
- Numericos
  - TINYINT
    Hasta 127
  - SMALLINT
    Hasta 32000
  - MEDIUMINT
    Hasta 8 millones
  - INT
    Hasta 250 millones
  - BIGINT
    Hasta 300 mil millones
  - FLOAT
    Numeros decimales
    
- Alfanumericos
  - CHAR
    255 Caracteres
  - VARCHAR
    65535 Caracteres
  - TEXT
    Textos largos
    
- Fecha y hora
  - DATE
    AA-MM-DD
  - TIME
    HH:MM:SS
  - DATATIME
    AAAA-MM-DD HH:MM:SS
  - TIMESTAMP
    AA-MM-DD HH:MM:SS
  - YEAR
    AA AAAA
## Crear una base de datos
  ```
  mysql> CREATE DATABASE prueba;
  ```

## Ver bases de datos
  ```
  mysql> SHOW DATABASES;
  ```

## Eliminar una base de datos
  ```
  mysql> DROP DATABASE prueba;
  ```

## Crear una tabla
  ```
  CREATE TABLE nombre(Columna1 tipo,Columna2 tipo, ... ,ColumnaN tipo);
  ```
  - Ejemplo
  ```
  CREATE TABLE usuarios (
                          id INT PRIMARY KEY,
                          nombre TEXT NOT NULL
                        );
  ```
    
