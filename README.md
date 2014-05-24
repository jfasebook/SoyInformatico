# Proyecto Soy Informático
***Documentemos la Ingeniería Informática***

Un repositorio que pretende ser la guía para recordar, aprender o retroalimentar información sobre distintas áreas de la Ingeniería Informática.

## Tabla de contenido
- [Objetivos](#objetivos).
- [¿Como funciona?](#como-funciona).
- [Contribuir](#contribuir).
- [Tips de sintaxis para dar formato a los README](#tips-de-sintaxis-para-dar-formato-a-los-readme).
  - [Insertar HN](#insertar-hn).
  - [Cursivas](#cursivas).
  - [Negrilla](#negrilla).
  - [Viñetas para tablas de contenido](#vi%C3%B1etas).
  - [insertar imágenes](#insertar-im%C3%A1genes).
  - [Insertar enlaces](#insertar-enlaces).
  - [Hacer anclaje](#hacer-anclaje).
  - [Insertar una línea de código](#insertar-una-l%C3%ADnea-de-c%C3%B3digo).
  - [Insertar un bloque de código](#insertar-un-bloque-de-c%C3%B3digo).
  - [Resaltar el código](#resaltar-el-c%C3%B3digo).
  - [Insertar tablas](#insertar-tablas).
  - [Referencias externas sobre markdown](#referencias-externas-sobre-markdown).
- [FAQs](#faqs).
  - [¿Porque debería documentar todo lo que aprendo?](#porque-deber%C3%ADa-documentar-todo-lo-que-aprendo)

### Objetivos

- A largo plazo cualquiera pueda aprender de la Ingeniería Informática por medio de este repositorio.
- A mediano plazo, tener información de calidad y minimalista para poder retroalimentar o recordar partes de código, definiciones y demás sobre la Ingeniería Informática.

### ¿Como funciona?

En el repositorio, las distintas áreas, campos o lenguajes de programación que se aprende en la Ingeniería Informática estan creados por carpetas, ejemplo: Java, C++, HTML, DISCRETAS, etc... Cada carpeta contiene un archivo `README.md` y una carpeta llamada `Images`. En el archivo `README.md` se documentará todo lo que más se pueda acerca de dicha categoría y en la carpeta `Images` se guardará las imágenes que se insertarán en el archivo `README` para explicar algo gráficamente.

El archivo `README.md` tiene la siguiente arquitectura de la información que deberás de tener en cuenta a la hora de colaborar ya sea mejorandolo, corrigiendo o creando uno nuevo para otra categoría aún no publicada:


- Una introducción sobre la definición de la categoría, ejemplo: Java es un lenguaje de programación, etc...

- Contribución: Recordando a las personas como pueden contribuir con el proyecto.

- Licencia: Recordando que todo artículo publicado es bajo licencia Atribución – No comercial – Compartir igual.

- Tabla de contenido [Con anclaje a cada item].

	- Item 1: tema 1 de la documentación. Al final debe tener anclaje para volver al inicio de la tabla.
	.
	.
	.
	- Item N.

	- Referencias externas: Todos los créditos con enlace (si requiere) de donde obtuvimos la información compartida.

	- FAQs

	- Créditos: Si eres aportante, deja un enlace de reconocimiento, ejemplo: tu usuario de alguna red social, pagina web, etc...

### Contribuir

Utiliza las opciones de GitHub como **Pull Request** o un **Fork** para colaborar con el proyecto:

**Fork**: Hace un clon de este repositorio en tu cuenta de GitHub. En el podrás hacer modificaciones o simplemente para tener una copia (con opción de clonarlo a tu PC también). De esa forma garantizas la información para tu uso personal.

**Pull Request**: Envía la sugerencias de cambio para este repositorio, los cuales hicistes en tu clon. Si son aceptadas por el master, se fucionan los cambios y el repositorio del proyecto queda actualizado.

Adicionalmente, se esta creando un sitio web, por ahora con el único objetivo de dar a conocer lo que estamos haciendo aquí a Universidades, foros, etc... El enlace es: [wwww.soyinformatico.org](http://www.soyinformatico.org)

### Tips de sintaxis para dar formato a los README

Los archivos README.md tienen formato de lenguaje de marcado `markdown` que es mucho más sencillo que el lenguaje `HTML`. Veamos algunos ejemplo:

#### Insertar HN

```plain
# Esto es un H1
## Esto es un H2
### Esto es un H3
#### Esto es un H4

```

#### Cursivas

`*Esto es cursiva*`

#### Negrilla

`**Esto es negrilla**`

#### Viñetas

```plain

- Esto es viñeta 1.
  - Viñeta 1.1 con sangria.
  - Viñeta N.
  
```

#### Insertar imágenes

`![texto cualquiera por si no carga la imagen](url completa de la imagen)`

#### Insertar enlaces

`[texto a mostrar](url completa)`

#### Hacer anclaje

Usar los títulos con la almohadilla `#` y para anclar el título a una tabla de contenido, ponemos lo siguiente:

`[texto a mostrar](#mi-titulo-a-anclar)`

#### Insertar una línea de código

Encerrar la linea de código entre la tilde al revez ` Código en ASCII: alt96

Ejemplo:

<pre><code>`tu linea de codigo`</code></pre>

#### Insertar un bloque de código

Encerrar el bloque de código entre tres tildes al revez ``` Código en ASCII: alt96

Ejemplo:

<pre>
		```
		
		//bloque de codigo...
		
		```
</pre>


#### Resaltar el código

Encerramos el bloque de código con las tres tildes al revez ``` y le ponemos al lado el lenguaje que se esta usando, ejemplo:

<pre>
		```java
		
		//bloque de codigo...
		
		```
</pre>

#### Insertar tablas

```plain

| TITULO1| TITULO2|

| ----- | ---- |

| CONTENIDO COLUMNA 1 | CONTENIDO COLUMNA 2 |


```

#### Referencias externas sobre Markdown

Para mayor información sobre la sintaxis del markdown:

http://www.genbeta.com/guia-de-inicio/que-es-markdown-para-que-sirve-y-como-usarlo

https://help.github.com/articles/markdown-basics

https://guides.github.com/features/mastering-markdown/


### FAQs

#### ¿Porque debería documentar todo lo que aprendo?
Garantizamos tener la información de nuestro conocimiento accesible todo el tiempo, con el objetivo de recordar partes de datos claves que necesitemos en futuros proyectos o simplemente retroalimentarnos de manera colectiva gracias a la facilidad de poder contribuir entre varias personas con el proyecto.
