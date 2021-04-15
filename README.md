# ANPR_IndianPlates
Welcome! to the Automatic Number Plate Recognition Repository for Indian Number Plates. 
Here in this repository i have used a pre-trained model from https://github.com/tensorflow/models repository for training it on my dataset

The dataset i have used contins 669 images of car number plate. The annotations for the data set are in Pascal VOC fromat.

Coming to the model that i used for custom model detection is ssd_mobilenet_v1_coco model having 
speed as 30ms and mAP(COCO) as 21.

Prerequisite libraries for this custom model detection task are. -
1. Tensorflow version 1.15(best for this model).
2. lxml
3. pillow
4. matplotlib
5. jupyter
6. contextlib2
7. cython 
8. tf_slim
9. clone of the https://github.com/tensorflow/models repository.
10. protoc 3.4

Conclusion - mAP-64.9%
