---
title: "SDP: Spiking Diffusion Policy for Robotic Manipulation with Learnable Channel-Wise Membrane Thresholds"
collection: publications
permalink: /publication/2025-09-01-sdp-spiking-diffusion-policy
excerpt: "A spiking diffusion policy for robotic manipulation that improves inference efficiency while maintaining task success rates."
date: 2025-09-01
venue: "PRCV 2025"
paperurl: "https://arxiv.org/abs/2409.11195"
citation: "Gao, M. et al. (2025). SDP: Spiking Diffusion Policy for Robotic Manipulation with Learnable Channel-Wise Membrane Thresholds. PRCV 2025."
---

This work applies spiking neural networks to Diffusion Policy for robotic manipulation. The project explores learnable channel-wise membrane thresholds and validates the method in simulation and real-robot settings.

Key contributions:

- Replaced parts of traditional floating-point MAC computation with efficient spiking operations.
- Evaluated the policy on PushT, Lift, Can, Square, and other manipulation tasks.
- Estimated an 80.36% dynamic energy reduction on 45nm hardware while maintaining comparable success rates.
- Completed Sim-to-Real deployment on Franka robot arms.
