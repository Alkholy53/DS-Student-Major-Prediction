# Student Major Prediction Project

This project aims to predict the major of a student based on their grades in courses and skills. The project utilizes machine learning techniques, specifically logistic regression, to make predictions. This README file provides an overview of the project and instructions for running the code.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Data Cleaning](#data-cleaning)
- [Data Visualization](#data-visualization)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The project involves predicting the major of a student based on their academic performance in courses and relevant skills. It utilizes a dataset containing information about students' grades and skills. The main goal is to build a machine learning model using logistic regression to accurately predict the major of a student based on the available data.

## Installation

To run the code for this project, you need to have the following libraries installed:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

You can install these libraries using the following command:
pip install numpy pandas matplotlib seaborn scikit-learn


## Usage

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Make sure you have the required dataset file (`final.csv`) in the project directory.
4. Open the code file (`main.py`) in your preferred Python IDE or text editor.
5. Run the code to execute the project.
6. Follow the instructions and check the output for the predicted major of the student.

## Data Cleaning

The dataset may contain unnecessary columns or missing values. In the code, we perform the following data cleaning steps:

- Drop unnecessary columns that do not contribute to the prediction.
- Rename columns with more meaningful names.
- Remove duplicate rows from the dataset.
- Handle missing values by dropping rows or filling them with appropriate values.

## Data Visualization

Visualizing the data can provide insights into the distribution of grades and skills among different majors. In the code, we use various plotting techniques to visualize the data, such as bar charts and pie charts. These visualizations help understand the patterns and relationships in the dataset.

## Model Training and Evaluation

The project utilizes logistic regression for the prediction task. The code trains a logistic regression model using the available data and evaluates its accuracy using the test set. The trained model is then used to predict the major of a student based on their grades and skills.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
