# GreatX Labs

Bienvenido a la organización de GreatX Labs. Aquí se encuentra el código fuente de nuestros proyectos principales, sistemas y demos técnicas.

## Proyectos

### Ikaros

Ikaros es un sistema de relevo de información y gestión basada en roles para misiones espaciales.

- [**ikaros-server**](https://github.com/GreatXLabs/ikaros-server) - Backend desarrollado en Java y Spring. Incluye un protocolo TCP propio y control de acceso por roles (RRHH, Coordinador, Asignador, Registrador, Jefe). En la primera entrega la persistencia se realizó sobre MariaDB; a partir de la segunda entrega se migró a persistencia en archivos JSON, manejando la concurrencia de forma propia.
- [**ikaros-client**](https://github.com/GreatXLabs/ikaros-client) - Frontend en React (JavaScript) y gateway en Spring Boot para interactuar con el sistema Ikaros: gestión de misiones espaciales, tripulación, eventos y cuentas con control de acceso por roles.

### Demos y otros

- [**java-mutex-concurrency-demo**](https://github.com/GreatXLabs/java-mutex-concurrency-demo) - Comparación visual sobre condiciones de carrera y su protección usando Mutex (Semáforos) en Java.
- [**frontend-trust-issues**](https://github.com/GreatXLabs/frontend-trust-issues) - Demo interactiva en TypeScript que expone por qué validar datos únicamente en el frontend es inseguro, mostrando cómo dicha validación puede evadirse fácilmente y por qué es necesaria la doble verificación (cliente + servidor).
- [**nge**](https://github.com/GreatXLabs/nge) - Generador de fondos de galaxias en React y Three.js, con panel de control para ajustar parámetros (brazos, dispersión, nebulosas, campo de estrellas), sistema de presets y exportación. Se usa para producir los fondos animados del frontend del sistema.
- [**PruebaArchivosIkaros**](https://github.com/GreatXLabs/PruebaArchivosIkaros) - Repositorio de pruebas para la implementación de persistencia en archivos dentro de Ikaros, previo a su integración en `ikaros-server`.

## Stack Tecnológico

La mayor parte de nuestro desarrollo se basa en:

- **Backend:** Java, Spring, persistencia en archivos JSON (anteriormente MariaDB en la primera entrega de Ikaros)
- **Frontend:** JavaScript, TypeScript, React
