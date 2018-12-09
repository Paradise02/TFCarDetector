COCO + Faster - RCNN + Pre-train Model

vs

COCO + Faster - RCNN + model from scratch

# Object Detection

## Steps to setup:

1. Installation from ReadMe

        $ pip install -r requirements.txt

    >Install protobuf based on your OS if pip fails for protobuf


2. Compile with protobuf

        $ protoc object_detection/protos/*.proto --python_out=.

3. setup the python path

        $ SLIM_PATH=/Users/nishant.gandhi/Project/models/research/slim
        $ RESEARCH_PATH=/Users/nishant.gandhi/Project/models/research
        $ OBJECT_DETECTION_PATH=/Users/nishant.gandhi/PycharmProjects/TFCarDetector/object_detection

        $ export PYTHONPATH=$PYTHONPATH:$SLIM_PATH:$RESEARCH_PATH:$OBJECT_DETECTION_PATH

4. Test installation

        $ python object_detection/builders/model_builder_test.py


## Run the example:

    $ /usr/local/bin/python2.7 /Users/nishant.gandhi/PycharmProjects/TFCarDetector/src/object_detection_demo.py

## Output:

The image with localization box are stored by index number.
check **src/<index>.png**