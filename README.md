# vsc-latex-sync

sub-files/treeing works

## Simple Compile
- cd into project folder
- terminal: `latexmk -pdf main.tex`

## Autosave + Live Compile
- cd into project folder
- terminal: `latexmk -pdf -pvc main.tex`

## Live Updates
- keep terminal running
- use `Cmd + S` to trigger rebuild
- open PDF via:
  - `Cmd + Shift + P`
  - `LaTeX Workshop: View LaTeX PDF`
  - choose "View in VS Code tab"