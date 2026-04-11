<h1 align="center">Misión 1: Las bases (HTML Semántico)</h1>

En esta misión construirán los cimientos de su proyecto empleando exclusivamente HTML semántico. El propósito es estructurar contenido con una jerarquía lógica que sea comprensible para navegadores, desarrolladores y tecnologías de asistencia.

### 1. Objetivo
Desarrollar una página principal y al menos tres artículos interconectados, aplicando las etiquetas semánticas correctas para definir la estructura. Se evaluará la intención y jerarquía del contenido por sobre el diseño visual; el objetivo es evitar el uso de contenedores genéricos para resolver la maquetación.

### 2. Temática
El sitio debe mantener una línea temática consistente transversal a todo el proyecto (por ejemplo: Librería Digital, Blog Personal o Portal de Noticias). El objetivo es que la portada y los artículos se perciban cohesionados como un producto único, no como páginas aisladas.

### 3. Estructura mínima
Como punto de partida, deben crear un archivo `index.html` en el directorio `gear1`, definiendo la estructura estándar de un documento (`<html>`, `<head>`, `<body>`). La composición del contenido debe apoyarse en etiquetas como `<header>`, `<main>`, `<section>` y `<article>`, limitando el uso de `<div>` estrictamente a casos donde no exista una alternativa semántica. El código debe ser autodescriptivo.

### 4. Contenido requerido
El proyecto debe incluir un mínimo de **3 artículos** (entradas, noticias o reseñas, según la temática elegida). Cada artículo debe residir en un archivo `.html` independiente (ej. `articulo_1.html`) y todos deben ser accesibles mediante enlaces funcionales desde el `index.html`.

*Ejemplo de artículo enlazado desde el index:*
```html
<article>
  <a href="como_usar_git.html">
    <h2>Cómo usar Git</h2>
  </a>
  <p>En esta entrada verán los comandos básicos...</p>
</article>
```

### 5. Flujo de entrega
El desarrollo debe aislarse en una rama dedicada (por ejemplo, `mision-1`) para mantener un historial limpio. Al finalizar, deben abrir un *Pull Request* (PR) hacia la rama `main` con el título `Misión 1 - [Breve descripción]` y completar la *checklist* de la plantilla.

> **Regla de oro:** Tienen prohibido realizar *merge* de sus propios PRs. Un mentor revisará el código y aprobará la integración.

### 6. Política de IA y recursos
El uso de Inteligencia Artificial se limita estrictamente a la resolución de dudas teóricas y apoyo conceptual. Para garantizar la transparencia del proceso de aprendizaje, es obligatorio registrar los enlaces de sus conversaciones con la IA en el archivo `IA.md`.

**Guía recomendada:**
[HTML Semántico: Qué es y buenas prácticas](https://es.semrush.com/blog/html-semantico/)