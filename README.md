# CafeeToMLModelConverter

This Demo script convert the caffe model into .mlmodel compatible to use with ios devices.

Caffe model downloaded from  https://s3.amazonaws.com/jgoode/oxford102_VGG_S_iter_20000.caffemodel

Core Ml Tool Documentation https://apple.github.io/coremltools/generated/coremltools.converters.caffe.convert.html

image_input_names='data' in converter.py get it from 	deploy.prototxt file input: "data" parameter
