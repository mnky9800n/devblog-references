# devblog-references

Rewrites devblog entries to include proper academic citations using pandoc.

You need to have a file structure like this:

```
root/
└── devblog/
    ├── devblog1.md
    └── refs.bib
```

on push the `devblog-references` action will rewrite all `*.md` entries to have proper academic citations and a references section.

The `refs.bib` file should follow normal bibtex styling.

This allows you to store bibtex style references in your repo if you are going to later write a paper about your computational efforts.
