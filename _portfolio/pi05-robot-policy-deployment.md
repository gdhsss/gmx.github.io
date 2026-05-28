---
title: "PI0.5 Robot Policy Training and Real-Robot Deployment"
excerpt: "Full PI0.5/VLA pipeline from teleoperation data collection and LeRobot conversion to policy fine-tuning and Franka execution."
collection: portfolio
---

This project focuses on deploying PI0.5 on a 7-DoF Franka robot arm for real manipulation tasks.

Responsibilities and outcomes:

- Built MuJoCo and Franka teleoperation, data collection, and evaluation environments.
- Used 3D mouse / Fast-UMI to collect demonstrations and completed trajectory cleaning, state normalization, and data quality checks.
- Adapted the full VLA pipeline: LeRobot format conversion, Dataset/DataLoader, policy modules, training configuration, full fine-tuning, LoRA fine-tuning, and policy server / evaluation client inference.
- Improved PushT real-robot success rate from 50%+ to around 70%.
