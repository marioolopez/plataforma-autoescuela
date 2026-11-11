# Plataforma Web de Autoescuela

## Descripción

Proyecto final del Grado Superior en Desarrollo de Aplicaciones Multiplataforma (DAM), basado en el desarrollo de una aplicación web full stack para la gestión y realización de tests de conducción.

La plataforma tiene como objetivo facilitar el aprendizaje online, permitiendo a los alumnos realizar exámenes y consultar sus resultados de forma flexible. Además, incorpora funcionalidades de administración para gestionar usuarios, asignaturas, preguntas y exámenes.

## Tecnologías utilizadas

**Frontend**
- Angular
- TypeScript
- HTML y CSS
- Angular Router
- HttpClient

**Backend**
- Node.js
- Express.js
- JavaScript
- Sequelize (ORM)
- API REST

**Base de datos**
- MySQL

## Arquitectura y funcionamiento

La aplicación sigue una arquitectura cliente-servidor que separa el frontend, el backend y la persistencia de datos.

**Frontend (Angular)**

La interfaz está desarrollada con Angular y organizada mediante componentes, modelos, servicios y rutas.

Los servicios utilizan HttpClient para realizar peticiones HTTP a los endpoints del backend, permitiendo consultar y gestionar la información de manera dinámica.

**Backend (Node.js y Express)**

El servidor implementa una API REST estructurada mediante rutas, controladores y modelos.

Las rutas definen los endpoints disponibles y los conectan con los controladores, donde se implementa la lógica de negocio y las operaciones necesarias para gestionar los datos.

Se utiliza Sequelize como ORM para interactuar con MySQL y gestionar las relaciones entre las diferentes entidades.

**Base de datos (MySQL)**

Se utiliza una base de datos relacional para almacenar y organizar la información de usuarios, asignaturas, exámenes, preguntas y resultados.

## Funcionalidades principales

- Registro e inicio de sesión de usuarios.
- Gestión de usuarios con diferentes roles: administrador, profesor y alumno.
- Creación, consulta, modificación y eliminación de asignaturas, preguntas y exámenes.
- Realización de tests con corrección automática de respuestas.
- Cálculo y almacenamiento de calificaciones.
- Consulta de resultados de los exámenes realizados.
- Panel de administración para gestionar los contenidos de la plataforma.

## Aprendizajes y desarrollo

Este proyecto me ha permitido aplicar los conocimientos adquiridos durante el ciclo formativo y profundizar en el desarrollo de aplicaciones web full stack.

Durante su implementación he trabajado con la comunicación entre frontend y backend mediante una API REST, la organización del código en diferentes capas y la gestión de bases de datos relacionales con Sequelize.

También he afrontado diferentes retos técnicos que me han ayudado a mejorar mis habilidades de resolución de problemas, depuración de errores y desarrollo de software.
