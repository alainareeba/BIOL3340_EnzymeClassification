# BIOL3340_EnzymeClassification

This repository holds an attempt to apply machine learning techniques to model and predict Enzyme Commission numbers (EC1 through EC6) based on molecular fingerprint data in Kaggle's [Multi-label Classification of Enzyme Substrates](https://www.kaggle.com/datasets/gopalns/ec-mixed-class?select=mixed_ecfp.csv) dataset.

---
## Contents of Repository
- `notebooks` folder containing current code/progress
  - `Bioinf_enzymesubstrates.ipynb`: initial EDA, minor preprocessing (e.g., consolidating given .csv files), and first models with data
  - `RF_top10s.ipynb`: builds on feature importances generated in `Bioinf_enzymesubstrates.ipynb`; explores effectiveness of this dimensionality reduction technique
- `docs` folder containing `ai_usage.md` log
- `metrics` folder containing raw calculated metrics (and other collected outputs) from modelling as .csv files
