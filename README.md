# Fruit Image Classification with TensorFlow

## 🍓before anything🍓, here's the dataset link for your use:
[https://www.kaggle.com/datasets/utkarshsaxenadn/fruits-classification?resource=download](https://www.kaggle.com/datasets/utkarshsaxenadn/fruits-classification?resource=download)

This project is a deep learning-based image classification model built using TensorFlow. It classifies images of fruits into five categories: **apple**, **banana**, **grape**, **mango**, and **strawberry**. The model has been trained and evaluated using a dataset split into training, validation, and test sets.

The project is implemented in Google Colab for easy accessibility and reproducibility.

---

## Features

- Classifies uploaded fruit images into one of five classes.
- Displays the predicted fruit label.
- Returns the prediction confidence (accuracy score).
- Easy to use via Google Colab.

---

## Dataset

The dataset consists of images categorized into five fruit types:
- Apple  
- Banana  
- Grape  
- Mango  
- Strawberry  

It is divided into:
- **Training set**
- **Validation set**
- **Test set**

Each subset is organized into separate folders per class.

---

## Getting Started

### 1. Open in Google Colab

Click the button below to open the notebook in Google Colab:

**[Open in Colab](https://colab.research.google.com/)**  
> *Upload the `.ipynb` notebook manually if you haven’t pushed it to a public repo yet.*

### 2. Upload the Notebook

If you haven't hosted the notebook in a public repository:
1. Go to [Google Colab](https://colab.research.google.com/)
2. Click on **File > Upload Notebook**
3. Select the `.ipynb` file from your local machine

---

## How to Use

1. **Run the Notebook**  
   Execute the cells in sequence to load the model, process the image, and make predictions.

2. **Upload an Image**  
   You'll be prompted to upload an image (JPG or PNG) of a fruit.

3. **View Prediction**  
   The model will display:
   - The predicted fruit class
   - The confidence score for the prediction

---

## Model Training

The model was trained on a custom dataset of fruit images using TensorFlow with:
- Convolutional Neural Network (CNN) architecture
- Image preprocessing (resizing, normalization, augmentation)
- Categorical cross-entropy loss
- Accuracy as the primary evaluation metric

Training was performed using GPU acceleration in Google Colab.

---

## Requirements

To run the notebook locally or in Colab, make sure the following are available:

- Python 3.x  
- TensorFlow  
- NumPy  
- Matplotlib  
- Google Colab (if using online)

These are typically pre-installed in Colab.

---

## License

This project is open-source and free to use for educational or research purposes.

