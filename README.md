# Enhanced Wild Fire Classification

## Project Overview
The Enhanced Wild Fire Classification project focuses on utilizing Convolutional Neural Networks (CNNs) to classify and detect wild fires in images. The project aims to enhance the classification accuracy by incorporating advanced features such as Local Binary Patterns (LBP), Histogram of Oriented Gradients (HOG), and Histograms, while also leveraging a simpler Neural Network (NN) model to reduce computational costs associated with CNNs.

## Precious Approach
The previous approach involved using CNNs for wild fire classification and detection. While CNNs are powerful for image recognition tasks, they can be computationally expensive, especially for large datasets or real-time applications.

## My Approach
My approach combines the power of advanced image features such as LBP, HOG, and Histograms with a simpler Neural Network model. This hybrid approach aims to achieve desirable classification results while reducing computational overhead. By extracting meaningful features from images using LBP, HOG, and Histograms, and then training a simple NN model, we can achieve efficient and accurate wild fire classification.

## Key Features
- Utilizes LBP, HOG, and Histograms for feature extraction.
- Trains a simple Neural Network model for classification.
- Aims to reduce computational costs compared to pure CNN approaches.
- Enhances classification accuracy for wild fire detection in images.

## Installation
1. Clone the repository:

2. Install the required dependencies: pip install -r requirements.txt

## Usage
1. Prepare your dataset of wild fire images.
2. Run the feature extraction script to extract LBP, HOG, and Histogram features from the images.
3. Train the Neural Network model using the extracted features.
4. Evaluate the model's performance and adjust hyperparameters as needed.
5. Use the trained model for wild fire classification and detection tasks.
