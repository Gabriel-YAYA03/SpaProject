# ⚛️ SpaProject

## Descripción del Proyecto

`SpaProject` es un proyecto de aplicación web completa (Full-stack) desarrollado con una arquitectura de Aplicación de Página Única (SPA). El objetivo de este repositorio es proporcionar una solución integral, separando claramente la lógica de la interfaz de usuario (Front-end) y la gestión de datos y la API (Back-end).

## 🚀 Tecnologías Utilizadas

Este proyecto está construido sobre las siguientes tecnologías principales:

| Categoría | Tecnología |
| :--- | :--- |
| **Front-end** | **JavaScript** (como lenguaje principal), **HTML5**, **CSS3** (Señala aquí el framework si usas React, Vue, Angular o si es Vanilla JS). |
| **Back-end** | **JavaScript** (generalmente con **Node.js** y **Express.js** para la creación de la API REST). |
| **Bases de Datos** | (Especifica aquí si utilizas MongoDB, PostgreSQL, MySQL, etc.) |

**Lenguajes por porcentaje en el repo:**

* JavaScript: 74.6%
* HTML: 16.3%
* CSS: 9.1%

## 📂 Estructura del Repositorio

El proyecto sigue una estructura modular dividida en dos directorios principales para facilitar el desarrollo independiente de la interfaz y el servidor:

SpaProject/
├── Back-end/             # Contiene la lógica del servidor (API)
│   ├── src/
│   ├── package.json      # Dependencias del servidor
│   └── ...
├── Front-end/            # Contiene la interfaz de usuario (SPA)
│   ├── src/
│   ├── public/
│   ├── package.json      # Dependencias del cliente
│   └── ...
├── .gitignore
└── README.md             # Este archivo

## 🛠️ Instalación y Configuración

Para poner en marcha el proyecto en tu entorno local, sigue los siguientes pasos:

### Requisitos Previos

Asegúrate de tener instalado:

* [Node.js](https://nodejs.org/) (versión LTS recomendada)
* [npm](https://www.npmjs.com/) (viene incluido con Node.js) o [Yarn](https://yarnpkg.com/)
* Un gestor de bases de datos, si es necesario.

### 1. Clonar el Repositorio
``bash
git clone [https://github.com/Gabriel-YAYA03/SpaProject.git](https://github.com/Gabriel-YAYA03/SpaProject.git)
cd SpaProject
### 2. Configuración del Back-end (Servidor)

Navega al directorio del servidor, instala las dependencias y arranca el servidor.

``bash
cd Back-end
npm install # o yarn install
npm start   # O el comando de inicio definido en tu 'package.json' del Back-end

### 3. Configuración del Front-end (Cliente)

``bash
cd ../Front-end
npm install # o yarn install
npm start   # O el comando de inicio definido en tu 'package.json' del Front-end

La aplicación front-end debería iniciarse y ser accesible en tu navegador (normalmente en http://localhost:3000 o http://localhost:8080).

### 4. Uso
Una vez que los servidores de Front-end y Back-end estén corriendo, la aplicación web estará completamente funcional.

Accede a la interfaz de usuario a través de la URL del Front-end.

El Front-end se comunicará con la API del Back-end para obtener y gestionar los datos.



