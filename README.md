# Light-Transport-Bibliography

A bibtex bibliography of papers, books and theses focusing on the topic of Light Transport Simulation.

### Usage
The bibliography can be used in LaTeX as any other would:
```
% in header of main.tex
\usepackage[backend=biber, style=ieee]{biblatex}
\addbibresource{lib_Books.bib}
\addbibresource{lib_Papers.bib}
...
% document contents
...
\printbibliography
```

### Style
This bibtex library for Light Transport Simulation combines the citation key style and the convenience of Google Scholar, with the entry completeness provided by other digital libraries. Most of the entries featured in this library were extracted from the ACM Digital Library, the Wiley Online Library, and Springer Link. A few entries were created/modified by hand to fix issues and mistakes. A custom script was used to ensure that all entries were formatted in the same style (e.g. indentations, braces), which allows for better visual parsing. In this library, braces are used instead of quotation marks; to avoid dependency on the automatic expansion, all *month* entries are given as integers.
In general, we seek to embed as much information as possible into each entry; however, we do deliberately omit the abstract of each paper.

### Collaboration
In case you notice any errors, inaccuracies or missing information please let me know via an issue! The same holds if you think that there are important papers missing. I'm very happy to add entries given that they are related to the topic. It may just take me a few days to read the suggested paper.