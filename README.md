# Gestión de Cursos (Angular)

Proyecto Angular con control de acceso por roles (Administrador y Usuario), desarrollado como entrega del curso.

---

## 🎯 Objetivo  
Aplicación frontend creada con Angular CLI para la gestión de alumnos, cursos e inscripciones.  
Incluye estructura de componentes, autenticación, roles y ABM con formularios reactivos.

---

## 🛡️ Roles

### 👨‍🏫 Administrador  
- Ver lista de alumnos, cursos e inscripciones  
- Crear, editar y eliminar alumnos  
- Crear y modificar usuarios  
- Gestionar inscripciones  

### 👤 Usuario  
- Ver lista de alumnos y cursos  
- Agregar o eliminar inscripciones  
- ❌ No puede modificar alumnos, cursos ni usuarios  

---

## ⚙️ Funcionalidades principales  
- Proyecto generado con Angular CLI  
- Formularios reactivos para altas y modificaciones  
- Angular Material para la interfaz y las tablas dinámicas  
- Control de rutas según el rol del usuario  
- Datos simulados desde arrays TypeScript  

---

## 📁 Estructura del repositorio  

```shell
.
├── README.md
├── dist/
│   └── gestion-cursos/  --> Carpeta de producción (compilada)
└── src/
    ├── app/             --> Componentes, servicios, rutas, layouts
    └── assets/          --> Archivos estáticos
