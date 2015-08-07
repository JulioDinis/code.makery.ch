---
layout: article
title: "Hello Dart: Introduction to Programming"
date: 2015-05-01 00:00
slug: hello-dart
github: https://github.com/marcojakob/code.makery.ch/edit/master/collections/library/hello-dart-en.md
description: "Hello Dart is a playful introduction to programming. Learn the basics of programming with the awesome Dart language."
image: /assets/library/hello-dart/hello-dart.png
published: true
prettify: false
comments: true
sidebars:
- header: Artigos nesta Série
  body:
  - text: "Introdução"
    link: /library/hello-dart/
    paging: Intro
    active: true
  - text: "Instalação"
    link: /library/hello-dart/install/
    icon-css: fa fa-fw fa-cog
    paging: <i class="fa fa-cog"></i>
  - text: "Parte 1: Primeiros Passos"
    link: /library/hello-dart/part1/
    paging: 1
  - text: "Parte 2: Repetições"
    link: /library/hello-dart/part2/
    paging: 2
  - text: "Parte 3: Desvios Condicionais"
    link: /library/hello-dart/part3/
    paging: 3
  - text: "Parte 4: Variaveis"
    link: /library/hello-dart/part4/
    paging: 4
  - text: "Parte 5: Funções"
    link: /library/hello-dart/part5/
    paging: 5
  - text: "Proximos Passos"
    link: /library/hello-dart/next/
    icon-css: fa fa-fw fa-flag-checkered
    paging: <i class="fa fa-flag-checkered"></i>
languages:
  header: Linguagens
  collection: library
  item: hello-dart
  part:
  active: en
---

![Hello Dart](/assets/library/hello-dart/hello-dart-animation.gif)

> `Hello Dart` é uma introdução divertida de programação com Dart.

Antigamente, era pouco realista programar aplicações móveis ou baseadas na Web. A linguagem de programação Dart representa uma forma de torna facil a programação de tais aplicações.

`Hello Dart` vai guia-lo através dos conceitos basicos de programação. Não sendo nescessario ter conhecimentos de programação. O mundo divertido de `Hello Dart` mostra a execução de seus programas. Logo você vai querer sair das regras do mundo de `Hello Dart`. Depois da introdução com `Hello Dart` você vai terá uma boa base para começar a realizar seus próprios projetos web.

<!--
<div class="alert alert-info">
  Read <a class="alert-link" href="/library/hello-dart/background/">Background Infos</a> to learn why I see Dart as the ideal language for beginners and professionals to program web and mobile apps.
</div>
-->

## The World

O mundo de `Hello Dart` consiste de campos, arvores, e estrelas.

![Elements](/assets/library/hello-dart/intro/elements.png)


## O Jogador

No mundo de `Hello Dart` podemos nos movimentar com com nosso . Você pode escolher um entre quatro personagens.

![Characters](/assets/library/hello-dart/intro/characters.png)

Um personagem do jogo, chamado `Player` tem as seguintes ações e sensores que ele/ela pode usar:


### Ações

<table class="table">
  <thead>
    <tr>
      <th>Ação</th>
      <th>Comando</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="vertical-align:middle">![Move](/assets/library/hello-dart/intro/move.png)</td>
      <td style="vertical-align:middle">`move()`</td>
      <td style="vertical-align:middle">O jogador anda um passo para frente.</td>
    </tr>
    <tr>
      <td style="vertical-align:middle">![Turn Left](/assets/library/hello-dart/intro/turn-left.png)</td>
      <td style="vertical-align:middle">`turnLeft()`</td>
      <td style="vertical-align:middle">O jogador vira 90 graus para a esquerda.</td>
    </tr>
    <tr>
      <td style="vertical-align:middle">![Turn Right](/assets/library/hello-dart/intro/turn-right.png)</td>
      <td style="vertical-align:middle">`turnRight()`</td>
      <td style="vertical-align:middle">O jogador vira 90 graus para a direita.</td>
    </tr>
    <tr>
      <td style="vertical-align:middle">![Put Star](/assets/library/hello-dart/intro/put-star.png)</td>
      <td style="vertical-align:middle">`putStar()`</td>
      <td style="vertical-align:middle">O jogador coloca uma estrela.</td>
    </tr>
    <tr>
      <td style="vertical-align:middle">![Move](/assets/library/hello-dart/intro/remove-star.png)</td>
      <td style="vertical-align:middle">`removeStar()`</td>
      <td style="vertical-align:middle">O jogador remove uma estrela.</td>
    </tr>
    <tr>
      <td style="vertical-align:middle">![Say](/assets/library/hello-dart/intro/say.png)</td>
      <td style="vertical-align:middle; ">`say('Hello')`</td>
      <td style="vertical-align:middle">O jogador diz algo usando um balão de fala.</td>
    </tr>
  </tbody>
</table>


### Sensores

<table class="table">
  <thead>
    <tr>
      <th>Sensor</th>
      <th>Comando</th>
      <th>Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="vertical-align:middle">![Can Move](/assets/library/hello-dart/intro/can-move.png)</td>
      <td style="vertical-align:middle">`canMove()`</td>
      <td style="vertical-align:middle">O jogador verifica se pode mover se para o proximo campo.</td>
    </tr>
    <tr>
      <td style="vertical-align:middle">![Tree Front](/assets/library/hello-dart/intro/tree-front.png)</td>
      <td style="vertical-align:middle">`treeFront()`</td>
      <td style="vertical-align:middle">O jogador verifica se tem uma árvore na frente.</td> `PAREI AQUEEEEE  oooooooossasdasdhasjkdhasjkdhasjkdhasjkdhajsdhaskjhdajkshdajkshdkjashdjashdkahsdHJFJHAJKFHAKSF`
    </tr>
    <tr>
      <td style="vertical-align:middle">![Tree Left](/assets/library/hello-dart/intro/tree-left.png)</td>
      <td style="vertical-align:middle">`treeLeft()`</td>
      <td style="vertical-align:middle">The player checks if there is a tree on the left side.</td>
    </tr>
    <tr>
      <td style="vertical-align:middle">![Tree Right](/assets/library/hello-dart/intro/tree-right.png)</td>
      <td style="vertical-align:middle">`treeRight()`</td>
      <td style="vertical-align:middle">The player checks if there is a tree on the right side.</td>
    </tr>
    <tr>
      <td style="vertical-align:middle">![On Star](/assets/library/hello-dart/intro/on-star.png)</td>
      <td style="vertical-align:middle">`onStar()`</td>
      <td style="vertical-align:middle">The player checks if he is on a star.</td>
    </tr>
  </tbody>
</table>


## Let's go

#### Installation

First you need to install the Dart Editor and the `Hello Dart` scenarios. It's described in those [installation instructions](/library/hello-dart/install/).


#### Background Infos

If you want to know more about why I recommend Dart for programming, see [background information](/library/hello-dart/background/).


***

### Copyright

I publish the `Hello Dart` materials under the [Creative Commons Attribution 4.0](http://creativecommons.org/licenses/by/4.0/) license. That means you can do pretty much everything you want with it. But you need to comply with the following:

* If you use my materials or programs, you must clearly indicate that I'm the original author of this material. Include my name, a link to the original and a link to the license. It could look something like the way I provide attribution to the images at the bottom of every page.


***

*Credits*<br>
<em class="small">
  [Planet Cute](http://www.lostgarden.com/2007/05/dancs-miraculously-flexible-game.html) images by Daniel Cook (Lostgarden.com), published under [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/us/).<br>
[Oleg Yadrov](https://www.linkedin.com/in/olegyadrov) improved the "Planet Cute" images and was so kind to let me use them. The images were optimized with the great [TexturePacker](https://www.codeandweb.com/texturepacker).
</em>
