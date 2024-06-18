# Quarto Manuscript Project Template

This is a template repo intended to speed up the process of setting up a new
project as a [Quarto manuscript](https://quarto.org/docs/manuscripts/).

It is a collection of literate computing notebooks (`.qmd` files) and related
source code. A lightweight virtual environment is already included via the
[`renv` package](https://rstudio.github.io/renv/articles/renv.html). The
organizational structure is as follows

* `data/`: raw data for data analysis or simulation experiments
* `notebooks/`: literate computing notebooks (as `.qmd`) implementing analyses;
   these [play a specific role](https://quarto.org/docs/manuscripts/#notebooks)
   in the Quarto manuscript format
* `sandbox/`: auxiliary and/or miscellaneous source code produced over the
  course of project development
* `simulations/`: source code for statistical/computational simulation
  experiments
