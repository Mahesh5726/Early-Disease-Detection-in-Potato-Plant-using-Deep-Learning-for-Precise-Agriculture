# Early Disease Detection in Potato Plant using Deep Learning

## Overview

This project aims to detect and classify diseases in potato plants using deep learning techniques. By leveraging Convolutional Neural Networks (CNNs), the system identifies and categorizes potato leaf conditions into five classes: Early Blight, Healthy, Late Blight, Non-Potato Leaf, and Object. The model is deployed through a user-friendly web interface built with Streamlit.

## Features

- **Deep Learning-based Detection**: Uses a trained CNN model for classification.
- **Web Interface**: Built using Streamlit for easy image uploads and predictions.
- **Fast & Accurate**: Achieves an accuracy of **98.59%**.
- **User-friendly Dashboard**: Simple navigation with options for Home, About, and Disease Recognition.

## Technologies Used

- **Python**
- **TensorFlow/Keras**
- **Streamlit**
- **NumPy & Pandas**
- **OpenCV**

## Installation

### Prerequisites

Ensure you have Python 3.8+ installed on your system.

### Steps to Install and Run the Project

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/potato-disease-detection.git
   cd potato-disease-detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Streamlit application:
   ```sh
   streamlit run main.py
   ```
4. Open the displayed URL in your browser to access the application.

## Usage

1. Navigate to the **Disease Recognition** section.
2. Upload an image of a potato leaf.
3. Click **Show Image** to preview your upload.
4. Click **Predict** to classify the image.
5. The system will return the prediction results.

## Dataset

The dataset consists of **6035 potato leaf images**, categorized into:

- **Early Blight**
- **Healthy**
- **Late Blight**
- **Non-Potato Leaf**
- **Object**

The dataset was sourced from Kaggle and augmented for better model performance.

### Dataset Link

You can access the dataset used in this project from Kaggle: [Potato and Non-Potato Leaves Dataset](https://www.kaggle.com/datasets/mahesh57r/potato-non-potato-leaves-and-objects)

## Model Details

- **Architecture**: CNN with multiple convolutional and max-pooling layers.
- **Optimizer**: Adam
- **Loss Function**: Sparse Categorical Crossentropy
- **Training Accuracy**: 98.59%

##
