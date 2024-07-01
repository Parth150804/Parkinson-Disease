# Parkinson's Disease Detection

This project focuses on detecting Parkinson's disease using a machine learning model. The model is trained on a dataset containing various biomedical voice measurements from people with and without Parkinson's disease. The goal is to classify whether a person has Parkinson's disease based on these voice measurements.

## Project Overview

1. **Data Collection and Analysis**:
    - The dataset is loaded from a CSV file and basic exploratory data analysis is performed.
    - The data is checked for missing values and statistical measures are computed.

2. **Data Preprocessing**:
    - The features and target variables are separated.
    - The data is split into training and testing sets.
    - Feature scaling is performed using standardization.

3. **Model Training**:
    - A Support Vector Machine (SVM) model with a linear kernel is used for training.
    - The model is trained on the training data.

4. **Model Evaluation**:
    - The accuracy of the model is evaluated on both the training and testing data.

5. **Predictive System**:
    - A predictive system is built to classify whether a person has Parkinson's disease based on input features.

## Dependencies

- Python 3.x
- NumPy
- Pandas
- scikit-learn

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/parkinsons-disease-detection.git
    ```
2. Navigate to the project directory:
    ```sh
    cd parkinsons-disease-detection
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the script to load the data, train the model, and evaluate its performance:
    ```sh
    python parkinson's_disease_detection.py
    ```
2. Use the predictive system to classify new data:
    - Update the `input_data` variable in the script with new measurements.
    - Run the script to get the prediction.

## Dataset

The dataset used in this project is from the UCI Machine Learning Repository:
- **Filename**: parkinsons.csv

## Results

The model's accuracy on the training data and test data is printed in the console.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project was developed with the help of the scikit-learn library and the dataset from the UCI Machine Learning Repository.
