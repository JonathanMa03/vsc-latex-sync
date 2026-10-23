# JM's Applied Mathematics and Statistics Notes

This repository is a consolidated collection of my personal notes compiled during my graduate studies in the Department of Applied Mathematics and Statistics at [Johns Hopkins University](https://engineering.jhu.edu/ams/).

The material were created as a personal "To-Go" reference covering topics in statistics, learning, and optimization

## Courses Taken

| Course Number | Course Name | Term | Last Updated |
|---|---|---|---|
| [EN.553.632](632_BayesianStatistics/632_main.pdf) | Bayesian Statistics | FA25 | 12/31/2025 |
| [EN.553.634](634_StatisticalLearning/634_main.pdf) | Elements of Statistical Learning | FA26 | 10/22/2026 |
| [EN.553.636](636_IntroDataScience/636_main.pdf) | Introduction to Data Science | FA25 | 12/31/2025 |
| [EN.553.639](639_TimeSeriesAnalysis/639_main.pdf) | Time Series Analysis | FA25 | 12/31/2025 |
| [EN.553.688](688_ComputingAppliedMath/688_main.pdf) | Computing for Applied Math | FA25 | 12/31/2025 |
| [EN.553.724](724_ProbabilisticML/724_main.pdf) | Probabilistic Machine Learning | SP26 | 5/20/2026 |
| [EN.553.730](730_StatisticalTheory/730_main.pdf) | Statistical Theory | FA26 | 10/22/2026 |
| [EN.553.733](733_NonparametricBayes/733_main.pdf) | Nonparametric Bayesian Statistics | SP26 | 5/20/2026 |
| [EN.553.734](734_AIforClinicalDS/734_main.pdf) | Generative AI and Statistical Methods in Clinical Data Science and Biopharamceutical Statistics | FA26 | 10/22/2026 |
| [EN.553.740](740_MachineLearning1/740_main.pdf) | Machine Learning 1 | FA26 | 10/22/2026 |
| [EN.553.747](747_MathOfDataScience/747_main.pdf) | Mathematics of Data Science | FA25 | 12/31/2025 |
| [EN.553.761](761_NonlinearOptimization1/761_main.pdf) | Nonlinear Optimization 1 | FA26 | 10/22/2026 |
| [EN.553.762](762_NonlinearOptimization2/762_main.pdf) | Nonlinear Optimization 2 | SP26 | 5/20/2026 |

Misc. Notes:
- `techtools`: Various lingo to prep for interviews in BME, AI, Finance, etc.
- `jma_git_guide`: A GitHub cheatsheet for project management
- `fund_ai`: Fifty Papers on the foundations of modern AI

My Notetaking template is also available in `template/`. 

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
