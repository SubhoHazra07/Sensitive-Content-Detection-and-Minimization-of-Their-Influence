# Sensitive Content Detection and Minimization of Their Influence

## Project Overview
Sensitive content refers to materials that expose personal or confidential information, which could lead to privacy violations, identity theft, or misuse. This project focuses on **detecting and minimizing the influence of sensitive content** shared on social media platforms. By utilizing **machine learning** and **deep learning** techniques, particularly **Convolutional Neural Networks (CNNs)**, this project aims to automate the detection of such content and reduce its impact through moderation and filtering.

## Key Features
- **Sensitive Content Detection**: Identifies sensitive images and documents like Aadhaar cards, PAN cards, and driver's licenses.
- **Psychological Impact Reduction**: Aims to reduce the stress and anxiety caused by accidental exposure of personal information.
- **Social Impact**: Prevents identity theft and privacy breaches by limiting the exposure of sensitive information.
- **Influence Minimization**: Reduces the dissemination of sensitive content by using AI to flag and filter inappropriate content.
- **Awareness**: Raises awareness of the dangers of sharing personal documents on social media and encourages stronger privacy controls.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Key Features](#key-features)
3. [Objectives](#objectives)
4. [Technologies Used](#technologies-used)
5. [Methodology](#methodology)
6. [Installation](#installation)
7. [How to Use](#how-to-use)
8. [Challenges](#challenges)
9. [Contributors](#contributors)

## Objectives
1. **Detect Sensitive Content**: Automatically detect sensitive content like personal documents in images.
2. **Reduce Psychological and Social Impact**: Implement measures to reduce the stress and anxiety caused by such content.
3. **Prevent Misuse**: Identify and flag sensitive documents that may be used for identity theft or online fraud.
4. **Educate Users**: Promote awareness about the dangers of sharing personal documents online and guide them toward safer practices.
5. **Minimize Influence**: Prevent the widespread dissemination of sensitive content through content warnings and filtering systems.

## Technologies Used
- **Python (v3.11.7 or above)**
- **TensorFlow & Keras** for deep learning and CNN implementation
- **Google Colab** for model training and cloud infrastructure
- **Natural Language Processing (NLP)** for text analysis and classification
- **Convolutional Neural Networks (CNN)** for image classification and content filtering
- **Anaconda** for environment management
- **Git** for version control

## Methodology
The following steps outline the methodology adopted for this project:

![Architecture](https://github.com/user-attachments/assets/039b3042-7b3d-4228-aa82-7fe88c405217)


1. **Data Collection and Labeling**:
    - Data is collected from social media platforms and other publicly available sources.
    - Experts label and annotate the data to ensure diversity and accuracy.
    - Sensitive content includes images of personal documents, images flagged for privacy concerns, etc.

2. **Model Training and Testing**:
    - **Convolutional Neural Networks (CNNs)** are used to detect sensitive content in images.
    - **NLP Models** are used to classify sensitive text content.
    - Both models are trained on labeled data, tested with real-world scenarios, and iterated upon to improve accuracy.
    - Model performance is evaluated through precision, recall, and F1-score metrics.

![Image_Classification1](https://github.com/user-attachments/assets/ff5de21b-1f30-4c8e-952a-7c7985787f20)

![Text_Classification](https://github.com/user-attachments/assets/005ce5e1-e855-44c9-a807-ba51333e6730)


3. **Content Moderation**:
    - Detected sensitive content is flagged for review or automatically filtered based on user-defined settings.
    - Users are provided with tools to report inappropriate content and control their privacy settings.

4. **Influence Minimization**:
    - Algorithms are adjusted to filter out sensitive material from users' feeds.
    - Customization options, such as content filters and warnings, are available to users to control what they see.


## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/SubhoHazra07/Sensitive-Content-Detection-and-Minimization-of-Their-Influence.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Sensitive Content Analysis
    ```
3. Create a virtual environment and activate it:
    ```bash
    conda create --name content-detection python=3.11.7
    conda activate content-detection
    ```
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## How to Use
1. **Data Upload**: Upload images or text to be analyzed for sensitive content.
2. **Run Models**: Execute the image and text classification scripts to get predictions on whether the content is sensitive.
    ```bash
    python src/image_classification.ipynb
    python src/text_classification.ipynb
    ```
3. **Customize Content Warnings**: Adjust content filters and privacy settings to manage the display of sensitive content.

## Challenges
- **False Positives/Negatives**: Achieving the perfect balance between flagging sensitive content and allowing legitimate content through remains a challenge.
- **Scalability**: Processing large volumes of user-generated content in real-time requires significant computational resources.
- **Cultural Sensitivity**: Different regions may interpret content differently, leading to misclassifications.

## Contributors
- **Subho Hazra** (GitHub: [SubhoHazra07](https://github.com/SubhoHazra07))
- **Shweta Das** (GitHub: [Shweta-Das01](https://github.com/Shweta-Das01))
