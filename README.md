# Image-Processing-using-YOLO-by-darknet

YOLO (You Only Look Once) is a method / way to do object detection. It is the algorithm /strategy behind how the code is going to detect objects in the image.

The official implementation of this idea is available through DarkNet (neural net implementation from the ground up in 'C' from the author). It is available on github for people to use.

Earlier detection frameworks, looked at different parts of the image multiple times at different scales and repurposed image classification technique to detect objects. This approach is slow and inefficient.

YOLO takes entirely different approach. It looks at the entire image only once and goes through the network once and detects objects. Hence the name. It is very fast. That’s the reason it has got so popular. 

OPENCV DNN MODULE

DNN (Deep Neural Network) module was initially part of opencv_contrib repo. It has been moved to the master branch of opencv repo last year, giving users the ability to run inference on pre-trained deep learning models within OpenCV itself.

(One thing to note here is, dnn module is not meant be used for training. It’s just for running inference on images/videos.)

Initially only Caffe and Torch models were supported. Over the period support for different frameworks/libraries like TensorFlow is being added.

Support for YOLO/DarkNet has been added recently. We are going to use the OpenCV dnn module with a pre-trained YOLO model for detecting common objects.
