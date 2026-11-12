# QUASY 2027 website

Source of https://quansyntax.github.io/quasy2027/, the website of QUASY 2027,
the 4th Workshop on Quantitative Syntax (part of SyntaxFest 2027, Prague).

- Plain static HTML (`index.html`, `cfp.html`, `committee.html`) and one shared
  stylesheet (`css/style.css`); no framework, no build step.
  GitHub Pages publishes the `main` branch as is.
- Colours and fonts are CSS variables at the top of `css/style.css`.
- Registration, venue and visa information live on the SyntaxFest site;
  this site links there instead of repeating them.

## Using this site as a template for a later QUASY

1. Copy this repository to `quasyYYYY` under the quansyntax account and
   enable GitHub Pages (branch `main`, root folder).
2. Replace the logo year, the hero photo (`images/photo-*.jpg`, with credit
   in the footer), dates, links and text. Adjust the hero crop
   (`object-position` in `.hero-photo img`) to the new photo.
3. Update `og:*` tags in each page head and `images/og-image.jpg`
   (1200 × 630, used for link previews).
4. Add the new edition to the series page (https://github.com/quansyntax/quasy).

The shared colours, fonts and logo rules are described in the README of
the series page repository.

## Photo credit

“Swans in front of Charles Bridge, Prague” by Pierre Blaché, via Wikimedia
Commons, CC0 1.0.
