# kaffaLove #

Repositorio dedicado a la creacion del sitio web para [Kaffa Love](https://kaffalove.netlify.app/), coffee shop ubicado en el municipio de La Estrella, Antioquia, en el mall Plaza77.

![Kaffa Love Logo](/images/logoKaffa(backgroundWhite)300x300.png)

## Change Control and Versioning

### Version 0.7.10 (Youtube responsive)
-  Se configura el iframe de los videos de Youtube para que sean responsive, con configuracion en nuevo archivo _youtube*video.scss

---

### Version 0.7.9 (Reduccion Texto quienes*somos)
- Se consolida el texto de la pagina quienes*somos eliminando parte de la historia.

---

### Version 0.7.8 (Cambios menores, previo clase final)
- Se le da sombra con box*shadow a diversos elementos (Photos y cards) en varias paginas
- Las fotos de leyenda.html y quienes*somos.html se les da una ligera rotacion para que junto con el efecto de sombre generen un efecto de foto instantanea

---

### Version 0.7.7 (Cambios menores, previo clase final)
- Se ajusta hover sobre los items del menu hamburguesa
- Se ajusta que margin vertical sea auto para los product*item de la seccion product (index.html) y asi reducir los valores de breakpoint a los cuales entran la tercera y cuarta card

---

### Version 0.7.6 (Pre*entrega3)
- Se ajusta la seccion de HowTos en index.html con par de articles
- Se adiciona juego de diferencias en la pagina de contacto.html
- Se cambia el icono para ver el menu (carta) en la seccion de productos destacados de index.html
- Se ajusta la curva SVG para que en index.html quede justo antes de footer y no en la mitad de la pagina

---

### Version 0.7.5 (Folder Images y varios)
- Todas las Imagenes quedan en la carpeta Images (Sin subfolders)
- Se corrigen grid 12 column para mobile (Gap se deja solo para tamanos mayores a lg), antes creaba un mimimum gap que hacia desbordar las imagenes en tamano mobile
- Se hace uniforme el nombre menu*general en lugar del mix con menu*global
- Tercera y cuarta card de producto (index.html) se muestran solo desde cierto ancho de viewport
- Color hover de los botones del menu se asocia a variable
- Hover sobre los botones de menu hace crecer ligeramente el boton
- Se invierten en todas las paginas, las posiciones de kaffa*motto y menu, para darle mas relevancia al menu a la derecha.
- Para curva SVG de index.html, se le elimina el margin negativo cuando se tienen dos columna en el grid (Evitar sobrelapo)

---

### Version 0.7.4 (12*column Grid Layout)
- Adicion estructura nested*grid para pagina leyenda.html. Se usa 12*Column Layout
   
---

### Version 0.7.3 (sass:color, placeholders, @extend and meta fields)
- Adicion de modulo sass:color para obtener colores derivados de la paleta de colores definida con transparencias.
- Adicion de placeholders en la definicion de los grids generales (No Media Queries).
- Adicion de @extend de la clase .quienes*somos*image (quienessomos.html) hacia .product*image (index.html).
- Adicion de los meta keywords y meta description en todas las paginas.

---

### Version 0.7.2 (Fourth product card, favicon, Animista infinite** bucle, Gmaps Link, Hamburger Icon Customization, Bootstrap survey)
- Adicion de la cuarta card en productos
- Cambio del max*width para permitir las 4 cards en una sola row
- Adicion del favicon para el sitio
- Ajuste de la animacion de Animista para que sea bucle inifinito
- Adicion del link en el footer a google maps con la ubicacion de Kaffa Love
- Customizacion del icono de hamburguesa
- Elaboracion de la encuesta en contacto.html con bootstrap

---
