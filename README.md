# DAM1M04-Exercici-CSS: Currículum Web con Estilos CSS Básicos

Repositorio para la entrega de la práctica de **CSS básico** del módulo **M04: Lenguajes de Marcas y Sistemas de Gestión de Información** (DAM 1 - Institut Esteve Terradas i Illa).

---

## 📋 Descripción del Proyecto

Este proyecto parte del sitio web del currículum vitae desarrollado en HTML y le aplica una hoja de estilos CSS externa profesional, siguiendo todas las pautas y requisitos de la práctica.

### 🌐 Páginas del Sitio Web
- **[`index.html`](./index.html)**: Presentación personal, perfil, habilidades y objetivos académicos.
- **[`estudios.html`](./estudios.html)**: Trayectoria formativa, estudios realizados y tecnologías aprendidas.
- **[`proyectos.html`](./proyectos.html)**: Portafolio de proyectos destacados y metodología de desarrollo.
- **[`estilos.css`](./estilos.css)**: Hoja de estilos externa global enlazada en todas las páginas.

---

## ✅ Cumplimiento de Requisitos del Ejercicio

| Requisito | Implementación en el Código | Ubicación |
|---|---|---|
| **Archivo `.css` global** | Enlazado en la cabecera `<head>` con `<link rel="stylesheet" href="estilos.css">` | En todas las páginas HTML |
| **Tipografía pública** | Importada desde Google Fonts (`Roboto` y acento `Pixelify Sans`) | `estilos.css` / `<head>` |
| **Títulos y enlaces por selector** | Reglas para `h1`, `h2`, `h3`, `p`, `a` | `estilos.css` |
| **Estilo de enlace `:hover`** | Efecto interactivo al pasar el ratón por los enlaces del menú y pie | `estilos.css` (`a:hover`) |
| **Elementos por clase (`.`)** | `.tarjeta`, `.subtitulo`, `.btn`, `.presentacion`, `.badge` | `estilos.css` |
| **Elementos por identificador (`#`)** | `#nom-alumne`, `#menu-principal`, `#pie-pagina`, `#base` | `estilos.css` |
| **Listas con `:first-child` y `:last-child`** | Estilos diferenciados para el primer y último elemento de listas | `estilos.css` |
| **Jerarquía combinada `id > element`** | Selector hijo directo `#base > li` y `#menu-principal > ul > li` | `estilos.css` |
| **Pseudoelementos `::before` y `::after`** | Inserción de iconos visuales decorativos (`👉`, ` ✔`, viñetas) | `estilos.css` |

---

## 🚀 Cómo visualizar el proyecto

1. Abrir la carpeta del proyecto en **VS Code** o en el editor.
2. Hacer clic derecho sobre `index.html` y seleccionar **"Show Preview"** o utilizar la extensión **Live Server**.
3. También se puede hacer doble clic en `index.html` para abrirlo en cualquier navegador web moderno (Google Chrome, Firefox, Edge, Safari).
4. Para inspeccionar los estilos y probar modificaciones en vivo, pulsar:
   - **Windows / Linux**: `F12` o `Ctrl + Shift + I`
   - **macOS**: `Cmd (⌘) + Option (⌥) + I`

---

## 👨‍💻 Autor
- **Alumno**: Owais Raza
- **Centro**: Institut Esteve Terradas i Illa (Cornellà de Llobregat)
- **Ciclo**: CFGS Desarrollo de Aplicaciones Multiplataforma (DAM1)
- **Módulo**: M04 - Lenguajes de Marcas
