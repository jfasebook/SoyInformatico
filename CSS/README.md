# CSS

CSS significa hoja de estilos en cascada y sirve para darle estilo y formato a la estructura de un proyecto escrito en un lenguaje de marcado, ejemplo: HTML.

## Tabla de contenido

- Propiedades en CSS
 - [Over flow](#propiedad-overflow)
 - [Border radius](propiedad-border-radius)
 - Float
 - Display
 - Position
 - Box shadown
 - Min y Max
 - @Font face
- Pseudo elementos
 - First child
 - Last child
 - NTH child
 - After
 - Before
- Valores de herencia
 - Inherit
 - Initial
 - Unset
- Herramientas adicionales
 - Normalize
 - Prefixfree
 - Modernizr
 - Mockups
 - Caniuse
 - Google fonts
- Recomendaciones
- FAQs

## Propiedad Overflow

Permite que se recorte el contenido de una capa, para mostrar únicamente el contenido que quepa, según sus dimensiones. Para acceder al contenido que no se muestra, porque no cabe en la capa, se puede configurar overflow para que aparezcan unas barras de desplazamiento.

**Sintaxis**:

```css

#objeto 
{
	overflow: hidden|visible|auto|scroll;
}

```

**Valores**:

visible: Muestra todo el contenido de la capa así no quepa en ella.
hidden: Para ocultar el contenido que sobrepasa el alto y ancho que tiene asignado la capa.
auto: Muestra un scroll en la capa para poder mostrar contenido que sea mayor al tamaño de dicha capa.
scroll: Muestra un scroll en la capa así el contenido no sea mayor al tamaño de dicha capa.

**Gráficamente se vería así**:

![valores overflow](https://raw.githubusercontent.com/victorhtorres/SoyInformatico/master/CSS/Images/overflow-values.jpg)

## Propiedad border radius

Permite darle estilos redondeados a las esquinas de las cajas. Esta propiedad nace en la versión CSS3.

**Sintaxis**:

```css

#objeto 
{
	border-radius: 1-4 length|% / 1-4 length|%|initial|inherit;
}

```
**Ejemplo 1**:

```css

border-radius:2em;

// is equivalent to:

border-top-left-radius:2em;
border-top-right-radius:2em;
border-bottom-right-radius:2em;
border-bottom-left-radius:2em;

```

**Ejemplo 2**:

```css

border-radius: 2em 1em 4em / 0.5em 3em;

// is equivalent to:

border-top-left-radius: 2em 0.5em;
border-top-right-radius: 1em 3em;
border-bottom-right-radius: 4em 0.5em;
border-bottom-left-radius: 1em 3em;

```

Los valores 0.5 y 3em del ejemplo 2, aproxima el grado de redondeo al eje x de la caja, ejemplo:

`border-top-left-radius: 10em;` produce lo siguiente:

![ejemplo border radius](https://raw.githubusercontent.com/victorhtorres/SoyInformatico/master/CSS/Images/border-radius-one-values.jpg)

Ahora con dos valores:

`border-top-left-radius: 10em 5em;` produce lo siguiente:

![Ejemplo de border radius con dos valores](https://raw.githubusercontent.com/victorhtorres/SoyInformatico/master/CSS/Images/border-radius-two-values.jpg)


