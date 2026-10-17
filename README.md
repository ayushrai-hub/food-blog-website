# Food Blog Website

A static food blog built with plain HTML, CSS, and JavaScript. Based on the W3Layouts "Foodie Blog" Bootstrap template, customized for personal use.

## Pages

- `index.html` - home page with a banner, featured blog cards, and a subscribe section
- `about.html` - about page
- `contact.html` - contact page with a form (posts to the template's default W3Layouts mail endpoint)

## Stack

- Bootstrap 4 for layout (`css/style-starter.css`)
- jQuery 3.3.1 plus a few plugins: Owl Carousel (sliders), Magnific Popup (lightbox), a counter script, and a light/dark theme toggle (`js/theme-change.js`)
- Font Awesome webfonts for icons

## Run it

No build step. Open `index.html` in a browser, or serve the folder with any static server:

```
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Notes

- Everything is static; there is no backend. The search box and contact form still point at the template's original endpoints and would need real backends to work.
- `blog-single.html` is linked from the home page but not included yet.
