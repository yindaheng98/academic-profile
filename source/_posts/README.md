---
title: Home
date: 2022-10-21 18:21:33
tags:
academia: true
---

# About Me

I am a graduate student at the [Key Laboratory of Computer Network and Information Integration (Southeast University) Ministry of Education](https://cse.seu.edu.cn/edulab/), advised by [Prof. Fang Dong](https://cse.seu.edu.cn/2019/0102/c23024a256994/page.htm). 
I obtained my Bachelor's degree from [Jiangnan University](https://www.jiangnan.edu.cn/) in 2020. 
My research interests include optimization and application of video super-resolution.

Currently, my research focuses on the distributed acceleration of super-resolution inference for live video streaming applications in an edge computing environment.
In this scenario, the video super-resolution model should be able of performing inference in real-time (>30FPS) with low latency (<500ms) on the support of distributed low-power computing devices, while ensuring smooth playback in the dynamic environment with varying bandwidth between computing devices.
To achieve this, various optimization strategies should be utilized, including:

1. Modification of model structure for better parallelism: Divide typical video super-resolution model into independent modules for parallel feature extraction.
2. Compression of intermediate features for bandwidth saving: Reduce the dimension of intermediate features, quantize features to INT8, and compress features with a video encoder such as H.264.
3. Leverage information in compressed video for smooth playback: Modify the VP9 decoder to merge the low-framerate high-resolution video (from super-resolution inference) and high-framerate low-resolution video to produce high-framerate high-resolution video.
4. Variable frame sequence length for dynamic bandwidth adaption: Dynamically adjust the sequence length of input frames to balance video quality and latency in dynamic bandwidth.

My goal is to achieve that "distance can't keep us two apart (天涯若比邻)" by building systems that can obtain high-quality live video at low cost, as well as investigate the nature of AI system stability and even abstract chaotic systems in practice.

# Education Experience

<dl>
<dt><img align="left" height="100" hspace="10" src="/img/SEUlogo.png"></dt>
<dt>Southeast University, Nanjing, China</dt>
<dd>August 2020 - July 2023</dd>
<dd>B.Sc. in Computer Science and Engineering.</dd>
<dd>GPA: 81.69.</dd>
<dt><img align="left" height="100" hspace="10" src="/img/JNUlogo.png"></dt>
<dt>Jiangnan University, Wuxi, China</dt>
<dd>August 2016 - July 2020</dd>
<dd>B.E. in IoT Engineering</dd>
<dd>GPA: 3.59, <strong>rank 9/141</strong>.</dd>
</dl>

# Publications

Xiaolin Guo, Fang Dong, Dian Shen, Zhaowu Huang, Zhenyang Ni, Yulong Jiang, **Daheng Yin**, "*Exploiting the computational path diversity with in-network computing for MEC*," 2022 19th Annual IEEE International Conference on Sensing, Communication, and Networking (SECON), 2022, pp. 1-9.

Mengyang Liu, Anran Tang, Huitian Wang, Lin Shen, Yunhan Chang, Guangxing Cai, **Daheng Yin**, Fang Dong, Wei Zhao, "*Accelerating Multi-Object Tracking in Edge Computing Environment with Time-Spatial Optimization*," 2021 Ninth International Conference on Advanced Cloud and Big Data (CBD), 2022, pp. 279-284, doi: 10.1109/CBD54617.2021.00055.

# Contest

* TensorRT Hackathon 2022, **Winner Prize**, <small>by NVIDIA & Alibaba Cloud TIANCHI, 2022.03 - 2022.5</small>
* TensorRT Hackathon 2021, **Ranking 4/48**, <small>by NVIDIA & Alibaba Cloud TIANCHI, 2021.03 - 2021.5</small>
* National College Mathematical Contest in Modeling, **2nd Prize(National)**, <small>2018.09</small>
* 9th National College Mathematical Contest, **2nd Prize(Provincial)**, <small>2017.11</small>
* 14th Jiangsu College Mathematical Contest, **1st Prize**, <small>2017.05</small>

# Honors & Awards

* Outstanding Graduate of Jiangnan University, <small>2020.06</small>
* China National Scholarship (2016-2017), <small>2017.11</small>
