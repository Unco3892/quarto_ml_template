# My ML Project: Report + Source code
## Author 1, Author 2
Information about the (general) structure of the code and directories to help users navigate & reproduce your results.
For example, you can provide the project structure like this:
```
.
├── data : This directory contains all the data files for the project.
├── report : Contains all the report files.
│   └── sections : Contains the seperate sections/chapters of the report.
└── src : This "source code" directory contains all the R/Python scripts used in this project.
```
You don't need to write the directories/paths manually but can generate it automatically. Search for "tree" path generation on google to find out how.

### Good practices
- Always use `seed` to ensure correct random number generation (only once needed on your side). Check with your colleagues to see if your results are compatible.
- Try using `git` and `github` for keeping track of your work.
- Preferably use virtual environments such as [`renv`](https://rstudio.github.io/renv/) in R, and [`conda`](https://docs.conda.io/en/latest/) or [`venv`](https://docs.python.org/3/library/venv.html) in Python to ensure smooth package management and reproducible workflow.
