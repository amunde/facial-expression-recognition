
# facial-expression-recognition
# Content: Convolutional Neural Network
## Project: Categorize face based on the emotion shown in the facial expression in to one of seven categories.
### Install

This project requires **Python 3.6** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Keras](https://keras.io/)
- [Tensorflow](https://www.tensorflow.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)


### Code

Template code is provided in the `Facial_expression_recognition.ipynb` notebook file.

### Run

Run the 'generate_records.py' script in the terminal to convert the downloaded csv dataset file 'fer2013.csv' into jpg images.

It creates the folders 'Training', 'PrivateTest' and 'PublicTest' out of which for simplicity we will use only the 'Training' folder.  

In a terminal or command window, navigate to the top-level project directory that contains this README and run the following commands:

```bash
jupyter notebook Facial_expression_recognition.ipynb 
```

This will open the Jupyter Notebook software and project file in your browser.

## Data

Facial Expression recognition challenge (https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/overview)

The data consists of 48x48 pixel grayscale images of faces. The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

