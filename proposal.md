# Propuesta TP DSW: EMPRESA DE LIMPIEZA

## Grupo
### Integrantes
* 47901 - Sinopoli, Martina
* 48038 - Tabini, Azul
* 51207 - Gauna, Santiago
* 48237- Gonzalez, Luciano

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
*Ofrecemos servicios de limpieza integral, desinfecciones y alquiler de hidroelevadores.
Atendemos bancos, oficinas, clínicas, fábricas y espacios al aire libre.
Contamos con productos como lavandina, detergente, papel higiénico y equipos profesionales.
Nuestro equipo incluye personal de limpieza y administrativos capacitados.
El sistema permite gestionar servicios, empleados, horarios y reemplazos.
Optimizamos recursos y presencia mediante programación inteligente y control de stock.*

### Modelo
![image](https://github.com/user-attachments/assets/b6cc0b47-d533-407f-85c7-b1629b4ecc0b)

*https://miro.com/welcomeonboard/MlNyczJJc2Z5Nnp5Zk10VGNYZW0xa1lMTnUwaGR0M1RIUWlubThGdmVmcVAzR1g5K1ZKRzd0dnRrWHVZYmV3b0dUd05yNjFSOG5EcDE1NTdrcEUwZnJYR3NseXhLNzJ2aVQwVzFYaTdLTmx2Q1pIL2N2bXMvdk5ubTFoVmZvODN0R2lncW1vRmFBVnlLcVJzTmdFdlNRPT0hdjE=?share_link_id=4292619785*

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad|
|CRUD dependiente|1. CRUD Habitación {depende de} CRUD Tipo Habitacion<br>2. CRUD Cliente {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de habitaciones filtrado por tipo de habitación, muestra nro y tipo de habitación => detalle CRUD Habitacion<br> 2. Listado de reservas filtrado por rango de fecha, muestra nro de habitación, fecha inicio y fin estadía, estado y nombre del cliente => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|

