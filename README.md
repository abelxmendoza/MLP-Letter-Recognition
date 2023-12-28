# Handwritten Letter Recognition with MLP

## Problem

Recognizing handwritten letters is a non-trivial task due to the inherent variability in how different individuals write. This project addresses the challenge of handwritten letter recognition, specifically focusing on converting handwritten letters into typed text. The problem involves training a machine learning model to accurately identify handwritten letters and convert them to their corresponding typed characters.

## Introduction

Handwritten Letter Recognition with MLP is a project that leverages the power of Multi-Layer Perceptron (MLP) neural networks to tackle the problem of recognizing handwritten letters. This repository provides a comprehensive solution that includes data preprocessing, model training, testing, and application to handwritten text.

## Concepts

### Multi-Layer Perceptron (MLP)

The Multi-Layer Perceptron is a feedforward artificial neural network widely used for various machine learning tasks, including pattern recognition. In this project, an MLP with multiple layers is employed to recognize handwritten letters. The MLP learns to map pixel values of handwritten letters to their corresponding typed characters.

### Data Preprocessing

To facilitate effective training, the dataset of handwritten letters is preprocessed. This includes resizing images, applying Gaussian blur, and normalizing pixel values. Preprocessing ensures that the data is in a suitable format for training the MLP.

### Training and Testing

The MLP model is trained on a dataset of handwritten letters, with a portion of the data reserved for testing. Training involves adjusting the model's internal parameters to minimize prediction errors. Testing assesses the model's accuracy in recognizing handwritten letters.

### Conversion to Typed Text

After training, the trained MLP model is applied to handwritten text. The handwritten text is processed similarly to the training data, and the model predicts the corresponding typed characters. The result is a conversion of handwritten text to typed text.



## Getting Started

### Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/abelxmendoza/MLP-Letter-Recognition.git
```

    or

2. Run in Google Colab

[https://colab.research.google.com/drive/1NyYH1EPpaJlMBLK0fcKYz4icaD1SNSLK?usp=sharing](https://colab.research.google.com/drive/1NyYH1EPpaJlMBLK0fcKYz4icaD1SNSLK?usp=sharing)


## Contributing

Contributions to this project are welcome! If you have ideas for improvements, bug fixes, or new features, please open an issue or submit a pull request.

## Acknowledgments

* Original code and concepts: Jabril from PBS Crash Course AI on YouTube. Watch the video [here](https://www.youtube.com/watch?v=6nGCGYWMObE&list=PL8dPuuaLjXtO65LeD2p4_Sb5XQ51par_b&index=6).

## License

This project is licensed under the MIT License - see the [LICENSE]() file for details.
