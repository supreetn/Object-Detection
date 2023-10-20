# Object-Detection using Tensorflow and PyTorch
Object Detection using Tensorflow and PyTorch with bounding boxes and masking. This computer vision project is widely used in autonomous driving. Here, Object detection task is performed using a pre-trained Mask R-CNN model on multiple images and videos. It showcases the power of this deep learning model for detecting and annotating objects within an image.
# Why MASK R-CNN??
Mask R-CNN is a popular and powerful model for object detection and segmentation tasks. It's chosen for this task because it provides both bounding box coordinates and pixel-level masks for detected objects, which is valuable for understanding and segmenting objects in an image.
- The code begins by loading a pre-trained Mask R-CNN model that has been trained on a large dataset (COCO dataset), making it capable of detecting a wide range of objects.
- The image is preprocessed to match the model's input requirements, and the perform_object_detection function is used to make predictions. Objects are detected with a specified confidence threshold, and their labels and bounding box coordinates are extracted.
- This methodology is effective for performing object detection, which has various applications, including image understanding, surveillance, and robotics.

![outputnew](https://github.com/supreetn/Object-Detection/assets/84839204/08056b1e-a652-4433-a331-8449f259108a)

![outputnew1](https://github.com/supreetn/Object-Detection/assets/84839204/17efb2d1-9121-4727-b7fe-59e7a0a1fdfa)

https://github.com/supreetn/Object-Detection/assets/84839204/904f319c-e7d3-47ad-8a02-1e459e8369e5

# Methodology

- Initialization and Importing Libraries:

The code starts by importing necessary libraries, including TensorFlow, OpenCV (cv2), and other utility libraries for visualization and processing.
- Model Selection:
 In this case, the "Mask R-CNN Inception ResNet V2 1024x1024" model is chosen gor both Pytorch and Tensorflow model
- Model Loading:

The selected model is loaded using TensorFlow Hub, making it available for object detection tasks.
- Video Processing:

The code processes a video by capturing each frame one at a time.
The frames are resized to a uniform size of 300x300 pixels for consistency.
The processed frames are passed through the loaded model for object detection.
- Object Detection:

The model processes each frame and returns detection results, including bounding boxes, class labels, and confidence scores.
The code uses the visualizing_the_results function to overlay bounding boxes and labels on the processed frame.
The code displays the processed frame with bounding boxes using OpenCV's cv2_imshow.
The frame count and status are printed to track progress.
The video processing continues until the user presses 'q' or until all frames are processed.

The "Mask R-CNN Inception ResNet V2" model is a powerful choice for such tasks, as it can detect and segment objects in images and videos. The code demonstrates the usage of a pre-trained model and showcases how to process and visualize the results in video frames.






