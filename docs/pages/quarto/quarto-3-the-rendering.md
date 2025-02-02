The great strength of Quarto is its diversity of rendering modes.

## Presentation 

Quarto supports a variety of formats for creating presentations, including:

- revealjs — reveal.js (HTML)
- pptx — PowerPoint (MS Office)
- beamer — Beamer (LaTeX/PDF)

The most capable format by far is revealjs so is highly recommended. For example, you can write this and render :

```r 
---
title: "Habits"
author: "John Doe"
format: revealjs
---

## Getting up

- Turn off alarm
- Get out of bed

## Going to sleep

- Get in bed
- Count sheep
```

You can find [here](https://quarto.org/docs/presentations/) a complete tutorial and and below a presentation made in Quarto with revealjs

<iframe src="https://mine.quarto.pub/hello-quarto/#/hello-quarto-title" frameborder="0" width="100%" height="700" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

## Websites

Quarto Websites are a convenient way to publish groups of documents. Documents published as part of a website share navigational elements, rendering options, and visual style. For example, the [Quarto website](https://quarto.org/) is generated by... quarto !

<iframe src="https://quarto.org/" frameborder="0" width="100%" height="700" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

You can find [here](https://quarto.org/docs/websites/) a complete tutorial

## Books

Quarto Books are combinations of multiple documents (chapters) into a single manuscript. Books can be created in a variety of formats:

- HTML
- PDF
- MS Word
- EPUB
- AsciiDoc

<iframe src="https://wesmckinney.com/book/" frameborder="0" width="100%" height="700" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

You can find [here](https://quarto.org/docs/books/) a complete tutorial

## Interactivity

Quarto can be connected with for example Shiny to make its content dynamic. Thus, it will be possible to have sliders, choice zones,...

<iframe src="https://jjallaire.shinyapps.io/diamonds-explorer/" frameborder="0" width="100%" height="800" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

You can find [here](https://quarto.org/docs/interactive/shiny/) a complete tutorial.

!!! Success "Quick recap"
    In this section, you had an overview of the different rendering methods from Quarto.