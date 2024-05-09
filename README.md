EXAMEN 32 - EVALUACIÓN DE PROGRAMACIÓN
08/05/2024


1.- Desde una aplicación Java, utilizando un conector JDBC contra MariaDB, se deberá crear una base de datos relacional llamada ClinicaVetBD que contenga tres tablas:

De las especialidades se debe almacenar su identificador (clave primaria) y su nombre.

Sobre los veterinarios se deberá almacenar su DNI (clave primaria), nombre, edad, dirección, sueldo mensual, la especialidad a la que se dedica y la fecha de contratación.

En cuanto a las mascotas, se almacenará su identificador (clave primaria), nombre, especie (perro, gato, ave, exótico), raza, fecha de nacimiento, fecha de registro en la plataforma y el veterinario asignado (clave foránea).

Un veterinario puede tener asignadas varias mascotas.
Una mascota solo puede estar asignada a un veterinario.

Puntuación por jerarquía de clases: 1 punto.

Por último, desarrolla un programa que realice lo siguiente:

Creación de la base de datos (si no existe).

Inserción de nuevas filas. (2 puntos)
Inserción de un nuevo Veterinario.
Inserción de una nueva Mascota.

Borrado de filas. (1.5 puntos)
Borrado de una mascota.
Borrado de un veterinario (se eliminan las mascotas asignadas).




Consultas. (3 puntos)
Introduciendo el nombre de un veterinario, visualice los datos de sus mascotas.
Introduciendo el nombre y la especie de una mascota, visualice el nombre del veterinario y su antigüedad en la clínica.
Exportar a un fichero de texto los datos de aquellos veterinarios que tengan un salario superior a 2.200€, y los datos de las mascotas que tienen asignadas.

Modificaciones. (2.5 puntos)
o Introduciendo el DNI de un veterinario, modificar su salario.
o Introduciendo el nombre y la especie de una mascota, modificar su veterinario asignado.
Salir.
