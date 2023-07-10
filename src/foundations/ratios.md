---
layout: foundations/_foundations.njk
permalink: /ratios/

titulo: parrilla 1
descripcion: XX falta texto descriptivo


date: 2023-06-19
fecha: 19 de junio de 2023
tags: ["Estructuras modulares", "web design", "SEO"]
image: /assets/static/images/8.jpg
imageAlt: Ilustración de un diseño de sistema web


---

Contenedores que conservan una relación de aspecto definida.
### Como se usa
Para poder usar el ratio solo tenemos que incluirlo dentro de .rat-2-1.rat-content para que su contenido tenga posicion absoluta.

Adjuntamos los paddings-tops para los ratios.
Si no existe tu ratio puedes crear nuevos ratios de esta manera. @include ratio(ancho, alto);



```
<div class='rat-2-1'>
    <div class='rat-content'>
        <img src='image.jpg' alt='Image description'>
    </div>
</div>
```

>![Descripción de la imagen](https://holygrailcss.github.io/assets/placeholder/2-3.jpg)
>![Descripción de la imagen](https://holygrailcss.github.io/assets/placeholder/3-4.jpg)
>![Descripción de la imagen](https://holygrailcss.github.io/assets/placeholder/1-1.jpg)
>![Descripción de la imagen](https://holygrailcss.github.io/assets/placeholder/4-3.jpg)
>![Descripción de la imagen](https://holygrailcss.github.io/assets/placeholder/3-2.jpg)
>![Descripción de la imagen](https://holygrailcss.github.io/assets/placeholder/16-9.jpg)
>![Descripción de la imagen](https://holygrailcss.github.io/assets/placeholder/2-1.jpg)
>![Descripción de la imagen](https://holygrailcss.github.io/assets/placeholder/21-9.jpg)



