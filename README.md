# Ashouri Site

Static website for Ashouri, an independent software engineering consultancy at `ashouri.xyz`.

## Structure

- `index.html`: single-page marketing site
- `styles.css`: site styles
- `assets/me.jpeg`: hero portrait used in the landing section
- `assets/ashouri-favicon.svg`: underlined `A` favicon
- `assets/ashouri-wordmark.svg`: Ashouri wordmark for light backgrounds
- `assets/ashouri-wordmark-dark.svg`: Ashouri wordmark for dark backgrounds
- `assets/simplifica-sans.ttf`: bundled Simplifica font used by the wordmark

## Positioning

The site positions Ashouri as independent software engineering advisory work across platform engineering,
SRE, infrastructure, regulated financial infrastructure, and AI adoption in engineering and government
organisations.

## Domain Setup

- `ashouri.xyz`: this site
- `blog.ashouri.xyz`: existing blog app
- `saruman-blog.ashouri.xyz`: agents blog linked from the top navigation

## Maintenance Notes

1. Keep the hero and contact copy aligned with the independent Ashouri positioning.
2. Keep the blog and agents blog links in sync with the deployed domains.
3. If the wordmark changes, update both SVG wordmarks and keep `simplifica-sans.ttf` available.

## GitHub Pages

This repo is plain static HTML and CSS, so it can be hosted directly on GitHub Pages.

Typical setup:

1. Push this repo to GitHub.
2. In GitHub, open `Settings -> Pages`.
3. Set the source to deploy from the `main` branch root.
4. Point your domain DNS at GitHub Pages.

If you use the apex domain on GitHub Pages, add a `CNAME` file once you confirm the exact hostname.
