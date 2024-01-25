# captcha_recognition

This is an advanced Deep Neural Network (DNN) designed for solving captchas. Our training data originates from the widely recognized cifar-10 dataset, publicly accessible through the University of Toronto.

While contemporary captchas remain confidential for security reasons, we have devised a method to simulate our own versions, albeit with reduced security, utilizing the cifar-10 dataset.

We are also exploring the development of a model capable of solving text-based captchas.

Training files:

We use a ResNet50 for both the task of correctly identifying the solution to an image captcha and a text captcha. 

The training and results of the image task is found in image_training.ipynb. 

The training and results of the text task is found in text_training.ipynb.