 Breast Cancer Prediction Using ANN from Colab
This project demonstrates how to build, train, and evaluate an Artificial Neural Network (ANN) to predict breast cancer using a publicly available dataset. All implementation is done in Python using Google Colab, making it fully accessible without the need for local setup.

📌 Project Overview
Breast cancer is one of the most common cancers affecting women globally. Early detection through data analysis and machine learning can play a crucial role in diagnosis and treatment planning.

This project uses a Supervised Learning approach to classify whether a tumor is malignant or benign using the Wisconsin Breast Cancer Dataset.

🔧 Tools & Technologies
🔍 Google Colab – For writing and running Python code in the cloud.

🧪 Pandas, NumPy – For data manipulation and preprocessing.

📊 Matplotlib, Seaborn – For data visualization and correlation analysis.

⚙️ Scikit-learn – For splitting the dataset and performance metrics.

🧠 TensorFlow / Keras – For building and training the ANN.

📁 Dataset
Name: Breast Cancer Wisconsin (Diagnostic) Data Set

Source: UCI Machine Learning Repository

Features: 30 numeric features computed from a digitized image of a breast mass.

Target:

M = Malignant

B = Benign

You can load the dataset directly from Scikit-learn or upload a CSV to Colab.

📈 Model Architecture
The ANN consists of:

Input Layer: 30 neurons (one per feature)

Hidden Layers: 2 Dense layers with ReLU activation

Output Layer: 1 neuron with Sigmoid activation (for binary classification)

Loss Function: Binary Crossentropy
Optimizer: Adam
Metrics: Accuracy

🚀 How to Run the Project in Colab
Open the Colab Notebook (replace # with actual Colab link).

Upload the dataset (data.csv) if not using scikit-learn's built-in loader.

Run each cell step-by-step:

Data loading

EDA (optional)

Preprocessing (scaling, encoding)

ANN model building

Training and evaluation

