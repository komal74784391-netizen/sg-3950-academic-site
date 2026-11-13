# Academic site (Jekyll source)

Personal academic website source. The site is built from this repository; the
generated `_site/` directory is deployed separately.

## Publication entries

Every publication is a Markdown file under `_publications/`. Front matter fields:

- `title` - paper title
- `venue` - venue and status text, rendered verbatim
- `citation` - full citation text, rendered verbatim
- `codeurl` - optional URL of the code repository

`_includes/archive-single.html` renders `codeurl` as a **Code** button. If the
field is absent or empty, no button is rendered.

## Local preview

```
bundle exec jekyll serve
```
