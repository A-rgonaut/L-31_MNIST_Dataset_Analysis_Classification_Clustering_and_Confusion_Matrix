# MNIST Dataset Analysis: Classification, Clustering, and Confusion Matrix

![Jupyter Notebook](https://img.shields.io/badge/Jupyter-FAFAFA?style=for-the-badge&logo=jupyter&logoColor=F37626)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

> Team implementation of a machine learning model in Python for the recognition of images of numbers, with related clustering and confusion matrix.

## 📖 **Context**

This project was developed for the **Data Science** examination of Prof. **Domenico Garlisi**, during the **2022/2023** Academic Year at the **Università degli Studi di Palermo**, **Computer Science (L-31, 2086)** course.

## 👥 **Authors**
_Andrea Spinelli - Marco Valenti - Raffaele Terracino_

## 🛠️ **Technologies Used**

*   **Languages:** Python
*   **Frameworks/Libraries:** scipy, sklearn, matplotlib, numpy 
*   **Other:** Git

## 🚀 **Installation and Startup**

To run this project, you will need Python and Jupyter Notebook installed. The following steps will guide you through the process.

### Instructions

1. **Clone the Repository**
    Open your terminal or command prompt and clone the repository to your local machine.
    ```bash
    git clone https://github.com/A-rgonaut/L-31-2023-Progetto-Data-Science.git
    cd L-31-2023-Progetto-Data-Science
    ```

2.  **Create and Activate a Virtual Environment (Recommended)**
    It is a best practice to create a virtual environment to keep project dependencies isolated.
    ```bash
    # Create the virtual environment
    python -m venv venv

    # Activate the environment
    # On Windows:
    .\venv\Scripts\activate
    # On macOS/Linux:
    source venv/bin/activate
    ```

3.  **Launch Jupyter Notebook**
    Once the dependencies are installed, you can start the Jupyter Notebook server.
    ```bash
    jupyter notebook
    ```
    This command will open a new tab in your web browser, showing the project's file directory.

4.  **Run the Project**
    Click on the `Progetto Data Science.ipynb` file from the browser interface. You can now run the cells in the notebook individually or all at once to see the complete analysis, from data loading to model evaluation.

## ✨ **Key Features**

This project provides a comprehensive walkthrough of a machine learning task for image recognition. The analysis is conducted within a Jupyter Notebook (`.ipynb`), which combines code, visualizations, and explanatory text.

The core functionalities are:

1. **Data Loading and Exploration**:
    
    The project loads a standard image dataset (likely the **MNIST dataset** of handwritten digits).
    
    It performs an initial exploratory data analysis (EDA) to understand the dataset's structure and visualizes sample images to provide context.

2.  **Data Preprocessing**:
    
    The image data is preprocessed to be suitable for machine learning models. This includes steps like:
    - **Flattening** the 2D image arrays into 1D vectors.
    - **Normalizing** pixel values (usually scaling them from a 0-255 range to a 0-1 range) to improve model performance.

3.  **Model Training and Classification**:
    
    A machine learning model is trained to **classify** the images, assigning a label (from 0 to 9) to each digit.
    
    The notebook likely implements a common classification algorithm such as K-Nearest Neighbors (KNN), Support Vector Machine (SVM), or a simple Neural Network.

4.  **Performance Evaluation**:
    
    The model's performance is rigorously evaluated using standard metrics. A key output is the **Confusion Matrix**, which gives a detailed breakdown of correct and incorrect predictions for each digit.
    
    Other metrics like **accuracy**, **precision**, and **recall** are also calculated to provide a complete picture of the model's effectiveness.

5.  **Clustering Analysis**:
    
    In addition to classification (supervised learning), the project also explores **unsupervised learning** through clustering.
    
    It groups the images based on their visual similarity *without* using the true labels. This analysis helps to discover the natural structure within the data and see how well the digits separate into distinct groups based on pixel data alone.
