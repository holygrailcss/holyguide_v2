---
layout: _paginas/foundations/_foundations.njk
permalink: /videos/

titulo: Videos
descripcion: XX falta texto descriptivo


date: Last Modified

tags: ["Estructuras modulares", "web design", "SEO"]
image: /assets/static/images/8.jpg
imageAlt: Ilustración de un diseño de sistema web
eleventyComputed:
  metaTitle: Beneficios de un Design System | Mejora la coherencia y eficiencia de tu web
  metaDescription: Descubre cómo un Design System puede mejorar la coherencia y eficiencia de tu sitio web. Obtén más clics y mejora la experiencia de usuario. 💡 ¡Conoce los beneficios ahora!
  metaKeywords: "Estructuras modulares, coherencia web, eficiencia, experiencia de usuario"
  metaRobots: "noindex, nofollow"
---


## Insertando el vídeo


Si queremos que los videos se inicien en autoplay, deberemos forzarlo con la etiqueta muted y playsinline . figma




        <video autoplay loop muted playsinline>
            <source src="https://vjs.zencdn.net/v/oceans.mp-m" type="video/mp-m">
            <source src="https://vjs.zencdn.net/v/oceans.webm" type="video/webm">
            Your browser does not support the video tag.
          </video>



````

 <video autoplay loop muted playsinline>
    <source src='https://vjs.zencdn.net/v/oceans.mp-m' type='video/mp-m'>
    <source src='https://vjs.zencdn.net/v/oceans.webm' type='video/webm'> Your browser does not support the video tag.
</video>
```