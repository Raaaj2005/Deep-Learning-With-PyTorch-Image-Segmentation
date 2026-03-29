# 🖼️ Deep Learning With PyTorch - Image Segmentation

## 📖 Overview
This project dives into advanced computer vision by focusing on pixel-level image segmentation. The notebook walks through the complete deep learning pipeline required to build and train a U-Net architecture from scratch using PyTorch. It covers everything from creating custom dataset classes and applying advanced image augmentations to writing custom training and evaluation loops.

## 🎯 Objective
The primary objective is to develop a deep learning model capable of accurately segmenting images by classifying each pixel. By implementing the widely used U-Net architecture and leveraging the Albumentations library for robust data preprocessing, the project aims to demonstrate end-to-end proficiency in handling complex computer vision tasks.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Deep Learning Framework:** PyTorch
* **Image Augmentation:** Albumentations
* **Data Manipulation & Visualization:** NumPy, Matplotlib

## 🧠 Key Learnings & Skills Demonstrated
* **Custom Data Pipelines:** Building custom PyTorch `Dataset` and `DataLoader` classes to efficiently handle images and their corresponding segmentation masks.
* **Advanced Augmentation:** Utilizing the Albumentations library to apply robust, high-performance image transformations to both images and masks simultaneously.
* **Model Architecture:** Architecting and constructing a complete U-Net convolutional neural network specifically designed for biomedical and general image segmentation.
* **Custom Training Loops:** Writing explicit training and evaluation functions to calculate loss, backpropagate gradients, and track model performance across epochs.
* **Model Evaluation:** Visualizing the predicted segmentation masks against the ground truth to qualitatively assess the model's accuracy.

## 🚀 Getting Started

### 📋 Prerequisites
To run this project, you will need:
* Python 3.x
* Jupyter Notebook or JupyterLab

### ⚙️ Installation & Setup

1. Clone the repository to your local machine:
   git clone https://github.com/Raaaj2005/Deep-Learning-With-PyTorch-Image-Segmentation.git

2. Navigate into the downloaded project folder:
   cd Deep-Learning-With-PyTorch-Image-Segmentation

3. Install the required dependencies:
   pip install torch torchvision albumentations numpy matplotlib jupyter

4. Launch the Jupyter Notebook environment:
   jupyter notebook

5. Open the project's .ipynb file and execute the cells sequentially to build the dataset, initialize the U-Net, and begin training.

## 👤 Author
Name: Raj Fatehveer Singh Brar<br>
Email ID: rbrar_be23@thapar.edu<br>
University: Thapar Institute of Engineering and Technology
