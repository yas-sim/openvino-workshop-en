# openvino-workshop-en

## Overview
Hands-on workshop contents to learn Intel distribution of OpenVINO toolkit - a deep learning inferencing library.
The workshop contents are tested on Ubuntu and Windows 10 systems.

## Description
[Intel distribution of OpenVINO toolkit](https://software.intel.com/en-us/openvino-toolkit) is a library suite for computer vision applications. OpenVINO consists of following libraries and tools.  
- Inference Engine - Efficient, high-performance and flexible deep learning inference run-time engine library
- Model Optimizer - Convert generic deep-learning models into OpenVINO IR format
- Model Downloader - Download OMZ (Open Model Zoo, Intel) models and popular deep learning models
- Deep Learning Workbench - Post training model re-quantization, benchmarking, accuracy checking
- OpenCV - High performance and feature-rich image processing library

OpenVINO provides great scalability. It supports wide variety of deep learning processors and accelerators. You can use almost the same code on different hardware easily.
- CPU - Atom to Xeon, OpenVINO supports the latest DL boot instructions
- Integrated GPU - OpenVINO can leverage the performance of integrated GPU and off load the task from CPU
- VPU - Vision Processing Unit (Myriad). A low power yet powerful deep-learning accelerator from Intel
- FPGA - OpenVINO compatible FPGA acclerator cards are available
- HDDL - High Density Deep Learning accelerator. Single or multiple Myriad devices are on a board   

Also, OpenVINO supports various operating systems.
- Windows 10, Ubuntu, CentOS, MacOS

You will learn the basics of OpenVINO through this workshop.
1.  Learning basic of OpenVINO API through a simple image classification program - [classification.ipynb](./classification.ipynb)
2.  Basic of object detection program using OpenVINO - [object-detection-ssd.ipynb](./object-detection-ssd.ipynb)
3.  Basic of asynchronous inferencing - [classification-async-single.ipynb](./classification-async-single.ipynb)
4.  Technique for high performance inference program - asynchronous and simultaneous inferencing - [classification-async-multi.ipynb](./classification-async-multi.ipynb)
4. < Appendix > Automate evaluation work on DevCloud - [automated-testing.ipynb](./automated-testing.ipynb)

## How to use
1. Go to Intel distribution of OpenVINO toolkit [web page](https://software.intel.com/en-us/openvino-toolkit) and download an OpenVINO package suitable for your operating system
2. Install OpenVINO and setup support tools and accelerators by following the instruction in ['Get Started'](https://software.intel.com/en-us/openvino-toolkit/documentation/get-started) page
3. Clone repository to your system
~~~shell
$ git clone https://github.com/yas-sim/openvino-workshop-en
~~~
4. Open a command terminal
5. Set up environment variables for OpenVINO
~~~
Linux $ source /opt/intel/openvino/bin/setupvars.sh  
~~~
~~~
Windows > call "Program Files (x86)\IntelSWTools\OpenVINO\bin\setupvars.bat"
~~~

6. Start Jupyter notebook
7. Open `openvino-workshop-en/START-HERE.ipynb` from Jupyter to start the workshop

## Requirement
This workshop requires [Intel distribution of OpenVINO toolkit](https://software.intel.com/en-us/openvino-toolkit
).

## Contribution

## Licence

[Apache2](http://www.apache.org/licenses/LICENSE-2.0.txt)

## Author

[Yasunori Shimura](https://github.com/yassim-intel)
