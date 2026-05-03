# JM's Applied Mathematics and Statistics Notes

The complete collection of all my notes taken during my study at JHU WSE's Applied Math and Statistics.

Courses Taken:
- EN.553.632 Bayesian Statistics, FA25
- EN.553.634 Elements of Statistical Learning, FA26 Audit
- EN.553.636 Introduction to Data Science, FA25
- EN.553.639 Time Series Analysis, FA25
- EN.553.688 Computing for Applied Math, FA25
- EN.553.724 Probabilistic Machine Learning, SP26
- EN.553.730 Statistical Theory, FA26 Audit
- EN.553.733 Nonparametric Bayesian Statistics, SP26
- EN.553.734 AI and Statistical Methods in Clinical Data Science, FA26
- EN.553.747 Mathematics of Data Science, FA25 Audit
- EN.553.761 Nonlinear Optimization 1, FA26
- EN.553.762 Nonlinear Optimization 2, SP26
- EN.553.796 Random Matrix Theory in Data Science and Statistics, FA26

My thanks to all the wonderful faculty in the AMS department.

## Simple Compile
- cd into project folder after cd ..
- terminal: `latexmk -pdf -output-directory=output main.tex`

## Autosave + Live Compile
- cd into project folder after cd ..
- terminal: `latexmk -pdf -pvc -output-directory=output main.tex`

## Live Updates
- keep terminal running
- use `Cmd + S` to trigger rebuild
- navigate to tex file
- open PDF via:
  - `Cmd + Shift + P`
  - `LaTeX Workshop: View LaTeX PDF`
  - choose "View in VS Code tab"