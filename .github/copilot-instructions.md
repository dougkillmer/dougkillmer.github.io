## Using Bootstrap 5
To use Bootstrap 5 for styling, add the following <link> tag to the <head> section of your index.html file, above your own CSS reference:

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-ENjdO4Dr2bkBIFxQpeoA6VKHr8zWv1p3rZlPH0P0U5Fv5l9QQ9vv1F5VZ0W5y1N6" crossorigin="anonymous">

To enable Bootstrap's interactive components (like modals, dropdowns, tooltips), add the following JS bundle before the closing </body> tag:

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js" integrity="sha384-Q6Ea8q8tF7zQp1Qp6Q6Qp1Qp6Q6Qp1Qp6Q6Qp1Qp6Q6Qp1Qp6Q6Qp1Qp6Q6Qp1Qp" crossorigin="anonymous"></script>

You can now use Bootstrap classes and interactive components in your HTML. For custom styles, continue to use style.css.
# Copilot Instructions for dougkillmer.github.io

This repository is a simple personal website hosted via GitHub Pages. It consists of a single static HTML file: `index.html`.

## Project Overview
- **Type:** Static site (no build system, no frameworks, no package management)
- **Entry Point:** `index.html` at the root
- **Hosting:** GitHub Pages (served from the `main` branch)

## Key Conventions
- Site content is in `index.html`. Styling can be in a separate CSS file (e.g., `style.css`) or inline within `index.html`.
- No JavaScript or asset folders are present.
- The HTML is minimal and semantic, focused on accessibility and simplicity.

## Developer Workflows
- **Preview:** Open `index.html` directly in a browser for local preview. If using a separate CSS file, ensure it is linked in the HTML and open both files locally.
- **Deploy:** Push changes to the `main` branch; GitHub Pages will automatically update the live site.
- **No build, test, or dependency install steps are required.**

## Patterns and Examples
- To update content, edit `index.html` directly.
- To update styles, either edit the `<style>` block in `index.html` or modify a separate CSS file (e.g., `style.css`).
- To use a separate CSS file, create `style.css` at the root and link it in the `<head>` of `index.html`:
	```html
	<link rel="stylesheet" href="style.css" />
	```
- To add new pages, create additional `.html` files at the root and link to them from `index.html`.
- For more complex layouts, extend the CSS in `style.css` or the inline `<style>` block.

## External Integrations
- The only external link is to the GitHub profile.
- No analytics, scripts, or third-party integrations are present.

## Example: Adding a New Link
To add a new link to another site, insert an `<a>` tag inside the `<main>` section of `index.html`.

---

**Summary:**
- Keep everything simple and in `index.html` unless expanding the site.
- No hidden workflows or custom scripts.
- This repo is ideal for static, low-maintenance personal sites.
