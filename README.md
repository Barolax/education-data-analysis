# Analyse des systèmes éducatifs

Projet réalisé dans le cadre de ma formation **Data Engineer**.

## Données
- 5 datasets (CSV) dans `data/` :
  - `Data` (à télécharger : https://datacatalog.worldbank.org/search/dataset/0038480 / Source : Banque Mondiale)
  - `Country`
  - `Country-Series`
  - `FootNote`
  - `Series`


## Installation (Poetry)
poetry install
poetry run jupyter lab

## Structure 
.
├── data/                   
├── notebooks/
│   └── code.ipynb             # notebook final
├── visu/                      # exports des visualisations 
│   ├── boxplot_internet.png
│   ├── distrib_internet.png
│   └── ...
├── pyproject.toml
└── README.md

