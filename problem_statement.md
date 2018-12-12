# Final Project for ADS Fall 2018

## Problem Statement:

The final assignment is on object detection (specifically, cars) in images via deep learning. I have deliberately avoided a detail guidance so you can research as a group to gain experience. But here are the overall steps:

1) Read a couple of academic papers on the R-CNN based techniques.

2) Make use of the Python-based TensorFlow object detection API from Google.

3) Train a model (e.g. Resnet 101 with Faster R-CNN) on your dataset (COCO or KITI).

4) Check the performance with or without the use of a pretrained model.

5) Prepare the presentation.

Your group must meet often to discuss the approaches to modeling and data preparation. In the presentation, you should be able to show your demo on one or two selected images. If you have any question, reach out to me or one of the TAs.

#### Notes:
+ You can use MS COCO and KITI datasets as I mentioned in the project description. 
+ You can use a pretrained model based on one dataset and then use the other one for object detection and fine tuning your model. 
+ Please note that a labeled image dataset for object detection requires the positional information of each of the boxes in an image and the type of the object it encloses.

### Notes 2:
+ Just try to run any pretrained model and evaluate some sample images.
+ Try running tensorboard and display the output.
+ The project is all about exploring, so no worry if you couldn't retrain.
+ Come and present what you have learnt from the academic papers and by running the package.

#### References:
+ [Tensor Flow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection)
+ [Fast R-CNN Paper](https://arxiv.org/pdf/1504.08083.pdf)
+ [Faster R-CNN Paper](https://arxiv.org/pdf/1506.01497.pdf)
+ [Facebook Detectron](https://github.com/facebookresearch/Detectron)
