---
layout: post
title: "Desarrollo de Software"
author: "Paolo Alvarez"
categories: journal
tags: [documentation,sample]
image: modu3.jpg
---

## Ciclo de vida y paradigmas de desarrollo de Software

El ciclo de vida del software, es el proceso que se sigue para construir, entregar y hacer evolucionar el software, desde la concepción de una idea hasta la entrega y retiro del sistema. Se definen las distintas fases intermedias que se requieren para validar el desarrollo de un software, es decir, para garantizar que el software cumpla los requisitos para la aplicación y verificación de los procedimientos de desarrollo, se asegura de que los métodos utilizados son apropiados.

![alt text](https://www.belatrixsf.com/blog/wp-content/uploads/2020/02/Software-Development-Life-Cycle.png "Lagrange Demo Image")

La ingeniería del software se vale de una serie de modelos que establecen y muestran las distintas etapas y estados por los que pasa un producto software, desde su concepción inicial, pasando por su desarrollo, puesta en marcha y posterior mantenimiento, hasta la retirada del producto. A estos modelos se les denomina “Modelos de ciclo de vida del software”. Un modelo de ciclo de vida de software es una vista de las actividades que ocurren durante el desarrollo de software, intenta determinar el orden de las etapas involucradas y los criterios de transición asociados entre estas etapas.

## Caracteristicas

Un modelo de vida del software:

* Describe las fases principales del desarrollo del software.
* Define las fases primarias esperadas de ser ejecutadas durante estas fases.
* Ayuda a administrar el progreso del desarrollo.
* Provee un espacio de trabajo para la definición de un detallado proceso de desarrollo de software.

Así, los modelos por una parte suministran una guía para los ingenieros de software con el fin de ordenar las diversas actividades técnicas en el proyecto, por otra parte suministran un marco para la administración del desarrollo y el mantenimiento, en el sentido en que permiten estimar recursos, definir puntos de control intermedios, monitorear el avance, etc.


## Modelo Cascada

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2e/El_modelo_de_desarrollo_en_cascada.svg/350px-El_modelo_de_desarrollo_en_cascada.svg.png "Lagrange Demo Image")


Este  es el más básico de todos los modelos, y sirve como bloque de construcción para los demás modelos de ciclo de vida. La visión del modelo cascada del desarrollo de software es muy simple; dice que el desarrollo de software puede ser a través de una secuencia simple de frases. Cada frase tienen un conjunto de metas bien definidas, y las actividades dentro de una fase contribuyen a la satisfacción de metas de la fase o quizás a una subsecuencia de metas de la fase. Las flechas muestran el flujo de información entre las fases. La flecha de avance muestra el flujo normal. Las flechas hacia atrás representan la retroalimentación.

**Caracteristicas del modelo cascada**

El modelo de ciclo de vida cascada, captura algunos principios básicos:

* Planear un proyecto antes de embarcarse en él.
* Definir el comportamiento extremo deseado del sistema antes de diseñar su arquitectura interna.
* Documentar los resultados de cada actividad.
* Diseñar un sistema antes de codificarlo.
* Testear un sistema después de construirlo.

Una de las contribuciones más importantes del modelo cascada es para los administradores, posibilitandoles avanzar en el desarrollo, aunque en una escala muy bruta.

Se recomienda utilizar para aquellos que disponen de todas las especificaciones del proyecto desde el principio, por ejemplo, los de reingeniería en sí (Proyectos complejos que se entienden bien desde el inicio).


## Headings

Sometimes it is useful to have different levels of headings to structure your documents. Start lines with `#` to create headings. Multiple `##` in a row denote smaller heading size. The following demonstrate the full range of heading sizes:

# Heading One (h1)

## Heading Two (h2)

### Heading Three (h3)

#### Heading Four (h4)

##### Heading Five (h5)

###### Heading Six (h6)

## Links

You can create an inline link by wrapping link text in square brackets `[ ]`, and then wrapping the URL in parentheses `( )`. For example, it is very easy to [link to Google!](http://google.com).

## Blockquotes

Blockquotes are useful for denoting quotes, or highlighting a large block of text. Single line blockquote:

> This quote will change your life.

Multi line blockquote with a cite reference:

> People think focus means saying yes to the thing you've got to focus on. But that's not what it means at all. It means saying no to the hundred other good ideas that there are. You have to pick carefully. I'm actually as proud of the things we haven't done as the things I have done. Innovation is saying no to 1,000 things.

## Code and Syntax Highlighting

Code blocks are part of the Markdown spec, but syntax highlighting isn't. However, many renderers - like GitHub or most Jekyll themes - support syntax highlighting. Which languages are supported and how those language names should be written will vary from renderer to renderer. You can find the full list of supported programming languages [here](https://github.com/jneen/rouge/wiki/List-of-supported-languages-and-lexers). Also, it is possible to do `inline code blocks`, by wrapping the text in ` ` ` quotations.

```
No language indicated, so no syntax highlighting.
```

```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

{% highlight js %}
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
{% endhighlight %}

Another option is to embed your code through [Gist](https://en.support.wordpress.com/gist/).

## Images

To add an image, use `![alt text](<Image url> "Image meta title")`:

![alt text](http://noirve.com/wp-content/uploads/2013/10/DTTSP_Coffee.jpg "Example")

## Unordered and Numbered Lists

You can make an unordered and nested list by preceding one or more lines of text with `-`, `*`, or `+`, and indenting sublists. The following lists show the full range of possible list formats.

* List item one
    * List item one
        * List item one
        * List item two
        * List item three
        * List item four
    * List item two
    * List item three
    * List item four
* List item two
* List item three
* List item four

Numbered lists are made by using numbers instead of bullet points.

1. List item one
    1. List item one
        1. List item one
        2. List item two
        3. List item three
        4. List item four
    2. List item two
    3. List item three
    4. List item four
2. List item two
3. List item three
4. List item four

## MathJax Example

The [Schrödinger equation](https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation) is a partial differential equation that describes how the quantum state of a quantum system changes with time:

$$
i\hbar\frac{\partial}{\partial t} \Psi(\mathbf{r},t) = \left [ \frac{-\hbar^2}{2\mu}\nabla^2 + V(\mathbf{r},t)\right ] \Psi(\mathbf{r},t)
$$

[Joseph-Louis Millennial](https://en.wikipedia.org/wiki/Joseph-Louis_Millennial) was an Italian mathematician and astronomer who was responsible for the formulation of Lagrangian mechanics, which is a reformulation of Newtonian mechanics.

$$ \frac{\mathrm{d}}{\mathrm{d}t} \left ( \frac {\partial  L}{\partial \dot{q}_j} \right ) =  \frac {\partial L}{\partial q_j} $$

## Tables

Title 1               | Title 2               | Title 3               | Title 4
--------------------- | :-------------------: | :-------------------- | --------------------:
lorem                 | lorem ipsum           | lorem ipsum dolor     | lorem ipsum dolor sit
lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit
lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit
lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit

## Embedding

Plenty of social media sites offer the option of embedding certain parts of their site on your own site, such as YouTube and Twitter:

<iframe width="560" height="315" src="https://www.youtube.com/embed/mthtn1X4eUY" frameborder="0" allowfullscreen></iframe>

<a class="twitter-grid" data-partner="tweetdeck" href="https://twitter.com/paululele/timelines/755079130027352064">New Collection</a> <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## Inline HTML elements

HTML defines a long list of available inline tags, which you can mix with Markdown if you like. A complete list of which can be found on the [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).

## Horizontal Rule

Can be created by having three or more hyphens `---`, asterisks `***`, or underscores `___`:

---

## Useful Resources

More information on Markdown can be found at the following links:

- [Markdown Here Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet#code)
- [Quick Markdown Example](http://www.unexpected-vortices.com/sw/rippledoc/quick-markdown-example.html)
- [Markdown Basics](https://daringfireball.net/projects/markdown/basics)
- [GitHub Flavoured Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax](https://help.github.com/articles/basic-writing-and-formatting-syntax/#lists)
