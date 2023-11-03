# Cats vs. Dogs Classification using VGG-16

This project involves the use of a VGG-16 neural network to distinguish between images of cats and dogs. Built with TensorFlow, it demonstrates effective data preprocessing, fine-tuning a pre-trained model, and evaluating performance with a detailed confusion matrix.

## Project Overview

- **Objective**: Binary classification to differentiate cat and dog images.
- **Techniques Used**:
  - Data augmentation and preprocessing with `ImageDataGenerator`.
  - Transfer learning with VGG-16.
  - Model evaluation using a confusion matrix.

## Results

The model demonstrates robust performance with a 97.5% accuracy on the validation set during training. Upon evaluation, it achieves a commendable 96.50% accuracy on the test set, indicating strong generalization and predictive capabilities.

## Dataset Source

The dataset utilized for training and evaluating the model is the popular "Dogs vs. Cats" dataset, which was originally used for a Kaggle competition. It comprises images of cats and dogs, aimed at developing algorithms to correctly classify the images into the respective categories. The dataset can be accessed at [Kaggle: Dogs vs. Cats](https://www.kaggle.com/competitions/dogs-vs-cats/data).

## Acknowledgments

This project was inspired by the "Keras with TensorFlow Course - Python Deep Learning and Neural Networks" provided by freeCodeCamp.org. The concepts and code examples from the [YouTube tutorial](https://www.youtube.com/watch?v=qFJeN9V1ZsI) were instrumental in the development of this project, offering a solid foundation in deep learning practices and model evaluation techniques.

## Contributing

Feel free to fork the project and submit pull requests.
