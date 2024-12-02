# Credit Fraud Detection with Machine Learning

## Project Overview

This project aims to detect credit card fraud using machine learning techniques. Utilizing a dataset of transactions made by European cardholders in September 2013, we aim to develop a model that effectively identifies fraudulent transactions among a significantly larger set of non-fraudulent ones. This project builds upon previous work to improve the accuracy of fraud detection models.

## Project Objectives

- Analyze and preprocess credit card transaction data.
- Engineer relevant features to enhance model performance.
- Visualize data to identify patterns and anomalies.
- Implement and evaluate machine learning models, particularly Support Vector Machines (SVM), for fraud detection.
- Provide a comprehensive analysis of results and insights gained throughout the project.

## Folder Structure

The project directory is organized as follows:

```bash

cmse492_project/
│
├── Data/
│   ├── Raw/ # Contains the raw dataset 
│   └── Oreprocessing/ # Contains preprocessed data and feature-engineered files
│
├── models/ # Contains files for model training, tuning, and evaluation 
│   ├── SVM
│   ├── SGD
│   └── BaselineModels 
│
├── Notebooks/ # Contains Jupyter notebooks for exploratory data analysis and final results
│   ├── Exploratory/
│
├── reports/ # Contains project reports and findings
│   ├── interim/
│   └── final/
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
    Download the dataset 'creditcard.csv' from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and upload it into Data/preprocessing 

