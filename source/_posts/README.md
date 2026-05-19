---
title: Home
date: 2022-10-21 18:21:33
tags:
academia: true
---

# About Me

I am a PhD student at [Simon Fraser University](https://cse.seu.edu.cn/edulab/), advised by [Prof. Jiangchuan (JC) LIU](https://www.cs.sfu.ca/~jcliu/). 
I received my Master's degree at [Southeast University](https://cse.seu.edu.cn/edulab/), advised by [Prof. Fang Dong](https://cs.seu.edu.cn/fdong/main.htm),
and my Bachelor's degree from [Jiangnan University](https://www.jiangnan.edu.cn/) in 2020, advised by [Prof. Ya Guo](https://iot.jiangnan.edu.cn/info/1141/3512.htm).
I design practical systems for photorealistic volumetric video reconstruction and transmission, targeting downstream applications in 3D scene understanding, embodied intelligence, and immersive volumetric telepresence.

# Research Interest

![](/img/Roadmap.png)

# Education Experience

<dl>
<dt><img align="left" width="100" hspace="10" src="/img/SFUlogo.svg"></dt>
<dt>Simon Fraser University, Burnaby, Canada</dt>
<dd>Ph.D. in Computing Science.</dd>
<dd>August 2023 - </dd>
<dd>--------------------------------</dd>
<dt><img align="left" width="100" hspace="10" src="/img/SEUlogo.svg"></dt>
<dt>Southeast University, Nanjing, China</dt>
<dd>M.Eng. in Computer Science and Engineering.</dd>
<dd>August 2020 - July 2023</dd>
<dd>--------------------------------</dd>
<dt><img align="left" width="100" hspace="10" src="/img/JNUlogo.svg"></dt>
<dt>Jiangnan University, Wuxi, China</dt>
<dd>August 2016 - July 2020</dd>
<dd>B.Eng. in Internet of Things (IoT) Engineering</dd>
<dd>GPA: 3.63, rank 9/141.</dd>
</dl>

# Publications

**Daheng Yin**, Yili Jin, Jianxin Shi, Isaac Ding, Miao Zhang, Fangxin Wang, Zhaowu Huang, Cong Zhang, Jiangchuan Liu, Fang Dong
"*[**CAGS**: Color-Adaptive Volumetric Video Streaming with Dynamic 3D Gaussian Splatting](https://arxiv.org/abs/2605.09279)*,"
SIGGRAPH 2026 Conference Papers (SIGGRAPH'26), 2026, [GitHub repo](https://github.com/yindaheng98/ColorAdaptiveGaussianSplatting)

**Daheng Yin**, Isaac Ding, Yili Jin, Jianxin Shi, Jiangchuan Liu
"*[**TrackerSplat**: Exploiting Point Tracking for Fast and Robust Dynamic 3D Gaussians Reconstruction](https://doi.org/10.1145/3757377.3763829)*,"
SIGGRAPH Asia 2025 Conference Papers (SA'25), 2025, [GitHub repo](https://github.com/yindaheng98/TrackerSplat)

Zhaowu Huang, Fang Dong, Xiaolin Guo, **Daheng Yin**
"*FaSei: Fast Serverless Edge Inference with Synergistic Lazy Loading and Layer-wise Caching*,"
IEEE International Conference on Computer Communications (INFOCOM), 2025

**Daheng Yin**, Jianxin Shi, Miao Zhang, Zhaowu Huang, Jiangchuan Liu, Fang Dong
"*[**FSVFG**: Towards Immersive Full-Scene Volumetric Video Streaming with Adaptive Feature Grid](https://doi.org/10.1145/3664647.3680908)*,"
32nd ACM International Conference on Multimedia (MM'24), 2024

**Daheng Yin**, Fang Dong, Baijun Chen, Dian Shen, Ruiting Zhou, Xiaolin Guo, Zhaowu Huang
"*WAEVSR: Enabling Collaborative Live Video Super-Resolution in Wide-Area MEC Environment*,"
IEEE/ACM 31st International Symposium on Quality of Service (IWQoS), 2023

Baijun Chen, **Daheng Yin**, Lifei Teng, Fang Dong
"*HyperRTV: Neural-Enhanced Adaptive Real-Time Video Streaming Based on Terminal-Edge Collaboration*,"
26th International Conference on Computer Supported Cooperative Work in Design (CSCWD), 2023

Xiaolin Guo, Fang Dong, Dian Shen, Zhaowu Huang, Zhenyang Ni, Yulong Jiang, **Daheng Yin**
"*Exploiting the computational path diversity with in-network computing for MEC*,"
19th Annual IEEE International Conference on Sensing, Communication, and Networking (SECON), 2022

Mengyang Liu, Anran Tang, Huitian Wang, Lin Shen, Yunhan Chang, Guangxing Cai, **Daheng Yin**, Fang Dong, Wei Zhao
"*Accelerating Multi-Object Tracking in Edge Computing Environment with Time-Spatial Optimization*,"
Ninth International Conference on Advanced Cloud and Big Data (CBD), 2021

# Open-source Projects

**[gaussian-splatting](https://github.com/yindaheng98/gaussian-splatting)** [![PyPI version](https://img.shields.io/pypi/v/gaussian-splatting.svg?logo=pypi)](https://pypi.org/project/gaussian-splatting/) [![Downloads](https://api.pepy.tech/personalized-badge/gaussian-splatting?period=month&left_color=grey&left_text=monthly%20downloads)](https://pepy.tech/project/gaussian-splatting) [![Total downloads](https://api.pepy.tech/personalized-badge/gaussian-splatting?period=total&left_color=grey&left_text=total%20downloads)](https://pepy.tech/project/gaussian-splatting)<br>
Refactored Python training and inference package for [3D Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting), preserving the original algorithms while reorganizing the code into a standard Python package. The project adds practical training features including exposure compensation, camera and 3DGS joint optimization, depth regularization, local relative depth regularization, image masks, and integrated [gsplat](https://github.com/nerfstudio-project/gsplat) / 2DGS backends.

**[InstantSplat](https://github.com/yindaheng98/InstantSplat)** [![PyPI version](https://img.shields.io/pypi/v/InstantSplat.svg?logo=pypi)](https://pypi.org/project/InstantSplat/) [![Downloads](https://api.pepy.tech/personalized-badge/InstantSplat?period=month&left_color=grey&left_text=monthly%20downloads)](https://pepy.tech/project/InstantSplat) [![Total downloads](https://api.pepy.tech/personalized-badge/InstantSplat?period=total&left_color=grey&left_text=total%20downloads)](https://pepy.tech/project/InstantSplat)<br>
Refactored Python package for [InstantSplat](https://github.com/NVlabs/InstantSplat), supporting sparse-view Gaussian Splatting initialization and camera/3DGS joint training. It includes DUSt3R, MASt3R, COLMAP sparse/dense reconstruction, VGGT, and Map-Anything based initialization workflows.

**[reduced-3dgs](https://github.com/yindaheng98/reduced-3dgs)** [![PyPI version](https://img.shields.io/pypi/v/reduced-3dgs.svg?logo=pypi)](https://pypi.org/project/reduced-3dgs/) [![Downloads](https://api.pepy.tech/personalized-badge/reduced-3dgs?period=month&left_color=grey&left_text=monthly%20downloads)](https://pepy.tech/project/reduced-3dgs) [![Total downloads](https://api.pepy.tech/personalized-badge/reduced-3dgs?period=total&left_color=grey&left_text=total%20downloads)](https://pepy.tech/project/reduced-3dgs)<br>
Refactored Python package for [Reduced-3DGS](https://github.com/graphdeco-inria/reduced-3dgs), maintaining the original memory-footprint-reduction algorithms while making the code easier to install and reuse. It provides pruning, SH culling, and K-Means vector quantization for compact 3D Gaussian Splatting models, and builds on the packaged `gaussian-splatting` project above.

**[feature-3dgs](https://github.com/yindaheng98/feature-3dgs)** [![PyPI version](https://img.shields.io/pypi/v/feature-3dgs.svg?logo=pypi)](https://pypi.org/project/feature-3dgs/) [![Downloads](https://api.pepy.tech/personalized-badge/feature-3dgs?period=month&left_color=grey&left_text=monthly%20downloads)](https://pepy.tech/project/feature-3dgs) [![Total downloads](https://api.pepy.tech/personalized-badge/feature-3dgs?period=total&left_color=grey&left_text=total%20downloads)](https://pepy.tech/project/feature-3dgs)<br>
Refactored Python package for [Feature 3DGS](https://github.com/ShijieZhou-UCLA/feature-3dgs), adding a modular Extractor-Decoder architecture for semantic feature distillation on Gaussian points. It supports DINOv3-based dense features, PCA visualization, interactive viewing, and the training modes inherited from packaged `gaussian-splatting`.

**[3dgs-mcmc](https://github.com/yindaheng98/3dgs-mcmc)** [![PyPI version](https://img.shields.io/pypi/v/gaussian-splatting-mcmc.svg?logo=pypi)](https://pypi.org/project/gaussian-splatting-mcmc/) [![Downloads](https://api.pepy.tech/personalized-badge/gaussian-splatting-mcmc?period=month&left_color=grey&left_text=monthly%20downloads)](https://pepy.tech/project/gaussian-splatting-mcmc) [![Total downloads](https://api.pepy.tech/personalized-badge/gaussian-splatting-mcmc?period=total&left_color=grey&left_text=total%20downloads)](https://pepy.tech/project/gaussian-splatting-mcmc)<br>
Refactored Python package for [3D Gaussian Splatting as Markov Chain Monte Carlo](https://github.com/ubc-vision/3dgs-mcmc), providing an installable MCMC trainer for 3D Gaussian Splatting and integration with `reduced-3dgs`.

**[gscompressor](https://github.com/yindaheng98/gscompressor)** [![PyPI version](https://img.shields.io/pypi/v/gscompressor.svg?logo=pypi)](https://pypi.org/project/gscompressor/) [![Downloads](https://api.pepy.tech/personalized-badge/gscompressor?period=month&left_color=grey&left_text=monthly%20downloads)](https://pepy.tech/project/gscompressor) [![Total downloads](https://api.pepy.tech/personalized-badge/gscompressor?period=total&left_color=grey&left_text=total%20downloads)](https://pepy.tech/project/gscompressor)<br>
Compresses 3DGS scenes with Draco and works with `gaussian-splatting`, `reduced-3dgs`, and `lapis-gs`.

**[lapis-gs](https://github.com/yindaheng98/lapis-gs)** [![PyPI version](https://img.shields.io/pypi/v/lapisgs.svg?logo=pypi)](https://pypi.org/project/lapisgs/) [![Downloads](https://api.pepy.tech/personalized-badge/lapisgs?period=month&left_color=grey&left_text=monthly%20downloads)](https://pepy.tech/project/lapisgs) [![Total downloads](https://api.pepy.tech/personalized-badge/lapisgs?period=total&left_color=grey&left_text=total%20downloads)](https://pepy.tech/project/lapisgs)<br>
Refactored Python package for [LapisGS](https://github.com/nus-vv-streams/lapis-gs), a layered progressive 3D Gaussian Splatting method for adaptive streaming. It provides multi-resolution training, progressive layer extraction, and integration with `gaussian-splatting` and `reduced-3dgs`.

**[feature-4dgs](https://github.com/yindaheng98/feature-4dgs)** [![PyPI version](https://img.shields.io/pypi/v/feature-4dgs.svg?logo=pypi)](https://pypi.org/project/feature-4dgs/) [![Downloads](https://api.pepy.tech/personalized-badge/feature-4dgs?period=month&left_color=grey&left_text=monthly%20downloads)](https://pepy.tech/project/feature-4dgs) [![Total downloads](https://api.pepy.tech/personalized-badge/feature-4dgs?period=total&left_color=grey&left_text=total%20downloads)](https://pepy.tech/project/feature-4dgs)<br>
Sequence-aware training extension for Feature 3DGS, built on top of `feature-3dgs` and `gaussian-splatting`. It extends semantic feature distillation from single scenes to multi-timestep 4D / dynamic-scene training with per-frame Gaussian models and one shared decoder for a consistent feature space.

**[track-4dgs](https://github.com/yindaheng98/track-4dgs)** [![PyPI version](https://img.shields.io/pypi/v/track-4dgs.svg?logo=pypi)](https://pypi.org/project/track-4dgs/) [![Downloads](https://api.pepy.tech/personalized-badge/track-4dgs?period=month&left_color=grey&left_text=monthly%20downloads)](https://pepy.tech/project/track-4dgs) [![Total downloads](https://api.pepy.tech/personalized-badge/track-4dgs?period=total&left_color=grey&left_text=total%20downloads)](https://pepy.tech/project/track-4dgs)<br>
Point tracking extension for 4D Gaussian Splatting. It wraps sequence point trackers such as CoTracker3 and VGGT, supports single-view image-sequence tracking, and projects/tracks 3D Gaussians across multi-timestep Gaussian Splatting camera datasets.

# Contest

* SIGGRAPH Asia 2025 Volumetric Video Workshop, **Compression Track 3rd**, <small>2025.08 - 2025.12</small>
* TensorRT Hackathon 2022, **Winner Prize**, <small>by NVIDIA & Alibaba Cloud TIANCHI, 2022.03 - 2022.5</small>
* TensorRT Hackathon 2021, **Ranking 4/48**, <small>by NVIDIA & Alibaba Cloud TIANCHI, 2021.03 - 2021.5</small>
* National College Mathematical Contest in Modeling, **2nd Prize (National)**, <small>2018.09</small>
* 9th National College Mathematical Contest, **2nd Prize (Provincial)**, <small>2017.11</small>
* 14th Jiangsu College Mathematical Contest, **1st Prize**, <small>2017.05</small>

# Honors & Awards

* Outstanding Graduate of Jiangnan University, <small>2020.06</small>
* China National Scholarship (2016-2017), <small>2017.11</small>
