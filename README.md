# #7daysofcode challenge from Alura's course

This is a 7 day code challenge to develop a page from a figma file using my HTML & CSS knowledge.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)



## Overview

### Screenshot

![](/img/screenshot.png)


### Links

- Live Site URL: [OptimusTech](https://ffernandocosta.github.io/OptimusTech-page-7DaysOfCode-Alura/)

## My process

I approached this project and took my time doing each section day by day as the challenge suggested.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

I learned how to build a page from a figma file, extracting information like font-size, weight and font-family, downloading images and logos and using google fonts was really helpful. Learned how to do lists and build a page section by section.


```html
<h1>Some HTML code I'm proud of</h1>
 <ul class="about-us__list">
                <ul class="list__items">
                    <li class="list__number">400+</li>
                    <li class="list__item"><p class="item__title">Projetos concluídos</p></li>
                    <li class="list__item"><p class="item__paragraph">Nós ajudamos a construir mais de 400 projetos incríveis.</p></li>
                </ul>
                <ul class="list__items">
                    <li class="list__number">100+</li>
                    <li class="list__item"><p class="item__title">Colaboradores</p></li>
                    <li class="list__item"><p class="item__paragraph">Temos mais de 100 colaboradores no nosso time que se preocupam com nossos clientes.</p></li>
                </ul>
                <ul class="list__items">
                    <li class="list__number">20k</li>
                    <li class="list__item"><p class="item__title">Downloads</p></li>
                    <li class="list__item"><p class="item__paragraph">Nossos projetos que estão disponíveis em lojas já foram baixados mais de 20.000 vezes.</p></li>
                </ul>
                <ul class="list__items">
                    <li class="list__number">500+</li>
                    <li class="list__item"><p class="item__title">Reviews 5 estrelas</p></li>
                    <li class="list__item"><p class="item__paragraph">Estamos orgulhosos de contar com mais de 500 reviews 5 estrelas em nossos produtos.</p></li>
                </ul>
            </ul>
```
```css
.proud-of-this-css {
  .collaboratos {
    text-align: center;
}

.collaborators__box {
    display: flex;
    flex-direction: column;
    text-align: center;
    gap: 1em;
    margin: 4em 7em;
    background: rgba(196, 25, 25, 0.03);
    border-radius: 16px;
    padding: 3em 4em;
}
```


## Author

- Website - [Fernando Costa](https://github.com/ffernandocosta)
