# 📚 API Librería --- README

## 📌 Descripción

La **API Librería** es un servicio backend diseñado para gestionar de
forma sencilla y estructurada la información de una librería digital.\
Permite manejar **libros, autores, categorías y clientes**, ofreciendo
endpoints claros y consistentes para integrar apps web, móviles o
paneles administrativos.

## 🎯 Objetivo del Proyecto

-   Proveer una API REST organizada, escalable y fácil de consumir.\
-   Servir como punto de aprendizaje para arquitectura backend,
    controladores, rutas y manejo de BD.\
-   Implementar buenas prácticas para futuras integraciones en entornos
    productivos.

## 🧱 Estructura del Proyecto

    api-libreria/
    │
    ├── src/
    │   ├── controllers/
    │   ├── models/
    │   ├── routes/
    │   ├── config/
    │   ├── middlewares/
    │   └── app.js
    │
    ├── public/
    ├── .env
    ├── .gitignore
    ├── package.json
    └── README.md

## 🛠️ Tecnologías Utilizadas

-   Node.js + Express\
-   PostgreSQL\
-   Azure
-   Postmant

## 🌐 URL de la API Desplegada

**URL PRODUCCIÓN:** *coloca aquí tu endpoint*

## 📸 Capturas de Postman

(Espacio reservado para imágenes)

## 🚀 Cómo Ejecutar el Proyecto Localmente

### 1️⃣ Clonar el repositorio

    git clone [https://github.com/DeltaBairon/LibroTech_Backend.git](https://github.com/DeltaBairon/LibroTech_Backend.git)
    cd api-libreria

### 2️⃣ Instalar dependencias

    npm install

### 3️⃣ Configurar variables de entorno

Crear archivo `.env` con ejemplo:

    PORT=3000
    DB_HOST=localhost
    DB_USER=postgres
    DB_PASS=tu_password
    DB_NAME=librotech
    DB_PORT=5432

### 4️⃣ Ejecutar la API

    npm run dev

## 📚 Endpoints Principales (Resumen)

  Recurso      Método   Endpoint            Descripción
  ------------ -------- ------------------- ------------------------
  Libros       GET      `/api/libros`       Lista todos los libros
  Libros       POST     `/api/libros`       Crea un libro
  Autores      GET      `/api/autores`      Lista autores
  Categorías   GET      `/api/categorias`   Lista categorías
  Clientes     POST     `/api/clientes`     Crea cliente

## 🤝 Contribución

Pull requests bienvenidos.

## 📄 Licencia

MIT


