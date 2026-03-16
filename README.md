# Plant Disease Detection Using CNN

This project is a deep learning based image classification system for identifying plant diseases from leaf images. It was implemented using Python, TensorFlow, and Keras, and trained on a plant disease image dataset containing multiple classes.

## Project Overview

The main objective of this project is to classify plant leaf images into their respective disease categories using a Convolutional Neural Network (CNN). The model learns visual patterns from leaf images and predicts the disease class for a given input image.

The project includes data preprocessing, model training, validation, model saving, and prediction on a custom test image.

## Dataset

This project uses the Plant Disease dataset.

**Dataset link:**  
[Plant Disease Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)

### Dataset Details
- Image dataset of plant leaves
- Multiple disease categories
- Used for multi-class image classification
- Suitable for deep learning based plant disease recognition

## Technologies Used

- Python
- Google Colab
- TensorFlow
- Keras
- NumPy
- Matplotlib
- PIL / OpenCV

## Model Workflow

The project follows these main steps:

1. Load and preprocess plant leaf images
2. Split the dataset into training and validation sets
3. Build a CNN model for classification
4. Train the model for multiple epochs
5. Evaluate performance on validation data
6. Save the trained model
7. Predict the disease class for a custom image

## Model Performance

Based on the training output:

- **Validation Accuracy:** `92.21%`
- The trained model successfully predicted the class:
  **`Tomato_Early_blight`**

This shows that the model performs well on the validation data and can classify test images effectively.

## Files in This Repository

- `PDD.ipynb` — Google Colab notebook
- `pdd.py` — Python script version
- `PDD_Output.jpg` — sample output screenshot
- `report.pdf` — project report
- `README.md` — project documentation

Update the filenames above if your actual repository names are different.

## Output

The trained model predicts the plant disease class for a given leaf image and also shows class probabilities for the prediction. In the sample output, the model predicted:

**Predicted Class:** `Tomato_Early_blight`

## How to Run

1. Open the notebook in Google Colab or run the Python script locally
2. Install the required libraries
3. Download the dataset from the Kaggle link above
4. Update dataset paths if needed
5. Train the model
6. Save the trained model
7. Test the model using a custom plant leaf image

## Conclusion

This project demonstrates the use of Convolutional Neural Networks for plant disease classification. It shows how deep learning can help in early detection of plant diseases from leaf images, which can support agricultural monitoring and crop management.