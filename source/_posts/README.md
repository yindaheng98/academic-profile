---
title: Home
date: 2022-10-21 18:21:33
tags:
academia: true
---

# About Me

I am currently a PhD student at [Simon Fraser University](https://cse.seu.edu.cn/edulab/), advised by [Prof. Jiangchuan (JC) LIU](https://www.cs.sfu.ca/~jcliu/). 
I received my Master's degree at [Southeast University](https://cse.seu.edu.cn/edulab/), advised by [Prof. Fang Dong](https://cse.seu.edu.cn/2019/0102/c23024a256994/page.htm),
and my Bachelor's degree from [Jiangnan University](https://www.jiangnan.edu.cn/) in 2020, majoring in Internet of Things Engineering. 
My research interests include optimization and application of video super-resolution.

Currently, my research focuses on the distributed acceleration of super-resolution inference for live video streaming applications in an edge computing environment.
In this scenario, the video super-resolution model should be able of performing inference in real-time (>30FPS) with low latency (<500ms) on the support of distributed low-power computing devices, while ensuring smooth playback in the dynamic environment with varying bandwidth between computing devices.
To achieve this, various optimization strategies should be utilized, including:

1. Modification of model structure for better parallelism: Divide typical video super-resolution model into independent modules for parallel feature extraction.
2. Compression of intermediate features for bandwidth saving: Reduce the dimension of intermediate features, quantize features to INT8, and compress features with a video encoder such as H.264.
3. Leverage information in compressed video for smooth playback: Modify the VP9 decoder to merge the low-framerate high-resolution video (from super-resolution inference) and high-framerate low-resolution video to produce high-framerate high-resolution video.
4. Variable frame sequence length for dynamic bandwidth adaption: Dynamically adjust the sequence length of input frames to balance video quality and latency in dynamic bandwidth.

My goal is to build systems that can achieve high-quality video communication at a low cost for everyone, as well as investigate the nature of AI system stability and even abstract chaotic systems in practice.

# Research Interest

* Edge computing & Cloud computing
* Live video streaming
* Application-driven deep learning algorithm optimization

# Education Experience

<dl>
<dt><img align="left" width="100" hspace="10" src="/img/SFUlogo.png"></dt>
<dt>Simon Fraser University, Burnaby, Canada</dt>
<dd>Ph.D. in Computing Science.</dd>
<dd>August 2023 - </dd>
<dd>--------------------------------</dd>
<dt><img align="left" width="100" hspace="10" src="/img/SEUlogo.png"></dt>
<dt>Southeast University, Nanjing, China</dt>
<dd>M.Eng. in Computer Science and Engineering.</dd>
<dd>August 2020 - July 2023</dd>
<dd>--------------------------------</dd>
<dt><img align="left" width="100" hspace="10" src="/img/JNUlogo.png"></dt>
<dt>Jiangnan University, Wuxi, China</dt>
<dd>August 2016 - July 2020</dd>
<dd>B.Eng. in IoT Engineering</dd>
<dd>GPA: 3.63, rank 9/141.</dd>
</dl>

# Publications

**Daheng Yin**, Fang Dong, Baijun Chen, Dian Shen, Ruiting Zhou, Xiaolin Guo, Zhaowu Huang "*WAEVSR: Enabling Collaborative Live Video Super-Resolution in Wide-Area MEC Environment*," 2023 IEEE/ACM 31st International Symposium on Quality of Service (IWQoS), 2023

Baijun Chen, **Daheng Yin**, Lifei Teng, Fang Dong "*HyperRTV: Neural-Enhanced Adaptive Real-Time Video Streaming Based on Terminal-Edge Collaboration*," 2023 26th International Conference on Computer Supported Cooperative Work in Design (CSCWD), 2023

Xiaolin Guo, Fang Dong, Dian Shen, Zhaowu Huang, Zhenyang Ni, Yulong Jiang, **Daheng Yin**, "*Exploiting the computational path diversity with in-network computing for MEC*," 2022 19th Annual IEEE International Conference on Sensing, Communication, and Networking (SECON), 2022

Mengyang Liu, Anran Tang, Huitian Wang, Lin Shen, Yunhan Chang, Guangxing Cai, **Daheng Yin**, Fang Dong, Wei Zhao, "*Accelerating Multi-Object Tracking in Edge Computing Environment with Time-Spatial Optimization*," 2021 Ninth International Conference on Advanced Cloud and Big Data (CBD), 2021

# Contest

* TensorRT Hackathon 2022, **Winner Prize**, <small>by NVIDIA & Alibaba Cloud TIANCHI, 2022.03 - 2022.5</small>
* TensorRT Hackathon 2021, **Ranking 4/48**, <small>by NVIDIA & Alibaba Cloud TIANCHI, 2021.03 - 2021.5</small>
* National College Mathematical Contest in Modeling, **2nd Prize(National)**, <small>2018.09</small>
* 9th National College Mathematical Contest, **2nd Prize(Provincial)**, <small>2017.11</small>
* 14th Jiangsu College Mathematical Contest, **1st Prize**, <small>2017.05</small>

# Honors & Awards

* Outstanding Graduate of Jiangnan University, <small>2020.06</small>
* China National Scholarship (2016-2017), <small>2017.11</small>
