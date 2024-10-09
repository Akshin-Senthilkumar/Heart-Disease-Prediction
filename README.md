
# Heart-Disease-Prediction

This project aims to predict the likelihood of heart disease based on various medical factors using machine learning techniques. The dataset used in this project comes from the `heart.csv` file, and the implementation is done in Python using Jupyter notebooks.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project uses a dataset containing medical data to predict whether a patient has heart disease. The notebook walks through the process of loading the dataset, performing exploratory data analysis (EDA), and building a machine learning model to make predictions.

### Key Features:
- Data exploration and visualization
- Feature engineering
- Model training (classification algorithms)
- Model evaluation metrics (accuracy, precision, recall, etc.)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd heart-disease-prediction
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ensure you have the dataset `heart.csv` in the working directory.
2. Open the Jupyter notebook `Heart Disease Prediction.ipynb`.
3. Run the cells sequentially to reproduce the results or modify them as per your requirements.

## Dataset

The dataset used in this project is a public dataset (`heart.csv`), which contains the following columns:

- **Age**: The age of the patient
- **Sex**: Gender (1 = male, 0 = female)
- **CP**: Chest pain type (categorical variable)
- **Trestbps**: Resting blood pressure (mm Hg)
- **Chol**: Serum cholesterol in mg/dl
- **Fbs**: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- ... [other medical features]

## Model Training

The following models are used in this project:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

Model performance is evaluated using accuracy, precision, recall, and F1-score.

## Results

The best model achieved a prediction accuracy of **X%** (to be filled based on the actual results in the notebook). Detailed performance metrics and confusion matrices are available in the notebook.

## Contributing

If you'd like to contribute to this project, feel free to submit a pull request or open an issue for any bugs or feature requests.

## License

This project is licensed under the MIT License.
