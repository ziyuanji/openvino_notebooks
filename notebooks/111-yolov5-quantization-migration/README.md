# Migrate quantization from POT API to NNCF API

![Ultralytics Yolov5 results](https://user-images.githubusercontent.com/44352144/177097174-cfe78939-e946-445e-9fce-d8897417ef8e.png)


This tutorial demonstrates how to migrate quantization pipeline written using the OpenVINO [Post-Training Optimization Tool (POT)](https://docs.openvino.ai/latest/pot_introduction.html) to [NNCF Post-Training Quantization API](https://docs.openvino.ai/latest/nncf_ptq_introduction.html). This tutorial is based on  [Ultralytics Yolov5](https://github.com/ultralytics/yolov5) model and additionally it compares model accuracy between the FP32 precision and quantized INT8 precision models and runs a demo of model inference based on sample code from [Ultralytics Yolov5](https://github.com/ultralytics/yolov5) with the OpenVINO backend.


## Notebook Contents

The tutorial consists from the following parts:

1. Convert YOLOv5 model to OpenVINO IR.
2. Prepare dataset for quantization.
3. Configure quantization pipeline.
4. Perform model optimization.
5. Compare accuracy FP32 and INT8 models
6. Run model inference demo
7. Compare performance FP32 and INt8 models

## Installation Instructions

If you have not installed all required dependencies, follow the [Installation Guide](../../README.md).