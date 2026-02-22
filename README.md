Object Detection with DETR (Detection Transformer)

This project implements end-to-end object detection using DETR (DEtection TRansformer) via the Hugging Face Transformers library.

The model detects objects in images and predicts:

Object class labels

Bounding box coordinates

Confidence scores

The project also includes optional visualization and a simple Gradio web interface for interactive inference.

 Model Used

facebook/detr-resnet-50

DETR combines:

A ResNet-50 CNN backbone for feature extraction

A Transformer encoder-decoder architecture for object reasoning

Unlike traditional object detectors (e.g., Faster R-CNN or YOLO), DETR:

Removes anchor boxes

Eliminates Non-Maximum Suppression (NMS)

Predicts objects directly in an end-to-end manner
