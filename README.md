# Blog personal JAMStack: Archivos iniciales

Estos son los archivos de inicio utilizados por [Manuel Ruiz](https://digitalstrategy.es) para crear un blog personal utilizando JAMStack para el desafío [DevProjects](https://www.codementor.io/projects/web/create-a-fast-and-secure-blog-using-jamstack-c93coupnxb) de [Codementor](https://www.codementor.io/). Eres libre de utilizarlos como desees para comenzar con el desafío, si deseas comenzar a trabajar en la creación del sitio sin preocuparte por el contenido en sí mismo.

Los archivos proporcionados son páginas terminadas utilizando HTML y CSS regular. Los archivos HTML se pueden descomponer y utilizar para construir las diferentes plantillas y archivos parciales utilizando el lenguaje de plantillas de tu elección.

La estilización de las páginas ya está completa. Dicho esto, la carpeta `design-files` contiene un archivo Figma y un archivo .webp de un diseño si deseas intentar construirlo desde cero. No es necesario utilizar este diseño en absoluto, depende de cómo desees abordar el desafío.

La carpeta `src` contiene archivos para que puedas poner en marcha tu proyecto sin preocuparte por el contenido de las publicaciones/artículos. Esa carpeta contiene:

- Archivos HTML que puedes utilizar como base para los diferentes diseños de página. Estos pueden convertirse en las plantillas que se utilizarán.
- Archivo CSS para la estilización de las páginas.
- 5 artículos de blog en la carpeta `blog`.
- Imágenes y un logotipo en la carpeta `assets`.

Los artículos están escritos en Markdown y contienen Front Matter. Dependiendo del Generador de Sitios Estáticos que utilices, es posible que debas modificarlos un poco si deseas utilizarlos.

## Desafío DevProjects

Como se mencionó, estos archivos están aquí para ayudarte a comenzar con el desafío DevProjects. Por favor, visita la [página del desafío](#) para obtener más información sobre el mismo.

## Tutorial

Puedes [ver este video](https://youtu.be/4wD00RT6d-g) para ver cómo Manuel utiliza Eleventy, Netlify y Netlify CMS para crear un sitio de blog completo construido completamente con archivos estáticos.


https://www.tablesgenerator.com/markdown_tables

## cheatsheet markdown

# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~


1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses


[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

Inline `code` has `back-ticks around` it.


```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```


Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.


## Tipos de macros

```
{% for Type in global.ButtonType %}
    <button class=" btn  {{Type.class}} hover  "> {{Type.class}} </button>
{% endfor %}


{% call helper.insert(elementType='button',['btn btn-primary', 'btn btn-limited' , 'btn btn-feel', 'btn btn-blue']) %} {% endcall %}
```