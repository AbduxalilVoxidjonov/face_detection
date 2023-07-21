# [YOLOv8](https://ultralytics.com/yolov8) Training and Deployment

![face detection](https://www.swiftlane.com/static/da27c6bbc87ffee7ad56f5d1d795ac79/a8acc/3.jpg)

## [Train](https://docs.ultralytics.com/modes/train/)
 - dataset: [wider face](https://www.kaggle.com/datasets/lylmsc/wider-face-for-yolo-training)
 - training file: [train.ipynb](train.ipynb)
 - model was trained using `YOLOv8l`, but `YOLOv8n` was used in the deploy part because the model was slow

## [Export](https://docs.ultralytics.com/modes/export/)

Export mode is used for exporting a YOLOv8 model to a format that can be used for deployment. In this mode, the model is converted to a format that can be used by other software applications or hardware devices. This mode is useful when deploying the model to production environments.

 - model has been exported to `onnx`, `engine`, `saved_model`, `tflite` formats

## Deployment

 - PyTorch       - [pytorch.ipynb](pytorch.ipynb)
 - ONNX          - [onnx.ipynb](onnx.ipynb)
 - TensorRT      - [tensorrt.ipynb](tensorrt.ipynb)
 - TF SavedModel - [tensorflow.ipynb](tensorflow.ipynb)
 - TF Lite       - [tflite.ipynb](tflite.ipynb)
