# Ecommerce Recommendation Model
 
This repository contains the implementation of an Ecommerce Recommendation Model using Alternating Least Squares (ALS) algorithm. The goal is to provide product recommendations to online shoppers based on their historical purchase data.

## Overview

The Jupyter Notebook `RecommendationModel.ipynb` walks through the process of building and evaluating an Alternating Least Squares (ALS) machine learning model for e-commerce recommendations.

## Prerequisites

- Python 3.x
- PySpark
- Seaborn
- Matplotlib
- pandas
- numpy

## Installation

To install the necessary libraries, you can use pip:

```bash
pip install pyspark seaborn matplotlib pandas numpy
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/jameschen256/Ecommerce_Rec_Model.git
```

2. Navigate to the project directory:

```bash
cd Ecommerce_Rec_Model
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook ALScodefin.ipynb
```

4. Run the cells in sequence to understand the data preprocessing, model building, and evaluation process.

## Features

- **Data Preprocessing**: The notebook starts by importing necessary libraries and loading the dataset. It then conducts exploratory data analysis (EDA) and preprocesses the data for the model.
  
- **Model Building**: The Alternating Least Squares (ALS) algorithm from PySpark's MLlib is utilized to train the recommendation model.
  
- **Evaluation**: The model's performance is assessed using the Root Mean Square Error (RMSE).

## Dataset

The dataset used for this model represents e-commerce purchase data. Each entry typically contains information about users, products, and their interactions (e.g., ratings, purchase history).
