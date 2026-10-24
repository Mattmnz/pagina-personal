# Página personal — Matthew Muñoz

Página personal estática desarrollada para la asignatura **Diseño de Sistemas de Internet** (Universidad Nacional de Ingeniería), Guía Frontend Básico — Semana 11.

**Sitio publicado:** https://Mattmnz.github.io/pagina-personal/

## Objetivo

Identificar la estructura básica del frontend mediante HTML, organizando correctamente los elementos de una página web.

## Contenido de la página

- Encabezado principal con nombre (`<h1>`)
- Párrafo de presentación personal (`<p>`)
- Lista de habilidades (`<ul>`, `<li>`)
- Imagen (`<img>`) y enlaces a redes (`<a>`)

## Estructura del proyecto

```text
pagina-personal/
├── index.html      # Documento HTML de la página
├── img/
│   └── foto.jpg    # Imagen de la página
└── README.md       # Documentación del proyecto
```

## Estructura del documento HTML

| Elemento | Función |
|---|---|
| `<!DOCTYPE html>` | Activa el modo estándar de renderizado del navegador |
| `<html lang="es">` | Raíz del documento; declara el idioma del contenido |
| `<head>` | Metadatos: codificación (UTF-8), viewport y título |
| `<body>` | Contenido visible de la página |
| `<header>` | Imagen, nombre y subtítulo |
| `<main>` | Contenido principal: secciones *Sobre mí*, *Habilidades* y *Enlaces* |
| `<section>` | Agrupa cada bloque temático, encabezado por su `<h2>` |
| `<footer>` | Pie de página |

Jerarquía de encabezados: `<h1>` (nombre) → `<h2>` (secciones).

## Validación

El documento fue validado con el [W3C Nu HTML Checker](https://validator.w3.org/nu/) sin errores ni advertencias.

## Cómo verlo localmente

1. Clonar el repositorio: `git clone https://github.com/Mattmnz/pagina-personal.git`
2. Abrir `index.html` con la extensión Live Server de VS Code, o directamente en el navegador.

## Autor

Matthew Muñoz — [LinkedIn](https://www.linkedin.com/in/matthew-mu%C3%B1oz-761857302/)
