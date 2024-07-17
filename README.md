# MediAssist


## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Snapshots](#snapshots)
- [Contributing](#contributing)
 

## Introduction
MediAssist is designed to assist users in predicting potential diseases based on their symptoms. Leveraging machine learning algorithms, the chatbot provides a preliminary diagnosis, helping users to seek further medical consultation if needed. This tool is particularly useful in remote areas where access to healthcare is limited.

## Features
- Symptom input through natural language
- Predicts possible diseases based on symptoms
- User-friendly chatbot interface
- Real-time predictions
- Easy integration with other platforms

## Technologies Used
- **Programming Language**: Python
- **Libraries**: scikit-learn, pandas, numpy, nltk, spacy
- **Machine Learning Algorithms**: K-Nearest Neighbors (KNN), Decision Tree
- **Framework**: Streamlit

## Installation
To get a local copy up and running follow these simple steps.

1. **Clone the repository**
    ```bash
    git clone https://github.com/chaitanya3105/MediAssist.git
    ```

2. **Navigate to the project directory**
    ```bash
    cd MediAssist
    ```

3. **Install the dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the chatbot**
    ```bash
    streamlit run app.py
    ```

## Usage
1. Launch the chatbot using the command above.
2. Enter your symptoms in natural language.
3. Receive a list of possible diseases.
4. Consult a healthcare provider with the preliminary diagnosis.

## Snapshots
Here are some snapshots of MediAssist in action.

### Home Page
![Home Page](hone.jpg)

### Symptom Input
![Symptom Input](2nd.jpg)

### Prediction Results
![Prediction Results](3.jpg)

## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

