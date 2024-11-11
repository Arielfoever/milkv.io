---
sidebar_label: 'Introduction'
sidebar_position: 10
---

# Introduction

:::tip
This section is only used to perform some simple tests on TPU. For TPU-related development, it is recommended to use [TDL SDK](https://milkv.io/docs/duo/application-development/tdl-sdk/tdl-sdk-introduction), which integrates most of the functions of TPU and provides some interfaces.
:::

Duo’s CPU CV1800B integrates CVITEK TPU for intelligent detection.

TPU is an AI acceleration engine for deep learning neural networks, which can be used to accelerate image classification, object detection, face detection and recognition, segmentation, LSTM, and more. The main function of TPU is to offload CPU work and accelerate computer vision and voice-related operations.

CV1800B TPU supported models:

![duo](/docs/duo/tpu/duo-cv1800b-tpu-model_202307.png)

:::tip
The Duo development board is equipped with the CV1800B chip, which supports the **ONNX series** and **Caffe models**. Currently, it does not support TFLite models. In terms of quantized data types, it supports **quantization in BF16 format** and **asymmetric quantization in INT8 format**.
:::
