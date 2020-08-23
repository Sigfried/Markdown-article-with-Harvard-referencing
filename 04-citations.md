# How to cite using Markdown

The last thing I'd like to demonstrate is the use of citations. It's incredibly simple using Markdown.

In the ```references.bib``` section of this template you will find a single reference, an article by Linda Candy from 2014 entitled **Interactive Experience in the Digital Age**. 

This reference is in what is known as ```BibTeX``` format, and was auto-generated via Mendeley. Any decent reference manager should be able to generate a BibTeX entry, or even an entire library of BibTeX entries, with very little effort.

Your own library of references should be added to the ```references.bib``` file from your reference manger of choice.

## Citing a reference in the text

Markdown has a very simple command for citations: ```[@citationkey]```. The citation key is normally in the format ```AuthorYear```, with no spaces. So, to cite Linda Candy's 2014 article **Interactive Experience in the Digital Age** you would add a reference to a sentence in the following manner:

```[@Candy2014] states that the evaluation of interactive art...```

Which the LaTeX interpreter compiles and displays in the following manner:

[@Candy2014] states that the evaluation of interactive art...

As you can see, the citation key has been replaced by the appropriate citation style, which in this instance is the Harvard referencing format.

Also, you will notice that this reference has automatically been placed in the references section at the end of this PDF document. Neat, not to mention infinitely quicker and better than referencing things manually. **\*shiver\***