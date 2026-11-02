# ENO product site (static front-end)

A static, Spanish-language HTML/CSS build of a product website for ENO, an antacid brand. The footer copy targets residents of Chile.

## Context

The whole repository is one commit from February 2021 by Pablo Malczewski. Nothing in the repo says whether this was paid client work or a practice exercise built from a design. So treat it as an early front-end project, not as a site known to have shipped. The brand names, logos, product photos and legal texts belong to their owner. They are here only because the build reproduces the brand's pages.

## What it does

- 11 static pages: a home page with a Bootstrap carousel, products (flavours and pack sizes), "¿Qué es la acidez?" (what heartburn is), an FAQ page using Bootstrap collapse panels, contact, and six legal pages (terms, privacy, cookies, accessibility, acceptable use, copyright).
- A shared sticky navbar and footer, repeated by hand on every page. There is no templating or build step.
- Responsive layout built on Bootstrap's grid, plus per-section stylesheets in `style/componentes/`.

Known gaps: the "¿Dónde comprar ENO?" (where to buy) link points to `donde_comprar_eno.html` on some pages and to the FAQ page on others. The first page does not exist, and `style/componentes/donde_comprar.css` is empty.

## Stack

HTML5, CSS3 and Bootstrap 4.5.2, with jQuery 3.5.1 and Popper.js 1.16.1 loaded from CDNs. There is no custom JavaScript.

## Run it

No install is needed. Open `index.html` in a browser, or serve the folder with any static server (for example `python3 -m http.server`). The CDN assets need an internet connection.

## Status

Archived early front-end project (2021), not maintained.
