# Light-Transport-Bibliography

A bibtex bibliography of papers, books and theses focusing on the topic of Light Transport Simulation.

### Usage
The bibliography can be used in LaTeX as any other would:
```
\usepackage[backend=biber, style=ieee]{biblatex}
\addbibresource{lib_Books.bib}
\addbibresource{lib_Papers.bib}
...
\printbibliography
```

### Style
The citation key style was adopted from google scholar (exporting bibtex entries) where unusual surnames were handled on a case by case basis (eg. van Antwerpen). Most of the entries were extracted from the ACM Digital Library, the Wiley Online Library and Springer Link, very few were also created by hand to fix issues and inaccuracies. The general idea is to embedd as much information as possible in the entries by using more than the data google scholar provides for citations. One counter example is the deliberate lack of abstracts.

A custom script was used to format entries in the same style (indentations and braces) to allow better visual parsing. Braces are used instead of quotation marks which implies that **month** entries are mostly given as integers (to not depend on the automatic expansion).

### Collaboration
In case you notice any errors, inaccracies or missing information please let me know via an issue! The same holds if you think that there are important papers missing. I'm very happy to add entries given that they are related to the topic. It may just take me a few days to read the suggested paper.