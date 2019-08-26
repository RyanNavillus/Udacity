# Udacity
A collection of my Udacity Deep Learning Nanodegree Projects

The syllabus for the class is available [here](https://github.com/RyanNavillus/Udacity/blob/master/syllabus.pdf). 
My certificate of completion is available [here](https://confirm.udacity.com/FRADHULF).

# Course organization
The class is organized into a number of sections. Each section contains a number of mini-projects, which provided practical experience with the course material. Each section ended with a larger project which was evaluated by one of Udacity's instructors. Each project needed to meet specific criteria to be accepted.

# Projects
The 5 section projects are listed and described below. All projects used some combination of Keras, Numpy, Pandas, and Tensorflow.

### Predicting Bike Sharing Data
Predicting daily bike rental ridership.
* **Task**: Regression
* **Architecture**: Feed forward neural network
* **Results**: 0.169 validation loss (mean squared error)
* **Learned**: Regression on simple vector data.

### Dog Breed Classifier
Predicting dog breeds from images.

* **Task**: Classification
* **Architecture**: Convolutional neural network
* **Results**: 73% accuracy
* **Learned**: Classification on image data with CNNs, and transfer learning from popular CNN encoders (InceptionV3).

### Generate TV Scripts
Generating Simpsons TV scripts.

* **Task**: Regression / Text Generation
* **Architecture**: Recurrent neural network
* **Results**: 0.326 validation loss (sequence loss)
* **Learned**: Regression on text data with RNNs, training networks directly with Tensorflow, and word embeddings.

### Generate Faces
Generating celebrity face images.

* **Task**: Classification / Image Generation
* **Architecture**: Generative adversarial neural network
* **Results**: Visually correct face generation after multiple epochs. Reasonable results after 1 epoch (displayed in project notebook).
* **Learned**: Image generation on image data with GANs, and custom loss functions in tensorflow.

### Teach a Quadcopter How to Fly
Design an agent to fly a quadcopter, and then train it using reinforcement learning.

* **Task**: Agent Design / Reinforcement Learning
* **Architecture**: Feed forward Actor-Critic
* **Results**: The simulated quadcopter was able to take off and reach the target position of 10 meters directly upward in 2.6 seconds.
* **Learned**: Reinforcement learning, agent design, reward function design, experience replay.
