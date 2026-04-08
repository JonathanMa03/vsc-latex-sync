# vsc-latex-sync

sub-files/treeing works

## To Compile:
- terminal: `latexmk -pdf path/to/main.tex`
- Put `% !TeX root = main.tex` at the top of every non-root file
- autocompile on save: 

```
cd path/to/project
latexmk -pdf main.tex
```