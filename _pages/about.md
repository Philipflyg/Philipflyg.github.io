---
permalink: /
title: ""
excerpt: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section id="about">
<h1>About</h1>

<p>
I am a fourth-year Ph.D. student at the <a href="https://air.tsinghua.edu.cn/">Institute for AI Industry Research (AIR)</a>, Tsinghua University, advised by <a href="https://air.tsinghua.edu.cn/en/info/1046/1621.htm">Prof. Yilun Chen</a> and <a href="https://air.tsinghua.edu.cn/en/About_Us/About_dean.htm">Prof. Ya-Qin Zhang</a>. I received my B.S. from the University of Chinese Academy of Sciences (UCAS) in 2022, where I worked with <a href="https://people.ucas.edu.cn/~qmhuang?language=en">Prof. Qingming Huang</a>.
</p>

<p>
My research focuses on <strong>Embodied AI</strong> and <strong>Autonomous Driving</strong>, with the goal of developing, optimizing, and deploying AI algorithms in <strong>real-world industrial scenarios</strong>. I am especially interested in world models, closed-loop motion planning, LiDAR perception, and task-oriented vision-language reasoning.
</p>
</section>

<section id="news">
<h1>News</h1>

<ul class="news-list">
  <li><span class="news-date">2026.02</span><span class="news-body"><strong>Human and Algorithmic Visual Attention in Driving Tasks</strong> published in <strong>npj Artificial Intelligence</strong> (Nature).</span></li>
  <li><span class="news-date">2026.03</span><span class="news-body">Released <a href="https://arxiv.org/abs/2603.02856"><strong>Rhythm</strong></a>, a dual-humanoid interactive whole-body control framework, deployed on real Unitree G1 robots.</span></li>
  <li><span class="news-date">2025.10</span><span class="news-body"><strong>World4Drive</strong> accepted to <strong>ICCV 2025</strong>.</span></li>
  <li><span class="news-date">2025.06</span><span class="news-body"><strong>Bench4Merge</strong> accepted to <strong>IROS 2025</strong>.</span></li>
  <li><span class="news-date">2025.05</span><span class="news-body">Released <a href="https://arxiv.org/pdf/2505.17209"><strong>LiloDriver</strong></a>, a lifelong learning framework for long-tail motion planning.</span></li>
  <li><span class="news-date">2025.02</span><span class="news-body">Released <a href="https://arxiv.org/abs/2502.07309"><strong>PreWorld</strong></a>, a semi-supervised vision-centric 3D occupancy world model.</span></li>
  <li><span class="news-date">2025.02</span><span class="news-body"><strong>MMTL-UniAD</strong> accepted to <strong>CVPR 2025</strong>.</span></li>
  <li><span class="news-date">2025.01</span><span class="news-body"><strong>Dual-AEB</strong> accepted to <strong>ICRA 2025</strong>.</span></li>
  <li><span class="news-date">2024.12</span><span class="news-body"><strong>LiON</strong> accepted to <strong>AAAI 2025</strong>.</span></li>
  <li><span class="news-date">2024.07</span><span class="news-body"><strong>TOD3Cap</strong> accepted to <strong>ECCV 2024</strong>.</span></li>
</ul>
</section>

<section id="publications">
<h1>Selected Publications <sup style="font-size:0.55em;color:#666;">(* equal contribution)</sup></h1>

<p style="color:#555;margin-top:0.4em;">
First-author / co-first-author works are highlighted below. A full list — including collaborations — is at the bottom of this section.
</p>

<div class="paper-box">
  <div class="paper-box-image">
    <a href="https://arxiv.org/abs/2603.02856"><img src="images/publications/rhythm.png" alt="Rhythm teaser"></a>
  </div>
  <div class="paper-box-text">
    <span class="venue-tag">Preprint 2026</span>
    <a class="paper-title" href="https://arxiv.org/abs/2603.02856">Rhythm: Learning Interactive Whole-Body Control for Dual Humanoids</a>
    <p class="paper-authors">Hongjin Chen<sup>*</sup>, Wei Zhang<sup>*</sup>, <span class="me">Pengfei Li</span><sup>*</sup>, Shihao Ma, Ke Ma, Yujie Jin, Zijun Xu, Xiaohui Wang, Yupeng Zheng, Zining Wang, Jieru Zhao, Yilun Chen, Wenchao Ding.</p>
    <p class="paper-tagline">First unified framework for real-world dual-humanoid whole-body interaction — interaction-aware retargeting + interaction-guided RL — deployed on Unitree G1 (greeting, hugging, dancing).</p>
    <p class="paper-links">
      <a href="https://arxiv.org/abs/2603.02856">Paper</a>
      <a href="https://hoshi-no-ai.github.io/Rhythm/">Project</a>
    </p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <a href="https://www.nature.com/articles/s44387-026-00079-1"><img src="images/publications/npj-attention.png" alt="Human and algorithmic visual attention teaser"></a>
  </div>
  <div class="paper-box-text">
    <span class="venue-tag venue-tag--accent">npj Artificial Intelligence 2026</span>
    <a class="paper-title" href="https://www.nature.com/articles/s44387-026-00079-1">Human and Algorithmic Visual Attention in Driving Tasks</a>
    <p class="paper-authors">Chen Zheng<sup>*</sup>, <span class="me">Pengfei Li</span><sup>*</sup>, Bu Jin<sup>*</sup>, Shanhe You, Ka I Chan, Ya-Qin Zhang, Guyue Zhou, Jiangtao Gong.</p>
    <p class="paper-tagline">Decomposes human driving attention into spatial / feature-based / mixed phases and shows that injecting human semantic attention closes both the "reasoning" and "grounding" gaps of detection, planning, and VLM models.</p>
    <p class="paper-links">
      <a href="https://www.nature.com/articles/s44387-026-00079-1">Paper</a>
      <a href="https://doi.org/10.1038/s44387-026-00079-1">DOI</a>
    </p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <a href="https://arxiv.org/abs/2502.07309"><img src="images/publications/preworld.png" alt="PreWorld teaser"></a>
  </div>
  <div class="paper-box-text">
    <span class="venue-tag venue-tag--accent">ICLR 2025</span>
    <a class="paper-title" href="https://arxiv.org/abs/2502.07309">Semi-Supervised Vision-Centric 3D Occupancy World Model for Autonomous Driving</a>
    <p class="paper-authors">Xiang Li<sup>*</sup>, <span class="me">Pengfei Li</span><sup>*</sup>, Yupeng Zheng, Wei Sun, Yan Wang, Yilun Chen.</p>
    <p class="paper-tagline">A two-stage occupancy world model that leverages cheap 2D labels via volume rendering, then fine-tunes with full 3D supervision for occupancy and ego-trajectory forecasting.</p>
    <p class="paper-links">
      <a href="https://arxiv.org/abs/2502.07309">Paper</a>
      <a href="https://arxiv.org/pdf/2502.07309">PDF</a>
      <a href="https://github.com/getterupper/PreWorld">Code</a>
    </p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <a href="https://arxiv.org/pdf/2505.17209"><img src="images/publications/lilodriver.png" alt="LiloDriver teaser"></a>
  </div>
  <div class="paper-box-text">
    <span class="venue-tag">Preprint 2025</span>
    <a class="paper-title" href="https://arxiv.org/pdf/2505.17209">LiloDriver: A Lifelong Learning Framework for Closed-loop Motion Planning in Long-tail Autonomous Driving Scenarios</a>
    <p class="paper-authors">Huaiyuan Yao<sup>*</sup>, <span class="me">Pengfei Li</span><sup>*</sup>, Bu Jin, Yupeng Zheng, An Liu, Lisen Mu, Qing Su, Qian Zhang, Yilun Chen, Peng Li.</p>
    <p class="paper-tagline">A memory-augmented LLM-guided planner that adapts to novel long-tail driving scenarios without retraining; SOTA on nuPlan.</p>
    <p class="paper-links">
      <a href="https://arxiv.org/pdf/2505.17209">Paper</a>
      <a href="https://github.com/Hyan-Yao/LiloDriver">Code</a>
    </p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <a href="https://arxiv.org/abs/2410.08616"><img src="images/publications/dual-aeb.png" alt="Dual-AEB teaser"></a>
  </div>
  <div class="paper-box-text">
    <span class="venue-tag venue-tag--accent">ICRA 2025</span>
    <a class="paper-title" href="https://arxiv.org/abs/2410.08616">Dual-AEB: Synergizing Rule-Based and Multimodal Large Language Models for Effective Emergency Braking</a>
    <p class="paper-authors">Wei Zhang<sup>*</sup>, <span class="me">Pengfei Li</span><sup>*</sup>, Junli Wang, Bingchuan Sun, Qihao Jin, Guangjun Bao, Shibo Rui, Yang Yu, Wenchao Ding, Peng Li, Yilun Chen.</p>
    <p class="paper-tagline">First MLLM-augmented AEB system — combines fast rule-based reaction with rich open-scenario reasoning from a multimodal LLM.</p>
    <p class="paper-links">
      <a href="https://arxiv.org/abs/2410.08616">Paper</a>
      <a href="https://github.com/ChipsICU/Dual-AEB">Code</a>
    </p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <a href="https://arxiv.org/abs/2309.10230"><img src="images/publications/lion.png" alt="LiON teaser"></a>
  </div>
  <div class="paper-box-text">
    <span class="venue-tag venue-tag--accent">AAAI 2025</span>
    <a class="paper-title" href="https://arxiv.org/abs/2309.10230">LiON: Learning Point-wise Abstaining Penalty for Point Cloud Anomaly Detection</a>
    <p class="paper-authors">Shaocong Xu<sup>*</sup>, <span class="me">Pengfei Li</span><sup>*</sup>, Xinyu Liu, Qianpu Sun, Yang Li, Shihui Guo, Zhen Wang, Bo Jiang, Rui Wang, Kehua Sheng, Bo Zhang, Hao Zhao.</p>
    <p class="paper-tagline">Reframes LiDAR outlier detection as selective classification with a learned point-wise abstaining penalty and synthetic-outlier curriculum — SOTA on SemanticKITTI and nuScenes.</p>
    <p class="paper-links">
      <a href="https://arxiv.org/abs/2309.10230">Paper</a>
      <a href="https://github.com/Daniellli/LiON">Code</a>
    </p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <a href="https://arxiv.org/abs/2302.14052"><img src="images/publications/lode.png" alt="LODE teaser"></a>
  </div>
  <div class="paper-box-text">
    <span class="venue-tag venue-tag--accent">ICRA 2023</span>
    <a class="paper-title" href="https://arxiv.org/abs/2302.14052">LODE: Locally Conditioned Eikonal Implicit Scene Completion from Sparse LiDAR</a>
    <p class="paper-authors"><span class="me">Pengfei Li</span>, Ruowen Zhao, Yongliang Shi, Hao Zhao, Jirui Yuan, Guyue Zhou, Ya-Qin Zhang.</p>
    <p class="paper-tagline">An eikonal-constrained implicit representation that turns sparse outdoor LiDAR into dense semantic 3D scenes — the first locally conditioned eikonal completion for autonomous driving.</p>
    <p class="paper-links">
      <a href="https://arxiv.org/abs/2302.14052">Paper</a>
      <a href="https://ieeexplore.ieee.org/document/10160552">IEEE</a>
      <a href="https://github.com/AIR-DISCOVER/LODE">Code</a>
    </p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <a href="https://proceedings.neurips.cc/paper_files/paper/2022/file/70270a1bc28ecb2a2aefad566c5e556b-Paper-Conference.pdf"><img src="images/publications/toist.png" alt="TOIST teaser"></a>
  </div>
  <div class="paper-box-text">
    <span class="venue-tag venue-tag--accent">NeurIPS 2022</span>
    <a class="paper-title" href="https://proceedings.neurips.cc/paper_files/paper/2022/file/70270a1bc28ecb2a2aefad566c5e556b-Paper-Conference.pdf">TOIST: Task Oriented Instance Segmentation Transformer with Noun-Pronoun Distillation</a>
    <p class="paper-authors"><span class="me">Pengfei Li</span>, Beiwen Tian, Yongliang Shi, Xiaoxue Chen, Hao Zhao, Guyue Zhou, Ya-Qin Zhang.</p>
    <p class="paper-tagline">Formulates task-oriented detection as preferred-object segmentation, and introduces noun-to-pronoun distillation so a transformer can act on verbs like "sit on" without explicit object naming.</p>
    <p class="paper-links">
      <a href="https://proceedings.neurips.cc/paper_files/paper/2022/file/70270a1bc28ecb2a2aefad566c5e556b-Paper-Conference.pdf">Paper</a>
      <a href="https://github.com/AIR-DISCOVER/TOIST">Code</a>
    </p>
  </div>
</div>

<details class="more-pubs">
  <summary>More publications (collaborations &amp; older works)</summary>
  <div class="more-pubs__list">
    <ul>
      <li><span class="venue-tag">ICCV 2025</span> <a href="https://arxiv.org/abs/2507.00603">World4Drive: End-to-End Autonomous Driving via Intention-aware Physical Latent World Model</a>. Yupeng Zheng, Pengxuan Yang, Zebin Xing, Qichao Zhang, Yuhang Zheng, Yinfeng Gao, <span class="me">Pengfei Li</span>, Teng Zhang, Zhongpu Xia, Peng Jia, Dongbin Zhao.</li>
      <li><span class="venue-tag">CVPR 2025</span> <a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Liu_MMTL-UniAD_A_Unified_Framework_for_Multimodal_and_Multi-Task_Learning_in_CVPR_2025_paper.pdf">MMTL-UniAD: A Unified Framework for Multimodal and Multi-Task Learning in Assistive Driving Perception</a>. Wenzhuo Liu, Wenshuo Wang, Yicheng Qiao, Qiannan Guo, Jiayin Zhu, <span class="me">Pengfei Li</span>, Zilong Chen, Huiming Yang, Zhiwei Li, Lening Wang, Tiao Tan, Huaping Liu.</li>
      <li><span class="venue-tag">IROS 2025</span> <a href="https://arxiv.org/abs/2410.15912">Bench4Merge: A Comprehensive Benchmark for Merging in Realistic Dense Traffic with Micro-Interactive Vehicles</a>. Zhengming Wang, Junli Wang, <span class="me">Pengfei Li</span>, Zhaohan Li, Chunyang Liu, Bo Zhang, Peng Li, Yilun Chen.</li>
      <li><span class="venue-tag">IEEE RA-L</span> <a href="https://ieeexplore.ieee.org/abstract/document/11183690">Enhancing Indoor Occupancy Prediction via Sparse Query-Based Multi-Level Consistent Knowledge Distillation</a>. Xiang Li, Yupeng Zheng, <span class="me">Pengfei Li</span>, Yilun Chen, Ya-Qin Zhang, Wenchao Ding.</li>
      <li><span class="venue-tag">IEEE RA-L</span> <a href="https://arxiv.org/abs/2403.10521">P-MapNet: Far-seeing Map Generator Enhanced by both SDMap and HDMap Priors</a>. Zhou Jiang, Zhenxin Zhu, <span class="me">Pengfei Li</span>, Huan-ang Gao, Tianyuan Yuan, Yongliang Shi, Hang Zhao, Hao Zhao.</li>
      <li><span class="venue-tag">IEEE RA-L</span> <a href="https://arxiv.org/abs/2403.09637">GaussianGrasper: 3D Language Gaussian Splatting for Open-vocabulary Robotic Grasping</a>. Yuhang Zheng, Xiangyu Chen, Yupeng Zheng, Songen Gu, Runyi Yang, Bu Jin, <span class="me">Pengfei Li</span>, Chengliang Zhong, Zengmao Wang, Lina Liu, Chao Yang, Dawei Wang, Zhen Chen, Xiaoxiao Long, Meiqing Wang.</li>
      <li><span class="venue-tag">Preprint</span> <a href="https://arxiv.org/abs/2503.03556">Afford-X: Generalizable and Slim Affordance Reasoning for Task-Oriented Manipulation</a>. Xiaomeng Zhu, Yuyang Li, Leiyao Cui, <span class="me">Pengfei Li</span>, Huan-ang Gao, Yixin Zhu, Hao Zhao.</li>
      <li><span class="venue-tag">Preprint</span> <a href="https://vilonge.github.io/OccLLaMA_Page/static/OccLLaMA.pdf">OccLLaMA: A Unified Occupancy-Language-Action World Model for Autonomous Driving</a>. Julong Wei, Shanshuai Yuan, <span class="me">Pengfei Li</span>, Xinyi Quan, Lei Tai, Jieru Zhao, Zhongxue Gan, Wenchao Ding.</li>
      <li><span class="venue-tag">Preprint</span> <a href="https://zhihua-hua.github.io/NavigationDrive-web/static/NavigationDrive.pdf">Unveiling the Surprising Efficacy of Navigation Understanding in End-to-End Autonomous Driving</a>. Zhihua Hua, Junli Wang, <span class="me">Pengfei Li</span>, Qihao Jin, Bo Zhang, Kehua Sheng, Yilun Chen, Zhongxue Gan, Wenchao Ding.</li>
      <li><span class="venue-tag">Preprint</span> <a href="https://arxiv.org/abs/2406.01587">PlanAgent: A Multi-modal Large Language Agent for Closed-loop Vehicle Motion Planning</a>. Yupeng Zheng, Zebin Xing, Qichao Zhang, Bu Jin, <span class="me">Pengfei Li</span>, Yuhang Zheng, Zhongpu Xia, Kun Zhan, Xianpeng Lang, Yaran Chen, Dongbin Zhao.</li>
      <li><span class="venue-tag">ECCV 2024</span> <a href="https://jxbbb.github.io/TOD3Cap/">TOD3Cap: Towards 3D Dense Captioning in Outdoor Scenes</a>. Bu Jin, Yupeng Zheng, <span class="me">Pengfei Li</span>, Weize Li, Yuhang Zheng, Sujie Hu, Xinyu Liu, Jinwei Zhu, Zhijie Yan, Haiyang Sun, Kun Zhan, Peng Jia, Xiaoxiao Long, Yilun Chen, Hao Zhao.</li>
      <li><span class="venue-tag">ICRA 2024</span> <a href="https://arxiv.org/abs/2403.08766">MonoOcc: Digging into Monocular Semantic Occupancy Prediction</a>. Yupeng Zheng, Xiang Li, <span class="me">Pengfei Li</span>, Yuhang Zheng, Bu Jin, Chengliang Zhong, Xiaoxiao Long, Hao Zhao, Qichao Zhang.</li>
      <li><span class="venue-tag">AAAI 2024</span> <a href="https://ojs.aaai.org/index.php/AAAI/article/view/28753">ModWaveMLP: MLP-based Mode Decomposition and Wavelet Denoising for Traffic Forecasting</a>. Ke Sun, Pei Liu, <span class="me">Pengfei Li</span>, Zhifang Liao.</li>
      <li><span class="venue-tag">KBS</span> <a href="https://www.sciencedirect.com/science/article/abs/pii/S095070512300895X">City-scale Continual Neural Semantic Mapping with Three-layer Sampling and Panoptic Representation</a>. Yongliang Shi, Runyi Yang, Zirui Wu, <span class="me">Pengfei Li</span>, Caiyun Liu, Hao Zhao, Guyue Zhou.</li>
      <li><span class="venue-tag">ICCV 2023</span> <a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Yan_INT2_Interactive_Trajectory_Prediction_at_Intersections_ICCV_2023_paper.pdf">INT2: Interactive Trajectory Prediction at Intersections</a>. Zhijie Yan, <span class="me">Pengfei Li</span>, Zheng Fu, Shaocong Xu, Yongliang Shi, Xiaoxue Chen, Yuhang Zheng, Yang Li, Tianyu Liu, Chuxuan Li, Nairui Luo, Xu Gao, Yilun Chen, Zuoxu Wang, Yifeng Shi, Pengfei Huang, Zhengxiao Han, Jirui Yuan, Jiangtao Gong, Guyue Zhou, Hang Zhao, Hao Zhao.</li>
      <li><span class="venue-tag">ICCV 2023</span> <a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Zhong_3D_Implicit_Transporter_for_Temporally_Consistent_Keypoint_Discovery_ICCV_2023_paper.pdf">3D Implicit Transporter for Temporally Consistent Keypoint Discovery</a>. Chengliang Zhong, Yuhang Zheng, Yupeng Zheng, Hao Zhao, Li Yi, Xiaodong Mu, Ling Wang, <span class="me">Pengfei Li</span>, Guyue Zhou, Chao Yang, Xinliang Zhang, Jian Zhao.</li>
      <li><span class="venue-tag">ICCV 2023</span> <a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Gao_DQS3D_Densely-matched_Quantization-aware_Semi-supervised_3D_Detection_ICCV_2023_paper.pdf">DQS3D: Densely-matched Quantization-aware Semi-supervised 3D Detection</a>. Huan-ang Gao, Beiwen Tian, <span class="me">Pengfei Li</span>, Hao Zhao, Guyue Zhou.</li>
      <li><span class="venue-tag">ICRA 2023</span> <a href="https://ieeexplore.ieee.org/document/10160326">ADAPT: Action-aware Driving Caption Transformer</a>. Bu Jin, Xinyu Liu, Yupeng Zheng, <span class="me">Pengfei Li</span>, Hao Zhao, Tong Zhang, Yuhang Zheng, Guyue Zhou, Jingjing Liu.</li>
      <li><span class="venue-tag">ICRA 2023</span> <a href="https://ieeexplore.ieee.org/document/10160708">STEPS: Joint Self-supervised Nighttime Image Enhancement and Depth Estimation</a>. Yupeng Zheng, Chengliang Zhong, <span class="me">Pengfei Li</span>, Huan-ang Gao, Yuhang Zheng, Bu Jin, Ling Wang, Hao Zhao, Guyue Zhou, Qichao Zhang, Dongbin Zhao.</li>
      <li><span class="venue-tag">ICRA 2023</span> <a href="https://ieeexplore.ieee.org/document/10161273">From Semi-supervised to Omni-supervised Room Layout Estimation Using Point Clouds</a>. Huan-ang Gao, Beiwen Tian, <span class="me">Pengfei Li</span>, Xiaoxue Chen, Hao Zhao, Guyue Zhou, Yurong Chen, Hongbin Zha.</li>
      <li><span class="venue-tag">ICRA 2023</span> <a href="https://ieeexplore.ieee.org/document/10161570">LATITUDE: Robotic Global Localization with Truncated Dynamic Low-pass Filter in City-scale NeRF</a>. Zhenxin Zhu, Yuantao Chen, Zirui Wu, Chao Hou, Yongliang Shi, Chuxuan Li, <span class="me">Pengfei Li</span>, Hao Zhao, Guyue Zhou.</li>
      <li><span class="venue-tag">ICRA 2023</span> <a href="https://ieeexplore.ieee.org/document/10160470">Unsupervised Road Anomaly Detection with Language Anchors</a>. Beiwen Tian, Mingdao Liu, Huan-ang Gao, <span class="me">Pengfei Li</span>, Hao Zhao, Guyue Zhou.</li>
      <li><span class="venue-tag">CICAI 2023</span> <a href="https://link.springer.com/chapter/10.1007/978-981-99-9119-8_16">M2Sim: A Long-Term Interactive Driving Simulator</a>. Zhengxiao Han, Zhijie Yan, Yang Li, <span class="me">Pengfei Li</span>, Yifeng Shi, Nairui Luo, Xu Gao, Yongliang Shi, Pengfei Huang, Jiangtao Gong, Guyue Zhou, Yilun Chen, Hang Zhao, Hao Zhao.</li>
      <li><span class="venue-tag">CICAI 2023</span> <a href="https://link.springer.com/chapter/10.1007/978-981-99-9119-8_17">Long-Term Interactive Driving Simulation: MPC to the Rescue</a>. Zhengxiao Han, Zhijie Yan, Yang Li, <span class="me">Pengfei Li</span>, Yifeng Shi, Nairui Luo, Xu Gao, Yongliang Shi, Pengfei Huang, Jiangtao Gong, Guyue Zhou, Yilun Chen, Hang Zhao, Hao Zhao.</li>
    </ul>
    <p style="text-align:right;margin-top:0.6em;"><a href="https://scholar.google.com/citations?user=hmii_L8AAAAJ">→ See full list on Google Scholar</a></p>
  </div>
</details>
</section>

<section id="awards">
<h1>Awards &amp; Honors</h1>

<ul class="simple-list">
  <li><span class="when">2023</span>1st Place — <a href="https://lcas.lincoln.ac.uk/wp/events/the-pub-r-competition/">ICRA 2023 PUB.R Competition</a> (Preparation and Dish-Up of an English Breakfast with Robots).</li>
  <li><span class="when">2021</span>National Scholarship (Undergraduate, Top 1%).</li>
  <li><span class="when">2020</span>National Scholarship (Undergraduate, Top 1%).</li>
</ul>
</section>

<section id="education">
<h1>Education</h1>

<ul class="simple-list">
  <li><span class="when">2022 – Present</span>Ph.D. Student, Institute for AI Industry Research (AIR), Tsinghua University.</li>
  <li><span class="when">2018 – 2022</span>B.S., School of Computer Science and Technology, University of Chinese Academy of Sciences. <em>GPA 3.94 / 4.00, Rank 1 / 104.</em></li>
</ul>
</section>

<div style="display:flex;justify-content:center;align-items:center;margin-top:3em;opacity:0.9;">
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?w=166&d=G22ZMDy2KEs5OGq6rS0JucNzUxHn13B0tIPWaEGNGJo"></script>
</div>
