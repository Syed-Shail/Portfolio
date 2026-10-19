# Syed Shail Suheb — Portfolio

A responsive, static portfolio site for software engineering roles, with interests in AI and cybersecurity. It uses plain HTML, CSS and JavaScript, with no build step or runtime dependencies.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>. You can also open `index.html` directly, though serving it locally gives the closest preview to a hosted site.

## Publish

Upload this directory, including `index.html`, `styles.css`, `theme.css`, `project-links.js`, `script.js` and `Shail-Resume.pdf`, to any static host such as GitHub Pages, Netlify or Cloudflare Pages. No build command is needed. The site uses Google Fonts when an internet connection is available and falls back to local fonts otherwise. Before publishing, add your real URLs in `project-links.js`: set each project’s `demo` and `source` values to full `https://` URLs. Those links appear automatically on the project card and case study; leave a value empty until it is ready.

## Content notes

- The Retail Trends Explorer is an interactive analysis demo built with synthetic data. The API Reliability Playground is a deterministic local simulation.
- The UAE Car Valuation Lab is a reproducible model study on a historical UAE used-car listing snapshot. Its case study reports held-out metrics and limitations; the raw data is not redistributed because the upstream repository does not state a dataset license. The project code, reproducibility notes, and local run instructions are in a separate [GitHub repository](https://github.com/Syed-Shail/uae-car-valuation-lab).
- The achievement cards use the details currently available. Add the hackathon name and project, student-exchange destination, and sports in the matching cards in `index.html` if you want to make them more specific.
