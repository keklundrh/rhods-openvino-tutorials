
# Red Hat OpenShift Data Science - Intel OpenVINO Tutorials

## Introduction 

Welcome! 

In this collection of tutorials, you will learn about:

![openvino-icon](assets/img/openvino-logo.png)

<!-- write this up in paragraph form with icons and other images
1. Intel OpenVINO Overview (including benefits)
2. getting started with Intel OpenVINO
3. optimizing your model
4. performance boosts to model inference
5. and see it in action with a few examples. 
-->


## Intel OpenVINO Overview 

Jump to [installation](01_install.md) or [tutorials](02_examples.md) instead.

### Introduction 

Intel OpenVINO optimizes our models to get the most performance possible without significant accuracy sacrifices. In other words, it optimizes your model's predictions for the *intended Intel inference device*. It eliminates the discrepancy between high-end hardware used in training and low-end, constrained deployment devices. Instead of making large accuracy sacrifices for adequate performance, OpnVINO *optimizes performance* by reducing precision with *minimal changes to accuracy*, a process called *quantization*. 

For example, a double precision representation of pi is *3.141592653589793* while single precision is *3.14159265*, 16 digits vs 8. Why calculate a precise representation if you don’t have to?

Additionally, Red Hat OpenShift Data Science runs on Intel hardware. Consider using OpenVINO as your default serving engine.

### How it works 


### Optimization details 


### Benefits 


### References 

* [OpenVINO Docs](https://docs.openvino.ai/latest/index.html)

## Navigation 

* [Welcome - Intel OpenVINO Tutorials Red Hat OpenShift Data Science](00_index.md)
* [Install OpenVINO to Red Hat OpenShift Data Science](01_install.md)
* [OpenVINO Examples](02_examples.md)
