# Credit Fraud Detection with Machine Learning

## Project Overview

This project aims to detect credit card fraud using machine learning technique trained off a dataset of transactions made by European cardholders in September 2013, particurly with SVM and SGDs.

## Project Objectives

- Analyze and preprocess credit card transaction data.
- Engineer relevant features to enhance model performance.
- Visualize data to identify patterns and anomalies.
- Create a Baseline Model to build off 
- Implement and evaluate Support Vector Machine and Stochastic Gradient Descent Models
- Provide a comprehensive analysis of results and insights gained throughout the project.

## Folder Structure

The project directory is organized as follows:

```bash

cmse492_project/
│
├── Data/
│   ├── Raw/ # Contains the raw dataset 
│   └── Preprocessing/ # Contains preprocessed data and feature-engineered files
│
├── Models/ 
│   ├── SVM/ #Contains all SVM Models
│   ├── SGD/ #Contains all SGD Models
│   └── BaselineModels/ #Contains Baseline Models
│
├── Notebooks/ # Contains Jupyter notebooks for exploratory data analysis and final results
│   └── Exploratory/
│
├── Reports/ # Contains project reports and findings
│   ├── Interim/
│   └── Final/
├── Visualizations/ #Contains Compact Visualization File
│
├── README.md
└── .gitignore 
```
## Setup Instructions

To set up and run the code in this project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/shirle21/cmse492_project.git
   cd cmse492_project
   ```
2. **Downloading the Data**
    Download the dataset 'creditcard.csv' from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and upload it into ...Data/PreProcessing and ..Data/Raw

