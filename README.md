# Object-detection-with-MobileNet-and-SSD
Object detection with MobileNet and SSD is a process of detecting objects in real time using the MobileNet and SSD object detection models. MobileNet is a lightweight, fast, and accurate object detection model that can be used on mobile devices. SSD is a single-shot object detection model that can detect objects in real time.

To perform object detection with MobileNet and SSD, you will need the following:

1. A iamge or computer or mobile device with a webcam or video input
2. The MobileNet and SSD object detection models
3. An object detection library, such as OpenCV or TensorFlow

Once you have all of the required components, you can follow these steps to perform real-time object detection:

1. Install the object detection library on your computer or mobile device.
2. Load the MobileNet and SSD object detection models into the object detection library.
3. ADD photo or Start the webcam or video input.
4. Loop over the frames of the webcam or video input.
5. For each frame, detect objects using the MobileNet and SSD object detection models.
6. Draw the bounding boxes around the detected objects.
7. Display the frames with the detected objects.

# Requirements
Make sure you have the following files in the same directory as the Python script:

1. MobileNetSSD.txt (the Caffe model architecture file)
2. MobileNetSSD_deploy.caffemodel (the pre-trained model weights file)

The code takes image, performs object detection using the MobileNet SSD model, and displays the resulting frames with bounding boxes and class labels. Press 'q' to quit the application.
