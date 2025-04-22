# Pneumonia Detection from Chest X-Ray Images using CNN & ANN

## Problem Statement
Pneumonia is a potentially life-threatening lung infection that requires early diagnosis for effective treatment. Chest X-rays are the most common diagnostic tool, but manual inspection can be time-consuming and prone to error. This project automates pneumonia diagnosis from chest X-ray images using deep learning techniques.

## Project Explanation
The objective is to classify chest X-ray images into two categories:
- Normal
- Pneumonia

### Approaches Implemented
1. **Convolutional Neural Network (CNN)**
   - CNNs are ideal for image classification as they preserve spatial hierarchies and learn features like edges, textures, and shapes through convolutional layers.
   - The CNN model consists of multiple convolutional and pooling layers, followed by dense layers for classification.

2. **Artificial Neural Network (ANN)**
   - ANNs can classify images by flattening them into 1D vectors but lack the ability to capture spatial features.
   - An ANN model was implemented to demonstrate this limitation and serve as a baseline against the CNN.

## Technologies Used
- Python
- TensorFlow & Keras
- NumPy, Matplotlib
- Google Colab for implementation and testing

## Dataset
The dataset used is the Chest X-Ray Images (Pneumonia) dataset from Kaggle, containing over 5,000 X-ray images categorized into Normal and Pneumonia.

[Link to Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

## Results
- **CNN Model Accuracy**: Achieved over 90% validation accuracy, demonstrating high performance in detecting pneumonia.
- **ANN Model Accuracy**: Lower than the CNN model, confirming that CNNs are more suitable for image-based tasks due to their spatial feature extraction capability.

## How to Run
1. Clone the repository.
2. Download the dataset from Kaggle and place it in the appropriate directory.
3. Run the Jupyter notebook or Python script in Google Colab or your local environment.
4. Follow the instructions in the notebook to train and evaluate the models.

## Conclusion
This project demonstrates the effectiveness of CNNs in automating pneumonia detection from chest X-ray images, providing a reliable tool for early diagnosis.

