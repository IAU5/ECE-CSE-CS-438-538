<p align="center">
  <img src="Digital System Banner.png" alt="Digital System Banner" width="100%">
</p>

##  ECE/CSE 438/538:  EdgeAI Hardware Systems

Welcome to **ECE/CSE 438/538:  EdgeAI Hardware Systems** Course. This 3-credit advanced-level course takes a hardware-centric view of AI/machine learning systems from constrained embedded devices to high-level distributed systems. It covers topics like ML design for low-power devices, optimization techniques for real-time processing, and deployment strategies for AI/ML models on embedded devices, bridging the gap between AI theory and practical hardware implementation.

For navigation, you can click the buttons below to access course materials:

<p align="center">
  <a href="./Module">
    <img src="module.png" alt="Module Button" width="200">
  </a>
  <br><br>
  <a href="./Assignment">
    <img src="assignment.png" alt="Assignment Button" width="200">
  </a>
  <br><br>
    <a href="./TinyML">
    <img src="tinyml.png" alt="Tinyml Button" width="200">
  </a>
</p>


---

##  Course Objectives
- Demonstrate understanding of how machine learning algorithms are implemented on different hardware systems.
- Apply key optimization techniques, including pruning, quantization, and binarization, to improve the efficiency of machine learning algorithms on various hardware platforms.
- Analyze and evaluate the performance and efficiency of hardware platforms with and without optimizations, understanding the trade-offs between efficiency and accuracy.
- Deploy and infer optimized AI/ML models on microcontrollers, specifically within the context of TinyML.
  
---

##  Evaluation System

| Component     | Weight (%) |
|---------------|------------|
| Modules       | 35%        |
| Assignments   | 20%        |
| Lab Report    | 15%        |
| Final Project | 30%        |

---

##  Grading Criteria

| Grade | Range   |
|-------|---------|
| A/A+  | 93-100% | 
| A-    | 90-92%  |
| B+    | 87-89%  |
| B     | 83-86%  |
| B-    | 80-82%  |
| C+    | 77-79%  |
| C     | 73-76%  | 
| C-    | 70-72%  |
| D+    | 67-69%  |
| D     | 63-66%  |
| D-    | 60-62%  |
| F     | 0-59%   |

---

##  Office Hours

| Name                    | Time                          | Room/Link                        |
|-------------------------|-------------------------------|----------------------------------|
| Omiya Hassan            | Wednesday: 3:30 PM - 4:30 PM **(Need Update)**  | MEC 202G                         |
| Ikteder Akhand Udoy     | Mon/Wed: 1:30 PM - 3:00 PM **(Need Update)**    | [Zoom link](https://boisestate.zoom.us/j/92926554873) & ID: 929 2655 4873 |

---

##  [Course Syllabus](syllabus.pdf) 

###  Course Schedule: ECE/CSE 438/538 - Edge AI Hardware Systems

| **Week** | **Topic**                                                                 | **Description**                                                                                                                                                                                                                                                                                                                                                                                                   | **Outcome**                                                                                                                                                      |
|----------|---------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **1–4**  | **Hardware-centric view of AI, Machine Learning (ML), and Deep Learning (DL) Models** | **Introduction to AI/ML/DL**: background, training vs inference, embedded vs cloud  <br> **ML/DL algorithm**  <br> **Structure of AI/ML/DL**: Attributes of connections within and between layers, types of DL modes.  <br> **Code Structure**: Coding basic ML and DL models, exploring popular benchmarked models used for computer vision and natural language processing. (All in Python/PyTorch) | Analysis (accuracy, latency, throughput, and memory utilization) of two computer vision tasks and comparable studies:<br>• VGG19<br>• MobileNetV2<br>• Any image dataset |
| **5–9**  | **Design of AI/ML/DL models for hardware and Systems**                   | **Model-level Optimizations**: Matrix decomposition, Quantization, Knowledge distillation, Hardware-aware AutoML and Pruning.                                                                                                                                                                                                                                                                                    | Analyze a single model of your choice with an image dataset of your choice:<br>• Pruning<br>• QAT<br>• Shifter-algo                                              |
| **10–14**| **Design of Hardware and Systems for Processing AI/ML/DL models**        | **ML Hardware**: Performance metrics, roofline analysis, Dataflow paradigms, and Hardware efficiency. <br><br> **Advanced/speculative hardware technologies** <br> **ML Compilers**: Mapping convolutions and matrix multiplications to hardware, Kernel transformations (e.g., Winograd, FFT-based computation), Domain-specific compilation (ML).                                                           | Roofline plot calculation of:<br>• VGG19<br>• MobileNetV2                                                                                                         |
| **15–16**| **TinyML Laboratory Session**                                            | **ML Systems**: Preprocessing and postprocessing in ML systems, Distributed training, Federated learning, Ethical, environmental, and societal concerns related to ML systems.                                                                                                                                                                                                                                   |                                                                                                                                                                  |
|          | **Final Project**                                                       | **Fundamentals of TinyML**: ML Paradigm, building blocks of DL, Building Computer Vision Models.                                                                                                                                                                                                                                                                                                                  | Inference your model on EdgeImpulse and use the TinyML microcontroller.                                                   |

##  Tiny ML
1. [Getting Started](./TinyML/tinyML_0_GettingStarted.pdf)
2. [Keyword Spotting](./TinyML/tinyML_1_KeywordSpotting.pdf)
3. [Gesture Detection](./TinyML/tinyML_2_GestureDetection.pdf)
4. [Object Detection](./TinyML/tinyML_3_Object_Detection.pdf)
