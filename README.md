Proyecto: Tabla de Usuarios

Este proyecto consiste en mostrar una tabla de usuarios con los campos Id usuario, Código de usuario, Nombre de usuario, Contraseña, Fecha de alta, Activo Si o No. Además, se pueden ordenar y filtrar por cada una de las columnas.
Tecnologías utilizadas

    Node.js
    Express.js
    Cors
    MySQL
    Dotenv
    Nodemon
    React
    React-Bootstrap-Table
    Hooks: useState, useEffect

Instrucciones para correr el proyecto
Requisitos previos

    Node.js instalado en tu ordenador
    npm instalado en tu ordenador
    Datos de conexión de la base de datos

id INT(11) AUTO_INCREMENT PRIMARY KEY,
codigo_usuario VARCHAR(50),
nombre_usuario VARCHAR(255),
contrasena VARCHAR(255),
fecha_alta DATETIME,
activo BOOLEAN

Pasos para correr el proyecto

    Clona el repositorio .
    Abre una terminal.
    Instala las dependencias con el comando npm install.
    Crea un archivo .env en la carpeta backend con los datos de conexión de la base de datos

    Corre el servidor con el comando npm start.
    Clona el repositorio 
    Abre una terminal .
    Instala las dependencias con el comando npm install.
    Corre el cliente con el comando npm start.
    Abre tu navegador en http://localhost:3000 y deberías ver la tabla de usuarios.

Mejoras futuras

    Implementar la funcionalidad de agregar, modificar y eliminar usuarios.
    Agregar un sistema de autenticación para acceder a la tabla de usuarios.
    Mejorar la experiencia de usuario.

Feedback sobre este ejercicio

Este ejercicio fue muy útil para aprender a utilizar Node.js y React para construir una aplicación completa. La utilización de las librerías de express, mysql y dotenv para el backend y react-bootstrap-table para el frontend me resultaron muy útiles y sencillas de implementar. En cuanto a las mejoras futuras, creo que podrían enriquecer mucho más el proyecto y hacerlo más completo y funcional. En general, me ha parecido un ejercicio muy práctico y entretenido para poner en práctica los conocimientos adquiridos.