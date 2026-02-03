# 📘 KARIO Media – Proyecto HTML (Campuslands)

## 🧾 Overview

Este proyecto corresponde al desarrollo de la plataforma *KARIO Media*, implementado utilizando tecnologías web estándar: **HTML5** y **CSS3**.  
Su propósito es presentar una estructura clara, modular y escalable para un sistema web con múltiples vistas independientes.

El proyecto se limita a la capa de presentación, sin incluir lógica de servidor ni persistencia de datos.

---

## 🎯 Objetivos

### Objetivo general
Desarrollar una interfaz web funcional, organizada y adaptable para la plataforma KARIO Media.

### Objetivos específicos
- 📌 Aplicar buenas prácticas en la estructuración de proyectos.
- 📌 Separar estilos por vista para mejorar la mantenibilidad.
- 📌 Implementar diseño responsivo utilizando Flexbox y Grid.
- 📌 Mantener coherencia visual mediante una paleta de colores unificada.

---

## 🛠️ Tecnologías Utilizadas

- 🧱 **HTML5** – Estructura semántica del contenido.
- 🎨 **CSS3** – Estilos y presentación visual.
- 📐 **Flexbox** y **CSS Grid** – Organización de layouts.
- 📱 **Media Queries** – Adaptación a diferentes tamaños de pantalla.

No se utilizan frameworks ni librerías externas.

---

## 🗂️ Estructura del Proyecto

```
/
├── assets/
│   └── imgs/
│       └── Recursos gráficos del proyecto
│ 
├── css/
│   ├── add.css
│   ├── bugfix.css
│   ├── dashboard.css
│   ├── delete.css
│   ├── help.css
│   ├── main.css
│   ├── profile.css
│   └── style.css

├── pages/
│   ├── add.html
│   ├── bugfix.html
│   ├── dashboard.html
│   ├── delete.html
│   ├── help.html
│   ├── login.html
│   └── profile.html
│
└── index.html
```
---

## 🧩 Descripción de las Vistas

- 🏠 index.html (Página principal del proyecto).
- 🔐 login.html (Interfaz de autenticación del usuario).
- 📊 dashboard.html (Panel principal de navegación y visualización de información).
- ➕ add.html (Vista destinada al registro de nuevos elementos).
- 🗑️ delete.html (Interfaz para la eliminación de elementos).
- 🐞 bugfix.html (Sección para el reporte de errores o incidencias).
- ❓ help.html (Centro de ayuda con temas y preguntas frecuentes).
- 👤 profile.html (Gestión y visualización del perfil del usuario).

---

## 📐 Prototipado y Diseño

Previo al desarrollo de la página web, la interfaz de la aplicación fue **maquetada y prototipada en Figma**, lo que nos permitió:

- Definir la estructura visual de las vistas.
- Establecer jerarquías de información claras.
- Unificar criterios de diseño y experiencia de usuario.
- Facilitar la posterior implementación en HTML y CSS.

![evidencia de maquetación y uso de Figma.](./assets/imgs/image.png)

El uso de Figma nos permitió una transición ordenada del diseño al desarrollo, reduciendo inconsistencias visuales y mejorando la coherencia general del proyecto.

---

## 🎨 Organización de Estilos

Cada vista posee su propio archivo CSS, lo que permite:

- Mayor claridad y orden en el código.
- Facilidad de mantenimiento.
- Escalabilidad del proyecto.
---
## 📱 Diseño Responsivo

- El diseño responsivo se implementa mediante:
- Uso de unidades relativas (rem, %).
- Reordenamiento de contenido con Flexbox y Grid.
-  Media queries para compatibilidad con dispositivos móviles.
---

## 🚧 Alcance y Limitaciones

- 🔒 Proyecto enfocado únicamente en frontend.
- 🧪 Contenido demostrativo sin funcionalidad backend.
- 🔄 Base preparada para futuras integraciones.

---
## 📥 Instrucciones para Clonar el Repositorio

Para obtener una copia local del proyecto, es necesario contar previamente con **Git** instalado en el sistema.

### Pasos

1. Abrir una terminal o consola de comandos.
2. Ejecutar el siguiente comando:

```bash
git clone https://github.com/KarinaMendez17/proyecto_html_p1.git
```
---

## 👥 Autores

Este proyecto fue desarrollado de manera colaborativa por:

### - 🎨[Dana Villamizar](https://github.com/Dana-villa)

### - 🤖[Karina Méndez](https://github.com/karinamendez17)

### - 💻[Santiago Domínguez](https://github.com/Shiroses)


