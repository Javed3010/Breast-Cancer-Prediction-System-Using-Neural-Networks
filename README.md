# Breast Cancer Prediction System Using Neural Networks

A deep learning project that predicts whether a breast tumor is benign or malignant using a neural network model. This project demonstrates data preprocessing, model training, evaluation, and prediction using medical diagnostic data.

---

## Project Overview

The goal of this project is to build a neural network-based classification system for breast cancer prediction. By analyzing diagnostic features from breast cancer datasets, the model learns patterns that help classify tumors as benign or malignant.

This project covers:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Feature Scaling
- Neural Network Model Building
- Model Training and Evaluation
- Breast Cancer Classification

---

## Features

- Predicts breast cancer diagnosis as benign or malignant
- Uses neural networks for binary classification
- Performs feature scaling for better model performance
- Evaluates model accuracy and loss
- Beginner-friendly deep learning project structure

---

## Tech Stack

### Languages and Tools

- Python
- Jupyter Notebook

### Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras

---

## Project Structure

```bash
Breast-Cancer-Prediction-System-Using-Neural-Networks/
│
├── data/                     # Dataset files
├── notebooks/                # Jupyter notebooks
├── models/                   # Saved neural network models
├── app.py                    # Main application file
├── requirements.txt          # Dependencies
└── README.md                 # Project documentation
```

---

## Machine Learning Workflow

### 1. Data Collection

Used a breast cancer dataset containing diagnostic features such as:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal dimension

### 2. Data Preprocessing

- Checked missing values
- Removed unnecessary columns
- Encoded target labels
- Split data into training and testing sets
- Applied feature scaling

### 3. Neural Network Model Building

Built a neural network model using dense layers for binary classification.

Common layers used:

- Input layer
- Hidden dense layers
- Output layer with sigmoid activation

### 4. Model Training

The model was trained using:

- Binary Crossentropy loss function
- Adam optimizer
- Accuracy as evaluation metric

### 5. Model Evaluation

Model performance was evaluated using:

- Accuracy Score
- Loss Curve
- Confusion Matrix
- Classification Report

### 6. Prediction

The trained model predicts whether a tumor is:

- Benign
- Malignant

---

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Javed3010/Breast-Cancer-Prediction-System-Using-Neural-Networks.git
cd Breast-Cancer-Prediction-System-Using-Neural-Networks
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

### 3. Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Mac/Linux

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Project

### Using Python Script

```bash
python app.py
```

### Using Jupyter Notebook

```bash
jupyter notebook
```

---

## Sample Output

```bash
Input:
- Radius Mean: 17.99
- Texture Mean: 10.38
- Perimeter Mean: 122.8
- Area Mean: 1001.0
- Smoothness Mean: 0.1184

Predicted Result:
Malignant
```

---

## Future Improvements

- Deploy using Flask or Streamlit
- Add an interactive prediction web interface
- Improve model accuracy with hyperparameter tuning
- Add model saving and loading functionality
- Deploy on Render, Heroku, or Streamlit Cloud
- Add visual dashboard for prediction results

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## License

This project is licensed under the MIT License.

---

## Author

Mohamed Javed Khan

- GitHub: https://github.com/Javed3010
- Project Repository: https://github.com/Javed3010/Breast-Cancer-Prediction-System-Using-Neural-Networks

---
