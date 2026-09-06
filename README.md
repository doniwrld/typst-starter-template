# Typst Thesis Starter Template

A simple Indonesian thesis/dissertation starter template built with [Typst](https://typst.app/).

## Included

- Cover page, Indonesian abstract, English abstract, and table of contents
- Five sample chapters
- Header, footer, page numbers, tables, and a dummy figure
- IEEE citations using a BibTeX file

## Start

1. Open this folder in VS Code.
2. Install the **Tinymist Typst** extension.
3. Open `main.typ` and run Typst Preview.
4. Update your university, title, author, and supervisor details at the top of `main.typ`.

## Citations with Mendeley

Export your Mendeley library as a BibTeX (`.bib`) file and merge it into `references.bib`. Cite an entry in your document with its citation key:

```typst
@knuth1984
```

The bibliography is generated automatically by `main.typ`.

## Build PDF

```sh
typst compile main.typ thesis.pdf
```

This is a generic starter template. Adjust the layout and citation style to match your university guidelines.
