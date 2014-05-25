# CSS

CSS significa hoja de estilos en cascada y sirve para darle estilo y formato a la estructura de un proyecto escrito en un lenguaje de marcado, ejemplo: HTML.

## Tabla de contenido

- Propiedades en CSS
 - Over flow
 - Border radius
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
