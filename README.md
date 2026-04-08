# vsc-latex-sync

sub-files/treeing works

## Simple Compile:
- Copy the full absolute path
- terminal: `latexmk -pdf path/to/main.tex`

## Autosave and run
- run:
```
cd /path/to/project
latexmk -pdf -pvc main.tex
```
- use Cmd + S to update automatically