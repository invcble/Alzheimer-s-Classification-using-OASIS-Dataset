# Alzheimer’s Classification using OASIS Dataset

This project was developed as part of a research initiative at Drexel University, Philadelphia, PA, between November and December 2023. It focuses on leveraging machine learning models to classify Alzheimer's disease progression using the OASIS Alzheimer’s Detection Dataset. This dataset comprises 80,000 brain MRI images of 461 patients and aims to classify Alzheimer's progression based on Clinical Dementia Rating (CDR) values.

## Dataset

The dataset used for this project is the OASIS Alzheimer’s Detection Dataset, which can be found at [Kaggle: ImagesOASIS](https://www.kaggle.com/datasets/ninadaithal/imagesoasis). This dataset is crucial for training and validating our machine learning models to ensure accurate Alzheimer's progression classification.

## Models and Accuracy

The project implements various machine learning models to classify Alzheimer's progression:

- **Logistic Regression and LDA**: Implemented from scratch, achieving 81% and 73% accuracy, respectively, for binary classification.
- **Multiclass Analysis**: Utilized KNN and Naive Bayes models with image preprocessing techniques such as Blur and Canny edge detection, achieving a peak accuracy of 73% with KNN using Canny edge.
- **Custom Models and Ensembling**: Developed custom one vs. one Logistic Regression and LDA models, attaining 84% and 78% accuracy, respectively. An ensemble of these models achieved a final accuracy of 86% for Multi-Class Classification.

## Setup and Running the Project

This project is designed to run on Google Colab, utilizing Google Drive for dataset storage due to the large size of the dataset. Follow these steps to set up and run the project:

1. **Download the Dataset**: Download the dataset from [Kaggle: ImagesOASIS](https://www.kaggle.com/datasets/ninadaithal/imagesoasis) and upload it to your Google Drive.
2. **Mount GDrive**: Run the first cell of the Python code in Google Colab to mount your Google Drive as a local drive.
3. **Unzip the Dataset**: Navigate to the left side file section in Google Colab, copy the path of `Dataset.zip`, and paste it into the unzip code cell.
4. **Execute the Code**: Run the remaining cells in the notebook to train and evaluate the models.

## Requirements

This project requires a Google Colab environment for execution. Specific library dependencies will be automatically handled by the notebook. Ensure you have access to Google Drive for storing and accessing the dataset.

## Contributions

We welcome contributions from the community, including improvements to the code, suggestions on model optimization, and enhancements to the project's overall methodology. Please submit a pull request or open an issue to discuss your ideas.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.

## Acknowledgments

We would like to thank Drexel University for supporting this research project and the creators of the OASIS dataset for providing a valuable resource for Alzheimer's research.