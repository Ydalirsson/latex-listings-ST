# latex-listings-ST

This repo shows a template for code highlighting **Structured text** (ST) in **LaTeX**.
For code highlighting in LaTeX you can use the LaTeX-package _listings_. The package includes a lot of different schemes and styles for a lot of programming languages, but *Structured Text* isn't an option yet. So I decided to create a custom scheme you can use, if you want to display Structured text in LaTeX. ST is a high level programming language, defined in EN 61131-3, for writing programmable logic controllers (PLCs). 
The color scheme is based on the syntax highlighting of IDEs for PLC programming, like IndraWorks or TwinCAT.

The scheme is defined in _codestyle.tex_ and _example.tex/pdf_ shows an example how it looks like. Make sure to include
```
\usepackage{listings}
\usepackage{xcolor}
```
