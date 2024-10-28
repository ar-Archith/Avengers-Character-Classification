# Avengers Character Image Classification with CNNs

This repository implements a Convolutional Neural Network (CNN) model to classify images of characters from the Avengers universe.

## Features:

- Utilizes TensorFlow and Keras for building and training the model.
- Performs image data augmentation for the training data (random shearing, zooming, and horizontal flipping) to improve model robustness.
- Employs a CNN architecture with convolutional and pooling layers for feature extraction, followed by dense layers for multi-class classification (considering multiple Avengers characters).
- Trains the model on a dataset of labeled character images.
- Predicts the character depicted in a new image.
- Visualizes training and validation accuracy and loss curves to monitor model performance.

## Requirements:

* Python 3.x
* Libraries: TensorFlow, Keras, Matplotlib, Numpy

## How to Use:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ar-archith/Avengers-Character-Classification.git
2. **Install Libraries:**
   ```bash
   pip install tensorflow keras matplotlib numpy
3. **Prepare Data:**
   Ensure you have a directory named `Avengers` containing three subdirectories: `train`, `test` and `val`.
   These subdirectories should further contain subfolders named after each Avenger character with their respective images.
4. **Run the Notebook:**
   Open the `avengers_character_classification.ipynb` file in your preferred Jupyter Notebook environment and execute the code cells.

## Note:

This is a basic example using a simple CNN architecture. You can explore more complex architectures and hyperparameter tuning for better performance.
The script assumes the data directory structure mentioned above.
Feel free to modify the code to adapt it for classifying characters in other datasets.

## License:

This project is licensed under the MIT License.
