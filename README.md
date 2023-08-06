# Titanic_Classification
---

# Titanic Survival Prediction

![Titanic](https://upload.wikimedia.org/wikipedia/commons/6/6e/St%C3%B6wer_Titanic.jpg)

This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. The Titanic dataset contains information about passengers' attributes such as age, sex, class, and more. The goal is to build a predictive model that can classify whether a passenger survived or not based on the available features.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Data Exploration](#data-exploration)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Visualizations](#visualizations)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. This project explores the Titanic dataset, visualizes the data distribution, preprocesses the data, trains a logistic regression model, and evaluates its performance using various metrics. The goal is to provide insights into the factors that influenced passenger survival and showcase the application of machine learning techniques.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository: `git clone https://github.com/thekasyap/Titanic_Classification.git`
2. Navigate to the project directory: `cd Titanic_Classification`
3. Install the required libraries: `pip install -r requirements.txt`

## Data Exploration

The data exploration phase includes visualizations that provide insights into passenger survival based on different factors such as sex, class, age, fare, and family relationships. These visualizations help in understanding the distribution of data and potential patterns.

![image](https://github.com/thekasyap/Titanic_Classification/assets/113460291/b5c08978-7ec8-4284-b3c4-61c573255b55)


## Data Preprocessing

In the data preprocessing step, categorical variables like 'Sex' are converted into numeric format using one-hot encoding. Missing values are handled, and irrelevant columns like 'Name', 'Ticket', 'Cabin', and 'Embarked' are dropped.

## Model Training

A logistic regression model is trained on the preprocessed data to predict passenger survival. The model learns from the training data and is later used to make predictions on the test data.

## Evaluation

The performance of the trained model is evaluated using a confusion matrix, classification report, and accuracy score. These metrics provide insights into the model's ability to predict survival correctly.


![CConfusion matrix](https://github.com/thekasyap/Titanic_Classification/assets/113460291/b8d5c2bd-4070-4bb7-a48c-bcf238dd560d)

![Model accuracy Score](https://github.com/thekasyap/Titanic_Classification/assets/113460291/eed4880b-d9e0-483a-b6f8-2051f54e643d)


## Visualizations

A set of data visualizations is provided to give a better understanding of the dataset and the relationships between different features. These visualizations help in identifying trends and patterns.

## Usage

1. Ensure you have Python and the required libraries installed.
2. Clone this repository and navigate to the project directory.
3. Run the `Titanic_Classification.ipynb` script: `python, jupyter notebook`

## Contributing

Contributions are welcome! If you find any issues or want to enhance the project, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---
