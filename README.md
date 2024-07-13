#  ForoHub WRH3 
¡Bienvenido a ForoHub WRH3! Este programa es un API que te permite Realizar diferentes solicitudes REST:

Iniciar Sesion
Registrar un topico
Actualizar un Topico
Eliminar un topico
Listar topicos

# Autorización
La API requiere autorización mediante tokens JWT para acceder a ciertas funciones.

# Tecnologías Utilizadas
Java 🔧
Maven 🔧
Spring Boot 🔧
Spring Data JPA 🔧
MySQL 🔧
JWT (JSON Web Tokens) 🔧
#🌟 Endpoints
Tópicos (topico-controller)
Actualizar un tópico

PUT /topico/actualizar
Body: DatosActualizarTopico
Crear un nuevo tópico

POST /topico
Body: DatosRegistroTopico
Listar todos los tópicos

GET /topico/listar
Respuesta: List<PageDatosListadoTopico>
Dar de alta un tópico

GET /topico/alta/{id}
Eliminar un tópico (lógico)

DELETE /topico/eliminar/{id}
Autenticación (autenticacion-controller)
Iniciar sesión (login)
POST /login
Body: DatosAutenticacionUsuario
Respuesta: DatosJWTtoken
