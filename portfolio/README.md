# Yegon J. Caroline Portfolio

A responsive full stack developer portfolio built with semantic HTML, Tailwind CSS via CDN, and vanilla JavaScript.

## Preview locally

Open `index.html` in a browser. Tailwind CSS and Google Fonts load from their CDNs, so an internet connection is needed for those styles and fonts.

## Deployment

The repository workflow in `.github/workflows/deploy-portfolio.yml` publishes the contents of this folder to GitHub Pages when changes are pushed to `main`. Merge the portfolio branch into `main` to publish it. The contact form currently performs browser-side validation only and does not send or store submissions.

## Structure

- `index.html` - portfolio sections and page content
- `script.js` - mobile navigation, form validation, and active section navigation
- `assets/` - project preview graphics
- `assets/cv/` - downloadable CV PDF

## Details to complete together

- Replace project preview illustrations with screenshots of the actual projects.
- Add confirmed live site and repository links for Grace Beauty and Maison.
- Add the bachelor's programme title, education completion years, and any confirmed certificates or experience to the CV draft.
- Confirm whether Amani Crest Academy and Jebwach Tours should be featured.
- The contact form validates in the browser only; it does not submit or store messages.
- The CV button downloads a working draft PDF; update it as details are confirmed.

## Technologies

HTML5, Tailwind CSS CDN, vanilla JavaScript, PHP, and MySQL (the latter three are included only as project skills, not dependencies of this portfolio page).
