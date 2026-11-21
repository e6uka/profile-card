# Profile Card

A three-page personal profile site built with plain HTML, CSS and JavaScript. It was made as a front-end exercise and carries `data-testid` attributes on its key elements for automated tests.

- Home: a profile card with name, bio, social links and the current time in milliseconds (`Date.now()`)
- About Me: sections for bio, goals, areas of low confidence, a note to a future self and extra thoughts
- Contact: a form that validates name, email, subject and message and shows an error under each field

Live site: https://e6uka.github.io/profile-card/

## Stack

HTML, CSS and JavaScript with no build step and no dependencies. The Aleo font is loaded from Google Fonts.

## Getting started

Open `index.html` in a browser, or serve the folder:

```bash
npx serve
```

## Files

- `index.html`, `about.html`, `contact.html`: the three pages, each with its own inline styles and script
- `1 1.png`: the avatar image
- `NOTES.md`: a manual test script for page load, mobile layout and accessibility

## Deployment

Published with GitHub Pages from the default branch.
