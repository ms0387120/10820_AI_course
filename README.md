# 10820_AI_course

## 0. Team Formulation & Data Download
* **Deadline: 2020/05/10 23:30**
* Team Formulation

  - iLMS
  - Register on [AI mango competition](https://aidea-web.tw/topic/72f6ea6a-9300-445a-bedc-9e9f27d91b1c)

* Data Download


---
## 1. Python Installation & Deep Learning Environment

* Tutorial

  - Read the pdf file and make sure Python and deep learning environment work in the computer.
  - Make sure that your team could do all jobs in the checklists before TAs announce the term project.

    - [Checklist](https://paper.dropbox.com/doc/practice-of-final-project--AxvG4ZHbneVrAU0O2yZq~zqtAQ-2GNV5YSCyFXTJA96Q7PUS)


---
## 2. Template Model

* Data preprocessing
  
  - Image
    - Convert image to array, the data type is float32.
    
  - Label
    - First, convert label \[A,B,C\] to \[0,1,2\].
    - Second, use one-hot encoding to encode converted label, the data type is float32.
    
  - Mapping converted image and label.
  - Generate .npz file, and upload it to google drive.
    - .npz file is the dataset that will be used to train, evaluate and predict. 
  
  - **Notice**
    - TA run it at localhost.
    - If you want to run it at colab, you need mount the google drive and modify the file path in the code.
  
  - **You can use your own way to preprocess these data.**

* Template model

  - There are three template models:
    - DenseNet-121
    - ResNeXt-50
    - VGG16
    
  - Some of these models' layers are trainable.
  - These models all can be built by importing Keras packages.
  - These models all can be run at colab.
  - Step by step: 
    - I. Create model
    - II. Load Training dataset
    - III. Train model by trainig dataset
    - IV. Save best model and weights
    - V. Draw learning curves
    - VI. Load best model and weights
    - VII. Load Dev dataset
    - VII. Evaluate and predict by dev dataset
    - IX. Use confusion matrix to analyze the predict result
   
   - **You can use your own way to create model to get best result.**


---
## 3. OOO



---
## Prof's Expectation
* Phase I - Deep Learning Classification

  - mango grade ranking
  - Advanced CNN methods
  
    - VGG16/19
    - ResNeXt
    - DenseNet
    - etc.

* Phase II - Ensemble Learning

  - Combine lost of methods in order to compare with accuracy of single model
  
    - Adaboost
    - Voting
    - etc.

* Phase III - Data Augmentation by GAN

  - In order to compared with phase II, let students do data augmentation by GAN
  
    - DCGAN
    - Conditional GAN
    - etc.

* **Final Model Version is fine-tuned via advanced CNN models, ensemble learning, and data augmentation by GAN.**


---
## Demo
* TA need to do

  - **Train GAN to generate pictures that students don't have in their dataset (Training set & Dev set)**


---
## Schedule

| Event | Date |
| :--------: | :--------: |
| Demo     | 6/17 (Wed)     |
| Presentation     | 6/19 (Fri)、24 (Wed)     |
| Summer Vacation Starts     | 6/29 (Mon)     |
