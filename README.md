
# NAME

tensorflow2tfjs  WIP

# SYNOPSYS

 * Train a computer vision model using transfer learning and Tensorflow python.
 * Convert that model from Tensorflow python Tensorflow javascript.
 * Use javascript model in a web page.

# DESCRIPTION

This is a tutorial on creating a computer vision model with Tensorflow Python and using it with Tensorflow Jaavascript.  In this example we will build a model that can classify images of dogs and cats.  We will start with a prebuilt model called mobilenet that has been trained on imagenet.  This will greatly reduce the time and data we need to train our model.

### Download image data.

We will use data from Kaggles Dogs vs. Cats dataset.

 * https://www.kaggle.com/c/dogs-vs-cats

You will need to log into Kaggle and download the dataset

### Prepare the data

mobilenet and many other prebuilt image classifiers out there ask that you break up your images into seperate directories.  One directory for each class.  In addition it's a good idea to break up your data into a training set and a testing set.

### Examine the build model script

We instantiate a mobilenet model using keras but we drop the final layer for our own 2 class layer.  This will take advantage of all the pre-training google did on this model whil all we have to do is train our own final layer.

we use mobilenet so the final model will be small enough to reasonabley import into tensorflow JS

### Train the model

run model script

### convert the model into tensorflow JS format

## move the files into www/ file

## fire up a tiny webserver and check out the html page

# AUTHOR

Dennis Watson
