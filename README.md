# Object-Detection using Tensorflow and PyTorch
Object Detection using Tensorflow and PyTorch with bounding boxes and masking. This computer vision project is widely used in autonomous driving. Here, Object detection task is performed using a pre-trained Mask R-CNN model on multiple images and videos. It showcases the power of this deep learning model for detecting and annotating objects within an image.
#Why MASK R-CNN??
Mask R-CNN is a popular and powerful model for object detection and segmentation tasks. It's chosen for this task because it provides both bounding box coordinates and pixel-level masks for detected objects, which is valuable for understanding and segmenting objects in an image.
- The code begins by loading a pre-trained Mask R-CNN model that has been trained on a large dataset (COCO dataset), making it capable of detecting a wide range of objects.
- The image is preprocessed to match the model's input requirements, and the perform_object_detection function is used to make predictions. Objects are detected with a specified confidence threshold, and their labels and bounding box coordinates are extracted.
- This methodology is effective for performing object detection, which has various applications, including image understanding, surveillance, and robotics.
- 
