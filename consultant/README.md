# Business Consultant / Coach Demo — Maya Bennett

A modern, responsive business consultant and coach website created by **Md. Masud Rana** as a self-directed portfolio demonstration.

All names, credentials, programs, statistics, testimonials and business details are fictional. This project does not represent a real client engagement.

## Live demo

`https://sm-masud-rana.github.io/web-demos/consultant/`

GitHub Pages may take 1–3 minutes to deploy a new commit.

## Run locally

1. Download or clone the `web-demos` repository.
2. Open the `consultant` folder.
3. Double-click `index.html` or open it with a modern browser.

No installation, npm command, framework, build step or local server is required.

## Main features

- Hero section with consultant name, tagline, profile photo and CTA
- About, mission, expertise and fictional credentials
- Six service/program cards
- Results statistics and fictional success story
- Automatic testimonials carousel with navigation controls
- Booking/contact form with demo confirmation
- Newsletter signup interaction
- Social links and portfolio disclaimer
- Smooth scroll and reveal animations
- Responsive mobile navigation
- Reduced-motion accessibility support

## Customize the website

Everything is contained in `consultant/index.html`.

### Name, tagline and content

Search for `Maya Bennett` and replace it with the new consultant or coach name. Update the hero tagline, About section, services, credentials and footer directly in the HTML.

### Brand colors

At the top of the `<style>` block, edit the CSS variables:

```css
:root {
  --forest: #274c3b;
  --dark: #173127;
  --sage: #dce8dc;
  --cream: #fbf7ef;
  --coral: #e4785b;
  --gold: #d6a84e;
}
```

### Profile and section images

Images use royalty-free Unsplash placeholder URLs. Search for `images.unsplash.com` and replace each URL with another royalty-free image or your own hosted image.

For production, download optimized images and store them in an `images` folder instead of relying on remote URLs.

### Services and programs

Find the cards inside the `#services` section. Each `<article class="card">` contains:

- Program label
- Icon
- Program name
- Short description
- Contact link

Copy an existing card to add another service or delete a card to remove it.

### Results and testimonials

The statistics and testimonials are fictional demo content. Replace them only with honest, verifiable information before using the website for a real professional.

### Booking form

The booking form currently validates fields and displays a demo success message. It does not send or store data.

For real enquiries, connect it to a secure backend, CRM, scheduling platform, or a form service such as Formspree or Netlify Forms. Add an appropriate privacy notice before collecting personal information.

### Newsletter form

The newsletter form is also a front-end demonstration. Connect it to an email platform such as Mailchimp, ConvertKit or Brevo before real use.

### Social links

The footer social buttons currently use `href="#"`. Replace these with real profile URLs:

```html
<a href="https://linkedin.com/in/USERNAME">in</a>
```

## Deploy with GitHub Pages

1. Open the `web-demos` repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Save and wait for deployment.

The consultant demo will be available at:

`https://sm-masud-rana.github.io/web-demos/consultant/`

## Suggested portfolio description

> Responsive business consultant and coach website built as a self-directed portfolio demo using HTML, CSS and vanilla JavaScript. Includes program cards, fictional results, testimonial carousel, contact form and newsletter interaction.

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts
- Unsplash placeholder images

## Important portfolio note

Present this work as a **self-directed practice project**. Do not claim that Maya Bennett, the programs, results or testimonials are real, and do not imply a client relationship.
