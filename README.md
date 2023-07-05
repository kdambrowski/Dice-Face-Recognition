# Dice Recognition and Counting Tool

The overall goal of this project is to develop a tool that can automatically recognize and count the values of dice based on photos of six-sided dice. We will achieve this by building a machine-learning model.

## Table of Contents
- [Project Description](#project-description)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Project Status](#project-status)

## Project Description
The overall goal of this project is to develop a tool that can automatically recognize and count the values of dice based on photos of six-sided dice. We will achieve this by building a machine-learning model.

### Dataset
The dataset used for training and validating the machine learning model consists of 1,944 images of dice. These images were captured using two different sizes and colors of dies.

**Image Specifications:**
- Image Format: JPG
- Size: 256 x 256
- Channel: 3 (Color)
- Depth: 8

**Labels Specification:**
| Label Dice | Count |
|------------|-------|
| 1          | 324   |
| 2          | 324   |
| 3          | 324   |
| 4          | 324   |
| 5          | 324   |
| 6          | 324   |

The labels are balanced, with equal images for each dice value.

### Recognition and Counting Approach
In order to recognize the face of the dice and count the circles, we will utilize image processing utilities and a deep learning model.

## Technologies Used
The following technologies and libraries are used in this project:
- Python
- TensorFlow
- Keras
- OpenCV
- pandas
- NumPy
- seaborn
- matplotlib

## Setup
To run the Dice Recognition and Counting Tool, follow the steps below:

1. Install the required libraries using the following command:
!pip install keras_cv
!pip install pretty_confusion_matrix

2. Import the necessary libraries in your Python environment.

3. Load the dataset and preprocess the images.

4. Build and train the machine learning model using TensorFlow and Keras.

5. Test the trained model using the testing dataset.

6. Evaluate the model's performance using metrics such as confusion matrix, ROC curve, and accuracy.

7. Visualize the results using Seaborn and matplotlib.

## Usage
1. Clone this repository or download the source code.

2. Install the required libraries by using pip.

3. Navigate to the project directory.

4. Run the necessary commands to preprocess the dataset and train the model.

5. Use the trained model to recognize and count dice values based on input images.

## Project Status
The project is in progress. The dataset has been collected, and the initial model training and testing have been completed. Further improvements and optimizations are being explored to enhance recognition and counting accuracy.
