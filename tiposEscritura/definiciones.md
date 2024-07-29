# Referencia de etiquetas HTML

## Estructura básica

### `<!DOCTYPE>`
- Descripción: Define el tipo de documento HTML.
- Uso: Se coloca al principio de cada documento HTML para especificar la versión de HTML que se está utilizando.
- Ejemplo: `<!DOCTYPE html>`

### `<html>`
- Descripción: Es el elemento raíz de un documento HTML.
- Uso: Contiene todos los demás elementos del documento HTML (excepto <!DOCTYPE>).
- Ejemplo:
  ```html
  <html lang="es">
    <!-- Contenido del documento -->
  </html>
  ```

### `<head>`
- Descripción: Contiene metadatos sobre el documento HTML.
- Uso: Se utiliza para incluir scripts, definir estilos, proporcionar información meta, etc.
- Ejemplo:
  ```html
  <head>
    <title>Título de la página</title>
    <meta charset="UTF-8">
  </head>
  ```

### `<body>`
- Descripción: Define el cuerpo del documento HTML.
- Uso: Contiene todo el contenido visible del documento, como texto, imágenes, enlaces, etc.
- Ejemplo:
  ```html
  <body>
    <h1>Bienvenido a mi página web</h1>
    <p>Este es un párrafo de ejemplo.</p>
  </body>
  ```

## Metadatos

### `<base>`
- Descripción: Especifica la URL base para todas las URLs relativas en el documento.
- Uso: Se utiliza en la sección `<head>` para definir una URL base común.
- Ejemplo: `<base href="https://www.ejemplo.com/images/">`

### `<link>`
- Descripción: Define la relación entre el documento actual y un recurso externo.
- Uso: Comúnmente usado para vincular hojas de estilo CSS.
- Ejemplo: `<link rel="stylesheet" href="styles.css">`

## Contenido de texto

### `<a>`
- Descripción: Define un hipervínculo.
- Uso: Se utiliza para crear enlaces a otras páginas web o recursos.
- Ejemplo: `<a href="https://www.ejemplo.com">Visita nuestro sitio web</a>`

### `<abbr>`
- Descripción: Define una abreviatura o un acrónimo.
- Uso: Se utiliza para proporcionar el significado completo de una abreviatura.
- Ejemplo: `<abbr title="World Wide Web">WWW</abbr>`

## Contenido semántico

### `<article>`
- Descripción: Define contenido independiente y autónomo.
- Uso: Se utiliza para contenido que puede distribuirse de forma independiente, como publicaciones de blog o artículos de noticias.
- Ejemplo:
  ```html
  <article>
    <h2>Título del artículo</h2>
    <p>Contenido del artículo...</p>
  </article>
  ```

## Agrupación de contenido

### `<div>`
- Descripción: Define una división o sección en un documento HTML.
- Uso: Se utiliza como contenedor para otros elementos HTML para aplicar estilos o scripts.
- Ejemplo:
  ```html
  <div class="contenedor">
    <p>Este es un párrafo dentro de un div.</p>
  </div>
  ```

## Listas

### `<ul>`
- Descripción: Define una lista desordenada.
- Uso: Se utiliza para crear listas con viñetas.
- Ejemplo:
  ```html
  <ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
  </ul>
  ```

## Tablas

### `<table>`
- Descripción: Define una tabla HTML.
- Uso: Se utiliza para presentar datos en filas y columnas.
- Ejemplo:
  ```html
  <table>
    <tr>
      <th>Encabezado 1</th>
      <th>Encabezado 2</th>
    </tr>
    <tr>
      <td>Dato 1</td>
      <td>Dato 2</td>
    </tr>
  </table>
  ```

## Formularios

### `<form>`
- Descripción: Define un formulario HTML para la entrada del usuario.
- Uso: Se utiliza para recopilar información del usuario.
- Ejemplo:
  ```html
  <form action="/enviar" method="post">
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre">
    <input type="submit" value="Enviar">
  </form>
  ```

## Multimedia

### `<audio>`
- Descripción: Define contenido de sonido.
- Uso: Se utiliza para incrustar archivos de audio en una página web.
- Ejemplo:
  ```html
  <audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    Tu navegador no soporta el elemento de audio.
  </audio>
  ```

## Scripts

### `<script>`
- Descripción: Define un script del lado del cliente.
- Uso: Se utiliza para incluir o referenciar JavaScript en un documento HTML.
- Ejemplo:
  ```html
  <script>
    function saludo() {
      alert("Hola, mundo!");
    }
  </script>
  ```

## Elementos interactivos

### `<details>`
- Descripción: Define detalles adicionales que el usuario puede ver u ocultar.
- Uso: Se utiliza para crear contenido desplegable.
- Ejemplo:
  ```html
  <details>
    <summary>Haz clic para ver más</summary>
    <p>Aquí hay información adicional.</p>
  </details>
  ```
