# Encriptador de transacciones
# Integrantes Del Grupo
  - Mateo Geronimo Ortiz Cruzate
  - Sergio Hernando Baron Rivera
  - Carlos Alberto Barrera Cadena

# ✏OBJETIVO
Diseñar un programa que proporcione mayor seguridad y privacidad a la información de transacciones bancarias mediante el uso de la encriptación.

# ✏RESUMEN:
Un banco planea implementar unos nuevos cajeros en sus principales sucursales para esto contrata unos ingenieros de sistemas que busquen la manera 
mas segura de proteger la base de datos dentro de estos cajeros.
Los datos que obtienen los bancos y cajeros automaticos no suelen ser del todo seguros, se propone cambiar esto haciendo uso de la encriptación,
de esta manera se puede garantizar la seguridad y privacidad 
de la informacion de los datos de los usuarios que utilizen el cajero y sentirse seguros usando el mismo.

Para poder lograr el cometido crearemos un algoritmo en python que nos permita
encriptar las distintas tuplas de una base de datos donde obtendremos
los datos a encriptar (Numero de identificación, tipo de transacción, monto de la transacción, fecha, balance)
Nota: el tipo de la transacción puede ser retiro o ingreso
Para ello usaremos dos formas de encriptación que se le aplicarán a cada elemento de la tupla, los métodos a usar son: 
Cifrado RSA para los elementos que únicamente contienen números y usaremos el cifrado Sha256 para el resto de elementos de la tupla que contiene
una mezcla entre numeros,letras y simbolos.


# ✏REFERENCIAS:

 - Encriptación de Contraseñas en Python 🔐 | 3 Formas de Cifrar y Desencriptar Textos y Passwords ✅. (2021, 2 julio). YouTube. Recuperado 2 de marzo de 2022, de https://www.youtube.com/watch?v=mgDIP46LEUo&feature=youtu.be
 - C. (2019, 21 marzo). Cifrado Asimétrico con Python. YouTube. Recuperado 2 de marzo de 2022, deC. (2019, 21 marzo). Cifrado Asimétrico con Python. YouTube. Recuperado 2 de marzo de 2022, de https://www.youtube.com/watch?v=MkdlDwqvUHk&feature=youtu.be
 - Werkzeug — Werkzeug Documentation (2.0.x). (s. f.). Werkzeug Documentation (2.0.x). Recuperado 2 de marzo de 2022, de https://werkzeug.palletsprojects.com/en/2.0.x/
 -  PyCrypto API Documentation. (2012). PyCrypto API Documentation. Recuperado 05–24, de https://www.dlitz.net/software/pycrypto/api/2.6/

