# Draft Proposal for DATA 606:

_______________________________________________________________________________

#### Name: Vivek Pandey
#### Date: 09/11/2022

## Project Title - FACIAL EXPRESSION RECOGNITION

___________________________________________________________________________

## Overview

#### 1. What is your issue of interest (provide sufficient background information)?

These Human facial expressions convey a lot of information visually rather than
articulately. Facial expression recognition plays a crucial role in the area of
human-machine interaction. Automatic facial expression recognition system has
many applications including, but not limited to, human behavior understanding,
detection of mental disorders, and synthetic human expressions. Recognition of
facial expression by computer with high recognition rate is still a challenging task.
Two popular methods utilized mostly in the literature for the automatic FER
systems are based on geometry and appearance. Facial Expression Recognition
usually performed in four-stages consisting of pre-processing, face detection,
feature extraction, and expression classification.

#### 2. Why is this issue important to you and/or to others?

Human facial expressions can be easily classified into 7 basic emotions: happy,
sad, surprise, fear, anger, disgust, and neutral. Our facial emotions are expressed through activation of specific sets of facial muscles. These sometimes subtle, yet complex, signals in an expression often contain an abundant amount of information about our state of mind. Through facial emotion recognition, we will be able to measure the effects that content and services have on the audience/users through an easy and low-cost procedure. For example, retailers may use these metrics to evaluate customer interest. Healthcare providers can provide better service by using additional information about patients' emotional state during treatment.
Entertainment producers can monitor audience engagement in events to
consistently create desired content. Humans are well-trained in reading the emotions of others, in fact, at just 14 months old, babies can already tell the difference between happy and sad. But can computers do a better job than us in accessing emotional states? To answer the question, I will be using a deep learning neural network that gives machines the ability to make inferences about our emotional states. In other words, we give them eyes to see what we can see.

#### 3. Where do you get the data to analyze and help answer your questions (creditability of source, quality of data, size of data, attributes of data. etc.)?

Collection of a data set of images. (In this case I am using FER2013
database of 35887 pre-cropped, 48-by-48-pixel grayscale images of faces each
labeled with one of the 7 emotion classes: anger, disgust, fear, happiness, sadness, surprise, and neutral.

#### 4. What will be your unit of analysis (for example, patient, organization, or country)? Roughly how many units (observations) do you expect to analyze?

1. Locating faces in the scene (e.g., in an image; this step is also referred to as face
detection),
2. Extracting facial features from the detected face region (e.g., detecting the shape
of facial components or describing the texture of the skin in a facial area; this step
is referred to as facial feature extraction),
3. Analyzing the motion of facial features and/or the changes in the appearance of
facial features and classifying this information into some facial-expressioninterpretative categories such as facial muscle activations like smile or frown,
emotion (affect)categories like happiness or anger, attitude categories like
(dis)liking or ambivalence, etc.(this step is also referred to as facial expression
interpretation).

#### 5. What variables/measures do you plan to use in your analysis (variables should be tied to the questions in #3)?

No questions in the mind regarding the project but trying to get good accuracy and this can be done by training more dataset into the systems to make the model more and more accurate but again resources becomes a hindrance in the path.

#### 6. What kinds of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)?

A Convolutional Neural Network (ConvNet/CNN) is a deep learning algorithm that can take an input image, assign importance (learnable weight and bias) to different aspects/objects in the image and be able to distinguish one from the other. The preprocessing required in ConvNet is much lower compared to other classification algorithms. While in primitive methods the filters are created manually, with enough training ConvNets have the ability to learn these filters/characteristics.

The architecture of the ConvNet network is analogous to the connection architecture of neurons in the human brain and was inspired by the Visual Cortex organization. Individual neurons respond to stimuli only in a limited area of ​​the visual field known as the Receptive Field. A collection of such fields overlap to cover the entire visual area.

#### 7. How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?

During training, Neural network Forward propagation and Backward
propagation performed on the pixel values.The Softmax function presents itself as a probability for each emotion class. The model will be able to show the detail probability composition of the emotions on the face.

#### 8. What outcomes do you intend to achieve (better understanding of problems, tools to help solve problems, predictive analytics with practicle applications, etc)?

Above Project of Image recogonization using machine learning  has multiple benefits in real world .
Image  recogonizations is spoting and classifying Patterns,texture in data.
Image  recogonization applications can be found in multiple industries like healthcare,finance,E-commerce and many more.
some of the use cases are listed below.

1.)In Healthcare Industries today Image processing can play a vital role while 
 diagnosis  and detecting brain tumors,cancer and other diseases just by studying  the image.
This may contribute to save lives of people by giving proper medical treatments.

2.) As cyber-crime cases are increasing past decade ,Image recogonization can help to detect fake accounts just by analyzing the account history and this techniques can make you aware of those fraud accounts and digital scams.

3.) Government organizations are also being using Image recogonization technology to  pinpoint people in videos and images.

4.) In past few years visual search market has been drastically increasing in E-commerce industry.
Customers are more inclined to search products by product images.


```python

```
