#  GameDev - Sistema de Gestión para Desarrollo de Videojuegos

Sistema de escritorio desarrollado en Python para la gestión integral de información relacionada con el desarrollo de videojuegos.

El proyecto implementa una interfaz gráfica desarrollada con Tkinter, conexión a una base de datos MySQL mediante procedimientos almacenados, validaciones de datos, manejo de imágenes y generación de reportes en formatos Excel y PDF.

---

## Descripción

GameDev es una aplicación de escritorio orientada a la administración de diferentes procesos relacionados con un proyecto de desarrollo de videojuegos.

El sistema permite gestionar:

-  Videojuegos
-  Empleados
-  Usuarios
-  Tareas

La aplicación está organizada mediante una arquitectura modular, separando la interfaz, conexión a base de datos, validaciones, manejo de imágenes y generación de reportes.

---

##  Objetivos

### Objetivo general

Desarrollar una aplicación de escritorio para la gestión de información de un entorno de desarrollo de videojuegos, integrando una interfaz gráfica con una base de datos relacional.

### Objetivos específicos

- Implementar una interfaz gráfica utilizando Tkinter.
- Integrar el sistema con una base de datos MySQL.
- Implementar operaciones CRUD mediante procedimientos almacenados.
- Aplicar validaciones para garantizar la integridad de los datos.
- Incorporar manejo y validación de imágenes.
- Generar reportes en formatos Excel y PDF.
- Implementar diferentes módulos funcionales.
- Aplicar una arquitectura modular y organizada.
- Incorporar temas visuales claro y oscuro.

---

##  Funcionalidades principales

###  Gestión de Videojuegos

Permite:

- Registrar videojuegos.
- Consultar videojuegos.
- Actualizar información.
- Eliminar registros.
- Gestionar imagen de portada.
- Aplicar filtros.
- Exportar información a Excel.
- Exportar información a PDF.

###  Gestión de Empleados

Permite:

- Registrar empleados.
- Consultar empleados.
- Actualizar información.
- Eliminar registros.
- Gestionar imagen de perfil.
- Aplicar validaciones.
- Aplicar filtros.
- Exportar información a Excel.
- Exportar información a PDF.

###  Gestión de Usuarios

Permite:

- Registrar usuarios.
- Consultar usuarios.
- Actualizar información.
- Eliminar usuarios.
- Gestionar correo electrónico y contraseña.
- Administrar estado del usuario.
- Gestionar plataformas y preferencias.
- Exportar información a Excel.
- Exportar información a PDF.

### 📋 Gestión de Tareas

Permite:

- Registrar tareas.
- Consultar tareas.
- Actualizar tareas.
- Eliminar tareas.
- Asociar tareas a videojuegos.
- Asociar tareas a módulos.
- Asignar responsables.
- Gestionar prioridades y estados.
- Gestionar fechas de asignación y límite.
- Controlar porcentaje de avance.
- Aplicar filtros.
- Exportar información a Excel.
- Exportar información a PDF.

---

##  Arquitectura del proyecto

El proyecto utiliza una estructura modular para separar responsabilidades:

```text
Gamedev-conocimiento/
│
├── assets/
│   ├── favicons/
│   │   └── icono pp.ico
│   │
│   ├── icons/
│   │   ├── auto-update.png
│   │   ├── cross.png
│   │   ├── file-excel.png
│   │   ├── file-pdf.png
│   │   ├── plus.png
│   │   ├── refresh.png
│   │   └── save.png
│   │
│   └── images/
│
├── database/
│   ├── conexion.py
│   └── procedimientos.sql
│
├── exports/
│   ├── excel/
│   └── pdf/
│
├── modules/
│   ├── empleados.py
│   ├── tareas.py
│   ├── usuarios.py
│   └── videogame.py
│
├── utils/
│   ├── estilos.py
│   ├── exportar_excel.py
│   ├── exportar_pdf.py
│   ├── iconos.py
│   ├── imagenes.py
│   └── validaciones.py
│
├── main.py
├── README.md
└── requirements.txt
