# Smile-on-Face-detector
A small .py script that detects faces and smiles in realtime

## Pre requisite
You need to have Python and OpenCV set up on your Environment.

## All you need to know
Machines can learn to recognize happiness and I’m going to show you how to set up a [smile recognition model](https://towardsdatascience.com/facial-recognition-happiness-bbb3c4293d1d) that can do so.

This method uses haar-like features to detect facial properties. The cascade is a series of filters that will apply one after the other to detect a face through its features.
These filters are stored in their own XML files in the [Haar Cascade GitHub Repository](https://github.com/opencv/opencv/tree/master/data/haarcascades)
To build our happiness detector, we need these 3 XML Files: 
- haarcascade_smile.xml
- haarcascade_frontalface_default.xml

These are the cascades for the face and smiles. We must have each one of these features if our image is of a happy face. You can download these filed from my Repository or Directly from the [Haar Cascade GitHub Repository](https://github.com/opencv/opencv/tree/master/data/haarcascades). Put all three XML files into the same folder where you will run it from.

### After Above

***Simply run the script from your Terminal or any IDE and see the results for yourself!***

