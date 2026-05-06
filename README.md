# JM's Applied Mathematics and Statistics Notes

This repository is a consolidated collection of my personal notes compiled during my graduate studies in the Department of Applied Mathematics and Statistics at [Johns Hopkins University](https://engineering.jhu.edu/ams/).

The material were created as a personal "To-Go" reference covering topics in statistics, learning, and optimization

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

Special thanks to the faculty of the [AMS Department](https://engineering.jhu.edu/ams/faculty/) for their excellent instruction and mentorship, along with their course materials.

---

## Disclaimer

These notes are a mash-up from me based on:
- lectures
- supplemental readings
- textbooks
- personal notes
- in-class QnA.

They are **not official course materials** and may contain errors, omissions, or personal interpretations of concepts. I am a practitioner and not a theorist, so some material (proofs especially) may be omitted.

All copyrights for referenced textbooks, lecture content, figures, and external materials remain with their respective authors and publishers. This repository is intended strictly for educational and reference purposes.

This repository does **not** contain:
- past assignments, exams, and solutioms
- graded assignments and projects (you can browse my GitHub for projects)

### AI Disclosure

Some formatting assistance, editing, restructuring, and explanatory expansion were performed with the assistance of AI tools, including Underleaf AI, ChatGPT, and Notion. Final organization and compilation are entirely performed by yours truly.

---

# Compile Instructions

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
