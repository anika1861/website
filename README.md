# alexander-anikin.eu

Personal website of Alexander Anikin, MD, served by GitHub Pages from the `main` branch at https://alexander-anikin.eu.

The site is plain HTML and CSS with no build step, no JavaScript, no cookies and no third-party requests. What is in this repository is exactly what the site serves.

## Pages

| File | Page |
| --- | --- |
| `index.html` | Home, with the table of trials by indication and phase |
| `about.html` | About, education and credentials |
| `experience.html` | Experience |
| `case-studies.html` | Case studies |
| `writing.html` | Writing and speaking |
| `impressum.html` | Impressum (German legal notice) |
| `datenschutz.html` | Datenschutzerklärung (privacy policy) |
| `404.html` | Page not found |

## Files for search engines and AI agents

- `llms.txt`: a short summary of the site and a note for AI agents, following the llms.txt convention
- `llms-full.txt`: the text of every page as Markdown in one file
- `sitemap.xml` and `robots.txt`: everything may be crawled, by search engines and AI crawlers alike
- Each page carries schema.org structured data (JSON-LD) describing Alexander Anikin as a Person

When a page changes, update `llms.txt`, `llms-full.txt` and the `lastmod` dates in `sitemap.xml` to match.

## Assets

- `assets/site.css`: all styles, with light and dark themes
- `assets/fonts/`: Newsreader and Red Hat Text, self-hosted (SIL Open Font License)
- `assets/portrait.jpg`: portrait on the About page
- `assets/og-image.png`: preview image for links shared on LinkedIn and elsewhere
- `assets/favicon.svg`, `assets/apple-touch-icon.png`, `favicon.ico`: browser and phone icons
- `cv/alexander-anikin-cv.pdf`: the downloadable CV

## Editing

Each page is a self-contained HTML file; the header and footer are repeated in every page, so a change to the navigation has to be made in all of them. Commit to `main` and GitHub Pages publishes the change within a minute or two.

`CNAME` holds the custom domain and `.nojekyll` tells GitHub Pages to serve the files as they are.
