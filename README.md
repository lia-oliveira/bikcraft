<h1> Bike Craft </h1>

This repo contains the solution to the final project of the [Origamid](https://www.origamid.com/curso/html-e-css-para-iniciantes/0101-html-e-css-para-iniciantes) HTML and CSS course.

Table of Contents:
- [Screenshots](#screenshots)
- [Process](#process)
  - [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)




# Screenshots

👷🏼‍♀️ Work in progress

# Process

## Built with
👷🏼‍♀️ Work in progress

# What I learned
1 - Para que o pseudo-elemento seja exibido é preciso declarar a propriedade display.
```css
.products ul h3::before {
    ...
    display: inline-block;     
}
```
2 - A propriedade transition pode ser aplicada somente a largura quando necessário:
```css
.products ul h3::before {
    ...
    transition: width 0.2s;
}

.products ul a:hover h3::before {
    width: 1.5rem;
}
```
3 - É possível criar um scroll horizontal em um container:
```css
.products ul {
overflow-y: hidden;
overflow-x: scroll;
}  
```



# Useful resources
👷🏼‍♀️ Work in progress

- MDN Web Docs. Aria. Avaiable at: <[https://developer.mozilla.org/pt-BR/docs/Web/Accessibility/ARIA](https://developer.mozilla.org/pt-BR/docs/Web/Accessibility/ARIA)>. Acessed on: 15-12-2024.
- MDN Web Docs. Marker. Avaiable at: <[https://developer.mozilla.org/en-US/docs/Web/CSS/::marker](https://developer.mozilla.org/en-US/docs/Web/CSS/::marker).Acessed on: 15-12-2024>
- https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Accessibility
- CSS-position Property Examples: [https://css-tricks.com/almanac/properties/o/object-position/](https://css-tricks.com/almanac/properties/o/object-position/)

# Author
👷🏼‍♀️ Work in progress


# Acknowledgments
👷🏼‍♀️ Work in progress
