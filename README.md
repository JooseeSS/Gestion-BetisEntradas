# Gestion-BetisEntradas
El proyecto consiste en el diseño e implementación de una aplicación de gestión de entradas para los partidos de fútbol que se disputan en el estadio Benito Villamarín, del Real Betis Balompié.
La aplicación permite:

-Gestionar los equipos visitantes contra los que juega el Betis.
-Registrar partidos siempre como local el Betis, desde la temporada 1970/71 hasta 2024/25, con un total de 24 partidos por temporada.
-Registrar zonas del estadio, su capacidad y precios distintos por partido y por zona.
-Registrar socios por temporada con un código exclusivo, que permite acceder gratuitamente a los partidos durante esa temporada o compartir su código con otros para aplicar un 20% de descuento en entradas.
-Permitir la venta de entradas a cualquier persona, aplicando el descuento si se introduce un código válido de socio.
-Controlar las entradas vendidas por partido y por zona, verificando disponibilidad y aforo.

Tecnologías utilizadas:
-Java
-MySQL
-MySQL Workbench / DBeaver
-IDE  Eclipse

Estructura del proyecto:
-Modelo de datos con diseño conceptual, lógico y físico.
-Clases Java para representar entidades como Socio, Partido, Zona, Entrada, PrecioEntrada, Temporada.
-Clases DAO para gestionar las operaciones con la base de datos.
-Clase Main para probar el funcionamiento del sistema.

Estructura de la base de datos:
-La base de datos contiene datos desde la temporada 1970/71 hasta 2024/25.
-Hay 24 partidos por temporada, dos partidos por mes.
-Los equipos visitantes se repiten en todas las temporadas, pero con fechas y horarios diferentes cada año.
-Los socios se registran al inicio de cada temporada.
-Las entradas pueden ser compradas por cualquier persona, pero si se introduce un código de socio válido, se aplica un descuento del 20%.
