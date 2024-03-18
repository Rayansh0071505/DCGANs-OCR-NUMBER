# DCGANs for creation of Synthesis data for Number Datasets
### `DCGAN - Deep Convolution Generative Adversial Network`

The DCGAN is more suitable for working with images and videos, while the other GAN is more suitable for general use.

For more info - https://arxiv.org/abs/1511.06434

DCGAN Consisr of two neural networks - 
- Generator
- Discriminator

- Generator receives random noise as input and returns fake image as output.
- The Discriminator recives both real and fake images as input and after analyzing the image, returns a value between 0 and 1, which is used to indicate how fake or how real the image look.
- DCGAN uses binary cross-entropy as the loss function.
- Generator does not `see` the real images,it only learn through feedback from the Discriminator.
- The goal of the Generator is to decive the Discriminator by generating increasingly realistic fake image, while the goal of the Discriminator is to correctly identify real and fake images.

<img width="1176" alt="image" src="https://github.com/Rayansh0071505/DCGANs-OCR-NUMBER/assets/98272246/2184b0ec-a654-4f67-9110-a4e530d043d6">



## Introduction

This project leverages Deep Convolutional Generative Adversarial Networks (DCGANs) . This repository includes a comprehensive notebook that details the process from start to finish, including code snippets and step-by-step explanations.
<img width="1196" alt="image" src="https://github.com/Rayansh0071505/DCGANs-OCR-NUMBER/assets/98272246/9598f318-0a41-4db1-b127-d8f70e990cc7">

## Features

- Detailed Jupyter notebook with full explanation.
- Implementation of DCGANs for numeric OCR.
- Examples and test results on number datasets.
- Guidelines for extending the project to other OCR tasks.

## Requirements

- Python 3.6+
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib (for visualization)

Please refer to `requirements.txt` for a complete list of dependencies.

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/yourgithubusername/DCGANs-OCR.git
cd DCGANs-OCR
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Navigate to the notebook:

```bash
jupyter notebook DCGANs_OCR.ipynb
```

Follow the instructions within the notebook for detailed steps on how to use the model.

## Contributing

We welcome contributions! If you have suggestions for improvements or want to contribute to the project, please feel free to fork the repository and submit a pull request.

## Support

If you have any questions or need further clarification, don't hesitate to raise an issue in the repository or directly message me. For more projects like this, check out my https://www.linkedin.com/in/rayansh-srivastava-419951219/


Feel free to customize each section based on the specific details of your project, such as installation instructions, usage examples, and any acknowledgments you'd like to include.
