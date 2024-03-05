# Creating anime characters using DCGANs and Keras

### Author :  
- [Joseph Santarcangelo](https://www.linkedin.com/in/joseph-s-50398b136/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkML0101ENSkillsNetwork20718538-2021-01-01)
- [Roxanne Li ](https://www.linkedin.com/in/roxanne-li/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkGuidedProjectsIBMGPXX0XCEEN72-2022-01-01)
- [Junxing(J.C.) Chen ](https://www.linkedin.com/in/junxing-chen-3591a4162/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkGuidedProjectsIBMGPXX0XCEEN72-2022-01-01)

Mentee Assignment from IBM Advance AI @ Infinite Learning Course completion of Creating anime characters using DCGANs and Keras from CognitiveClass.Ai

### Mentee Info
- Name    : Iffo Elsande Pratama Putra
- Program : IBM Academy Advance AI

## Overview
GANs could generate new data following the statistic features of the data in the training set. GANs is widely used to generate new and realistic photograph that is authentic to human observers.

Convolutional networks (CNNs) has seen huge adoption in computer vision applications. Applying the CNNs to GANs models could help us in building a photo generating model. The combined method is called Deep Convolutional Generative Adversarial Networks (DCGANs).

In this lab, we will first focus on simulated data to better understand GANs. Further, we will use the case of massive anime avatar production to introduce how to use DCGANs.

### Table of Contents
1. Objectives
2. Setup
  - Installing Required Libraries
  - Importing Required Libraries
  - Defining Helper Functions
3. Basic: Generative Adversarial Networks (GANs)
  - Introduction
  - Toy Data
  - The Generator
  - The Loss Function GANs (Optional)
  - Training GANs
4. Deep Convolutional Generative Adversarial Networks (DCGANs)
  - Case background
  - Loading the Dataset
  - Creating Data Generator
  - Generator and Discriminator (for DCGANs)
  - Defining Loss Functions
  - Defining Optimizers
  - Create Train Step Function
  - Training DCGANs
5. Explore Latent Variables
  - Exercise 1
  - Exercise 2
  - Exercise 3

### Objectives
After completing this lab, you will be able to:
- Understand the original formulation of GANs, and their two separately trained networks: Generator and Discriminator
- Implement GANs on simulated and real datasets
- Apply DCGANs to a dataset
- Understand how to train DCGANs
- Generate an image using a DCGAN
- Understand how changing the input of the latent space of DCGANs changes the generated image

### Setup
For this lab, we will be using the following libraries:
- pandas for managing the data.
- numpy for mathematical operations.
- sklearn for machine learning and machine-learning-pipeline related functions.
- seaborn for visualizing the data.
- matplotlib for additional plotting tools.
- keras for loading datasets.
- tensorflow for machine learning and neural network related functions.

