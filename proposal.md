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
|CRUD simple|1. CRUD Producto<br>2. CRUD Empresas<br>3. CRUD Empleado<br>4. CRUD Maquina|
|CRUD dependiente|1. CRUD Servicio {depende de} CRUD Tipo Servicio<br>2. CRUD Cliente {depende de} CRUD Empresa|
|Listado<br>+<br>detalle| 1. Listado de Servicios que se brindan en la semana, con los empleados asignados.<br> 2. Listado de empleados que tengan horas libres y traer los servicios asignados si tienen|
|CUU/Epic|1. Venta de un servicio<br>2. Programar Horarios de servicio|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Venta de un servicio<br>2. Programar Horarios de servicio<br>3. Gestionar reemplazos<br>4. Gestionar stock de productos|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1.  <br>2. |
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de Venta|
|Otros|1. Envío de notifiacion al empleado que se le asignó un nuevo servicio<br>2. Conectar api de google maps para poder aconsejar y asignar el empleado más cercano al lugar donde se prestará un servicio|

