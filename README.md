## Contents

1.  [Repository Name](#repository-name)
2.  [Title of the Project](#title-of-the-project)
3.  [Short Description of the Project](#short-description-of-the-project)
4.  [Objectives of the Project](#objectives-of-the-project)
5.  [Name of the Dataset](#name-of-the-dataset)
6.  [Description of the Dataset](#description-of-the-dataset)
7.  [Goal of the Project using this Dataset](#goal-of-the-project-using-this-dataset)
8.  [Why did we choose this dataset](#why-did-we-choose-this-dataset)
9.  [Size of dataset](#size-of-dataset)
10. [Algorithms which can be used as part of our investigation](#algorithms-which-can-be-used-as-part-of-our-investigation)
11. [Expected Behaviors and Problem Handling](#expected-behaviors-and-problem-handling)
12. [Issues to focus on](#issues-to-focus-on)
13. [Project Requirements](#project-requirements)
14. [Usage Instructions in Local System](#usage-instructions-in-local-system)
15. [Usage Instructions in Google Colab](#usage-instructions-in-google-colab)
16. [Authors](#authors)

# Repository Name
pneumonia-detection-in-chest-X-rays

# Title of the Project
Comparative Analysis of Image-Based and Feature-Based Approaches for Pneumonia Detection in Chest X-rays

# Short Description of the Project
This project focuses on detecting pneumonia from chest X-ray images using Advanced Machine Learning and Deep Learning techniques (Rajpurkar et al., 2017; Wang et al., 2017). By leveraging a comprehensive dataset, including annotated images of pneumonia and normal cases, we aim to develop and compare image-based and feature-based approaches. Our goal is to identify the most effective method for accurate and interpretable pneumonia detection, contributing to improved patient outcomes through early diagnosis and treatment. This model will classify patients based on their chest X-ray images as either having pneumonia (1) or not having pneumonia (0).

# Objectives of the Project
**1. Image Analysis:** Develop and evaluate deep learning models to classify chest X-rays directly. This approach leverages deep learning models, particularly Convolutional Neural Networks (CNNs), to perform end-to-end image classification. The models directly process raw chest X-ray images to classify them as normal or pneumonia.
**2. Feature Analysis:** Extract meaningful features from the images and use them to train and evaluate traditional machine learning models. In this approach, we first extract features from the chest X-ray images. These features are then used as inputs for traditional machine learning algorithms. The process includes steps such as feature extraction, selection, and transformation, followed by the application of machine learning techniques like Support Vector Machines (SVM), Random Forests.

# Name of the Dataset
The dataset used in this project is the Chest X-ray dataset considered from the Research paper named **Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification**.

**Data Source:** https://data.mendeley.com/datasets/rscbjbr9sj/2

**Type of the Dataset:** X-ray Images

# Description of the Dataset
The considered dataset has the following information for better reference:
- Separate folders to train and validate/test the model.
- Enough number of Chest X-ray images to train the model to detect and diagnose Pneumonia.
- The target variable for classification is whether patient has pneumonia or not.

# Goal of the Project using this Dataset
The goal of this project is to conduct a comprehensive comparative analysis of image-based and feature-based approaches for pneumonia detection using chest X-ray images. By evaluating the performance, robustness, and interpretability of deep learning and traditional machine learning models, we aim to identify the most effective method for accurately classifying chest X-rays as normal or pneumonia. This comparison will provide valuable insights into the strengths and limitations of each approach, ultimately contributing to improved detection and diagnosis of pneumonia, which can enhance patient outcomes and survival rates.

# Why did we choose this dataset
We selected this dataset based on several factors. For more detailed information, please refer to the following:
- The dataset is extensive, providing a large number of images suitable for evaluating and training deep learning models.
- It aligns well with the project's objectives by offering a challenging and realistic scenario for developing an image classification model using deep learning, specifically for Chest X-ray images.
- The dataset is annotated with images of two different diseases, enabling the development of a binary-class classification model.
- It is publicly available, facilitating easy access for research and development purposes.

# Size of dataset
- Total images size = 1.27 GB
- Dataset has 2 folders:
  -  **Train:**
    -  Normal (without Pneumonia) = 1349 images
    -  Pneumonia = 5233 images
  -  **Test:**
    -  Normal (without Pneumonia) = 5467 images
    -  Pneumonia = 5857 images

# Algorithms which can be used as part of our investigation
- Deep Learning Algorithms
  - Convolutional Neural Networks (CNNs)
  - Transfer Learning
- Traditional Machine Learning Algorithms
  - Support Vector Machines (SVM)
  - Random Forests
- Optimization Techniques
  - Local Search, Search Strategies, and Heuristics

# Expected Behaviors and Problem Handling
- Classify Chest X-ray images with high accuracy.
- Handle variations in image quality, resolution, and orientation.
- Be robust to noise and artifacts in the images.
- Provide interpretable results.

# Issues to focus on
- Improving model interpretability and explainability.
- Optimizing model performance on a held-out test set.
- Following AI Ethics and Data Safety practices.

# Project Requirements
TBD

# Usage Instructions in Local System
- Clone using HTTPS
```commandline
git clone https://github.com/kraviteja95usd/pneumonia-detection-in-chest-X-rays.git
```
OR - 

- Clone using SSH
```commandline
git clone git@github.com:kraviteja95usd/pneumonia-detection-in-chest-X-rays.git
```

OR -

- Clone using GitHub CLI
```commandline
git clone gh repo clone kraviteja95usd/pneumonia-detection-in-chest-X-rays
```
 
- Switch inside the Code Directory
```commandline
cd pneumonia-detection-in-chest-X-rays
```

- Install Requirements
```commandline
pip3 install -r requirements.txt
```

- Open your terminal (Command Prompt in Windows OR Terminal in MacBook)
- Type any one of the below commands based on the software installed in your local system. You will notice a frontend webpage opened in the browser.
```commandline
jupyter notebook
```
OR -
```commandline
jupyter lab
```
- Click (Single click or double click whatever works) on the `Diabetes_Detector.ipynb` file.
- You will notice the file opened.
- Click `Run` button from the Menu bar and select the option of your interest (`Run Cell` or `Run All` button).
- You can look at the execution results within the file.

# Usage Instructions in Google Colab
- Follow the same steps as above till switching to the `bin` directory.
- Goto [Google Colab](https://colab.research.google.com).
- You will find an option to `Upload Notebook`. 
- Upload the notebook from your laptop to Google Colab.
- Click on `Run` option and select `Run All` or `Run Cell` or any option of your interest. You will see the code running.
- You can look at the execution results within the file.

# Authors
| Author                           | Contact Details                  |
|----------------------------------|----------------------------------|
| Prof. Dr. Soumi Ray              | soumiray@sandiego.edu            |
| Ravi Teja Kothuru                | rkothuru@sandiego.edu            |
| Abhay Srivastav                  | asrivastav@sandiego.edu          |
