# kaffaLove

Repositorio dedicado a la creacion del sitio web para [Kaffa Love](https://kaffalove.netlify.app/), coffee shop ubicado en el municipio de La Estrella, Antioquia, en el mall Plaza77.

![Kaffa Love Logo](</images/logoKaffa(backgroundWhite)300x300.png>)

## Change Control and Versioning

### Version 0.8.0-S1 Branch Crear-paginas-para-submenus (Menus desplegables) 2022-08-17

- Se agrega menu desplegable al boton de Menu, para que se muestren todos los enlaces a las paginas de sub-menus
- Se le retorna la configuracion de flex para una sola imagen eliminado en v0.7.11, se usa para centrar a quienes-somos-image. Si la necesitaba alli.

### Version 0.8.0 (Pull Request #8 Creacion de las paginas para sub-menus) 2022-08-14

- Merge del branch Crear-paginas-para-submenus en version 0.7.11-S1

### Version 0.7.11-S1 Branch Crear-paginas-para-submenus (Nuevas paginas Sub-Menus) 2022-08-16

- Creacion de 6 nuevas paginas para los submenus (Carta de alimentos)
- Imagenes de background de los menus (carta Alimentos) se cargan al 100% de opacity, y esta se modifica con CSS
- Se aplica solucion dada en https://coder-coder.com/background-image-opacity/ para manipular el opacity de background si alterar el opacity de elementos hijos, esto usando ::before
- Se configuran los links desde el menu general y las paginas de sub menus, directo a la parte de productos, usando ID en los h2 de cada submenu, de manera que el usuario no vea la parte de header si no desea, sino directamente los productos (Navegabilidad de la carta)
- Se organiza de mejor forma la jerarquia de scss para menugeneral (\_menugeneral.scss)

---

### Version 0.7.11 (Submenus Page, Cards Horizaontales) 2022-08-14

- En la pagina leyenda.html se reduce la medida desde la cual el grid se vuelve de dos columnas
- Se hacen las cards de producto clickable, usando la clase de bootstrap (stretched-link)
- Se cambia global la class .btn por .button-rectangle para que no se sobrelape con la class de bootstrap
- Se le agrega sombra (text-shadow) a los h2 de main.
- Se elimina el uso de displa: flex para una sola imagen en los sitios donde no es necesario, se deja solo en las imagenes de las cards de producto
- Se crea primera pagina de submenu (Preparaciones Calientes), combinando la seccion de productos (index) con el menu General (menu.html)
- Se modifican las cards de producto para que sean horizontales
- Las cards de producto en Mobile se muestran por defecto sin la descripcion, a partir de sm se vuelve visible.
- Se organiza de mejor forma la jerarquia de scss para products.

### Version 0.7.10 (Youtube responsive) 2022-08-11

- Se configura el iframe de los videos de Youtube para que sean responsive, con configuracion en nuevo archivo \_youtube\*video.scss

---

### Version 0.7.9 (Reduccion Texto quienes somos) 2022-08-11

- Se consolida el texto de la pagina quienes\*somos eliminando parte de la historia.

---

### Version 0.7.8 (Cambios menores, previo clase final) 2022-08-11

- Se le da sombra con box\*shadow a diversos elementos (Photos y cards) en varias paginas
- Las fotos de leyenda.html y quienes\*somos.html se les da una ligera rotacion para que junto con el efecto de sombre generen un efecto de foto instantanea

---

### Version 0.7.7 (Cambios menores, previo clase final) 2022-08-11

- Se ajusta hover sobre los items del menu hamburguesa
- Se ajusta que margin vertical sea auto para los product\*item de la seccion product (index.html) y asi reducir los valores de breakpoint a los cuales entran la tercera y cuarta card

---

### Version 0.7.6 (Pre_entrega3) 2022-08-10

- Se ajusta la seccion de HowTos en index.html con par de articles
- Se adiciona juego de diferencias en la pagina de contacto.html
- Se cambia el icono para ver el menu (carta) en la seccion de productos destacados de index.html
- Se ajusta la curva SVG para que en index.html quede justo antes de footer y no en la mitad de la pagina

---

### Version 0.7.5 (Folder Images y varios) 2022-08-10

- Todas las Imagenes quedan en la carpeta Images (Sin subfolders)
- Se corrigen grid 12 column para mobile (Gap se deja solo para tamanos mayores a lg), antes creaba un mimimum gap que hacia desbordar las imagenes en tamano mobile
- Se hace uniforme el nombre menu*general en lugar del mix con menu*global
- Tercera y cuarta card de producto (index.html) se muestran solo desde cierto ancho de viewport
- Color hover de los botones del menu se asocia a variable
- Hover sobre los botones de menu hace crecer ligeramente el boton
- Se invierten en todas las paginas, las posiciones de kaffa\*motto y menu, para darle mas relevancia al menu a la derecha.
- Para curva SVG de index.html, se le elimina el margin negativo cuando se tienen dos columna en el grid (Evitar sobrelapo)

---

### Version 0.7.4 (12 column Grid Layout) 2022-08-07

- Adicion estructura nested*grid para pagina leyenda.html. Se usa 12*Column Layout

---

### Version 0.7.3 (sass:color, placeholders, @extend and meta fields) 2022-08-06

- Adicion de modulo sass:color para obtener colores derivados de la paleta de colores definida con transparencias.
- Adicion de placeholders en la definicion de los grids generales (No Media Queries).
- Adicion de @extend de la clase .quienes*somos*image (quienes-somos.html) hacia .product\*image (index.html).
- Adicion de los meta keywords y meta description en todas las paginas.

---

### Version 0.7.2 (Fourth product card, favicon, Animista infinite_bucle, Gmaps Link, Hamburger Icon Customization, Bootstrap survey) 2022-08-05

- Adicion de la cuarta card en productos
- Cambio del max\*width para permitir las 4 cards en una sola row
- Ajuste de la animacion de Animista para que sea bucle inifinito
- Adicion del link en el footer a google maps con la ubicacion de Kaffa Love
- Customizacion del icono de hamburguesa
- Elaboracion de la encuesta en contacto.html con bootstrap

---

### Version 0.7.1 (Favicon) 2022-08-02

- Se instala favicon para el sitio

---

### Version 0.7.0 (Pull Request #7 - Animista infinito) 2022-08-02

- Configuracion de parametros para tener Animista infinito (Animacion de la foto de background de los headers)
- Adicion de google maps link en el footer

---

### Version 0.6.0 (Pull Request #6 Migracion a Sass) 2022-08-02

- Migracion a Sass completa
- Se agregan variables para manejar los colores del sitio
- Se mueven los comentarios de CSS fuera de los {}

---

### Version 0.5.0 (Pull Request #5 - Corrigiendo Animista) 2022-07-27

- Se corrige el problema de la animacion de animista en las fotos de los headers, haciendo un overflow-x

---

### Version 0.4.4 (Carousel Eventos) 2022-07-26

- Se agregan carruseles con 3 fotos para 2 eventos en la seccion de eventos, index.html

---

### Version 0.4.3 (Navbar con Bootstrap) 2022-07-24

- Se agregar la navbar con bootstrap en todas las paginas

---

### Version 0.4.2 (Cambios iniciales Bootstrap) 2022-07-23

- Se agregan links de bootstrap
- Se hace una card inicial, para que quede paralela a las existente y poder modificarle los parametros para cuadrar el diseno

---

### Version 0.4.1 (Se elimina Animista) 2022-07-23

- Se vuelven a dejar las fotos de los headers estaticos, para poder agregar bootstrap

---

### Version 0.4.0 (Pull Request #4 Previo Revision Maxi) 2022-07-22

- Se sube a main, para que Maxi pueda revisar el repositorio, los problemas con animista y bootstrap

---

### Version 0.3.0 (Pull Request #3 Animacion de Animista desde los 750px) 2022-07-21

- Se ajusta la animacion de animista de las fotos de los headers desde los 750px

---

### Version 0.2.0 (Pull Request #2 Animaciones varias) 2022-07-21

- Se agregan varias animaciones tanto con css como con AOS (michalsnik.github.io)

---

### Version 0.1.0 (Pull Request #1 Reinicio repositorio) 2022-07-20

- Se reinicia el repositorio por la corrupcion de git.

---
