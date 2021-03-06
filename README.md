README
===========================
This repository contains docker image of ubuntu16.04+cuda9.0+cudnn7.0+tensorrt3.0

****
	
|Author|Alex Cheng|
|---|---
|E-mail|chybhao666@126.com

# About Docker Engine Utility for NVIDIA GPUs

[![GitHub license](https://img.shields.io/badge/license-New%20BSD-blue.svg?style=flat-square)](https://raw.githubusercontent.com/NVIDIA/nvidia-docker/master/LICENSE)
[![Documentation](https://img.shields.io/badge/documentation-wiki-blue.svg?style=flat-square)](https://github.com/NVIDIA/nvidia-docker/wiki)
[![Package repository](https://img.shields.io/badge/packages-repository-b956e8.svg?style=flat-square)](https://nvidia.github.io/nvidia-docker)

![nvidia-gpu-docker](https://cloud.githubusercontent.com/assets/3028125/12213714/5b208976-b632-11e5-8406-38d379ec46aa.png)

Please following the instructions in https://github.com/NVIDIA/nvidia-docker/blob/master/README.md to install nvidia-docker.

# About TensorRT

![TensorRT](https://devblogs.nvidia.com/parallelforall/wp-content/uploads/2017/12/pasted-image-0-12-e1512971301482.png)

The following sentences are quoted from https://devblogs.nvidia.com/parallelforall/int8-inference-autonomous-vehicles-tensorrt/, which is developed by Joohoon Lee.

TensorRT is a high-performance deep learning inference optimizer and runtime engine for production deployment of deep learning applications. Developers can optimize models trained in TensorFlow or Caffe to generate memory-efficient runtime engines that maximize inference throughput, making deep learning practical for latency-critical products and services like autonomous driving..

The latest TensorRT 3 release introduces a fully-featured Python API, which enables researchers and developers to optimize and serialize their DNN using familiar Python code. With TensorRT 3 you can deploy models either in Python, for cloud services, or in C++ for real-time applications such as autonomous driving software running on the NVIDIA DRIVE PX AI car computer.

# Pull CUDA-9.0 + CUDNN_7.0 + TensorRT-3.0 GA docker image

	docker pull chybhao666/cuda9_cudnn7_tensorrt3.0:latest

Play docker image:
	nvidia-docker run -it --net=host chybhao666/cuda9_cudnn7_tensorrt3.0:latest



