# Ehsan Ashouri Site

Static freelance website for `ashouri.xyz`.

## Structure

- `index.html`: single-page marketing site
- `styles.css`: site styles
- `assets/me.jpeg`: hero portrait used in the landing section

## Recommended domain setup

- `ashouri.xyz`: this site
- `blog.ashouri.xyz`: existing blog app

If you prefer keeping the blog on the main domain temporarily, link to it from the navigation and move it later.

## Before publishing

1. Add your direct email address or scheduling link in the contact section.
2. Update outbound links if you move the blog to `blog.ashouri.xyz`.

## GitHub Pages

This repo is plain static HTML and CSS, so it can be hosted directly on GitHub Pages.

Typical setup:

1. Push this repo to GitHub.
2. In GitHub, open `Settings -> Pages`.
3. Set the source to deploy from the `main` branch root.
4. Point your domain DNS at GitHub Pages.

If you use the apex domain on GitHub Pages, add a `CNAME` file once you confirm the exact hostname.
