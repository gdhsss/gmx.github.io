---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **M.S. in Applied Mathematics and Data Science**, Macau University of Science and Technology, Macau, 2023.09 - 2025.06
  * GPA: 3.67/4.0
  * Coursework: Time Series Analysis, Applied Statistical Analysis, Numerical Linear Algebra, Convex Optimization, Inverse Problems, Machine Learning
* **B.S. in Science**, Macau University of Science and Technology, Macau, 2019.09 - 2023.08
  * Outstanding Graduate
  * Coursework: Computer Networks, Data Structures, Object-Oriented Programming, Software Engineering, Calculus, Probability and Statistics

Work experience
======
* **Algorithm Engineer**, Around Technology, Shenzhen, 2025.07 - Present
  * Core work: desktop companion robot development.
  * Researched multimodal emotion computing with CNN + LSTM temporal-spatial feature fusion on DEAP and WESAD.
  * Introduced data augmentation and mixup for domain generalization; evaluated using Leave-One-Subject-Out cross validation.
  * Designed emotion-triggering experiments and collected 500+ samples from 26 subjects.
  * Integrated embedded Linux system trimming, GPIO pin mapping, driver installation, Docker deployment, and RKNN inference on RK3568.

* **Research Intern**, Guangdong Institute of Intelligence Science and Technology, Zhuhai, 2024.07 - 2025.06
  * Reproduced and deployed Diffusion Policy and PI0.5 models in simulation and real-robot scenarios.
  * Researched SNN for embodied intelligence to improve Diffusion Policy inference speed.
  * Teleoperated Franka robot arms for data collection, data cleaning, and dataset preparation for real-world deployment.

Projects
======
* **Brain-inspired computing for embodied intelligence**
  * Applied SNN to Diffusion Policy with U-Net and Transformer denoising networks.
  * Proposed a learnable channel-wise membrane threshold design for spiking diffusion policy.
  * Validated on PushT, Lift, Can, Square and other tasks in Pygame and MuJoCo.
  * Reduced estimated dynamic energy consumption by 80.36% on 45nm hardware while maintaining comparable success rates.
  * Completed Franka Sim-to-Real deployment: 96% success rate on Lift and over 50% on PushT.
  * Responsible for core code implementation, simulation/real-robot experiments, and paper writing.

* **PI0.5-based 7-DoF robot teleoperation, training, deployment, and real-robot validation**
  * Built teleoperation, data collection, and evaluation environments based on MuJoCo and Franka.
  * Used 3D mouse / Fast-UMI for demonstrations, trajectory cleaning, state normalization, and data quality control.
  * Developed the full VLA training and inference pipeline, including LeRobot conversion, Dataset/DataLoader adaptation, policy module development, training configuration, inference interface wrapping, and real-robot deployment.
  * Completed full fine-tuning and LoRA fine-tuning; connected natural-language instruction, visual observation, robot state, and action output through policy server and evaluation client.
  * Improved PushT real-robot success rate from 50%+ to around 70%.
  
Skills
======
* Robotics learning: Diffusion Policy, PI0.5/VLA, LeRobot, MuJoCo, LIBERO, Sim-to-Real, Franka deployment.
* Model development: PyTorch, CNN + LSTM, SNN, Transformer, LoRA fine-tuning, policy inference interface design.
* Edge deployment: RKNN quantization, RK3568 inference, Linux system trimming, GPIO/driver integration, Docker deployment.
* Data pipeline: 3D mouse teleoperation, trajectory cleaning, state normalization, data quality control, LOSO validation.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Email: maogao623@gmail.com
* GitHub: https://github.com/gdhsss
* Phone / WeChat: 15562327103
