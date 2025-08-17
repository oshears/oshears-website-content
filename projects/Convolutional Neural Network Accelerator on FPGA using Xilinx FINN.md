---
title: Convolutional Neural Network Accelerator on FPGA using Xilinx FINN
pubDate: 2023-03-15
description: FPGA-based CNN accelerator implementation using Xilinx FINN framework for high-performance neural network inference
heroImage: /isi.webp
badge: USC ISI
draft: false
tags:
---

In this project I used the [Xilinx FINN](https://github.com/Xilinx/finn) compiler to generate CNNs for evaluation in a heterogenous ASIC-FPGA-GPU object tracking system. The FPGA and ASIC implemented were designed to implement the ResNet-50 CNN, while the back-end GPU would perform object tracking using QDTrack or GTR. The target data set was BDD100K. The ASIC would be in charge of implementing the first layer of 

This PIXELS project (Processing In-Pixel-in-Memory for Efficient Low-energy Heterogeneous Systems) was funded by DARPA IP2. 


# Related Links
- [PIXELS: Processing In-Pixel-in-Memory for Efficient Low-energy Heterogeneous Systems - Reconfigurable Computing Group](https://www.isi.edu/research-groups-rcg/projects/current-projects/pixels/)
- [Advancing Computer Vision One Pixel at a Time - USC Viterbi | School of Engineering](https://viterbischool.usc.edu/news/2023/05/advancing-computer-vision-one-pixel-at-a-time/)
- [In-Pixel Intelligent Processing (IP2) - SAM.gov](https://sam.gov/opp/64ae26eed1f446588bf2bdc5e1e2c936/view)
- [DARPA releases IP2 AIE - Intelligence Community News](https://intelligencecommunitynews.com/darpa-releases-ip2-aie/)
- [In-Pixel Computing for the Extreme-Edge](https://eri-summit.darpa.mil/docs/ERISummit2023/Slides/Day2/Jacob_Ajey_USC%20ISI.pdf)
- [Xilinx/finn: Dataflow compiler for QNN inference on FPGAs](https://github.com/Xilinx/finn)
- [FINN | finn](https://xilinx.github.io/finn/)
- [BDD100K: A Large-scale Diverse Driving Video Database – The Berkeley Artificial Intelligence Research Blog](https://bair.berkeley.edu/blog/2018/05/30/bdd/)

<!-- - https://bdd-data.berkeley.edu/ --> 

<!--
This project focuses on implementing a high-performance Convolutional Neural Network (CNN) accelerator on FPGA using the Xilinx FINN framework. The work demonstrates how FPGAs can be leveraged to achieve efficient neural network inference for edge computing applications.

## Project Overview

The CNN accelerator utilizes the Xilinx FINN (Fast, Scalable Quantized Neural Network Inference) framework to deploy quantized neural networks on FPGA hardware. This approach enables:

- **High-Performance Inference**: Optimized CNN execution on FPGA fabric
- **Low-Power Operation**: Efficient power consumption for edge applications
- **Scalable Architecture**: Configurable design for different CNN models
- **Real-Time Processing**: Low-latency inference capabilities

## Technical Approach

### Xilinx FINN Framework

FINN provides:
- **Quantized Network Support**: Support for low-precision neural networks
- **Hardware Generation**: Automated FPGA implementation from neural network models
- **Optimization Tools**: Performance and resource optimization capabilities
- **Deployment Pipeline**: Complete flow from training to FPGA deployment

### FPGA Implementation

The accelerator design includes:
- **Dataflow Architecture**: Streaming-based processing for high throughput
- **Memory Optimization**: Efficient on-chip and off-chip memory utilization
- **Pipeline Optimization**: Multi-stage pipeline for concurrent processing
- **Resource Management**: Optimal use of FPGA resources (DSPs, BRAMs, LUTs)

## Applications

This CNN accelerator technology enables:

- **Computer Vision**: Real-time image classification and object detection
- **Edge AI**: On-device machine learning inference
- **Autonomous Systems**: Vision processing for robotics and automotive applications
- **IoT Devices**: Intelligent sensor processing with low power consumption

## Performance Benefits

The FPGA implementation provides:

- **Reduced Latency**: Hardware acceleration for faster inference
- **Energy Efficiency**: Lower power consumption compared to GPU implementations
- **Customization**: Tailored hardware for specific CNN architectures
- **Scalability**: Configurable design for different performance requirements

## Future Enhancements

Potential improvements include:
- Support for additional CNN architectures
- Integration with other Xilinx AI tools
- Extended precision support
- Multi-model concurrent execution

This project demonstrates the potential for FPGA-based neural network acceleration, providing a foundation for deploying sophisticated AI capabilities in resource-constrained environments.
-->