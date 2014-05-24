# HTML5
HTML (HyperText Markup Language), versión 5 es la quinta revisión importante del lenguaje básico de la World Wide Web, HTML. No es un lenguaje de programación en la web, sino un lenguaje de marcado para estructurar o maquetar diseños web y/o apps.

## Tabla de contenido

- [Estructura base de un archivo en HTML5](#estructura-base-de-un-archivo-en-html5)
- [LLamar un archivo CSS](#llamar-un-archivo-css)
- [Llamar un archivo JS](#llamar-un-archivo-js)
- [Etiqueta figure](#etiqueta-figure)
- [Etiqueta video](#etiqueta-video)
- [Recomendaciones](#recomendaciones)
- [FAQs](#faqs)
	- [¿Cómo está compuesto un diseño web?](#com%C3%B3-est%C3%A1-compuesto-un-dise%C3%B1o-web)

## Estructura base de un archivo en HTML5
```html
<!DOCTYPE html>
<html lang="es"> 
<head>
	<meta charset="utf-8">
	<meta name="description" content="160 caracteres max.">
	<title>
	70 caracteres max.
	</title>
</head>
<body>
	<header>
		<h1>Uno solo por documento.</h1>
	</header>
	<section> 
		<!-- permite dividir el contenido del sitio en varias secciones. Ejemplo: Un blog tiene un section para el post y otro para el gestor de comentarios -->
		<article> 
			<!-- Para definir contenido independiente. Ejemplo: Un blog tiene varios post y cada post es un <article>. Ejemplo: Si tenemos 1 post y 10 comentarios, entonces tenemos 2 <section>, uno para el post y otro para el gestor de comentarios y 11 <article> uno por cada comentario. -->
		</article>
		<aside>
			<!-- Lo que no hace parte del contenido principal de nuestro sitio web y puede ir en cualquier parte de la estructura. -->
		</aside>
	</section>
	<footer>
		<!-- Exclusivo para el pie de página -->
	</footer>
</body>
</html>
```
## LLamar un archivo CSS

Colocar dentro de la etiqueta `<head>` y debajo del `<title>` la siguiente linea de código:

**Sintaxis**:

`<link rel="stylesheet" href="tuarchivo.css" />`

## Llamar un archivo JS

Colocar dentro del `<head>` y debajo de los archivos CSS llamados la siguiente linea de código:

**Sintaxis**:

`<script src="tuarchivo.js"></script>`

> Algunos llamados de archivos en JS es mejor insertarlos después del <footer>. Ejemplo: la librería jQuery.

## Etiqueta figure

Sirve para insertar imágenes.

Dentro del `<body>` se coloca las siguientes lineas de código:

**Sintaxis**:

```html
<figure id="">
<img src="" width="" height="" alt="" />
</figure>
```

Se recomienda ponerle un id a la etiqueta `<figure>`.

## Etiqueta video

Se inserta con la etiqueta `<video>` dentro del `<body>`.  Debe tener una id para estilos, un ancho y alto para visualizar el video. El elemento **controls** nos permite tener funciones adicionales por medio de botones en el vídeo, ejemplo: botón play, stop, etc…

**Sintaxis**:

```html
<video id="mejorandola" width="640" height="320" controls>
				<source src="video.mp4" type="video/mp4; codecs='avc1,mp4'" /><!-- Formato de video H.264 -->
				<source src="video.webm" type="video/webm; codecs='vp8,vorbis'" /> <!-- Formato de video WebM -->
</video>
```

(Leer más sobre los codecs de video...)[https://developer.mozilla.org/es/docs/HTML/Formatos_admitidos_de_audio_y_video_en_html5]


## Recomendaciones

- Al momento de maquetar el sitio, tome decisiones pensando en la estructura de contenido pero no en el diseño.
- Siempre debemos guardar el archivo en codificación utf-8.
- Todos los tag semánticos (header, section, article, etc..) reemplaza los divs que se usaban para esto, pero los divs no están del todo muerto.
- Si tienen botonera o menú, usan la etiqueta <nav></nav>.
- No implemente componentes de diseño gráfico en HTML5.
- Google recomienda tener un solo H1 por página.

## FAQs

### ¿Comó está compuesto un diseño web?
Todo empieza por la base de datos (MySQL, Postgres, MongoDB, etc...), luego tenemos el BACKEND con sus respectivos lenguajes de programación o frameworks (Php, Djando, Express.js, Node.js, Socket.io) y por último tenemos en FRONTEND (HTML5, CSS3, Javascript [jquery, y otros frameworks]) donde el único lenguaje de programación para el frontend es el Javascript y los demás son frameworks o lenguajes modelados de datos o estilos como HTML5 y CSS3.



