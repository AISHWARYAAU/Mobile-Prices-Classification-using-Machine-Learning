
# Mobile Price Classification with Machine Learning

## Overview

This repository contains a Python script to classify mobile prices based on various features using machine learning. The script reads the "mobile_prices.csv" dataset, performs data exploration and preparation, trains a logistic regression model, and evaluates its accuracy for predicting mobile price ranges.

## About the Project

The main objective of this project is to classify mobile prices into different ranges based on various features such as battery power, clock speed, dual sim support, etc. The script utilizes a logistic regression algorithm to train a classification model and predict the mobile price range.

## Dataset

The dataset used in this project is "mobile_prices.csv", which contains information about various mobile features and their corresponding price ranges.

## Getting Started

### Prerequisites

Before running the script, ensure you have the following installed:

- Python (3.x recommended)
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/mobile-price-classification.git
cd mobile-price-classification
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

## Analysis and Model Training

### Data Exploration

The script visualizes the correlation between different features using a heatmap to understand the relationships between them.

### Data Preparation

The data is split into features (x) and target variable (y), scaled using StandardScaler, and further split into training and testing sets.

### Model Training

A logistic regression model is trained using the training data to classify mobile price ranges.

### Model Evaluation

The accuracy of the trained logistic regression model is evaluated using the testing data, and the predicted mobile price ranges are printed along with their frequencies.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

##images


![image](https://github.com/AISHWARYAAU/Mobile-Prices-Classification-using-Machine-Learning/assets/91381783/c994ba6d-4ff6-4f77-b2d3-63cca8c425bf)
![image](https://github.com/AISHWARYAAU/Mobile-Prices-Classification-using-Machine-Learning/assets/91381783/1cbe45e2-3f6a-450b-943a-6d3430bd1fe0)




