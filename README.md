# Cheetah
**Cheetah** is an end-to-end deep learning prediction serving sevice that speeds up deployment of image classification, object detection, segmentation and tracking techniques. It is based on NVIDIA Trition server and docker. To adapt on any backbends, we provide three implementations (TensorFlow, ONNX and TensorRT) for each model. <br>
Prior to our implementation, I listed all influencing papers in real-time image recognition and summarized their common efficient components. Based on these modules, we built **Cheetah**, an API for real-time object detection. Unlike [mmdetection](https://github.com/open-mmlab/mmdetection), [deep-person-reid](https://github.com/KaiyangZhou/deep-person-reid) and [pysot](https://github.com/STVIR/pysot), **Cheetah** paid more attention to **real-time features** and provided **more developer-friendly code through modular design** (the minimal unit is the common component like feature pyramid module and isn't the whole model like YOLOv3). 
<!-- In the end, we also provide codes for speeding up training and inference on CPU and GPU (CUDA). -->
## Installation and Documentation (Finished)
### Docker 
### Triton Installation (Docker mode)
### Kubernetes (for scalability)
## Code (TBD)
## Paper (In progress)
### Image Classification
### Object Detection (In progress)
1. [YOLOv4: Optimal Speed and Accuracy of Object Detection. In arXiv'2020.](https://arxiv.org/abs/2004.10934) [Official Code by Darknet (C)](https://github.com/AlexeyAB/darknet#how-to-use-on-the-command-line)
2. [YOLOv3: An Incremental Improvement. In arXiv'2018.](https://arxiv.org/abs/1804.02767) [Official Code by Darknet (C)](https://github.com/AlexeyAB/darknet#how-to-use-on-the-command-line) / [Unofficial Code by Pytorch (Python)](https://github.com/ultralytics/yolov3) - the most popular model in real-time object detection.

### Segmentation
### Tracking
<!-- #### Fast training and inference -->
<!-- ##### CPU -->
<!-- ##### GPU -->
### Useful Tricks
1. [Computation Reallocation for Object Detection. In ICLR'20.](https://iclr.cc/virtual_2020/poster_SkxLFaNKwB.html)
## Contributors
* [Yan Lu](https://sites.google.com/view/yanluhome)
