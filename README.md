![WhatsApp Image 2022-03-06 at 4 09 03 PM](https://user-images.githubusercontent.com/76496647/156947374-e31507db-d1a0-4408-990d-408a1e7c61dd.jpeg)

# Encriptador de transacciones
# Integrantes Del Grupo
  - Mateo Geronimo Ortiz Cruzate
  - Sergio Hernando Baron Rivera
  - Carlos Alberto Barrera Cadena

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

# ✏OBJETIVO
Diseñar un programa que proporcione mayor seguridad y privacidad a la información de transacciones bancarias mediante el uso de la encriptación.

# ✏CONJUNTO DE DATOS:
[DatosOrdenados.xlsx](https://github.com/CarlosBarrera21/Proyecto-Matematicas-Discretas/files/8248838/DatosOrdenados.xlsx)

# ✏Instrucciones para reproducir el proyecto:
1- Descargar el conjunto de datos dado
2- Abrir el Google Colab que se encuentra en la parte superior de este repositorio
3- Subir el archivo excel previamente descargado
![image](https://user-images.githubusercontent.com/93603188/158271490-a08508d1-1c13-402a-a40c-716b811c894a.png)
4-Ejecutar las celdas en orden descendente
5-
6-

# ✏VIDEO EXPLICATIVO:
https://www.youtube.com/watch?v=tFWOAoO5aLg


# ✏REFERENCIAS:

 - Encriptación de Contraseñas en Python 🔐 | 3 Formas de Cifrar y Desencriptar Textos y Passwords ✅. (2021, 2 julio). YouTube. Recuperado 2 de marzo de 2022, de https://www.youtube.com/watch?v=mgDIP46LEUo&feature=youtu.be
 - C. (2019, 21 marzo). Cifrado Asimétrico con Python. YouTube. Recuperado 2 de marzo de 2022, deC. (2019, 21 marzo). Cifrado Asimétrico con Python. YouTube. Recuperado 2 de marzo de 2022, de https://www.youtube.com/watch?v=MkdlDwqvUHk&feature=youtu.be
 - Werkzeug — Werkzeug Documentation (2.0.x). (s. f.). Werkzeug Documentation (2.0.x). Recuperado 2 de marzo de 2022, de https://werkzeug.palletsprojects.com/en/2.0.x/
 -  PyCrypto API Documentation. (2012). PyCrypto API Documentation. Recuperado 05–24, de https://www.dlitz.net/software/pycrypto/api/2.6/
 -  Gonzales Gouveia, R. J. (2020, 3 diciembre). Cómo exportar data frames de pandas a csv o excel en python.Recuperado 6 de marzo de 2022, de https://gonzalezgouveia.com/como-exportar-data-frames-de-pandas-a-csv-o-excel-en-python/
 -  Neobank Transactions. (2021, 29 noviembre). Kaggle. Recuperado 24 de marzo de 2022, de https://www.kaggle.com/arshi2nlp/neobank-transactions

