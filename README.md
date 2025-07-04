# Brain Tumor Detection using CNN, OpenCV, and Streamlit

This project is a deep learning-based web application for detecting brain tumors from MRI scans. It uses a Convolutional Neural Network (CNN) built with TensorFlow and OpenCV for image processing. The user interface is built using Streamlit, making it easy to upload and analyze MRI images in a browser.

## Features

- Upload MRI brain scan images  
- Automatic classification: Tumor or No Tumor  
- Built with a custom CNN for high accuracy  
- User-friendly web interface using Streamlit  
- Image preprocessing using OpenCV

## Technologies Used

- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Streamlit

## How the Model Works

1. Image Input: User uploads an MRI scan  
2. Preprocessing: Image is resized, normalized, and processed using OpenCV  
3. Prediction: CNN model classifies the image as Tumor or No Tumor  
4. Output: Prediction is displayed on the Streamlit interface

## How to Run the App

### Step 1: Clone the Repository

```bash
git clone https://github.com/piyush09-09/brain-tumor-detection
cd brain-tumor-detection
