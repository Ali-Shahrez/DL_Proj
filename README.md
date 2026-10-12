# Road Crack and Pothole Classifier



Two-head EfficientNet-B0 model that classifies road images as Normal, Crack, or Pothole, and assigns Low or High severity to crack and pothole images.



## Data



The dataset is not stored in this repository.



- Cleaned, group-aware split (use this one): https://drive.google.com/drive/folders/1qGQW4hsbbcA2QpF70j-QTd_TP0Sv7AH4?usp=sharing

- Original dataset: https://drive.google.com/drive/folders/1Nmf_e7zlw1wALNXUHu5lxLw0v7gCtY3L



Source paper: Chu et al. (2023), https://doi.org/10.32604/cmc.2023.035287



## Split



`data/splits/assignment_v3.csv` lists each image's class, group, and split.



Final counts: train 4,196, validation 899, test 898 (5,993 total).



## Repository layout



- `Documentation/`: data cleaning and leakage report, architecture diagram and description.

- `data/splits/`: split assignment file.

- `notebooks/`: cleaning and training notebooks.



## Status



Data cleaning and split are complete. Model training is in progress.

