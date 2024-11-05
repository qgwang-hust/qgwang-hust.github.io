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

长期从事高效能可重构计算系统相关研究，从上层算法理论，到中间层编译工具链、再到底层硬件架构，均有深厚的技术基础和经验积累。以第一作者/通讯作者在计算机体系结构领域顶级会议和期刊（MICRO、HPCA、DAC、FPGA、ACM TACO、IEEE TCAD等）上发表论文7篇，其中CCF A类论文6篇，申请国家发明专利5项和美国专利2项，主持国家自然科学基金青年项目、博士后特别资助（站前）/面上、国家重点研发计划青年科学家项目课题、浙江省自然科学基金探索青年项目，参与国家重点研发项目、国家自然科学基金重点项目等的研发工作，部分关键技术应用于国家电网、平安科技、浙江天猫等企业。曾获APPT’21学术会议最佳论文奖、2023年度“国际测试委员会Top 100 Chips Achievement Award”和“全国创新创业优秀博士后”，2021-2022连续两年获得图计算领域最具影响力挑战赛IEEE/MIT/Amazon Graph Challenge全球冠军(2021年国内首次获得)，博士论文入选2023年度“ACM ChinaSys优秀博士论文奖”和2023年度“CCF DAC最佳博士论文海报奖”。担任Frontiers of Computer Science、GPC审稿人。

# 📝 Publications 

- **[HPCA]** Wenju Zhao, Pengcheng Yao, Dan Chen, Long Zheng, Xiaofei Liao, **<ins>Qinggang Wang</ins>**, Shaobo Ma, Yu Li, Haifeng Liu, Wenjing Xiao, Yufei Sun, Bin Zhu, Hai Jin, Jingling Xue. MeHyper: Accelerating Hypergraph Neural Networks by Exploring Implicit Dataflows. In ***Proceedings of the 31st IEEE International Symposium on High-Performance Computer Architecture***, 2025.
- **[MICRO]** **<ins>Qinggang Wang</ins>** Long Zheng, Zhaozeng An, Shuyi Xiong, Runze Wang, Yu Huang, Pengcheng Yao, Xiaofei Liao, Hai Jin, Jingling Xue. A Scalable, Efficient, and Robust Dynamic Memory Management Library for HLS-based FPGAs. In ***Proceedings of the 57th ACM/IEEE International Symposium on Microarchitecture***, 2024.
- **[DAC]** **<ins>Qinggang Wang</ins>**, Long Zheng, Zhaozeng An, Haoqin Huang, Haoran Zhu, Yu Huang, Pengcheng Yao, Xiaofei Liao, Hai Jin. High-Performance and Resource-Efficient Dynamic Memory Management in High-Level Synthesis.  In ***Proceedings of the 61st ACM/IEEE Design Automation Conference***, 2024.
- **[中国计算机学会A类期刊]** **<ins>Qinggang Wang</ins>**, Long Zheng, Ao Hu, Qinggang Wang (Corresponding author), Yu Huang, Haoqin Huang, Pengcheng Yao, Shuyi Xiong, Xiaofei Liao, Hai Jin. PhGraph: A High-Performance ReRAM-Based Accelerator for Hypergraph Applications. In ***IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems***, 2024.
- **[中国计算机学会A类期刊]** Runze Wang, Ao Hu, Long Zheng, **<ins>Qinggang Wang</ins>**, Jingrui Yuan, Haifeng Liu, Linchen Yu, Xiaofei Liao, Hai Jin. An Efficient GCNs Accelerator Using 3D-Stacked Processing-In-Memory Architectures. In ***IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems***, 2024.
- **[ICDE]** Long Zheng, Xiangyu Ye, Haifeng Liu, **<ins>Qinggang Wang</ins>**, Yu Huang, Chuangyi Gui, Pengcheng Yao, Xiaofei Liao, Hai Jin, Jingling Xue. AFaVS: Accurate Yet Fast Version Switching for Graph Processing Systems. In ***Proceedings of the 39th IEEE International Conference on Data Engineering***, 2023.
- **[DAC]** Yu Huang, Long Zheng, Haifeng Liu, Zhuoran Zhou, Dan Chen, Pengcheng Yao, **<ins>Qinggang Wang</ins>**, Xiaofei Liao, Hai Jin. MeG2: In-Memory Acceleration for Genome Graphs Analysis. In ***Proceedings of the 60th ACM/IEEE Design Automation Conference***, 2023.
- **[MICRO]** **<ins>Qinggang Wang</ins>**, Long Zheng, Ao Hu, Yu Huang, Pengcheng Yao, Chuangyi Gui, Xiaofei Liao, Hai Jin, Jingling Xue. A Data-Centric Accelerator for High-Performance Hypergraph Processing.  In ***Proceedings of the 57th ACM/IEEE International Symposium on Microarchitecture***, 2022.
- **[HPCA]** **<ins>Qinggang Wang</ins>**, Long Zheng, Jingrei Yuan, Yu Huang, Pengcheng Yao, Chuangyi Gui, Ao Hu, Xiaofei Liao, Hai Jin. Hardware-Accelerated Hypergraph Processing with Chain-Driven Scheduling.  In ***Proceedings of the 28th IEEE International Symposium on High-Performance Computer Architecture***, 2022.
- **[HPCA]** Pengcheng Yao, Long Zheng, Yu Huang, **<ins>Qinggang Wang</ins>**, Chuangyi Gui, Zheng Zeng, Xiaofei Liao, Hai Jin, Jingling Xue. ScalaGraph: A Scalable Accelerator for Massively Parallel Graph Processing.  In ***Proceedings of the 28th IEEE International Symposium on High-Performance Computer Architecture***, 2022.
- **[HPCA]** Yu Huang, Long Zheng, Pengcheng Yao, **<ins>Qinggang Wang</ins>**, Xiaofei Liao, Hai Jin, Jingling Xue. Accelerating Graph Convolutional Networks Using Crossbar-based Processing-In-Memory Architectures.  In ***Proceedings of the 28th IEEE International Symposium on High-Performance Computer Architecture***, 2022.
- **[中国计算机学会A类期刊]** Yu Huang, Long Zheng, Pengcheng Yao, **<ins>Qinggang Wang</ins>**, Haifeng Liu, Xiaofei Liao, Hai Jin, Jingling Xue. ReaDy: A ReRAM-based Processing-In-Memory Accelerator for Dynamic Graph Convolution Networks.  In ***IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems***, 2022.
- **[IPDPS]** Dan Chen, Hai Jin, Long Zheng, Yu Huang, Pengcheng Yao, Chuangyi Gui, **<ins>Qinggang Wang</ins>**, Haifeng Liu, Haiheng He, Xiaofei Liao, Ran Zheng. A General Offloading Approach for Processing-In-Memory Architectures.  In ***Proceedings of the 36th IEEE International Parallel and Distributed Processing Symposium***, 2022.
- **[HPEC]** Xufei Sun, Long Zheng, **<ins>Qinggang Wang</ins>**, Xiangyu Ye, Yu Huang, Pengcheng Yao, Xiaofei Liao, Hai Jin. Accelerating Sparse Deep Neural Network Inference Using GPU Tensor Cores. In ***Proceedings of the 2022 IEEE High Performance Extreme Computing Conference***, 2022.
- **[FPGA]** **<ins>Qinggang Wang</ins>**, Long Zheng, Yu Huang, Pengcheng Yao, Chuangyi Gui, Xiaofei Liao, Hai Jin, Wenbin Jiang, Fubing Mao. GraSU: A Fast Graph Update Library for FPGA-based Dynamic Graph Processing.  In ***Proceedings of the 2021 ACM/SIGDA International Symposium on Field Programmable Gate Arrays***, 2021.
- **[PACT]**  Chuangyi Gui, Xiaofei Liao, Long Zheng, Pengcheng Yao, **<ins>Qinggang Wang</ins>**, Hai Jin. SumPA: Efficient Pattern-Centric Graph Mining with Pattern Abstraction. In ***Proceedings of the 30th International Conference on Parallel Architectures and Compilation Techniques***, 2021.
- **[APPT]** Yuwei Wu, **<ins>Qinggang Wang</ins>**, Long Zheng, Xiaofei Liao, Hai Jin, Wenbin Jiang, Ran Zheng, Kan Hu. FDGLib: A Communication Library for Efficient Large-Scale Graph Processing in FPGA-Accelerated Data Centers. In ***ournal of Computer Science and Technology***, 2021.
- **[HPEC]** Jie Xin, Xianqi Ye, Long Zheng, **<ins>Qinggang Wang</ins>**, Yu Huang, Pengcheng Yao, Linchen Yu, Xiaofei Liao, Hai Jin. Fast Sparse Deep Neural Network Inference with Flexible SpMM Optimization Space Exploration. In ***Proceedings of the 2022 IEEE High Performance Extreme Computing Conference***, 2021.
- **[HPEC]** Runze Wang, Linchen Yu, **<ins>Qinggang Wang</ins>**, Jie Xin, Long Zheng. Productive High-Performance k-Truss Decomposition on GPU Using Linear Algebra. In: Proceedings of the 2021 IEEE High Performance Extreme Computing Conference  In ***Proceedings of the 2022 IEEE High Performance Extreme Computing Conference***, 2021.
- **[中国计算机学会A类期刊]** **<ins>Qinggang Wang</ins>**, Long Zheng, Jieshan Zhao, Xiaofei Liao, Hai Jin, Jingling Xue. A Conflict-free Scheduler for High-performance Graph Processing on Multi-pipeline FPGAs. In ***ACM Transactions on Architecture and Code Optimization***, 2020.
- **[IPDPS]** Long Zheng, Jieshan Zhao, Yu Huang, **<ins>Qinggang Wang</ins>**, Zhen Zeng, Jingling Xue, Xiaofei Liao, Hai Jin. Spara: An Energy-Efficient ReRAM-Based Accelerator for Sparse Graph Analytics Applications. In: Proceedings of the 2021 IEEE High Performance Extreme Computing Conference  In ***Proceedings of the 34th IEEE International Parallel and Distributed Processing Symposium***, 2020.
- **[CGO]** Long Zheng, Xiaofei Liao, Hai Jin, Jieshan Zhao, **<ins>Qinggang Wang</ins>**. Scalable concurrency debugging with distributed graph processing. In ***Proceedings of the 2018 International Symposium on Code Generation and Optimization***, 2018.

# 🎖 Honors and Awards
- 2023年 “ACM ChinaSys优秀博士论文奖”
- 2023年 “CCF DAC最佳博士论文海报奖”
- 2023年 “全国创新创业优秀博士后”
- 2023年 国际测试委员会Top 100 Chips Achievement Award
- 2023年 第二届全国博士后创新创业大赛金奖
- 2022年 第八届中国国际“互联网+”大学生创新创业大赛产业命题赛道全国金奖
- 2021/2022年 图计算领域最具影响力挑战赛IEEE/MIT/Amazon Graph Challenge全球冠军
- 2021年 国家奖学金、华为奖学金、腾讯奖学金、BIGO奖学金、潍柴动力奖学金
- 2021年 先进并行计算国际会议APPT最佳论文奖

# 📖 Educations
- 2013.9-2017.6，华中农业大学（211），计算机科学与技术（本科）
- 2017.9-2023.3，华中科技大学（985），计算机软件与理论（博士），导师：廖小飞 教授
- 2023.3-至今，之江实验室/华中科技大学，计算机科学与技术（博士后），合作导师：金海 教授/廖小飞 教授

# 💬 Invited Talks
- 2024.09，CCF HPC China 2024 “第六届数值模拟工程应用中的智能超算融合技术论坛”，报告：稀疏高阶图计算加速研究
- 2021.12，CCF APPT 2021，报告：FDGLib: A Communication Library for Efficient Large-Scale Graph Processing in FPGA-Accelerated Data Centers

# 💻 Projects
- **国家自然科学基金青年项目**（主持） 基于异质数据流图的多领域融合计算关键技术研究（No.62402456） 
- **第5批博士后特别资助（站前）** （主持）	重叠性感知的超图计算加速器关键技术研究（No.2023TQ0328）
- **第74批博士后面上资助**（主持）基于数据流的多领域融合计算关键技术研究（No.2023M743256）
- **浙江省自然科学基金探索青年项目**（主持）基于FPGA的超图计算加速器关键技术研究（No.LQ24F020027）
- **国家重点研发计划青年科学家项目** （任务负责人） 多层次融合的软件定义数据流关键技术与系统（No.2023YFB4503400）
- **之江实验室重大科研项目** （课题负责人） 图计算加速器（No.2022PI0AC02）
- **国家重点研发计划项目** （课题骨干） 面向复杂计算场景的图计算机 （No.2023YFB4502300）
- **国家重点研发计划项目** （参与） 面向图计算的通用计算机技术与系统（No.2018YFB1003500）
