# Cheetah
**Cheetah** is an optimization zoo for vision transformer (ViT) that consists of all popular ViT optimization techniques (sparse, pruning and multi-exit). Prior to our implementation, I listed all influencing papers about ViT acceleration and develop them as optimization modules for any ViT models. Unlike [FasterTransformer](https://github.com/NVIDIA/FasterTransformer) and [DeepSpeed](https://github.com/microsoft/DeepSpeed), **Cheetah** paid more attention to **vision transformer** instead of **BERT**, and provided **more developer-friendly code through modular design** (users can use their favorite optimizations to accelerate ViT). In the end, I will introduce how to profile your new ViT models and deploy them to [NVIDIA Trition server](https://github.com/triton-inference-server) (including how to accelerate them with TensorRT).
- Cheetah
  - ViT Models (Pytorch)
  - Optimizations (Pytorch and CUDA)
  - Model Profiling (Pytorch, PyProf and nsight)
  - Model Development (ONNX, TensorRT and Triton)
  - End2end Profiling (Triton and DCGM)
  - Advanced Optimization (TVM)
  - Documentation (User Guide and Installation)
 
## ViT Models
<!-- In the end, we also provide codes for speeding up training and inference on Pytorch and GPU (CUDA). -->
<!-- ## Installation and Documentation (Finished) -->
<!-- ### Docker  -->
<!-- ### Triton Installation (Docker mode) -->
<!-- ### Kubernetes (for scalability) -->
<!-- ## Code (TBD) -->
<!-- ## Paper (In progress) -->
<!-- ### Image Classification -->
<!-- ### Object Detection (In progress) -->
<!-- 1. [YOLOv4: Optimal Speed and Accuracy of Object Detection. In arXiv'2020.](https://arxiv.org/abs/2004.10934) [Official Code by Darknet (C)](https://github.com/AlexeyAB/darknet#how-to-use-on-the-command-line)
2. [YOLOv3: An Incremental Improvement. In arXiv'2018.](https://arxiv.org/abs/1804.02767) [Official Code by Darknet (C)](https://github.com/AlexeyAB/darknet#how-to-use-on-the-command-line) / [Unofficial Code by Pytorch (Python)](https://github.com/ultralytics/yolov3) - the most popular model in real-time object detection.

### Segmentation
### Tracking
<!-- #### Fast training and inference -->
<!-- ##### CPU -->
<!-- ##### GPU -->
<!-- ### Useful Tricks -->
<!-- 1. [Computation Reallocation for Object Detection. In ICLR'20.](https://iclr.cc/virtual_2020/poster_SkxLFaNKwB.html) --> -->
## Contributors
* [Yan Lu](https://sites.google.com/view/yanluhome)
