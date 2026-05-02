# Cardiovascular Risk Classification Project

This project focuses on classifying cardiovascular risk levels (low, moderate, high) using a small set of clinical features from the Framingham dataset. Two models were implemented and compared: a Random Forest classifier and a simple 1D Convolutional Neural Network (CNN). The goal was to explore how traditional machine learning compares to deep learning on structured healthcare data.

---

## Table of Contents
* Implementation
* Organization
* Requirements
* Installation
* Running the Project
* Citations and References

---

## Implementation

This project does not require any hardware or specialized lab equipment. It is a fully software-based machine learning project that can be run locally or in a cloud environment.

The workflow of the project is:

1. Load the Framingham dataset  
2. Select relevant clinical features (age, blood pressure, BMI)  
3. Generate risk labels using a custom scoring system  
4. Preprocess the data (imputation + scaling)  
5. Train two models:
   - Random Forest  
   - 1D CNN  
6. Evaluate models using accuracy, precision, recall, F1-score, and confusion matrices  
7. Visualize results (training curves, feature importance, comparison graphs)

This project was developed and tested using **Google Colab**, which allowed for easy execution and visualization without local setup. Additionally, **Cursor AI** was used during development to assist with code generation, debugging, and structuring the project.

---

## Organization

Project structure (simplified):

```

.
├── Predicting-Cardiovascular-Risk-Levels-from-Blood-Pressure-Age-and-BMI
│── docs # important pdfs (none right now)
├── src
│   └── cardio_risk_project.py   # main script (entry point) 
│   └── cardio_risk_project.ipynb   # notebook showing outputs
├── media                   # plots / visuals 
│   └── CNN-accuracy-loss.png
│   └── CNN-confusion-matrix.png
│   └── model-comparison.png
│   └── random-forest-confusion-matrix.png
│   └── random-forest-feature-importance.png
│   └── readme.txt
├── README.md
├── requirements.txt       # important installations (none right now since ran on Google Colab)
└── .gitignore

```

---

## Requirements

It is recommended to use a virtual environment when running locally.

This project was developed using Python 3.10+.

Main libraries used:

```

numpy
pandas
matplotlib
scikit-learn
tensorflow

```

Install dependencies with: (none at the moment)

```

pip install -r requirements.txt

```

Or manually:

```

pip install numpy pandas matplotlib scikit-learn tensorflow

```

---

## Installation

To run this project locally:

1. Install Python: https://www.python.org/downloads/  
2. Install VSCode (recommended)  
3. Install the Python extension  
4. (Optional) Create a virtual environment  

Alternatively, you can run this project directly in **Google Colab** without installing anything locally.

---

## Running the Project

Run the main script:

```

python cardio_risk_project.py

```

The program will:
- Train both models  
- Print evaluation metrics (accuracy, precision, recall, F1-score)  
- Display confusion matrices  
- Show CNN training graphs (accuracy and loss)  
- Show feature importance for Random Forest  
- Display a final model comparison graph

---

## Citations and References

[1] Framingham Heart Study Dataset:  
https://raw.githubusercontent.com/GauravPadawe/Framingham-Heart-Study/master/framingham.csv  

[2] Scikit-learn Documentation:  
https://scikit-learn.org  

[3] TensorFlow Documentation:  
https://www.tensorflow.org  

[4] Matplotlib Documentation:  
https://matplotlib.org  

[5] Cursor AI (used for development support):  
https://cursor.sh  

[6] Google Colab:  
https://colab.research.google.com  

