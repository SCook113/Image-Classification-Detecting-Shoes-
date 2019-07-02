## About this project

In this project I wanted to create an image classifier that can detect shoes on images from scratch.

I downloaded lots of pictures of shoes and photography not containing shoes from google images and other sources.
After that I trained a convolutional neural network using data augmentation.
I trained the network on 4927 pictures (with roughly half being pictures of shoes) and validated the model on about 540 pictures while training (also half-half).

The pictures are too big to push to github so I didn't.

### Files:

#### Make Predictions Model ... Notebook
You can test the models on your own pictures by placing them in the directory "data/test/shoe" (pictures containing shoes) and "data/test/no_shoe" and running one of the the "Make Predictions"-Notebooks.

#### Analyse Model Notebook
Shows architecture of a model.

#### Training Model ... Notebook
In these notebooks you can train a model.

#### Data Preprocessing Notebook
Contains a function that takes all pictures in a given directory and places them in a different directory with a given naming convention after rescaling them.

#### Make Predictions From URL Notebook Or File Path
In this notebook you can load a model and get the predictions on pictures from their URL or file path.

#### other files/
Here are some code snippets I found useful when collecting the training data and other stuff.