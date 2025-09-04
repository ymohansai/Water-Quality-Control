## Water-Quality-Control

This project analyzes water quality parameters and applies data analysis and machine learning techniques to assess and predict water safety.
The goal is to support environmental monitoring and ensure safe drinking water standards.

-> Project Overview

Exploratory Data Analysis (EDA) of water quality dataset

Preprocessing and feature engineering for clean analysis

Random Forest Classifier to classify water as safe (1) or not safe (0)

Evaluation of model performance using accuracy, precision, recall, and F1-score

-> Dataset

The dataset contains chemical and biological properties of water samples, including:

Aluminium

Ammonia

Arsenic

Barium

Cadmium

Chloramine

Chromium

Copper

Fluoride

Bacteria

Lead

Nitrates

Nitrites

Mercury

Perchlorate

Radium

Selenium

Silver

Uranium

Target Variable: is_safe (1 = Safe, 0 = Not Safe)

-> Dataset size: ~7996 rows × 21 columns

-> Installation

Clone this repository and install the required dependencies:

git clone https://github.com/your-username/water-quality-control.git
cd water-quality-control
pip install -r requirements.txt

-> Usage

Run the notebook or script to train and evaluate the model:

jupyter notebook water_quality_control.ipynb


The notebook will:

Perform EDA with graphs and insights

Preprocess data (handle missing values, type conversion)

Train a Random Forest Classifier

Evaluate model performance with metrics

-> Results

Identified key features impacting water safety

Built a predictive ML model to classify water safety

Achieved 96% accuracy with strong precision/recall scores

-> Technologies Used

Python 

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn 

Jupyter Notebook

-> Applications

Public health monitoring

Water treatment analysis

Early detection of unsafe drinking water
