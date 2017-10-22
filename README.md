## MENÚ VERTICAL

Este repositorio contiene un proyecto de (Maquetación de una barra de navegacion vertical).

## Consideraciones generales
Tomar en cuenta los siguientes requisitos para maquetar un menú de navegacion vertical.
  * La primera palabra o elemento tenga un background mostaza y el color de texto blanco, a diferencia del resto de opciones del navegador.
  * El resto de opciones verticales tenga un background gris y color de texto negro.
  * Cuando el usuario coloca el puntero sobre algún elemento(opción del navegador), se muestre un background gris transparente.
  * Cuando el usuario presiona el botón del ratón sobre la lista hasta el momento en que lo suelta, el background cambie un color negro y el color del texto cambie a blanco (Haciendo referencia que el usuario a escojido esa opción).

### Pondremos en práctica lo siguiente:
1. Aplicaremos **selectores:**
    * Selector elemento: (body, nav, ul, li, a)
    * Selector descendient, hijos: (ul li:first-child a)
    * Pseudo selectores: (:first-child)

2. Aplicaremos __"elementos que componen el modelo de caja"__
    * Padding **(relleno)**.
    * Margin **(margen)**

3. Aplicaremos la __"propiedad de los elementos de caja""__
    * display **(por bloques)**
    * background-color **(Color al bloque)**
    * color **(color de texto)**
    * width **(Ancho de la caja)**
    * height **(Alto de la caja)**
    * list-style **(indica estilo de la lista)**
    * line-height **(especifica la altura de la caja tipo en línea (inline))**


4. Aplicaremos __*Estados de los enlaces*__ pseudo-clase.
    * Hover   **(cuando el usuario se desplaza sobre ella)**
    * Active  **(cuando el usuario hace clic en el momento)**

### Herramientas Utilizadas:
1. HTML
2. CSS3

### Objetivo final:
    * Imagen final del menú vertical:

![recursos](assets/imgs/posicionandoCajas.png)