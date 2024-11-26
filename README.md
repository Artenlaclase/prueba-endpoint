# Prueba de Endpoint - Proyecto Techxcelerators

Este repositorio contiene una prueba de endpoint desarrollada como parte del proyecto **Techxcelerators** del bootcamp UDD. El código fue implementado por **Raúl Rosales**, desarrollador web, y está diseñado para recibir solicitudes HTTP POST y verificar la validación de datos en el cuerpo de la solicitud.

## Descripción

El endpoint implementado es un servidor básico creado con **Node.js** y **Express.js**. Permite recibir datos como `nombre`, `apellido` y `cohorte`, y responde con mensajes personalizados dependiendo de si los datos enviados son válidos o si faltan valores requeridos.

## Características

- Endpoint principal: `POST /mensaje`
- Validación de datos en el cuerpo de la solicitud.
- Respuestas claras para solicitudes válidas e inválidas.
- Código modular y fácil de ejecutar para pruebas locales.

## Requisitos previos

Antes de comenzar, asegúrate de tener instalado lo siguiente en tu sistema:

- **Node.js** (versión 16 o superior)
- **npm** (incluido con Node.js)

## Instalación

1. **Clona este repositorio**:
   ```bash git clone https://github.com/Artenlaclase/prueba-endpoint.git cd prueba-endpoint ```
2. **Instala las dependencias**:
    ```npm install```
3. **Ejecuta el servidor**:
       ```node index.js```
4. **El servidor estará corriendo en**:
``` http://localhost:3000```

## Uso
Endpoint disponible
POST /mensaje
Descripción: Este endpoint recibe un objeto JSON con los siguientes campos requeridos:

nombre: Nombre del usuario.
apellido: Apellido del usuario.
cohorte: Identificador de cohorte.

## Probar con herramientas
Se recomienda probar el endpoint utilizando herramientas como:
Thunder Client (integrado en VS Code)
Postman
curl


## Contribuciones
Este repositorio forma parte del aprendizaje en el bootcamp UDD y no está destinado para uso en producción. Sin embargo, se agradecen sugerencias y mejoras.

## Autor
Raúl Rosales R.
GitHub

## Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más información.
