# Problem Statement
In this project, we will create a deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism on Flickr8K dataset. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library. 

 

This problem statement is an application of both deep learning and natural language processing. The features of an image will be extracted by a CNN-based encoder and this will be decoded by an RNN model.


The project is an extended application of Show, Attend and Tell: Neural Image Caption Generation with Visual Attention paper.
https://arxiv.org/abs/1502.03044
 

The dataset is taken from the Kaggle website and it consists of sentence-based image descriptions having a list of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events of the image.

 

### Project Pipeline
In the next video, let's observe what are the broader pipelines that you need to follow in order to fulfill your requirements for the capstone project.

The major steps that you have to perform can be briefly summarised in the following four steps:

- Data Understanding: Here, you need to load the data and understand the representation.
- Data Preprocessing: In this step, you will process both images and captions to the desired format.
- Train-Test Split: Combine both images and captions to create the train and test dataset.
- Model Building: This is the stage where you will create your image captioning model by building Encoder, Attention and Decoder model.
- Model Evaluation: Evaluate the models using greedy search and BLEU score.
