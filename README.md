# CNN Image Classification – CBIS-DDSM Dataset

This repository contains a convolutional neural network (CNN) model for classifying breast cancer images from the CBIS-DDSM dataset. The notebook includes data preprocessing, model architecture, training, and evaluation, developed as part of a collaborative university group assignment.

## 📁 Files

- `CNN_CBIS_DDSM_Image_Classification_(Group_3).ipynb` — Main Jupyter Notebook with full implementation
- `requirements.txt` — Python packages needed to run the notebook
- `README.md` — Project documentation

## 🧠 Features

- Reads and preprocesses medical images using OpenCV
- Builds a CNN model using TensorFlow/Keras
- Evaluates model performance with accuracy and loss plots
- Uses CBIS-DDSM breast cancer image data for classification

## 📦 Dataset Access

⚠️ **Important**: The CBIS-DDSM image dataset is **not included** in this repository due to size and licensing restrictions.

To run the notebook:

1. Download the dataset from [The Cancer Imaging Archive – CBIS-DDSM](https://www.cancerimagingarchive.net/)
2. Store the images in your own Google Drive or local machine
3. Update the image path references in the notebook

Optionally, you may include a few sample images in a `sample_images/` directory for testing or demonstration.

## 🚀 How to Run

### Step 1: Clone the repository

```bash
git clone https://github.com/your-username/cnn-cbis-ddsm-classification.git
cd cnn-cbis-ddsm-classification
```
### Step 2: Install dependencies
```bash
pip install -r requirements.txt
```
### Step 3: Launch the notebook
```bash
jupyter notebook "CNN_CBIS_DDSM_Image_Classification_(Group_3).ipynb"
```
