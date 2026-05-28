---
permalink: /
title: "高茂煦个人主页"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Robotics AI Engineer

我是高茂煦，机器人算法工程师，目前在阿圆科技参与桌面陪伴机器人研发。我的工作聚焦于把具身智能算法从论文和仿真推进到真机系统：Diffusion Policy、PI0.5/VLA、SNN、Franka 机械臂部署、RKNN 端侧推理、多模态情感计算，以及 Docker/Linux 嵌入式工程化。

### Research & Engineering Focus

- **Embodied intelligence**: Diffusion Policy、PI0.5、LeRobot、MuJoCo、LIBERO、Franka 真机部署。
- **Efficient policy learning**: 将脉冲神经网络引入 Diffusion Policy，降低推理能耗并提升部署效率。
- **Robot data loop**: 3D mouse / Fast-UMI 遥操作采集、轨迹清洗、状态归一化、数据质检与策略训练。
- **Edge AI deployment**: Torch 到 RKNN 的模型转换、RK3568 部署推理、Linux 裁剪、GPIO 与驱动集成、Docker 环境迁移。

### Highlights

- PRCV 2025: *SDP: Spiking Diffusion Policy for Robotic Manipulation with Learnable Channel-Wise Membrane Thresholds*。
- ICTA 2025: *An Accuracy-Improved Low-Computational-Cost Spiking Transformer Network for Robotic Arm Manipulation*。
- 在 Franka 真机上完成 Lift / PushT 等任务验证；Lift 任务成功率达到 **96%**。
- 在 45nm 硬件动态能耗预估中，脉冲扩散策略降低约 **80.36%**。
- 面向桌面陪伴机器人，完成多模态情感计算模型研发与 26 名被试、500+ 条实验数据采集。

### Selected Work

#### Spiking Diffusion Policy for Robotic Manipulation

针对 Diffusion Policy 推理速度慢的问题，我将 SNN 应用于 U-Net 和 Transformer 去噪网络，提出基于可学习通道膜电荷阈值的脉冲扩散策略。项目覆盖 Pygame、MuJoCo 仿真和 Franka 真机部署，在保持任务成功率的同时显著降低硬件动态能耗。

#### PI0.5 / VLA Robot Policy Deployment

负责 PI0.5 从数据采集、LeRobot 数据格式转换、Dataset/DataLoader 适配、policy 模块二次开发、训练配置修改、全量与 LoRA 微调，到 policy server / evaluation client 闭环推理和 Franka 真机执行的完整链路。

#### Multimodal Emotion Computing for Desktop Companion Robot

面向圆点产品研发，基于 DEAP、WESAD 等数据集设计 CNN + LSTM 时空特征融合模型，引入数据增强与 mixup 提升跨主体泛化，并使用 LOSO 交叉验证评估实际场景中的泛化性能。
