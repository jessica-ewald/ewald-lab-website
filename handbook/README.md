# How to update the handbook

The handbook is created using [mkdocs-material](https://squidfunk.github.io/mkdocs-material/). To specify the structure, add pages and links to mkdocs.yml. If you're not finished drafting a page, comment out the nav lines in that file. To build the documentation:
```
cd handbook
mkdocs build
```

This will generate the html and css files in the **site** directory. 