# Kaggle NBME Notebook

Submission for [Kaggle NBME - Score Clinical Patient Notes competition](https://www.kaggle.com/competitions/nbme-score-clinical-patient-notes).

**Notebooks** contains the notebooks for the competition.
- **NBME_Generate_Models.ipynb** was the notebook used to produce roberta-large and deberta-v3-large folds for the competition, and was run on Google Colab, with the folds were later uploaded to Kaggle.
- **NBME_Generate_Predictions.ipynb** was the Kaggle notebook used to generate predictions for the test set for submission (the directory structure used with the Kaggle notebook was slightly different).

**NBME** contains the data input/output directory. In **NBME**:

- **input**
  - **nbme-score-clinical-patient-notes** contains the data for the competition. The other two folders help to convert the deberta slow tokenizer to a fast one.
  - During the Kaggle competition, this folder also contained the large transformer folds that were used for final predictions.

- **public_models**
  - Skeleton directory for saving models/folds, optimizer states, and training metrics.
