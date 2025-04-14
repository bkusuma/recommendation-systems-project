# Recommendation Systems Project
Experimenting with recommendation systems techniques on real world datasets.
 ## Table of Contents
<!-- | [![Abstract](https://img.shields.io/badge/abstract-green?style=plastic)](#abstract)  | [![Abstract](https://img.shields.io/badge/abstract2-green?style=plastic)](#abstract)  | [![Abstract](https://img.shields.io/badge/abstract-green?style=plastic)](#abstract)  | [![Abstract](https://img.shields.io/badge/abstract-green?style=plastic)](#abstract)  |
|---|---|---|---|
| [![Abstract](https://img.shields.io/badge/abstract-green?style=plastic)](#abstract)  | [![Abstract](https://img.shields.io/badge/abstract-green?style=plastic)](#abstract)  | [![Abstract](https://img.shields.io/badge/abstract-green?style=plastic)](#abstract)  |  [![Abstract](https://img.shields.io/badge/abstract-green?style=plastic)](#abstract) | -->

1. [Abstract](#abstract)
2. [Introduction](#introduction)
3. [Data](#data)
4. [Results](#results)
5. [References](#discussion--next-steps)
6. [Project Organization](#project-organization)
7. [Acknowledgements & References](#acknowledgements--references)

# Abstract
Work on utltizing a large dataset and breaking down the input with use of sparse matrices and eventually singular value decomposition (SVD) to identify recommendations by: 
1. User-based collaborative filtering
2. Item-based collaborative filtering

# Introduction
The task at hand: 
1. Asks user to enter a personal identification number.

2. Uses a pre-built model to determine the three best items to recommend that person.

3. Uses another pre-built model which was trained on SVD-reduced data to recommend three items to that person.

4. Prints the estimated standard deviation between the original model and the SVD-reduced model (RMSE between two utility matrices).

# Data
These datasets contain attributes about products sold on Amazon which may be sources of bias in recommendations (in particular, attributes about how the products are marketed). Data also includes user/item interactions for recommendation.

<!-- # Methods

Add methods text here. -->

# Results

I was able to wield the data to make a a recommendation matrix.

# Discussion & Next Steps

Still need to create a function to pull out recommendations for a user via an interface.

# Project Organization

```
📦recommendation-system                         <- GitHub repository
│
├── 📜 README.md                                <- The top-level README for this project.
├── 📂 data
│   ├── 📂 external                             <- Data from third party sources.
│   ├── 📂 interim                              <- Intermediate data that's been transformed.
│   ├── 📂 processed                            <- The final, canonical data sets for modeling.
│   └── 📂 raw                                  <- The original, immutable data dump.
│
├── 📂 models                                   <- Trained and serialized models, model predictions, or model summaries
│
├── 📂 notebooks                                <- Jupyter notebooks. Naming convention is a number (for ordering)
│   └── 📜  1.0-bk-project-notebook.ipynb       <- The original, immutable data dump.
│
├── 📂 references                               <- Data dictionaries, manuals, and all other explanatory materials.
│
├── 📂 reports                                  <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── 📂 figures                              <- Generated graphics and figures.
│
└── 📜 requirements.txt                         <- Requirements file for reproducing the analysis environment.
```
<!-- 
│ e.g.

,
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.


│                         generated with `pip freeze > requirements.txt`
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
    └── plots.py                <- Code to create visualizations -->

# Acknowledgements & References
1. Martin Heroux, pandoc_article_template, (2021), GitHub repository, https://github.com/MartinHeroux/pandoc_article_template
2. __Addressing Marketing Bias in Product Recommendations__  
Mengting Wan, Jianmo Ni, Rishabh Misra, Julian McAuley, WSDM, (2020), https://cseweb.ucsd.edu/~jmcauley/reviews/wsdm20a.pdf
