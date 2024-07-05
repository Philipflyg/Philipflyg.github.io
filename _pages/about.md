---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a second-year Ph.D. student at [Institute for AI Industry Research (AIR)](https://air.tsinghua.edu.cn/), Tsinghua University, supervised by [Prof. Ya-Qin Zhang](https://air.tsinghua.edu.cn/en/About_Us/About_dean.htm) and [Prof. Yilun Chen](https://air.tsinghua.edu.cn/en/info/1046/1621.htm). I got the B.S. degree from University of Chinese Academy of Sciences (UCAS) in 2022, supervised by [Prof. Qingming Huang](https://people.ucas.edu.cn/~qmhuang?language=en).

My research interest includes Autonomous Driving and Robotics. And I will be committed to the development, optimization and deployment of AI algorithms in real industrial scenarios.


# 📝 Publications 
- ```Preprint``` [PlanAgent: A Multi-modal Large Language Agent for Closed-loop Vehicle Motion Planning](https://arxiv.org/pdf/2406.01587), Yupeng Zheng, Zebin Xing, Qichao Zhang, Bu Jin, **Pengfei Li**, Yuhang Zheng, Zhongpu Xia, Kun Zhan, Xianpeng Lang, Yaran Chen, Dongbin Zhao.
- ```Preprint``` [P-MapNet: Far-seeing map generator enhanced by both SDMap and HDMap priors](https://arxiv.org/pdf/2403.10521), Zhou Jiang, Zhenxin Zhu, **Pengfei Li**, Huan-ang Gao, Tianyuan Yuan, Yongliang Shi, Hang Zhao, Hao Zhao.
- ```Preprint``` [Learning Point-wise Abstaining Penalty for Point Cloud Anomaly Detection](https://arxiv.org/pdf/2309.10230), Shaocong Xu, **Pengfei Li**, Xinyu Liu, Qianpu Sun, Yang Li, Shihui Guo, Zhen Wang, Bo Jiang, Rui Wang, Kehua Sheng, Bo Zhang, Hao Zhao.

- ```IEEE RA-L``` [GaussianGrasper: 3D Language Gaussian Splatting for Open-vocabulary Robotic Grasping](https://arxiv.org/pdf/2403.09637), Yuhang Zheng, Xiangyu Chen, Yupeng Zheng, Songen Gu, Runyi Yang, Bu Jin, **Pengfei Li**, Chengliang Zhong, Zengmao Wang, Lina Liu, Chao Yang, Dawei Wang, Zhen Chen, Xiaoxiao Long, Meiqing Wang.
- ```ECCV 2024``` [TOD3Cap: Towards 3D Dense Captioning in Outdoor Scenes](https://jxbbb.github.io/TOD3Cap/), Bu Jin, Yupeng Zheng, **Pengfei Li**, Weize Li, Yuhang Zheng, Sujie Hu, Xinyu Liu, Jinwei Zhu, Zhijie Yan, Haiyang Sun, Kun Zhan, Peng Jia, Xiaoxiao Long, Yilun Chen, Hao Zhao.
- ```ICRA 2024``` [MonoOcc: Digging into Monocular Semantic Occupancy Prediction](https://arxiv.org/abs/2403.08766), Yupeng Zheng, Xiang Li, **Pengfei Li**, Yuhang Zheng, Bu Jin, Chengliang Zhong, Xiaoxiao Long, Hao Zhao, Qichao Zhang.
- ``` Knowledge-Based Systems ``` [City-scale continual neural semantic mapping with three-layer sampling and panoptic representation](https://www.sciencedirect.com/science/article/abs/pii/S095070512300895X), Yongliang Shi, Runyi Yang, Zirui Wu, **Pengfei Li**, Caiyun Liu, Hao Zhao, Guyue Zhou.
- ```ICCV 2023```[INT2: Interactive Trajectory Prediction at Intersections](https://openaccess.thecvf.com/content/ICCV2023/papers/Yan_INT2_Interactive_Trajectory_Prediction_at_Intersections_ICCV_2023_paper.pdf), Zhijie Yan, **Pengfei Li**, Zheng Fu, Shaocong Xu, Yongliang Shi, Xiaoxue Chen, Yuhang Zheng, Yang Li, Tianyu Liu, Chuxuan Li, Nairui Luo, Xu Gao, Yilun Chen, Zuoxu Wang, Yifeng Shi, Pengfei Huang, Zhengxiao Han, Jirui Yuan, Jiangtao Gong, Guyue Zhou, Hang Zhao, Hao Zhao.
- ```ICCV 2023```[3D Implicit Transporter for Temporally Consistent Keypoint Discovery](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhong_3D_Implicit_Transporter_for_Temporally_Consistent_Keypoint_Discovery_ICCV_2023_paper.pdf), Chengliang Zhong, Yuhang Zheng, Yupeng Zheng, Hao Zhao, Li Yi, Xiaodong Mu, Ling Wang, **Pengfei Li**, Guyue Zhou, Chao Yang, Xinliang Zhang, Jian Zhao.
- ```ICCV 2023```[DQS3D: Densely-matched Quantization-aware Semi-supervised 3D Detection
](https://openaccess.thecvf.com/content/ICCV2023/papers/Gao_DQS3D_Densely-matched_Quantization-aware_Semi-supervised_3D_Detection_ICCV_2023_paper.pdf), Huan-ang Gao, Beiwen Tian, **Pengfei Li**, Hao Zhao, Guyue Zhou.
- ```CICAI 2023``` [M2Sim: A Long-Term Interactive Driving Simulator](https://link.springer.com/chapter/10.1007/978-981-99-9119-8_16), Zhengxiao Han, Zhijie Yan, Yang Li, **Pengfei Li**, Yifeng Shi, Nairui Luo, Xu Gao, Yongliang Shi, Pengfei Huang, Jiangtao Gong, Guyue Zhou, Yilun Chen, Hang Zhao, Hao Zhao.
- ```CICAI 2023``` [Long-Term Interactive Driving Simulation: MPC to the Rescue](https://link.springer.com/chapter/10.1007/978-981-99-9119-8_17), Zhengxiao Han, Zhijie Yan, Yang Li, Pengfei Li, Yifeng Shi, Nairui Luo, Xu Gao, Yongliang Shi, Pengfei Huang, Jiangtao Gong, Guyue Zhou, Yilun Chen, Hang Zhao, Hao Zhao.
- ``ICRA 2023`` [Lode: Locally conditioned eikonal implicit scene completion from sparse lidar](https://ieeexplore.ieee.org/document/10160552), **Pengfei Li**, Ruowen Zhao, Yongliang Shi, Hao Zhao, Jirui Yuan, Guyue Zhou, Ya-Qin Zhang.
- ``ICRA 2023`` [Adapt: Action-aware driving caption transformer](https://ieeexplore.ieee.org/document/10160326), Bu Jin, Xinyu Liu, Yupeng Zheng, **Pengfei Li**, Hao Zhao, Tong Zhang, Yuhang Zheng, Guyue Zhou, Jingjing Liu.
- ``ICRA 2023`` [Steps: Joint self-supervised nighttime image enhancement and depth estimation](https://ieeexplore.ieee.org/document/10160708), Yupeng Zheng, Chengliang Zhong, **Pengfei Li**, Huan-ang Gao, Yuhang Zheng, Bu Jin, Ling Wang, Hao Zhao, Guyue Zhou, Qichao Zhang, Dongbin Zhao.
- ``ICRA 2023`` [From semi-supervised to omni-supervised room layout estimation using point clouds](https://ieeexplore.ieee.org/document/10161273), Huan-ang Gao, Beiwen Tian, **Pengfei Li**, Xiaoxue Chen, Hao Zhao, Guyue Zhou, Yurong Chen, Hongbin Zha.
- ``ICRA 2023`` [LATITUDE: Robotic Global Localization with Truncated Dynamic Low-pass Filter in City-scale NeRF](https://ieeexplore.ieee.org/document/10161570), Zhenxin Zhu, Yuantao Chen, Zirui Wu, Chao Hou, Yongliang Shi, Chuxuan Li, **Pengfei Li**, Hao Zhao, Guyue Zhou.
- ``ICRA 2023`` [Unsupervised Road Anomaly Detection with Language Anchors](https://ieeexplore.ieee.org/document/10160470), Beiwen Tian, Mingdao Liu, Huan-ang Gao, **Pengfei Li**, Hao Zhao and Guyue Zhou.
- ``NeurIPS 2022`` [TOIST: Task Oriented Instance Segmentation Transformer with Noun-Pronoun Distillation Supplementary Material](https://proceedings.neurips.cc/paper_files/paper/2022/file/70270a1bc28ecb2a2aefad566c5e556b-Paper-Conference.pdf), **Pengfei Li**, Beiwen Tian, Yongliang Shi, Xiaoxue Chen, Hao Zhao, Guyue Zhou, Ya-Qin Zhang.

# 🏆 Competitions
- ```ICRA 2023``` [1st Place](https://lcas.lincoln.ac.uk/wp/events/the-pub-r-competition/) in the Preparation and dish Up of an English Breakfast with Robots (PUB.R) competition.

# 🎖 Honors and Awards
- *2021.12* National Scholarship (Undergraduate) (Top 1%)
- *2020.12* National Scholarship (Undergraduate) (Top 1%)

# 📖 Educations
- *2022.09 - now*, Ph.D. student, Institute for AI Industry Research (AIR), Tsinghua University. 
- *2018.09 - 2022.06*, Undergraduate, School of Computer Science and Technology, University of Chinese Academy of Sciences. 

<div style="display: flex; justify-content: center; align-items: center;">
<script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?w=166&d=G22ZMDy2KEs5OGq6rS0JucNzUxHn13B0tIPWaEGNGJo"></script>
</div>
