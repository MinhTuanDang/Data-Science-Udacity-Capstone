# Data-Science-Udacity-Capstone
### Problem Overview
This project is part of the Data Science Nanodegree at Udacity. Convolutional Neural Networks (CNN) are used to classify dog breeds in this study. The algorithm will determine a dog's breed based on a photograph of the canine. If a human photograph is provided, the algorithm will identify the dog breed that most closely resembles it.
### Summary of the project:
To categorize dog breeds, we'll use a deep learning method called Convolution neural network. To recognize humans and dogs in the photos, we'll utilize open cv2. After that, we'll create our own CNN architecture. The precision of this CNN model is poor, hence the findings are unconvincing. As a result, we shall employ the notion of transfer learning. That is, we will employ a model that has already been trained. We will utilize the ResNet50 model in our scenario. The accuracy that we obtain here is roughly 80%. We will also utilize a sample of six photographs to test a real-world scenario in order to test our application.
### Interesting and difficult things in the project:
It was incredible to see how well the CNN algorithm worked in photographs. There are 133 different categories, and CNN excels in predicting them. The most challenging aspect is creating my own CNN algorithm. It's tough to adjust a neural network since there are so many parameters. But owing to udacity's example model, I was able to develop a model that was more than 1% accurate.
### Instructions:
- Clone the repository and navigate to the downloaded folder.
- Download the dog dataset. Unzip the folder and place it in the repo

- Download the human dataset. Unzip the folder and place it in the repo
- Donwload the VGG-16 bottleneck features for the dog dataset. Place it in the repo.
- Open the notebook
### Metrics
We will utilize accuracy to calculate the model's performance. The project's requirement is to enhance accuracy, and it also provides very clear information on how effectively we can categorize dog breeds. For example, if we are able to accurately categorize 60 out of 100 photos, then the accuracy is 60%.

The categorical crossentropy loss function is the loss function of a neural network. Softmax activation function is the most common loss function used in neural networks for multi-class classification. It is possible to differentiate the loss function.
Classification accuracy is the used metric for evaluating models. The reason for its wide use is because it is easy to calculate, easy to interpret, and is a single number to summarize the model's capability.
### Steps
Step 0: Import Datasets

Step 1: Detect Humans

Step 2: Detect Dogs

Step 3: Create a CNN to Classify Dog Breeds (from Scratch)

Step 4: Use a CNN to Classify Dog Breeds (using Transfer Learning)

Step 5: Create a CNN to Classify Dog Breeds (using Transfer Learning)

Step 6: Write your Algorithm

Step 7: Test Your Algorithm
### Blog Post
https://mikahdang.blogspot.com/2022/02/udacity-data-science-capstone-project.html
### Final Outcome
Used Xceptron model. The accuracy of test dataset is 85 percent, which beats the set benchmark at 60 percent
