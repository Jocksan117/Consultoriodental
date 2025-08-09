# Consultoriodental
"Esta base de datos, muestra un consultorio dental, donde se pueden agregar citas, nombres de doctores, tanto como los mismos pacientes y ver el inventario que esta dentro de la misma sucursal"

En cambio la base de datos se ira actualizando constantemente y agregando mas funciones.

Por el momento la base de datos solo cuenta con los esquemas y tablas ya terminadas.

Posteriormente se le ira agregando:

Reportes.
Roles de seguridad.
Triggers.
Logins.

Todo se ira actualizando y se agregara a la descripcion cada actualizacion y lo que tiene.

Diagrama actualmente de la base de datos.

<img width="1487" height="860" alt="image" src="https://github.com/user-attachments/assets/8ba9f96c-3f0d-4752-b43f-909bd7441e8c" />


Codigo del programa:

"Creacion de la base de datos"
CREATE DATABASE consultorio
Go

USE consultorio
Go

"Creacion de schemas"
CREATE SCHEMA personas;
Go
CREATE SCHEMA citas;
Go
CREATE SCHEMA sucursales;
Go
CREATE SCHEMA inventario;
Go
CREATE SCHEMA clinical;
Go
CREATE SCHEMA trabajadores;
Go
