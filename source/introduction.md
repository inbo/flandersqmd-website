---
title: Introduction
toc: false
---
 
This document is only intended to display all elements from the corporate identity.

## Lipsum

Lorem ipsum is simply dummy text of the printing and typesetting industry. 
Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. 
It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. 
It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## Things to keep in mind

- Every `.md` or `.qmd` should have a title and no level 1 heading (`#`).
- Quarto renders all files separately.
  If you want to reuse a code object from one file in another file, you need to store the object when running the code in the first file (e.g. with `saveRDS()`) and read that object when running the code of the second file (e.g. with `readRDS()`).
  Likewise, you need to list what packages to use in every file.
- You can use a link to a [section](static-figure.html#sec-static-figure) in a different file, but you cannot use the automatic cross reference feature of Quarto to create links between files.
- The numbering in every file starts at 1.
- Add `toc: false` to a file to hide the file specific table of content shown on the righthand side of the page.
