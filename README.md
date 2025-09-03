# Heart Disease Workflow (Orange Data Mining)

A comprehensive workflow for analyzing and predicting heart disease using Orange, a visual programming and data mining toolkit. This project covers preprocessing and machine learning model fitting, all implemented with Orange’s intuitive workflow interface.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Workflow](#workflow)
- [Screenshots](#screenshots)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This repository provides an Orange workflow for heart disease analysis. The goal is to demonstrate data preprocessing, exploratory analysis, and predictive modeling using an accessible, drag-and-drop platform.

## Features

- End-to-end workflow in Orange
- Data preprocessing and cleaning nodes
- Exploratory data analysis (EDA) with visualization widgets
- Multiple machine learning models (classification)
- Visual performance evaluation

## Workflow

1. **Data Import**  
   Load the heart disease dataset into Orange.

2. **Preprocessing**  
   Handle missing values, normalize data, and encode categorical features using Orange's Preprocess widgets.

3. **Modeling**  
   Fit various classification models (e.g., Logistic Regression, Random Forest, SVM) by connecting learner widgets.

4. **Evaluation**  
   Compare models using Test & Score, ROC Analysis, and Confusion Matrix widgets.

## Screenshots

Below are key steps of the workflow, as executed in Orange:

### Data Preprocessing
![Data Preprocessing](screenshots/data_preprocessing.png)

### Model Fitting
![Model Fitting](screenshots/model_fitting.png)

### Evaluation Results
![Evaluation Results](screenshots/evaluation_results.png)

*(Add or rename sections/screenshots as needed. For each, adjust the image path and description.)*

## Getting Started

### Requirements

- [Orange](https://orange.biolab.si/) (version 3.30+ recommended)

### Installation

Download and install Orange from the [official website](https://orange.biolab.si/download/).

## Usage

1. **Open Orange.**
2. **Load the Workflow:**
   - Go to `File > Open` and select the provided `.ows` workflow file from this repository.
3. **Run the Analysis:**
   - Ensure the dataset is loaded correctly.
   - Inspect and modify preprocessing steps as needed.
   - Try different models by connecting/disconnecting learner widgets.
   - View results in evaluation widgets.

> **Tip:** You can visualize and tweak each step interactively within Orange.

## Results

Document your findings here. You can include exported results or discuss the performance of different models.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements, new datasets, or alternative workflows.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
