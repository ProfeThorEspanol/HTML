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
  <html lang="es"># Referencia de etiquetas HTML más relevantes y de uso común

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

### `<title>`
- Descripción: Define el título del documento HTML.
- Uso: Se muestra en la barra de título del navegador o en la pestaña de la página.
- Ejemplo: `<title>Mi Página Web</title>`

### `<meta>`
- Descripción: Define metadatos sobre el documento HTML.
- Uso: Se utiliza para especificar el conjunto de caracteres, la descripción de la página, palabras clave, autor, etc.
- Ejemplo: 
  ```html
  <meta charset="UTF-8">
  <meta name="description" content="Descripción de la página">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  ```

### `<link>`
- Descripción: Define la relación entre el documento actual y un recurso externo.
- Uso: Comúnmente usado para vincular hojas de estilo CSS.
- Ejemplo: `<link rel="stylesheet" href="styles.css">`

## Contenido de texto

### `<h1>` a `<h6>`
- Descripción: Define encabezados HTML.
- Uso: Se utilizan para estructurar el contenido de la página, siendo `<h1>` el más importante y `<h6>` el menos importante.
- Ejemplo: 
  ```html
  <h1>Título principal</h1>
  <h2>Subtítulo</h2>
  ```

### `<p>`
- Descripción: Define un párrafo.
- Uso: Se utiliza para agrupar contenido de texto relacionado.
- Ejemplo: `<p>Este es un párrafo de ejemplo.</p>`

### `<a>`
- Descripción: Define un hipervínculo.
- Uso: Se utiliza para crear enlaces a otras páginas web o recursos.
- Ejemplo: `<a href="https://www.ejemplo.com">Visita nuestro sitio web</a>`

### `<strong>`
- Descripción: Define texto con fuerte importancia.
- Uso: Típicamente se muestra en negrita y se usa para enfatizar texto importante.
- Ejemplo: `<strong>Advertencia:</strong> Este texto es importante.`

### `<em>`
- Descripción: Define texto enfatizado.
- Uso: Típicamente se muestra en cursiva y se usa para dar énfasis al texto.
- Ejemplo: `<em>Este texto está enfatizado</em>.`

### `<br>`
- Descripción: Produce un salto de línea.
- Uso: Se utiliza para crear un salto de línea sin iniciar un nuevo párrafo.
- Ejemplo: `Línea 1<br>Línea 2`

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

### `<section>`
- Descripción: Define una sección en un documento.
- Uso: Se utiliza para agrupar contenido temático relacionado.
- Ejemplo:
  ```html
  <section>
    <h2>Sección de Noticias</h2>
    <article>Noticia 1</article>
    <article>Noticia 2</article>
  </section>
  ```

### `<nav>`
- Descripción: Define un conjunto de enlaces de navegación.
- Uso: Se utiliza para crear menús de navegación principales.
- Ejemplo:
  ```html
  <nav>
    <ul>
      <li><a href="#inicio">Inicio</a></li>
      <li><a href="#acerca">Acerca de</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>
  ```

### `<header>`
- Descripción: Define un encabezado para un documento o sección.
- Uso: Típicamente contiene elementos introductorios o de navegación.
- Ejemplo:
  ```html
  <header>
    <h1>Nombre del Sitio</h1>
    <nav>
      <!-- Enlaces de navegación -->
    </nav>
  </header>
  ```

### `<footer>`
- Descripción: Define un pie de página para un documento o sección.
- Uso: Típicamente contiene información de autoría, enlaces relacionados, etc.
- Ejemplo:
  ```html
  <footer>
    <p>&copy; 2024 Mi Sitio Web. Todos los derechos reservados.</p>
  </footer>
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

### `<span>`
- Descripción: Define una sección en un documento inline.
- Uso: Se utiliza para aplicar estilos a una parte específica del texto.
- Ejemplo: `<p>Este es un <span style="color: red;">texto rojo</span> en un párrafo.</p>`

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

### `<ol>`
- Descripción: Define una lista ordenada.
- Uso: Se utiliza para crear listas numeradas.
- Ejemplo:
  ```html
  <ol>
    <li>Primer paso</li>
    <li>Segundo paso</li>
  </ol>
  ```

### `<li>`
- Descripción: Define un elemento de lista.
- Uso: Se utiliza dentro de `<ul>` o `<ol>` para definir cada elemento de la lista.
- Ejemplo: `<li>Este es un elemento de lista</li>`

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

### `<tr>`
- Descripción: Define una fila en una tabla HTML.
- Uso: Se utiliza dentro de `<table>` para crear filas.
- Ejemplo: `<tr><td>Celda 1</td><td>Celda 2</td></tr>`

### `<td>`
- Descripción: Define una celda en una tabla HTML.
- Uso: Se utiliza dentro de `<tr>` para crear celdas de datos.
- Ejemplo: `<td>Datos de la celda</td>`

### `<th>`
- Descripción: Define una celda de encabezado en una tabla HTML.
- Uso: Se utiliza para crear celdas de encabezado en una tabla.
- Ejemplo: `<th>Encabezado de columna</th>`

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

### `<input>`
- Descripción: Define un campo de entrada.
- Uso: Se utiliza para crear varios tipos de campos de entrada como texto, contraseña, casillas de verificación, etc.
- Ejemplo: 
  ```html
  <input type="text" name="usuario">
  <input type="password" name="contraseña">
  <input type="checkbox" name="suscribir" value="yes">
  ```

### `<textarea>`
- Descripción: Define un campo de entrada de texto multilínea.
- Uso: Se utiliza cuando se necesita una entrada de texto más larga.
- Ejemplo: `<textarea name="comentario" rows="4" cols="50"></textarea>`

### `<select>`
- Descripción: Define una lista desplegable.
- Uso: Se utiliza para crear menús de selección.
- Ejemplo:
  ```html
  <select name="pais">
    <option value="es">España</option>
    <option value="mx">México</option>
    <option value="ar">Argentina</option>
  </select>
  ```

### `<button>`
- Descripción: Define un botón clickeable.
- Uso: Se utiliza para crear botones en formularios o en cualquier parte de la página.
- Ejemplo: `<button type="submit">Enviar</button>`

## Multimedia

### `<img>`
- Descripción: Define una imagen.
- Uso: Se utiliza para insertar imágenes en el documento HTML.
- Ejemplo: `<img src="imagen.jpg" alt="Descripción de la imagen">`

### `<video>`
- Descripción: Define contenido de video.
- Uso: Se utiliza para incrustar videos en una página web.
- Ejemplo:
  ```html
  <video width="320" height="240" controls>
    <source src="movie.mp4" type="video/mp4">
    Tu navegador no soporta el elemento de video.
  </video>
  ```

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
