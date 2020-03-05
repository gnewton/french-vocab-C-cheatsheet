# french-vocab-C-cheatsheet
Cheatsheet I created for my level C French oral exam. [Link to PDF](https://github.com/gnewton/french-vocab-C-cheatsheet/raw/master/gnfrench.pdf).


##
I have cloned [tim-st's](https://github.com/tim-st)
[latex-cheatsheet](https://github.com/tim-st/latex-cheatsheet) and
used it almost as-is (except for removing the content and replacing it
with my own).

If you are using texlive, you will haver to install `texlive-fonts-extra`.

## How to use
I have added a new LaTeX command `\fr`:

```tex
\fr{french-word}{word's-french-article}  {english-definition}
```

It prints out:

_word's-french-article-french word_ = english-definition

The french word is in _italic_


This allows me to sort words by word, not by their article (for
nouns).
For non-nouns, leave the second brace brackets empty, `{}`, like:
```tex
\fr  {aborder}{}   {to approach}
```

## Margins
**NB**: When viewing the PDF in a viewer, it may look cut-off at the margins.
On my printer it prints ok.
If text at the margins gets cut-off at the margins when you print it,
edit `gnfrench.tex` in the lines below for the margins ("-2mm")
to something more positive, like zero (0):
```tex
%%%%%%%%%%%Edit below to adjust print margins
\usepackage[top=0mm,bottom=-2mm,left=-2mm,right=-2mm]{geometry}
%%%%%%%%%%%
```
edited to zero:
```tex
%%%%%%%%%%%Edit below to adjust print margins
\usepackage[top=0mm,bottom=0mm,left=0mm,right=0mm]{geometry}
%%%%%%%%%%%
```

# Caveat emptor
**NB:** There will likely be errors both in spelling and in meaning in this document, as much as I have tried hard to verify this information.
I am not a native french speaker, and this has not been validated by a native french speaker or expert in the french language.


Copyright Glen Newton 2020

