oct-qiskit-pulse
==============================

Internship project repository for Ben Rosand. Looking into how to incorporate optimal control theory into Qiskit.
See `reports/final_writeup/` for full-featured README.

NOTE: TO run any of this software,, in addition to looking at the final writeup,
https://github.com/Qiskit/qiskit-terra/pull/5085  must be added to make the demo
work. 

The two main files that should be run through are `notebooks/final_demo.py` and
`notebooks/testing.ipynb`. For a detailed description of this project and the
research performed on QOC, visit `reports/final_writeup/writeup.tex`. Also, to
see more detail about the code implementation, specifically as it is integrated
into qiskit, see `docs/0000-qiskit-optimal-control.md`.

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   │
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
