# Shoe Site

Mobile first shoe site design using HTML, CSS and JS - [Take a look](https://shoe-site.vercel.app/)

[![Practice](https://img.shields.io/badge/Practice-HTML/CSS/JS-orange.svg)](https://shoe-site.vercel.app/)

_<p align="center">"Eating website for fun... nyom nyom nyom"</p>_

<div align="center" style="text-align:center; margin:auto;">
<img align="center" src="https://i.imgur.com/EgCvXyK.png" width="150"/>
</div>

## What it is

A basic warmup exercise. Simple, mobile first shoe site design Built with:

- HTML
- CSS
- Vanilla JS - ES6
- [Awesomeness](https://www.wikihow.com/Love-Programming) - Strictly for the love of coding :-)

## What it does

- Look pretty, that's about it :-)

## Learning Points

- UI/UX
- Interactive CSS
- Mobile First CSS
- Mobile Navigation
- CSS Animations
- JS

## Some cool stuff

Nothing much, basic way of navigation using Vanilla JS:

```javascript
const menu = document.querySelector(".menu");
const close = document.querySelector(".close");
const nav = document.querySelector("nav");

menu.addEventListener("click", () => {
  nav.classList.add("open-nav");
});

close.addEventListener("click", () => {
  nav.classList.remove("open-nav");
});
```

## Features in Development

I might add the other pages on the this website if I ever come back to refactor ^-^

## Contribution

Contributions are highly welcome. Feel free to fork, clone, make pull requests, report issues etc.

## Acknowledgments

- For everyone who is reading this... _You're awesome!_

That being said
_<p align="center">To the Front... to the Back... End to End... cut no slack. Making ends meet. lol</p>_
