# MongoDB
Apuntes curso Mongo DB

**¿Qué es Mongo?**

Es un SGBD NoSQL (no usa el modelo relacional). Orientado a documentos, almacena en  formato JSON,
podemos hacer consultas con lenguajes como JS (nativa) y python.
Los docuemntos se agrupan en colecciones, se tienen esquemas dinámicos, se tiene acceso rápido a la información.

Ranking de bases de datos: https://db-engines.com/en/ranking

Testear el puerto libre para mongo db: 
http://portquiz.net:27017

Usar base de datos remot Atlas para práctica
Nos conectamos desde mongo compass a la siguiente dirección

Hostname: cluster0-shard-00-00-jxeqq.mongodb.net
Authentication: Username / Password
Username: m001-student
Password: m001-mongodb-basics
Replica Set Name: Cluster0-shard-0
Read Preference: Primary Preferred

## Conceptos NoSQL

Base de datos -> Agrupa colecciones usadas para una aplicación
Colección -> Agrupa documentos similares
Documento -> Guarda los JSONs

Espacio Nombres: para referirinos NOMBREBASEDATOS.NOMBRECOLECCIÓN, ejemplo: Empresa.Usuarios

Cada documento se identifica por su _id

### Usando Mongo Compass

Permite visualizar las bases de datos, sus datos operaciones CRUD de los objetos. Schema permite analizar y presentar un pequeño resumen de los datos. No olvidar que el schema es solo tomado a partir de una muestra. Este schema me permite hacer una análisis rápido de los datos, puedo usar los filtros en formato {clave: valor}

### Tipos de datos

1. Cadena de caracteres (string)
2. Enteros (int32)
3. Decimales (double)
4. Fechas (dates)
5. Documentos (object document)
6. Vectores (array)
7. Sistemas de coordenadas espaciales.


Ejemplo de visualización en Schema
![schema](/imgs/schema.PNG)