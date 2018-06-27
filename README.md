# Visionome

Visionme is an intelligence agent involving four functional networks: stage 1 for screening abnormal people in populations, stage 2 for localizing anatomical parts and foci in images, stage 3 for determining the attributes of anatomical parts and foci.
Please feel free to contact us for any questions or comments: Erping Long, E-mail: liwangting@gzzoc.com.
All codes for deep-learning convolutional neural networks were executed in the Caffe (Convolutional Architecture for Fast Feature Embedding) framework with Ubuntu 16.04 64bit + CUDA (Compute Unified Device Architecture).
The script "create_imagenet.sh" is used to generate the dataset. The file "make_imagenet_mean.sh" is used to generate the mean file for dataset accordingly.
The file "train.sh" in /DL-Source code/myself is used for network training.
The "yunxing_cnn.py" in /DL-Source code/python_script could be used to test and have the evaluation indices.
The codes for Faster-RCNN were executed in the Caffe (Convolutional Architecture for Fast Feature Embedding) framework with Ubuntu 16.04 64bit + CUDA (Compute Unified Device Architecture). Please refer to https://github.com/rbgirshick/py-faster-rcnn to obtain Faster-RCNN and the specification of it.
