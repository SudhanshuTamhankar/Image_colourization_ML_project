# 🎨 Image Colourization — Machine Learning Project

This repository contains the implementation of an **Image Colourization** pipeline using deep learning techniques. The project was developed as part of the coursework for the **Introduction to Machine Learning (IML)** course.

We take grayscale art images (drawings, engravings, paintings, etc.) and use a convolutional neural network (CNN) model to predict their corresponding colorized versions.

---

## 📊 Dataset

We used the following dataset from Kaggle:

🔗 [Art Images: Drawings, Paintings, Sculptures, Engravings](https://www.kaggle.com/datasets/thedownhill/art-images-drawings-painting-sculpture-engraving)

This dataset includes a wide variety of artistic image types:
- Drawings
- Paintings
- Sculptures
- Engravings
- Iconography

> ⚠️ **Note**:  
> Due to GitHub's file size restrictions, the **full dataset is not included** in this repository.  
> Only a **sample** of the training and validation set is provided to demonstrate the folder structure.

---

## 🗂️ Project Structure

IML_Project/
├── image-colorization.ipynb # Main Jupyter notebook with model code
├── dataset/
│ ├── sample_training_set/
│ │ ├── drawings/
│ │ ├── paintings/
│ │ └── ...
│ └── sample_validation_set/
│ ├── drawings/
│ ├── paintings/
│ └── ...
├── musemart/
│ ├── sample_training_set/
│ │ ├── drawings/
│ │ ├── paintings/
│ │ └── ...
│ └── sample_validation_set/
│ ├── drawings/
│ ├── paintings/
│ └── ...
└── README.md


> Place full dataset folders in:
dataset/dataset_updated/training_set/
dataset/dataset_updated/validation_set/
musemart/training_set/
musemart/validation_set/


---

## 🚀 Getting Started

### 📦 1. Clone the Repository

```bash
git clone https://github.com/SudhanshuTamhankar/Image_colourization_ML_project.git
cd Image_colourization_ML_project
📥 2. Download Full Dataset
Download from Kaggle:
📎 https://www.kaggle.com/datasets/thedownhill/art-images-drawings-painting-sculpture-engraving

Extract and place it in the following structure:
dataset/dataset_updated/training_set/[class folders]
dataset/dataset_updated/validation_set/[class folders]

🧪 3. Run the Notebook
Launch image-colorization.ipynb in Jupyter Notebook, VS Code, or Google Colab.

Train the model and test colorization results.

🧠 Features
Grayscale to RGB image colorization

Data preprocessing (resizing, normalization)

CNN model for image-to-image translation

Training with validation loss tracking

Visualization of predicted colorizations

🖼️ Sample Results
Sample output images comparing grayscale inputs and predicted colorized outputs can be placed here.

🧾 License
This project is for educational and academic use only.

👨‍💻 Author
Sudhanshu Tamhankar
BTech, IIT Jodhpur


---

You can save this as `README.md` in your project folder, commit it, and push it using:

```bash
git add README.md
git commit -m "Add complete README"
git push

