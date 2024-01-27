# Colorization Project 
## Overview
Welcome to the Colorization Project! This project focuses on the development of a colorization model using a variety of powerful libraries and techniques. We leverage the capabilities of Numpy, Pandas, PyTorch, and Matplotlib to enhance our understanding of colorization processes and achieve remarkable outcomes.

## Key Technologies Used
### Numpy
Learned for efficient numerical operations and array manipulation crucial for preprocessing in the colorization project.

### Pandas
Adopted for streamlined data handling, offering a robust solution for loading, cleaning, and preparing datasets.

### PyTorch
Gained proficiency in PyTorch, a foundational tool for creating and training our colorization model.

### Matplotlib
Utilized for visualizing colorization outcomes, representing colorized images, and displaying performance metrics.

## Project Milestones
### Week 1: MNIST Dataset and Linear Model
Loaded, preprocessed, and augmented MNIST datasets using Numpy and PyTorch.
Trained a model with Linear layers achieving an accuracy of 89% in colorization.
### Week 2: CNN Implementation and Advanced Techniques
Implemented a CNN using PyTorch for improved feature extraction and model performance.
Explored custom loss functions, focusing on perceptual losses for colorization.
Introduced transfer learning for future model development.
### Week 3: Batch Normalization and Model Optimization
Implemented batch normalization techniques to stabilize training and address gradient-related issues.
Achieved an impressive accuracy of over 96% on the MNIST dataset using advanced techniques.
### Week 4: Research Paper Exploration and Model Iterations
Studied a Medium article by Emil Wallner on [Colorize B&W Photos with a 100-line Neural Network](https://emilwallner.medium.com/colorize-b-w-photos-with-a-100-line-neural-network-53d9b4449f8d).
Understood Convolutional Autoencoder architecture, a crucial concept for subsequent implementation phases.
Explored a [research paper](https://emilwallner.medium.com/colorize-b-w-photos-with-a-100-line-neural-network-53d9b4449f8d) on the colorization of black and white images for valuable insights.
## Model Iterations
### Alpha Model
Trained a proof-of-concept model on a single image using autoencoders, demonstrating significant success in image retrieval.
### Beta Model
Expanded the scope by training the model on multiple images and increasing the number of epochs.
Structured the use of encoder and decoder components, contributing to improved colorization outcomes.
### Final Model
Leveraged transfer learning by integrating the Inception ResNet v2, a powerful classifier trained on 1.2M images.
Transferred learning from the classifier to the coloring network, enhancing the model's understanding of object representations.
## Conclusion
The success of the alpha model, scalability in the beta model, and the integration of transfer learning in the final model collectively demonstrate a progressive and well-rounded approach to achieving the project objectives. This README serves as a guide to understanding the journey, techniques, and accomplishments of the Colorization Project. Feel free to explore the code and contribute to further advancements in colorization technology!
