# Elysian Radiance

This repository contains the static marketing site for Elysian Radiance, a luxury fire pit brand. The site is composed of standalone HTML documents styled by a shared `style.css` file and a collection of images.

## Project Structure

- `index.html` – splash page currently used as an under-construction notice.
- `preview.html` – primary marketing landing page that introduces the product line.
- `phoenix.html` – detailed sales page for the Phoenix fire pit founders edition.
- `about.html` – brand story and background information.
- `contact.html` – contact options and link to the inquiry form.
- `style.css` – shared typography and layout styles used across most pages.
- `images/` – renders, logos, and photography referenced by the pages.

## Development Notes

- Pages are static and can be served from any web server without a build step.
- Google Analytics tracking is embedded directly in the HTML files.
- Several pages still rely on extensive inline styles; consolidating these rules into `style.css` will make the design easier to maintain.
- Update the contact information in the HTML files if email addresses or representatives change.

## Previewing Locally

You can open any of the HTML files directly in a browser, or run a simple static server. For example, with Python installed:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000/preview.html](http://localhost:8000/preview.html) (or any other page) to preview the site.
