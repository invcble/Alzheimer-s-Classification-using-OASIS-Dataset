# Alzheimer’s Classification using OASIS Dataset

This project was developed as part of Machine Learning (CS 613) course requirement at Drexel University, Philadelphia, PA, between November and December 2023. It focuses on leveraging built-from-scratch machine learning models to classify Alzheimer's disease progression using the OASIS Alzheimer’s Detection Dataset. This dataset comprises 80,000 brain MRI images of 461 patients and aims to classify Alzheimer's progression based on Clinical Dementia Rating (CDR) values.

## Dataset

The dataset used for this project is the OASIS Alzheimer’s Detection Dataset, which can be found at [Kaggle: ImagesOASIS](https://www.kaggle.com/datasets/ninadaithal/imagesoasis). This dataset is crucial for training and validating our machine learning models to ensure accurate Alzheimer's progression classification.

## Models and Accuracy

The project implements various machine learning models to classify Alzheimer's progression:

- [**Click here for Source Codes**](https://github.com/invcble/Alzheimer-s-Classification-using-OASIS-Dataset/tree/c3b38a183a95d75954925389a3b73099e85a1fa1/Python%20source%20codes)
- [**Click here for Confusion Matrices**](https://github.com/invcble/Alzheimer-s-Classification-using-OASIS-Dataset/tree/c3b38a183a95d75954925389a3b73099e85a1fa1/Confusion%20Matrix)
- [**Click here for Detailed Results**](https://github.com/invcble/Alzheimer-s-Classification-using-OASIS-Dataset/blob/6a36a896b1e88f9f232883aab4faa0174e0fd1ee/RESULTS.txt)
- [**Click here for Project Paper**](https://github.com/invcble/Alzheimer-s-Classification-using-OASIS-Dataset/blob/c3b38a183a95d75954925389a3b73099e85a1fa1/Final_Project_Paper_CS_613.pdf)


## Setup and Running the Project

This project is designed to run on Google Colab, utilizing Google Drive for dataset storage due to the large size of the dataset. Follow these steps to set up and run the project:

1. **Download the Dataset**: Download the dataset from [Kaggle: ImagesOASIS](https://www.kaggle.com/datasets/ninadaithal/imagesoasis) and upload it to your Google Drive.
2. **Mount GDrive**: Run the first cell of the Python code in Google Colab to mount your Google Drive as a local drive.
3. **Unzip the Dataset**: Navigate to the left side file section in Google Colab, copy the path of `Dataset.zip`, and paste it into the unzip code cell.
4. **Execute the Code**: Run the remaining cells in the notebook to train and evaluate the models.

## Requirements

This project requires a Google Colab environment for execution. Specific library dependencies will be automatically handled by the notebook. Ensure you have access to Google Drive for storing and accessing the dataset.

## Acknowledgments

We would like to thank Professor Mathew Burlick, Drexel University for supporting this academic project and the creators of the OASIS dataset for providing a valuable resource for Alzheimer's research.
