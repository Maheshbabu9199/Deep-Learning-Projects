# This is the documentation of scenario_05

The scenario is as following:
  A military organization wants to develop a machine learning model that can identify enemy
  vehicles in satellite imagery. The model will take as input a satellite image and output a list
  of bounding boxes that correspond to the location of enemy vehicles in the image. Develop
  a ML solution for the aforesaid scenario with an example Dataset.

# Taking the pre-trained models from the ultralytics
YOLO (You Only Look Once) is a popular set of object detection models used for real-time object detection and classification in computer vision.

The key feature of YOLO is its single-stage detection approach, which is designed to detect objects in real time and with high accuracy. Unlike two-stage detection models, such as R-CNN, that first propose regions of interest and then classify these regions, YOLO processes the entire image in a single pass, making it faster and more efficient.



## About the dataset
The COCO (Common Objects in Context) dataset is a large-scale object detection, segmentation, and captioning dataset.

Key Features
COCO contains 330K images, with 200K images having annotations for object detection, segmentation, and captioning tasks.
The dataset comprises 80 object categories, including common objects like cars, bicycles, and animals, as well as more specific categories such as umbrellas, handbags, and sports equipment.
Annotations include object bounding boxes, segmentation masks, and captions for each image.
COCO provides standardized evaluation metrics like mean Average Precision (mAP) for object detection, and mean Average Recall (mAR) for segmentation tasks, making it suitable for comparing model performance.

Dataset Structure
The COCO dataset is split into three subsets:

Train2017: This subset contains 118K images for training object detection, segmentation, and captioning models.
Val2017: This subset has 5K images used for validation purposes during model training.
Test2017: This subset consists of 20K images used for testing and benchmarking the trained models. Ground truth annotations for this subset are not publicly available, and the results are submitted to the COCO evaluation server for performance evaluation.


## Running the above program
To run the above code, execute the below commands,execute pip install -r requirements.txt and then run the code.

