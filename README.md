# Resume Classification System

## Overview

The Resume Classification System is an automated tool designed to categorize resumes into pre-defined job domain classes like Data Science, Web Designing, and others. This project utilizes advanced Natural Language Processing (NLP) and Machine Learning (ML) techniques, including K-Nearest Neighbors (KNN), Convolutional Neural Networks (CNN), and DistilBERT, to streamline the recruitment process by efficiently sorting through large volumes of resumes.

## Features

- **Automated Classification:** Quickly categorizes resumes into relevant job domains, facilitating faster recruitment decisions.
- **Advanced ML Models:** Incorporates multiple machine learning models to ensure high accuracy and adaptability to various resume formats.
- **User-Friendly Interface:** Provides a simple and intuitive interface for users to upload and classify resumes.
- **Detailed Analytics:** Offers insights into the classification process with detailed accuracy and performance metrics.

## Built With

- **Languages:** Python
- **Libraries/Frameworks:** Scikit-learn, Keras, TensorFlow, Hugging Face's Transformers
- **Tools:** Jupyter Notebook, Pandas, NumPy
- **APIs:** GloVe for Word Representation

## Languages: Python
Libraries/Frameworks: Scikit-learn, Keras, TensorFlow, Hugging Face's Transformers
Tools: Jupyter Notebook, Pandas, NumPy
APIs: GloVe for Word Representation

## Getting Started
To get a local copy up and running follow these simple steps.
### Prerequisites
- Python 3.8+
- pip

**sudo apt-get install python3-pip**

### Installation
- Clone the repo

**git clone https://github.com/soundaryalaharivalipe/Resume_Classification_using_NLP**
- Install required packages

**pip install -r requirements.txt**

### Usage
To use the system, run the main script and follow the on-screen prompts to upload a resume and see the classification results.

**python main.py**

## Models

- **K-Nearest Neighbors (KNN):** Used for its simplicity and effectiveness in classification tasks.
- **Convolutional Neural Networks (CNN):** Employs a deep learning approach to extract higher-level features from the resume text.
- **DistilBERT:** A transformer-based model that provides state-of-the-art performance for NLP tasks.

## Data Visualization and Results 

- Visualizing the data distribution in each category:

![image](https://github.com/soundaryalaharivalipe/Resume_Classification_using_NLP/assets/169948476/3e5612fd-5062-43fb-bfd4-bc1c2499ab71)

- Visualizing most commonly used words in each type of Resumes:
![image](https://github.com/soundaryalaharivalipe/Resume_Classification_using_NLP/assets/169948476/f49e2525-126b-457f-95a3-209f8ba203d9)

![image](https://github.com/soundaryalaharivalipe/Resume_Classification_using_NLP/assets/169948476/358dfd3e-4333-4c4c-805e-510bd07f8f97)

![image](https://github.com/soundaryalaharivalipe/Resume_Classification_using_NLP/assets/169948476/3964c9e6-5ec7-464f-9a99-c4415524bd20)

- Visualizing the length distribution of the content in the Resumes:

![image](https://github.com/soundaryalaharivalipe/Resume_Classification_using_NLP/assets/169948476/b5e380d8-f0d0-4e24-8f13-a8964b0294aa)

- Visualizing of number of words in each category of resume using boxplot

![image](https://github.com/soundaryalaharivalipe/Resume_Classification_using_NLP/assets/169948476/e71f9c37-7378-4ae5-bffe-21b6985a68c7)

- Results – Evaluation Metrics Comparison:

![image](https://github.com/soundaryalaharivalipe/Resume_Classification_using_NLP/assets/169948476/439810f9-ab06-4f8c-ac61-9e0d6a6bded7)


## Contributions

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

- Fork the Project
- Create your Feature Branch (git checkout -b feature/AmazingFeature)
- Commit your Changes (git commit -m 'Add some AmazingFeature')
- Push to the Branch (git push origin feature/AmazingFeature)
- Open a Pull Request

## Acknowledgements

- Kaggle for Resume Dataset
- Hugging Face for Transformer Models
- GloVe: Global Vectors for Word Representation
