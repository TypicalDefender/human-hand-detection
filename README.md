# handy
An easy to use wrapper for hand recognition, made using OpenCV.

![Alt Text](sample.gif)

```sh


## Get started
Clone or download the repo, and then,
```sh
$ cd handy-master
$ pip install -r requirements.txt
$ python test.py
```

## Documentation
I didn't want to make a full, proper documentation. 😅
However, `test.py` contains all the functions and their usage.

## Purpose
The purpose of this project was to detect hands in images/videos without using Machine/Deep Learning. So, this has been done using only Image Processing, and it is much faster than ML/DL solutions on a normal system. However, it is not as as accurate.
Also note that, this isn't really a "Hand detector". It is just an Object Detector, using color. You can play around and modify the code to detect other objects as well, pretty easily.
