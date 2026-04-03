# DRUM: Diffusion-based Raydrop-aware Unpaired Mapping for Sim2Real LiDAR Segmentation (ICRA 2026)

![teaser](https://github.com/user-attachments/assets/bb6971d8-5123-4af5-8164-8dc818f8e9c8)

This is an official implementation of the following paper:

**DRUM: Diffusion-based Raydrop-aware Unpaired Mapping for Sim2Real LiDAR Segmentation**<br>
[Tomoya Miyawaki](https://miyawakitomoya.com/), [Kazuto Nakashima](https://kazuto1011.github.io/), [Yumi Iwashita](https://www-robotics.jpl.nasa.gov/who-we-are/people/yumi_iwashita/), [Ryo Kurazume](https://robotics.ait.kyushu-u.ac.jp/kurazume/en/)<br>
IEEE International Conference on Robotics and Automation (ICRA), 2026

[![](https://img.shields.io/badge/arXiv-2603.26263-red?logo=arxiv)](https://arxiv.org/abs/2603.26263)
[![](https://img.shields.io/badge/Website-DRUM-blue)](https://miya-tomoya.github.io/drum)

## Abstract

LiDAR-based semantic segmentation is a key component for autonomous mobile robots, yet large-scale annotation of LiDAR point clouds is prohibitively expensive and time-consuming. Although simulators can provide labeled synthetic data, models trained on synthetic data often underperform on real-world data due to a data-level domain gap. To address this issue, we propose DRUM, a novel Sim2Real translation framework. We leverage a diffusion model pre-trained on unlabeled real-world data as a generative prior and translate synthetic data by reproducing two key measurement characteristics: reflectance intensity and raydrop noise. To improve sample fidelity, we introduce a raydrop-aware masked guidance mechanism that selectively enforces consistency with the input synthetic data while preserving realistic raydrop noise induced by the diffusion prior. Experimental results demonstrate that DRUM consistently improves Sim2Real performance across multiple representations of LiDAR data.
