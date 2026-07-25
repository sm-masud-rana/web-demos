# Restaurant / Café Demo — Saffron & Ember

A responsive, animated restaurant website created by **Md. Masud Rana** as a self-directed portfolio demonstration. All names, menu items, prices, reviews, contact details and business information are fictional.

## Live demo

`https://sm-masud-rana.github.io/web-demos/restaurant/`

If GitHub Pages is still deploying, wait 1–3 minutes and refresh.

## Run locally

1. Download or clone the `web-demos` repository.
2. Open the `restaurant` folder.
3. Double-click `index.html` or open it in any modern browser.

No npm install, build command or server is required.

## Features

- Full-screen restaurant hero
- Light entrance and scroll animations
- Responsive mobile navigation
- Digital menu tabs: Starters, Main Course, Drinks and Desserts
- Interactive demo reservation form
- Food gallery with hover zoom
- Fictional customer reviews
- Google Maps embed and opening hours
- Reduced-motion accessibility support

## Customize the website

Everything is inside `restaurant/index.html`.

### Restaurant name and text

Search for `Saffron & Ember` and replace it with the new restaurant name. Update the tagline, story, address, phone number and footer text directly in the HTML.

### Colors

At the beginning of the `<style>` section, edit these CSS variables:

```css
:root {
  --red: #781d21;
  --orange: #e35f28;
  --cream: #fff8ec;
  --sand: #f3e5d1;
}
```

### Menu and prices

Near the bottom of the file, find:

```js
const data = {
  starters: [],
  mains: [],
  drinks: [],
  desserts: []
};
```

Each item follows this format:

```js
['Item name', 'Short description', '$14']
```

### Images

Images currently use royalty-free Unsplash URLs. Replace any URL inside `src="..."` or `url('...')` with another image URL. For reliable production use, download optimized images and keep them in an `images` folder.

### Google Maps

Find the map iframe and replace its `src` query:

```html
https://www.google.com/maps?q=YOUR+LOCATION&output=embed
```

Replace spaces with `+`.

### Reservation form

The current form is a front-end demo. It validates fields and shows a success message, but does not send or store information. Before using it for a real business, connect it to a secure backend or a service such as Formspree, Netlify Forms or a booking platform.

## Deploy with GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Save and wait for deployment.

## Portfolio usage

You may show this as a self-directed demo project. Do not claim it was created for a real client. Suggested description:

> Responsive fictional restaurant website built as a self-directed portfolio demo using HTML, CSS and JavaScript.

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts
- Unsplash images
- Google Maps embed

No framework or build step is used.
