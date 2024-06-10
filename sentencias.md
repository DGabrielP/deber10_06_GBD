# Sentencias SQL y Capturas

## 1. Obtener la edad promedio de los miembros:
### Sentencia
SELECT COUNT(*) 
FROM Product 
WHERE category = 'Audio';

![Edad promedio](capturas/1_edad.PNG)

## 2. Obtener la edad mínima de los miembros:
### Sentencia
SELECT COUNT(*) 
FROM Client 
WHERE city = 'Cuenca';

![Edad minima](capturas/2_edad.PNG)

## 3. Obtener el número total de registros asistidos:
### Sentencia
SELECT COUNT(*) 
FROM Product 
WHERE price BETWEEN 500 AND 1000;

![Registros asistidos](capturas/3_registros.PNG)

## 4. Obtener el número total de asistentes a todas las conferencias:
### Sentencia
SELECT * 
FROM Client 
WHERE city = 'Quito' AND type_of_client = 'A';

![Total asistentes](capturas/4_asistentes.PNG)

## 5. Obtener el número total de eventos por cada ciudad:
SELECT * 
FROM Product 
WHERE category = 'Audio' AND price > 500;

![Total eventos por ciudad](capturas/5_ciudad.PNG)

## 6. Obtener el número de registros por cada miembro:
### Sentencia

SELECT * 
FROM Product 
WHERE year_of_product = 2022 AND country_of_origin = 'China';

![Registros por cada miembro](capturas/6_miembro.PNG)

## 7. Obtener el número de registros por cada conferencia:
SELECT * 
FROM Client 
WHERE fullname LIKE 'J%';

![Registros por cada conferencia](capturas/7_conference.PNG)









