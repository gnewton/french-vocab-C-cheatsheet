# french-vocab-C-cheatsheet
Cheatsheet I created for my level C French oral exam

##
I have cloned [tim-st's](https://github.com/tim-st)
[latex-cheatsheet](https://github.com/tim-st/latex-cheatsheet) and
used it almost as-is (except for removing the content and replacing it
with my own).



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

Copyright Glen Newton 2020

