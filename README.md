# Maaz Ansari — SEO Content Writer &amp; SEO Specialist Portfolio

A static, dependency-free portfolio website for **Maaz Ansari**, SEO Content Writer &amp; SEO Specialist, built to showcase real SEO content writing work and to be hosted on **GitHub Pages**.

## Who this is

Maaz Ansari is an SEO content writer with approximately two years of practical, hands-on experience working with WordPress, Google AdSense-monetized sites, keyword research, on-page SEO, and search-focused blog/article writing. This site presents that work directly — real articles, restructured for the web, alongside honest case studies and a documented content workflow.

## What's in this portfolio

- **6 real articles**, sourced from the original portfolio repository (`.docx` files), converted into clean HTML web pages with proper H1/H2/H3 hierarchy, tables of contents, and FAQ sections (only where the source article actually contained one — none were invented).
- **2 SEO case studies** breaking down objective, target keyword, search intent, research, content strategy, on-page SEO, and publishing approach for the two most structurally complete articles. Where no measurable result is available, the case study says so explicitly (*"Performance data not publicly disclosed"*) rather than inventing a number.
- **Skills, workflow, and experience pages** describing the actual SEO/content skill set and a 9-step content workflow (keyword research &rarr; search intent &rarr; SERP research &rarr; content planning &rarr; writing &rarr; on-page SEO &rarr; review &rarr; WordPress publishing &rarr; optimization).

No clients, employers, certifications, rankings, traffic numbers, or revenue figures are claimed anywhere on this site unless they can be backed by evidence.

## SEO skills demonstrated

Keyword research, search intent analysis, SERP analysis, on-page SEO, content optimization, internal/external linking, meta title &amp; description optimization, H1/H2/H3 structuring, content gap analysis, local SEO content, FAQ content, and WordPress publishing/formatting. See the [Skills](skills.html) page for the full breakdown by category.

## Tools

Ahrefs, Google Search, WordPress, Google AdSense, AI-assisted writing tools, and plagiarism-checking tools — used as part of a normal editorial process, not as a substitute for research or original writing.

## Site structure

```
/
├── index.html              Homepage
├── about.html
├── experience.html
├── skills.html
├── workflow.html            9-step content workflow
├── work.html                 Featured work (curated selection)
├── articles.html             All 6 articles
├── case-studies.html         Case studies index
├── contact.html
├── README.md
│
├── articles/
│   ├── ghani-shinwari-restaurant/index.html
│   ├── cafe-crosta-multan/index.html
│   ├── kolachi-restaurant-ocean-mall/index.html
│   ├── burgreat-menu-rawalpindi/index.html
│   ├── tayto-cafe/index.html
│   └── safilo-ice-cream-rawalpindi/index.html
│
├── case-studies/
│   ├── ghani-shinwari-restaurant/index.html
│   └── cafe-crosta-multan/index.html
│
└── assets/
    ├── css/style.css
    ├── js/main.js
    └── images/favicon.svg
```

## Tech

Static HTML5 + CSS3 + vanilla JavaScript. No build step, no framework, no backend, no database. Fonts loaded from Google Fonts (Fraunces, Manrope, IBM Plex Mono). Fully responsive (375px &rarr; 1440px+), keyboard-accessible, and built with semantic HTML throughout.

## Deploying with GitHub Pages

1. Push all files in this repository to the `main` branch.
2. In the repository, go to **Settings &rarr; Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save. GitHub will publish the site at `https://maaz827.github.io/maaz-jaffar-portfolio/` within a few minutes.
5. Update the `<link rel="canonical">` and Open Graph URLs across the site if the final live URL differs from that address.

## Adding a new article yourself

1. Duplicate an existing folder under `/articles/` (e.g. `articles/burgreat-menu-rawalpindi/`) and rename it to your new article's slug.
2. Edit `index.html` inside it: update the `<title>`, meta description, canonical URL, H1, meta strip (category/location/word count), body content, and FAQ block (delete the FAQ block entirely if the article has none — don't invent one).
3. Add a matching row to `articles.html` and, if it's strong enough, a card to `work.html`.
4. Link it from the "Related Articles" section of at least one existing article.

## Content integrity note

Every article and case study on this site is built directly from Maaz's own original documents. Where an original document had structural or grammatical issues (see `articles/tayto-cafe/index.html`), those issues are flagged in an on-page editorial note rather than silently corrected, per the no-fabrication policy this portfolio was built under.
