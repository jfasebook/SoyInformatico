# Matemáticas Discretas
Las matemáticas discretas son un área de las matemáticas encargadas del estudio de los conjuntos discretos: finitos o infinitos numerables. En oposición a las matemáticas continuas, que se encargan del estudio de conceptos como la continuidad y el cambio continuo, la matemáticas discretas estudian estructuras cuyos elementos pueden contarse uno por uno separadamente. Es decir, los procesos en matemáticas discretas son contables, como por ejemplo, los números enteros, grafos y sentencias de lógica.

## ¿Para que sirven?
Sirven para resolver problemas analíticos, incluyendo teoría básica de conjuntos, combinatoria, relaciones y funciones, propiedades básicas de grafos y sus aplicaciones en la ciencia de la computación y son importantes en dicha ciencia porque sólo son computables las funciones de conjuntos numerables. La clave en matemáticas discretas es que no es posible manejar las ideas de proximidad o límite y suavidad en las curvas, como se puede en el cálculo. Por ejemplo, en matemáticas discretas una incógnita puede ser 2 ó 3, pero nunca se aproximará a 3 por la izquierda con 2.9, 2.99, 2.999, etc. Las gráficas en matemáticas discretas vienen dadas por un conjunto finito de puntos que se pueden contar por separado; es decir, sus variables son discretas o digitales, mientras que las gráficas en cálculo son trazos continuos de rectas o curvas; es decir, sus variables son continuas o analógicas.

**Referencias**:

http://es.wikipedia.org/wiki/Matem%C3%A1ticas_discretas

## Tabla de contenido

- [Progresión aritmética](#progresi%C3%B3n-aritmetica)
- Progresión geométrica
- Principio de inducción matemática (PIM)
- Relaciones recursivas de una semilla
- Relaciones recursivas de dos semillas
- Conjuntos
    - Conjuntos contables o enumerables
    - Conjunto finito
    - Conjunto infinito
    - Conjunto universo
  - Operaciones entre conjuntos
    - Unión
    - Intercepción
    - Diferencia o resta
    - Diferencia simétrica
    - Complemento
    - Producto cartesiano
  - Partes de un conjunto o conjunto potencia
  - Partición de conjuntos
- Conteo
  - Principio de la multiplicación
  - Principio de adición
  - Combinación
  - Combinación con repetición
  - Permutación
  - Permutación con repetición (objetos indistinguibles)
  - Permutación sin repetición
  - Principio de inclusión y exclusión
- Relaciones
  - Propiedades
    - Reflexiva
    - Simetrica
    - Transitiva
  - Clasificación
    - Uno a uno
    - Uno a muchos
    - Muchos a uno
    - Muchos a muchos
  - Relaciones de equivalencia
  - Cerradura
- Funciones
  - Dominio, codominio y rango
  - Función inyectiva
  - Función sobreyectiva
  - Función biyectiva
  - Función compuesta
  - Función inversa
- Grafos
  - Grafo no dirigido
  - Grafo dirigido
  - Terminología de grafos
  - Representación de un grafo en una matriz de adyacencia
  - Representación de un grafo en una lista de adyacencia
  - Arboles
- FAQs
- Créditos

## Progresión aritmetica

Es una sucesión de números tales que la diferencia de dos términos sucesivos cualesquiera de la secuencia es una constante, cantidad llamada diferencia de la progresión o razón de cambio. Por ejemplo, la sucesión matemática: 3, 5, 7, 9, 11,... es una progresión aritmética de constante o razón de cambio de 2. Así como: 5, 2, -1, -4 es una progresión aritmética de constante "-3".

Veremos como calcular el n-ésimo término de una sucesión aritmética (1, 2, 3, 4, .... ?) y posterior a eso, vamos hallar la suma de la sucesión.

**Hallar el n-ésimo término de la sucesión**

Para hallar el n-ésimo término de una progresión aritmética, tenemos la siguiente formula:

![formula enesimo aritmetica](https://raw.githubusercontent.com/victorhtorres/SoyInformatico/master/MatematicasDiscretas/Images/formula-enesimo-artimetica.png)

>La formula solo es válida para los n>=1 donde "a" es el primer término de la sucesión, "r" la razón de cambio y "n" es una variable cualquiera que se reemplaza por el número de término que se desea encontrar en la sucesión. 

**Hallar la sumatoria de la sucesión**

Para hallar la suma de una sucesión aritmética, usamos la siguiente fórmula:

![formula sucesion aritmetica](https://raw.githubusercontent.com/victorhtorres/SoyInformatico/master/MatematicasDiscretas/Images/formula-suma-sucesion-artimetica.png)

>Donde "n" es una constante que sirve para reemplazarla por la cantidad de términos que se desea sumar. La letra "a" hace referencia al primer término de la sucesión y "Tn" es el término general o n-ésimo de la sucesión.

Ejemplo:

![Ejemplo 1 sobre progresión aritmetica](https://raw.githubusercontent.com/victorhtorres/SoyInformatico/master/MatematicasDiscretas/Images/ejemplo-1-progresion-aritmetica.png)

Nota: este ejemplo se realizó con la aplicación de google chrome Daum Equation Editor y este es el siguiente código para su respectiva modificación:

```plain
Hallar\quad el\quad n-esimo\quad termino\quad y\quad la\quad suma\quad de\quad la\quad siguente\quad secuencia:\\ \\ 1\quad +\quad 3\quad +\quad 5\quad +\quad 7\quad +\quad 9...\quad +\quad (\quad \quad \quad \quad \quad )\quad =\quad (\quad \quad \quad \quad \quad )\\ \\ Solución:\\ \\ Primero\quad hallemos\quad el\quad termino\quad n-esimo:\\ \\ Sabemos\quad que\quad la\quad r\quad =\quad 2\quad y\quad a\quad =\quad 1\quad y\quad eso\quad lo\quad podemos\quad visualizar\quad en\quad la\quad secuencia...\\ Entonces\\ \\ { t }_{ n\quad  }\quad =\quad a\quad +\quad (n-1)r\\ \qquad =\quad 1\quad +\quad (n-1)2\\ \qquad =\quad 1\quad +\quad 2n-2\\ { t }_{ n }\quad =\quad 2n-1\\ \\ Ya\quad tenemos\quad el\quad n-esimo\quad termino:\quad 1\quad +\quad 3\quad +\quad 5\quad +\quad 7\quad +\quad 9...\quad +\quad 2n-1\quad =\quad (\quad \quad \quad \quad )\\ \\ Ahora\quad hallamos\quad la\quad suma\quad de\quad los\quad n-terminos:\\ \\ { S }_{ n }\quad \quad =\quad \frac { n\quad ({ a }_{ 1 }\quad +\quad { t }_{ n }) }{ 2 } \\ \qquad \quad =\quad \frac { n\quad (1\quad +\quad 2n-1) }{ 2 } \\ \qquad \quad =\quad \frac { n\quad (2n) }{ 2 } \\ { S }_{ n }\quad \quad =\quad { n }^{ 2 }\\ \\ Por\quad lo\quad tanto\quad la\quad secuencia\quad queda\quad así:\\ \\ 1\quad +\quad 3\quad +\quad 5\quad +\quad 7\quad +\quad 9\quad +\quad ...\quad +\quad (2n-1)\quad =\quad { n }^{ 2 }\\ 
```

