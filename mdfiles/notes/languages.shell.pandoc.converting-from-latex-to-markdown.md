---
id: cartyoud4mkk3btdsq28gl5
title: Converting from Latex to Markdown
desc: ''
updated: 1706735358488
created: 1706735207826
---

To convert from LaTeX to markdown, you need:

1. to have the bibligraphy file which can be fed in with the `--bibliography` flag
2. feed something in like this:

```sh
pandoc -s test.tex --bibliography=lib.bib -o test.md
```