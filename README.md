# recommendation-systems-project
 Experimenting with recommendation systems techniques on real world datasets.

```
📦recommendation-systems-project
 ┣ 📂data
 ┃ ┣ 📂external
 ┃ ┃ ┗ 📜.gitkeep
 ┃ ┣ 📂interim
 ┃ ┃ ┗ 📜.gitkeep
 ┃ ┣ 📂processed
 ┃ ┃ ┗ 📜.gitkeep
 ┃ ┗ 📂raw
 ┃ ┃ ┗ 📜.gitkeep
 ┣ 📂docs
 ┃ ┗ 📜.gitkeep
 ┣ 📂models
 ┃ ┗ 📜.gitkeep
 ┣ 📂notebooks
 ┃ ┗ 📜.gitkeep
 ┣ 📂references
 ┃ ┗ 📜.gitkeep
 ┣ 📂reports
 ┃ ┣ 📂figures
 ┃ ┃ ┗ 📜.gitkeep
 ┃ ┗ 📜.gitkeep
 ┣ 📂src
 ┃ ┣ 📂modeling
 ┃ ┃ ┣ 📜__init__.py
 ┃ ┃ ┣ 📜predict.py
 ┃ ┃ ┗ 📜train.py
 ┃ ┣ 📜__init__.py
 ┃ ┣ 📜config.py
 ┃ ┣ 📜dataset.py
 ┃ ┣ 📜features.py
 ┃ ┗ 📜plots.py
 ┣ 📜.env
 ┣ 📜.gitignore
 ┣ 📜Makefile
 ┣ 📜README.md
 ┣ 📜pyproject.toml
 ┗ 📜requirements.txt
 ```

 # recommendation-systems-project

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

Experimenting with recommendation systems techniques on real world datasets.

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         src and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── src   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes src a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------
Dataset Description
These datasets contain attributes about products sold on Amazon which may be sources of bias in recommendations (in particular, attributes about how the products are marketed). Data also includes user/item interactions for recommendation.

Citation:
__Addressing Marketing Bias in Product Recommendations__  
Mengting Wan, Jianmo Ni, Rishabh Misra, Julian McAuley
WSDM, 2020  
[pdf](https://cseweb.ucsd.edu/~jmcauley/reviews/wsdm20a.pdf)
