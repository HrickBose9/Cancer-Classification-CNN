# Breast Cancer Classification with CNN

## Project Overview
This project uses a Convolutional Neural Network (CNN) to classify breast cancer images as malignant or benign. The model is trained on labeled images and tested on unlabeled images.

## Instructions to Run the Code

### Prerequisites
- Python 3.x
- TensorFlow and Keras
- Matplotlib
- Google Colab (recommended)

### Dataset Setup
1. Upload the extracted `Dataset2` folder to your Google Drive in the path `/MyDrive/BreastCancerDataset/`.
2. Inside the `test` folder, create a subfolder named `unknown` and place all 14 test images in this folder.

### Running the Model
1. Open Google Colab and mount your Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')

Set the paths to the dataset in the code:

dataset_path = '/content/drive/MyDrive/BreastCancerDataset/Dataset2/FNA'
test_path = '/content/drive/MyDrive/BreastCancerDataset/Dataset2/test/unknown'

Run each cell step-by-step, following the provided code to preprocess, train, and test the CNN model.
To view predictions for the unlabeled test data, check the output of the last cell
