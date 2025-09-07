# A Systematic Survey of Natural Language Processing for the Greek Language

This is the repository accompanying the paper: **A systematic survey of natural language processing for the Greek language**  by Juli Bakagianni, Kanella Pouli, Maria Gavriilidou, John Pavlopoulos, published at *Patterns, 2025*  [📄 Open-access article](https://www.cell.com/patterns/fulltext/S2666-3899(25)00161-8)

<p align="center">
    <img src="https://raw.githubusercontent.com/greek-nlp/survey/refs/heads/main/survey.nlp.gr.svg" alt="Greek NLP Survey" width="250"/>
</p>

## Overview

Comprehensive monolingual natural language processing (NLP) surveys are essential for assessing language-specific challenges, resource availability, and research gaps. This work introduces a generalizable framework for systematic monolingual NLP surveys, applied here to Greek NLP (2012–2023).  

This repository contains the structured data collected during the survey, which is continuously updated to provide an evergreen resource for the community.

---

## Contents

- **`greek_nlp_articles.csv`**  
  A curated list of research articles (2012–2023) relevant to Greek NLP, including metadata such as title, year, venue, and task coverage.

- **`greek_nlp_datasets.csv`**  
  A catalog of datasets used in Greek NLP research, annotated with task type, availability, and other key attributes.

---

## Usage

You can easily explore the data using Python and pandas:

```python
# Comment out below to download (inside a notebook)
#!git clone https://github.com/greek-nlp/survey.git
#%cd survey
import pandas as pd

articles = pd.read_csv("greek_nlp_articles.csv")
datasets = pd.read_csv("greek_nlp_datasets.csv")

print("Articles:", articles.shape)
print(articles.shape)

print("Datasets:", datasets.shape)
print(datasets.shape)
datasets.sample(3)
```

## Citation

If you use this resource, please cite the paper:

```bibtex
@article{bakagianni2025systematic,
  title={A systematic survey of natural language processing for the Greek language},
  author={Bakagianni, Juli and Pouli, Kanella and Gavriilidou, Maria and Pavlopoulos, John},
  journal={Patterns},
  year={2025},
  publisher={Elsevier}
}
```

## License

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
