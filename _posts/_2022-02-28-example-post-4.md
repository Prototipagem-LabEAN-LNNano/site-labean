---
title: Post Teste/Tutorial
tags: exemplo
author: Thiago
member:
image: images/posts/example-post-4/img.png
---

## Markdown

#### Títulos

# Top level heading
## Secondary heading
### Very specific heading
#### Even more specific heading

Para quebrar o parágrafo é preciso separar as linhas por uma linha vaziaa

Linha 1
Linha 2 <- Sem linha vazia

Linha 1

Linha 2 <- Com linha vazia

#### Modificação no texto

_texto itálico_

**texto negrito**

~~texto cortado~~

#### Listas

- Item a
- Item b
- Item c

1. Item a
2. Item b
3. Item c

#### Centralizando

Texto não centralizado: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Texto centralizado: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
{:.center}

#### Links

Link externo [Texto para o usuário](https://www.google.com/)

Referencia para outra página, no site: [Pesquisa](/research)

Referencia algum membro do time: [El hombre](/members/gabriel)

{% include section.html %}

## Seções

As seções tem cores alternadas.

{% include section.html %} 

Texto após uma quebra de seção

{% include section.html %} 

Texto após outra quebra de seção

{% include section.html %} 

## Figuras

{%
  include figure.html
  image="images/posts/example-post-4/img.png"
  caption="Legenda da foto"
%}

{% include section.html %}

## Vídeo

![](https://www.youtube.com/watch?v=worP6qwyBGQ)
{:.full}

![](https://www.dailymotion.com/video/x7tfyq3)
{:.full}

![](https://vimeo.com/263856289)
{:.full}
