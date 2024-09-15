# Brain Tumor Detection Web Application

## Overview

This project is a web-based application for brain tumor detection using MRI scans. It utilizes deep learning techniques to analyze MRI images and provide probability estimates for the presence of tumors. The application offers a user-friendly interface for uploading scans, conducting analyses, and generating detailed reports.

## Features

- **MRI Scan Upload**: Support for JPG, JPEG, and PNG image formats.
- **Tumor Detection**: Utilizes a pre-trained deep learning model to predict tumor probability.
- **Advanced Image Processing**: Implements image preprocessing techniques for enhanced analysis.
- **3D Visualization**: Generates interactive 3D plots of MRI scans with potential tumor regions highlighted.
- **Patient Information Management**: Allows input and storage of patient details.
- **Consultation Interface**: Provides a structured workflow for medical consultations.
- **Report Generation**: Creates comprehensive HTML reports with visualizations and analysis results.

## Technologies Used

- Python
- Streamlit
- TensorFlow
- Scikit-learn
- Plotly
- Matplotlib
- Pillow (PIL)
- NumPy
- SciPy

## Model File

The pre-trained model file is hosted on Google Drive due to its large size.

**Google Drive Link**: https://drive.google.com/file/d/1GxejhxN0J0oWBMIpspKHEFGDJmBMaCOT/view?usp=drive_link

## Google Colab

To view and interact with the source code online, you can use our Google Colab notebook:

**Google Colab Link**: https://colab.research.google.com/drive/1E1q9KKJr45EQiwnZls1jKKY4mlxPRUye?usp=sharing

This Colab notebook contains the core functionality of our project and allows you to run the code in a cloud environment.

## Setup and Installation

1. Clone the repository:
   ```
   git clone https://github.com/Mahi3005/Brain_Tumor_Detection.git
   cd brain-tumor-detection
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Download the pre-trained model:
   - Download `brain_tumor_detection_model (1).h5` from the Google Drive link provided in the "Model File" section above.
   - Place the downloaded file in the project's root directory.

## Usage

1. Ensure you have downloaded the model file as described in the setup instructions.

2. Start the Streamlit application:
   ```
   streamlit run app.py
   ```

3. Open your web browser and navigate to the URL provided by Streamlit (usually `http://localhost:8501`).

4. Use the sidebar to navigate between different pages:
   - **Upload MRI Scan**: Upload and analyze MRI scans.
   - **Consultation**: Enter patient information and view detailed analysis results.
   - **Report**: Generate and download comprehensive HTML reports.


## Note on Model File

The deep learning model used in this project (`brain_tumor_detection_model (1).h5`) is not included in the GitHub repository due to its large size. It is instead hosted on Google Drive to ensure easy access while keeping the repository size manageable. Make sure to download this file before running the application locally.

## Online Code Exploration

For those who want to explore or run the code without local setup, please use the Google Colab link provided in the "Google Colab" section. This allows you to interact with the core functionality of the project in a cloud-based environment.
