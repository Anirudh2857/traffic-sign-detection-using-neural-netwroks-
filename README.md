# Traffic Sign Detection

## Overview
This project is focused on detecting and classifying traffic signs using a deep learning model. The dataset used is the German Traffic Sign Recognition Benchmark (GTSRB). The project involves loading, preprocessing, training, and evaluating a convolutional neural network (CNN) model for traffic sign classification.

## Dataset
The dataset consists of images of German traffic signs, provided in three sets:
- **Training Set**: Used to train the model.
- **Validation Set**: Used to fine-tune the model hyperparameters.
- **Test Set**: Used to evaluate the final model performance.

## Project Structure
- **Cloning Dataset**: The dataset is cloned from a Bitbucket repository.
- **Data Loading**: The training, validation, and test datasets are loaded using pickle.
- **Data Preprocessing**: The dataset is explored and visualized to understand class distributions.
- **Model Definition**: A CNN model is built using Keras.
- **Training & Evaluation**: The model is trained using training data and evaluated on validation/test data.
- **Visualization**: Data distribution and example images from the dataset are displayed.

## Prerequisites
Ensure you have the following dependencies installed:
- Python 3.x
- NumPy
- Pandas
- OpenCV
- Matplotlib
- TensorFlow/Keras

## Installation
1. Clone the dataset repository:
   ```sh
   git clone https://bitbucket.org/jadslim/german-traffic-signs
   ```
2. Install dependencies:
   ```sh
   pip install numpy pandas matplotlib keras tensorflow opencv-python
   ```
3. Run the Jupyter Notebook or script:
   ```sh
   jupyter notebook Traffic_sign_detection.ipynb
   ```

## Usage
1. Load and preprocess the dataset.
2. Train the CNN model on the dataset.
3. Evaluate model performance using test data.
4. Visualize predictions and analyze misclassifications.

## Model Architecture
- **Convolutional Layers**: Extract spatial features from images.
- **Pooling Layers**: Reduce dimensionality and computational complexity.
- **Fully Connected Layers**: Classify traffic signs into appropriate categories.

## Results
The model is evaluated based on accuracy and loss metrics, with visualizations provided for performance analysis.

## Acknowledgments
- German Traffic Sign Recognition Benchmark (GTSRB) Dataset
- TensorFlow/Keras framework for deep learning model development

## License
This project is open-source and available for educational and research purposes.

