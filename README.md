# Deepfake Detection Model with XceptionNet

This repository contains code and instructions for building a deepfake detection model. The project is divided into several steps, including dataset preparation, frame selection and face alignment, RGB and SRM training, and the use of the Xception model for classification.

## Table of Contents
- Introduction
- Project Structure
- Requirements
- Setup
- Usage
- Acknowledgments

## Introduction
Deepfakes are synthetic media in which a person in an existing image or video is replaced with someone else's likeness. This project aims to develop a robust model to detect such deepfake videos.

## Project Structure
- **Dataset_Preparation.ipynb:** Notebook for preparing the dataset, including downloading and organizing data.
- Frame_Selection_and_Face_Alignment.ipynb: Notebook for selecting relevant frames from videos and aligning faces for consistency.
- RGB_Training.ipynb: Notebook for training the model on RGB data.
- SRM_Training.ipynb: Notebook for training the model on Spatial Rich Model (SRM) data.
- Xception.ipynb: Notebook for using the Xception model to classify the data and detect deepfakes.

## Requirements
The project requires the following packages:

```plaintext
numpy
pandas
scikit-learn
tensorflow
keras
opencv-python
dlib
matplotlib
tqdm
```

## Setup
### Clone this repository:

```bash
git clone <repository-url>
cd deepfake_detection_model
```

### Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### Install the required packages:

```bash
pip install -r requirements.txt
```

### Usage

#### Dataset Preparation:
>Open [Dataset_Preparation.ipynb](./Notebooks/Dataset_Preparation-Copy1.ipynb) and run the cells to prepare the dataset.

#### Frame Selection and Face Alignment:
>Open [Frame_Selection_and_Face_Alignment.ipynb](./Notebooks/Frame%20Selection%20and%20Face%20Alignment.ipynb) and run the cells to select frames and align faces. This is only for understanding purposes the script has been added in the Dataset Preparation Notebook

#### RGB Training:
>Open [RGB_Training.ipynb](/Notebooks/RGB%20Training.ipynb) and run the cells to train the model on RGB data.

#### SRM Training:
>Open [SRM_Training.ipynb](./Notebooks/SRM%20Training.ipynb) and run the cells to train the model on SRM data.

#### Xception Model:
>Open [Xception.ipynb](./Notebooks/Xception%20(2).ipynb) and run the cells to use the Xception model for classification.

## Acknowledgments
This project utilizes various open-source libraries and resources. Special thanks to the contributors and maintainers of these projects.