# GAN-MNIST-Image-Generator
This repository contains a TensorFlow/Keras implementation of a Generative Adversarial Network (GAN) designed to generate images resembling handwritten digits from the MNIST dataset. The project aims to explore and demonstrate the capabilities of GANs in generating new, realistic images based on a training set of handwritten digits

## Features
- **Data Preparation:** Script for loading and preprocessing MNIST dataset.
- **Model Architecture:** Customizable generator and discriminator models.
- **Training Loop:** Efficient training process with real-time loss tracking.
- **Visualization:** Utilities for plotting training loss and saving generated images.

## Installation

To get started with this project, you will need Python 3 and the following Python libraries installed:

- TensorFlow
- Keras
- NumPy
- Matplotlib

You can install these packages using `pip`:

```python
pip install tensorflow keras numpy matplotlib
```
## Usage
To train the GAN model with default settings, run the following command:

```python
python gan_mnist.py
```
This will start the training process for 100 epochs with a batch size of 128. You can adjust the epochs and batch size in the mnist_GAN.ipynb script.

## Structure
mnist_GAN.ipynb: Main script containing the data preparation, model definitions, training loop, and visualization utilities.
images/: Directory where generated images and loss plots are saved during training.

## Visualization
After each training epoch, generated images will be saved in the images/ directory. Loss plots for both the generator and discriminator will be saved as well, providing insight into the training process.

## Contributing
Contributions to this project are welcome! Please fork the repository, make your changes, and submit a pull request.

## License
This project is open-source and available under the MIT License.

