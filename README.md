# BIOL3340_EnzymeClassification

This repository holds an attempt to apply machine learning techniques to model and predict Enzyme Commission numbers (EC1 through EC6) based on molecular fingerprint data in Kaggle's [Multi-label Classification of Enzyme Substrates](https://www.kaggle.com/datasets/gopalns/ec-mixed-class?select=mixed_ecfp.csv) dataset.

## Data
- Type: 3 .csv files of molecular/chemical fingerprint data in tabular format
- Size: each file is ~1 MB (3.2 MB total), 1039 instances, 1229 features (total)
- Modelling: a train/test split of 80/20 has been used for majority of models

### Preprocessing/Clean Up
The data from all 3 .csv files were concatenated into one file for simplicity.

---
## Contents of Repository
- `notebooks` folder containing current code/progress
  - `Bioinf_enzymesubstrates.ipynb`: initial EDA, minor preprocessing (e.g., consolidating given .csv files), and first models with data
  - `RF_top10s.ipynb`: builds on feature importances generated in `Bioinf_enzymesubstrates.ipynb`; explores effectiveness of this dimensionality reduction technique
- `docs` folder containing `ai_usage.md` log
- `metrics` folder containing raw calculated metrics (and other collected outputs) from modelling as .csv files


### Software Setup
Google Colab was used for majority of model training. Visualizations were completed with matplotlib and seaborn. Modelling and analysis was done through pandas, numpy, and scikit-learn.

### Data Availability
Data can be downloaded from its [Kaggle page](https://www.kaggle.com/datasets/gopalns/ec-mixed-class?select=mixed_ecfp.csv).
