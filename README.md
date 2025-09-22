# Deep Learning Homework 5 - Sharif University of Technology
### Instructor: Dr. Mahdieh Soleymani

This repository contains my solutions and code for the fifth and final homework assignment of the Deep Learning course. This assignment delves into advanced topics in modern deep learning, focusing on generative models, self-supervised learning, and their applications in computer vision.

---

### **Theoretical Section**

The theoretical portion of this homework covers cutting-edge research in deep learning. My solutions are submitted in a single PDF file as required by the course. The topics covered are:

* **DetailCLIP Architecture**: An in-depth analysis of a novel model for fine-grained image segmentation. I explain how it uses a teacher-student framework with three key techniques:
    1. **Patch-Level Self-Distillation**: A hierarchical approach where a student model learns from the details of a teacher model to preserve fine-grained information.
    2. **Attention-Based Token Removal**: A filtering technique that prioritizes important image regions, which improves both processing speed and accuracy by eliminating noise.
    3. **Pixel-Level Reconstruction**: A method to enhance the sharpness and clarity of low-resolution inputs, which is crucial for precise segmentation of complex objects like animal fur or foliage.
* **Self-Supervised Learning**: An exploration of why some self-supervised methods like SimCLR require negative samples, while others like BYOL (Bootstrap Your Own Latent) do not. I also analyze how BYOL demonstrates greater robustness to hyperparameter choices and data transformations, and explain the rationale behind using global and local crops in modern self-supervised strategies.
* **CLIP-Based Image Generation**: A theoretical overview of how discriminative models like CLIP, which learn aligned representations for text and images, can be leveraged for image generation.

---

### **Practical Section**

The practical part of this homework involves hands-on experience with state-of-the-art models for generative AI and computer vision. The code is structured into separate notebooks.

* **DINO**: This notebook introduces the **DINO** (Self-distillation with no labels) model, a self-supervised learning approach for generating representations. I will also work with **Grounded DINO**, an object detector built on the DINO framework.
* **Stable Diffusion**: This exercise provides a step-by-step walkthrough of **text-to-image generation** using the Stable Diffusion model. It covers the process of generating images from an initial image prompt and addresses common issues like "object missing."
* **Image Generation with CLIP**: This notebook demonstrates how to leverage the learned representations of discriminative models like **CLIP** to perform image generation. The goal is to use the model's ability to align image and text embeddings for creative image synthesis.
