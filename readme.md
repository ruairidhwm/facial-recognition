# Facial Recognition

## Description

This is a really quick and dirty facial recognition script which compares people in the view of the webcam to faces it can check in its `people` folder. If someone in the `people` folder isn't present, and you are unknown, then the script will tell you to go away.

## Usage

Store a photo of your face in `people` with your name as the filename. Then on line 38 set `owner` to match your name.

Make sure that you install the following:

```bash
pip3 install cmake
pip3 install face_recognition
pip3 install numpy
pip3 install dlib
pip3 install opencv-python
```

Then run:

`python3 face-recogniser.py`

It will identify your face and label it appropriately. Anyone not contained in the `people` folder is unknown.

If you then have a friend / colleague walk up to your machine while you are away, they'll be told to go away!

## Other

This isn't for any real purpose, it's just a script to mess around with. Facial recognition and computer vision are becoming much more simple thanks to high level libraries such as [Face Recognition](https://github.com/ageitgey/face_recognition).

There are definitely things in the code which are a bit messy and this is not something that would ever be put in production...

## Acknowledgments

- [Face Recognition](https://github.com/ageitgey/face_recognition)
- [A Beginners guide to Building your own Face Recognition System to creep out your Friends](https://towardsdatascience.com/a-beginners-guide-to-building-your-own-face-recognition-system-to-creep-out-your-friends-df3f4c471d55)

## Preview

![](facial-recognition.gif)
