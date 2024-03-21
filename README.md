# Airbnb Clone (Proyecto Fullstack) - Spring Boot 3, Angular 17, PrimeNG, PostgreSQL, Auth0 (2024) - Backend

Backend en Spring Boot del clon de Airbnb.

## Características Principales:
- 📅 Gestión de reservas para viajeros
- 🏠 Gestión de reservas para propietarios
- 🔍 Búsqueda de viviendas por criterios (ubicación, fecha, número de huéspedes, camas, etc.)
- 🔐 Autenticación y autorización (gestión de roles) con Auth0 (OAuth2)
- 🏢 Diseño orientado al dominio (DDD)

## Uso

### Requisitos previos:
- JDK 21
- PostgreSQL
- IDE (VSCode, IntelliJ)


### Repositorio del Frontend:
[Angular FrontEnd](https://github.com/miltonAlan/airbnb-enhanced-clone-frontend)


### Despliegue
#### Maven
``./mvnw spring-boot:run  -Dspring-boot.run.arguments="--AUTH0_CLIENT_ID=<client-id> --AUTH0_CLIENT_SECRET=<client-secret>"``

#### IntelliJ
Agrega las variables de entorno en IntelliJ y luego ejecuta el proyecto.
