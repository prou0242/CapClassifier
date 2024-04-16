# CapClassifier
CapClassifier: A Poisonous Mushroom Classification Project is a data-driven machine learning project aimed at classifying hypothetical mushrooms as edible, poisonous, or of unknown edibility. Leveraging a dataset of 61,069 entries across 173 species with detailed physical attributes, this project serves as a practical exercise to enhance machine learning skills and understanding of classification systems.

# Features
Data Exploration: Thorough examination and visualization of the mushroom attributes to understand their distributions and potential influence on edibility.
Data Preprocessing: Implements techniques such as cleaning, normalization, and encoding to prepare data for model training.
Model Training: Utilizes multiple machine learning algorithms to determine the most effective model based on various performance metrics.
Model Evaluation: Applies metrics such as accuracy, precision, recall, F1 score, and ROC curves to evaluate model performance on validation and test datasets.

# Technologies Used
Python: Primary programming language for development.
Pandas & NumPy: For data manipulation and numerical operations.
Scikit-learn: Used for building, training, and evaluating models.
Matplotlib: For generating ROC curves and other relevant plots.
XGBoost & LightGBM: Advanced frameworks for improving model accuracy and training efficiency.

# Dataset Description
The dataset utilized in this project comprises 61,069 hypothetical mushrooms categorized by their edibility. Each entry is described using 20 distinct attributes, including cap characteristics, stem features, habitat, and season.

# Installation
This project supports two environments setup methods: using Conda and using Pip. Depending on your environment management preference, follow one of the setup instructions below.

# Using Conda
```
git clone https://github.com/prou0242/CapClassifier.git
cd CapClassifier
conda create --name mushroom_classification --file conda-requirements.txt
conda activate mushroom_classification

# If jupyterlab is not already installed:
conda install jupyterlab
```

# Using Pip
```
git clone https://github.com/prou0242/CapClassifier.git
cd CapClassifier
python -m venv venv
source venv/bin/activate
pip install -r pip-requirements.txt

# If jupyterlab is not already installed:
pip install jupyterlab
```

# Usage
```
# Launch JupyterLab
jupyter lab

# Alternatively, launch Jupyter Notebook
jupyter notebook
```
