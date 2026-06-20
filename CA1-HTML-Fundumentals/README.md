# HTML Fundamentals

## Overview
The first assignment focused entirely on semantic, accessible HTML — no CSS, no JavaScript. The goal was to demonstrate fluent, purposeful use of HTML tags and document metadata, with every choice of element judged on whether it was the *right* tag for the job.

## What's Inside

### Q1 — Personal Profile Page
A self-introduction page built using a deliberately wide vocabulary of HTML elements: headings, paragraphs, links, images, lists, semantic sectioning tags (`header`, `main`, `section`, `footer`, etc.), and inline text-formatting tags. Written in Persian and using the `dir` attribute to correctly render right-to-left text.

### Q2 — SEO & Metadata Page
A page demonstrating practical use of the `<meta>` tag for information that's invisible in the rendered page but meaningful to browsers and search engines: a last-modified date, an author tag, and SEO-relevant keywords. Also includes an external link, a `<form>`-based button that navigates to an external resource, a downloadable image link, and a data table built with `<thead>`, `<tbody>`, and `<tfoot>`, using `colspan` to merge cells.

### Q3 — Survey Form
A multi-field feedback form covering the full range of standard HTML input types: text, date, tel (with a regex `pattern` and matching `placeholder`), email, radio buttons, checkboxes, a `<select>` dropdown, and free-text fields — submitting to redirect the user to an external URL.

## Key Skills
- Semantic HTML5 (`header`, `main`, `section`, `article`, `footer`)
- Document `<meta>` tags for SEO and authorship
- HTML forms and native browser validation (`pattern`, `required`, input types)
- Tables with `thead` / `tbody` / `tfoot` and column spanning
- Internationalization basics (`dir="rtl"`)

## What I Learned
Working without any CSS forced a focus on structure and meaning over appearance — picking the right semantic tag for the right purpose, understanding how search engines and browsers read metadata differently from human readers, and relying on native HTML form validation before reaching for JavaScript.

## Folder Structure
```
CA1-HTML-Fundamentals/
├── Q1/
├── Q2/
└── Q3/
```