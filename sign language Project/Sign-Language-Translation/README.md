# TensorFlow Lite Object Detection Android Demo

### Overview

This is a camera app that continuously detects the objects (bounding boxes and
classes) in the frames seen by your device's back camera, using a quantized
[MobileNet SSD](https://github.com/tensorflow/models/tree/master/research/object_detection)
model trained on the downloaded data and tested with manufactured data. 

The model files are downloaded via Gradle scripts when you build and run. You
don't need to do any steps to download TFLite models into the project
explicitly.

Application can run either on device or emulator.

<!-- TODO(b/124116863): Add app screenshot. -->

## Build the demo using Android Studio

### screenshots from testing

![2](https://user-images.githubusercontent.com/109518544/186063342-0bf5bd85-402d-4bfc-a5fc-7d4bbc9127e1.jpeg)
![1](https://user-images.githubusercontent.com/109518544/186063345-b6601f7b-d036-49e2-b296-aeb232690604.jpeg)







