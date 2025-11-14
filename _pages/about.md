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

王庆刚，华中科技大学计算机学院副教授，主要从事软硬件协同的高效能图计算系统相关研究，从上层算法理论，到中间层编译工具链、再到底层硬件架构，均有深厚的技术基础和经验积累，在计算机体系结构领域顶级会议和期刊（MICRO、HPCA、SC、DAC、ACM TACO、IEEE TCAD等）上发表论文20余篇，申请国家发明专利5项和美国专利2项，主持国家自然科学基金青年项目、博士后特别资助（站前）/面上、国家重点研发计划青年科学家项目任务、浙江省自然科学基金探索青年项目，参与国家重点研发项目、国家自然科学基金重点项目等的研发工作，部分关键技术应用于国家电网、平安科技、浙江天猫、百度等企业。2023年3月在华中科技大学获得计算机软件与理论博士学位。2021-2022连续两年获得图计算领域最具影响力挑战赛IEEE/MIT/Amazon Graph Challenge全球冠军(2021年国内首次获得)，曾获APPT’21学术会议最佳论文奖、2023年度“国际测试委员会百强芯片成就奖”、“全国创新创业优秀博士后”、第二届全国博士后创新创业大赛金奖和第八届中国国际“互联网+”大学生创新创业大赛产业命题赛道全国金奖。

# 🔥 News
- 2025.11: 🎉🎉 Our paper “Accelerating Out-of-Core Random Walk Processing via Locality-Aware Algorithm-Hardware Co-Design” is accepted by ACM TACO!
- 2025.11: 🎉🎉 Our paper “Adaptive Draft Sequence Length: Enhancing Speculative Decoding Throughput on PIM-Enabled Systems” is accepted by HPCA'26!
- 2025.06: 🎉🎉 Our paper “Diff-MoE: Efficient Batched MoE Inference with Priority-Driven Differential Expert Caching” is accepted by SC 2025!
- 2024.11: 🎉🎉 Our paper “MeHyper: Accelerating Hypergraph Neural Networks by Exploring  Implicit Dataflows” is accepted by HPCA 2025!
- 2024.07: 🎉🎉 Our paper “A Scalable, Efficient, and Robust Dynamic Memory Management Library for HLS-based FPGAs” is accepted by MICRO 2024!

# 📝 Publications 
**{*}** denotes corresponding author
- **[HPCA'26]** Adaptive Draft Sequence Length: Enhancing Speculative Decoding Throughput on PIM-Enabled Systems. ```CCF A```
<br> Runze Wang, **Qinggang Wang***, Haifeng Liu, Long Zheng, Xiaofei Liao, Hai Jin, Jingling Xue. 
<br> In Proceedings of the 32th IEEE International Symposium on High-Performance Computer Architecture, 2026.
- **[TACO'25]** Accelerating Out-of-Core Random Walk Processing via Locality-Aware Algorithm-Hardware Co-Design. ```CCF A```
<br> Huanghai Liu, **Qinggang Wang***, Huize Li, Long Zheng, Liwei Si, Xu Zhao, Xiaofei Liao, Hai Jin, Jingling Xue. 
<br> In ACM Transactions on Architecture and Code Optimization, 2025.
- **[SC'25]** Diff-MoE: Efficient Batched MoE Inference with Priority-Driven Differential Expert Caching. ```CCF A```
<br> Kexin Li, Wenkan Huang, **Qinggang Wang***, Long Zheng, Xiaofei Liao, Hai Jin, Jingling Xue. 
<br> In Proceedings of the International Conference for High Performance Computing, Networking, Storage, and Analysis, 2025.
- **[HPCA'25]** MeHyper: Accelerating Hypergraph Neural Networks by Exploring Implicit Dataflows. ```CCF A```
<br> Wenju Zhao, Pengcheng Yao, Dan Chen, Long Zheng, Xiaofei Liao, **Qinggang Wang**, Shaobo Ma, Yu Li, Haifeng Liu, Wenjing Xiao, Yufei Sun, Bin Zhu, Hai Jin, Jingling Xue.
<br> In Proceedings of the 31st IEEE International Symposium on High-Performance Computer Architecture, 2025.
- **[MICRO'24]** A Scalable, Efficient, and Robust Dynamic Memory Management Library for HLS-based FPGAs. ```CCF A```
<br> **Qinggang Wang**, Long Zheng, Zhaozeng An, Shuyi Xiong, Runze Wang, Yu Huang, Pengcheng Yao, Xiaofei Liao, Hai Jin, Jingling Xue.
<br> In Proceedings of the 57th ACM/IEEE International Symposium on Microarchitecture, 2024.
- **[DAC'24]** High-Performance and Resource-Efficient Dynamic Memory Management in High-Level Synthesis. ```CCF A```
<br> **Qinggang Wang**, Long Zheng, Zhaozeng An, Haoqin Huang, Haoran Zhu, Yu Huang, Pengcheng Yao, Xiaofei Liao, Hai Jin.
<br> In Proceedings of the 61st ACM/IEEE Design Automation Conference, 2024.
- **[TCAD'24]** PhGraph: A High-Performance ReRAM-Based Accelerator for Hypergraph Applications. ```CCF A```
<br> Long Zheng, Ao Hu, **Qinggang Wang***, Yu Huang, Haoqin Huang, Pengcheng Yao, Shuyi Xiong, Xiaofei Liao, Hai Jin.
<br> In IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2024.
- **[TCAD'24]** An Efficient GCNs Accelerator Using 3D-Stacked Processing-In-Memory Architectures. ```CCF A```
<br> Runze Wang, Ao Hu, Long Zheng, **Qinggang Wang**, Jingrui Yuan, Haifeng Liu, Linchen Yu, Xiaofei Liao, Hai Jin.
<br> In IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2024.
- **[ICDE'23]** AFaVS: Accurate Yet Fast Version Switching for Graph Processing Systems. ```CCF A```
<br> Long Zheng, Xiangyu Ye, Haifeng Liu, **Qinggang Wang**, Yu Huang, Chuangyi Gui, Pengcheng Yao, Xiaofei Liao, Hai Jin, Jingling Xue.
<br> In Proceedings of the 39th IEEE International Conference on Data Engineering, 2023.
- **[DAC'23]** MeG2: In-Memory Acceleration for Genome Graphs Analysis. ```CCF A```
<br> Yu Huang, Long Zheng, Haifeng Liu, Zhuoran Zhou, Dan Chen, Pengcheng Yao, **Qinggang Wang**, Xiaofei Liao, Hai Jin.
<br> In Proceedings of the 60th ACM/IEEE Design Automation Conference, 2023.
- **[MICRO'22]** A Data-Centric Accelerator for High-Performance Hypergraph Processing. ```CCF A```
<br> **Qinggang Wang**, Long Zheng, Ao Hu, Yu Huang, Pengcheng Yao, Chuangyi Gui, Xiaofei Liao, Hai Jin, Jingling Xue.
<br> In Proceedings of the 55th ACM/IEEE International Symposium on Microarchitecture, 2022.
- **[HPCA'22]** Hardware-Accelerated Hypergraph Processing with Chain-Driven Scheduling. ```CCF A```
<br> **Qinggang Wang**, Long Zheng, Jingrei Yuan, Yu Huang, Pengcheng Yao, Chuangyi Gui, Ao Hu, Xiaofei Liao, Hai Jin.
<br> In Proceedings of the 28th IEEE International Symposium on High-Performance Computer Architecture, 2022.
- **[HPCA'22]** ScalaGraph: A Scalable Accelerator for Massively Parallel Graph Processing. ```CCF A```
<br> Pengcheng Yao, Long Zheng, Yu Huang, **Qinggang Wang**, Chuangyi Gui, Zheng Zeng, Xiaofei Liao, Hai Jin, Jingling Xue.
<br> In Proceedings of the 28th IEEE International Symposium on High-Performance Computer Architecture, 2022.
- **[HPCA'22]** Accelerating Graph Convolutional Networks Using Crossbar-based Processing-In-Memory Architectures. ```CCF A```
<br> Yu Huang, Long Zheng, Pengcheng Yao, **Qinggang Wang**, Xiaofei Liao, Hai Jin, Jingling Xue.
<br> In Proceedings of the 28th IEEE International Symposium on High-Performance Computer Architecture, 2022.
- **[TCAD'22]** ReaDy: A ReRAM-based Processing-In-Memory Accelerator for Dynamic Graph Convolution Networks. ```CCF A```
<br> Yu Huang, Long Zheng, Pengcheng Yao, **Qinggang Wang**, Haifeng Liu, Xiaofei Liao, Hai Jin, Jingling Xue.
<br> In IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2022.
- **[IPDPS'22]** A General Offloading Approach for Processing-In-Memory Architectures. ```CCF B```
<br> Dan Chen, Hai Jin, Long Zheng, Yu Huang, Pengcheng Yao, Chuangyi Gui, **Qinggang Wang**, Haifeng Liu, Haiheng He, Xiaofei Liao, Ran Zheng.
<br> In Proceedings of the 36th IEEE International Parallel and Distributed Processing Symposium, 2022.
- **[HPEC'22]** Accelerating Sparse Deep Neural Network Inference Using GPU Tensor Cores. ```IEEE/MIT/Amazon Graph Challenge 2022 Champion```
<br> Xufei Sun, Long Zheng, **Qinggang Wang**, Xiangyu Ye, Yu Huang, Pengcheng Yao, Xiaofei Liao, Hai Jin.
<br> In Proceedings of the 2022 IEEE High Performance Extreme Computing Conference, 2022.
- **[FPGA'21]** GraSU: A Fast Graph Update Library for FPGA-based Dynamic Graph Processing. ```CCF B```
<br> **Qinggang Wang**, Long Zheng, Yu Huang, Pengcheng Yao, Chuangyi Gui, Xiaofei Liao, Hai Jin, Wenbin Jiang, Fubing Mao.
<br> In Proceedings of the 2021 ACM/SIGDA International Symposium on Field Programmable Gate Arrays, 2021.
- **[PACT'21]** SumPA: Efficient Pattern-Centric Graph Mining with Pattern Abstraction. ```CCF B```
<br> Chuangyi Gui, Xiaofei Liao, Long Zheng, Pengcheng Yao, **Qinggang Wang**, Hai Jin.
<br> In Proceedings of the 30th International Conference on Parallel Architectures and Compilation Techniques, 2021.
- **[JCST'21]** FDGLib: A Communication Library for Efficient Large-Scale Graph Processing in FPGA-Accelerated Data Centers. APPT 2021 Best Paper Award ```CCF B```
<br> Yuwei Wu, **Qinggang Wang**, Long Zheng, Xiaofei Liao, Hai Jin, Wenbin Jiang, Ran Zheng, Kan Hu.
<br> In Journal of Computer Science and Technology, 2021.
- **[HPEC'21]** Fast Sparse Deep Neural Network Inference with Flexible SpMM Optimization Space Exploration. ```IEEE/MIT/Amazon Graph Challenge 2021 Champion```
<br> Jie Xin, Xianqi Ye, Long Zheng, **Qinggang Wang**, Yu Huang, Pengcheng Yao, Linchen Yu, Xiaofei Liao, Hai Jin.
<br> In Proceedings of the 2021 IEEE High Performance Extreme Computing Conference, 2021.
- **[HPEC'21]** Productive High-Performance k-Truss Decomposition on GPU Using Linear Algebra. ```IEEE/MIT/Amazon Graph Challenge 2021 Innovation Award```
<br> Runze Wang, Linchen Yu, **Qinggang Wang**, Jie Xin, Long Zheng.
<br> In Proceedings of the 2021 IEEE High Performance Extreme Computing Conference, 2021.
- **[TACO'20]** A Conflict-free Scheduler for High-performance Graph Processing on Multi-pipeline FPGAs. ```CCF A```
<br> **Qinggang Wang**, Long Zheng, Jieshan Zhao, Xiaofei Liao, Hai Jin, Jingling Xue.
<br> ACM Transactions on Architecture and Code Optimization, 2020.
- **[IPDPS'20]** Spara: An Energy-Efficient ReRAM-Based Accelerator for Sparse Graph Analytics Applications. ```CCF B```
<br> Long Zheng, Jieshan Zhao, Yu Huang, **Qinggang Wang**, Zhen Zeng, Jingling Xue, Xiaofei Liao, Hai Jin.
<br> In Proceedings of the 34th IEEE International Parallel and Distributed Processing Symposium, 2020.
- **[CGO'18]** Scalable Concurrency Debugging with Distributed Graph Processing. ```CCF B```
<br> Long Zheng, Xiaofei Liao, Hai Jin, Jieshan Zhao, **Qinggang Wang**.
<br> In Proceedings of the 2018 International Symposium on Code Generation and Optimization, 2018.


# 🎖 Honors and Awards
- 2025年 入选“CCF体系结构优秀博士学位论文激励计划”
- 2023年 “ACM ChinaSys优秀博士论文奖”
- 2023年 “CCF DAC最佳博士论文海报奖”
- 2023年 “全国创新创业优秀博士后”
- 2023年 国际测试委员会百强芯片成就奖（Top 100 Chips Achievement Award）
- 2023年 第二届全国博士后创新创业大赛金奖
- 2022年 第八届中国国际“互联网+”大学生创新创业大赛产业命题赛道全国金奖
- 2021/2022年 图计算领域最具影响力挑战赛IEEE/MIT/Amazon Graph Challenge全球冠军
- 2021年 国家奖学金、华为奖学金、腾讯奖学金、BIGO奖学金、潍柴动力奖学金
- 2021年 先进并行计算国际会议APPT最佳论文奖

# 📖 Educations
- 2023.3-2025.3，之江实验室/华中科技大学，计算机科学与技术（博士后），合作导师：金海 教授/廖小飞 教授
- 2017.9-2023.3，华中科技大学（985），计算机软件与理论（博士），导师：廖小飞 教授
- 2013.9-2017.6，华中农业大学（211），计算机科学与技术（本科）

# 💬 Invited Talks
- 2024.09，CCF HPC China 2024 “第六届数值模拟工程应用中的智能超算融合技术论坛”，报告：稀疏高阶图计算加速研究
- 2021.12，CCF APPT 2021，报告：FDGLib: A Communication Library for Efficient Large-Scale Graph Processing in FPGA-Accelerated Data Centers

# 💻 Projects
- **国家自然科学基金青年项目**（主持） 基于异质数据流图的多领域融合计算关键技术研究（No.62402456） 
- **第5批博士后特别资助（站前）**（主持）	重叠性感知的超图计算加速器关键技术研究（No.2023TQ0328）
- **第74批博士后面上资助**（主持）基于数据流的多领域融合计算关键技术研究（No.2023M743256）
- **浙江省自然科学基金探索青年项目**（主持）基于FPGA的超图计算加速器关键技术研究（No.LQ24F020027）
- **国家重点研发计划青年科学家项目**（任务负责人） 多层次融合的软件定义数据流关键技术与系统（No.2023YFB4503400）
- **之江实验室重大科研项目**（课题负责人） 图计算加速器（No.2022PI0AC02）
- **国家重点研发计划项目**（课题骨干） 面向复杂计算场景的图计算机 （No.2023YFB4502300）
- **国家重点研发计划项目**（参与） 面向图计算的通用计算机技术与系统（No.2018YFB1003500）

# 🔖 Patents
- **<ins>王庆刚</ins>**、司礼玮、陈浩宇、易小萌，一种细粒度管理顶点更新的方法及多版本图系统，中国，发明专利，专利号: ZL202510971817.1
- **<ins>王庆刚</ins>**、刘黄海、黄禹、易小萌，一种基于局部性感知的核外图随机游走处理方法及系统，中国，发明专利，专利号: ZL202510098121.2
- **<ins>王庆刚</ins>**、刘黄海、郑龙、黄禹，一种基于异质数据流图的多领域融合执行方法，中国，发明专利，专利号: ZL202510138660.4
- **<ins>王庆刚</ins>**、安昭增、郑龙，一种基于笛卡尔树的高层次综合动态内存管理方法及装置，中国，发明专利，专利号: ZL202411020646.6
- 黄禹、黄浩岩、郑龙、**<ins>王庆刚</ins>**，一种基于数据流的稀疏矩阵运算编程模型，中国，发明专利，专利号: ZL202410841907.4
- 郑龙、**<ins>王庆刚</ins>**、安照增、金海，一种面向高层次综合的动态内存管理装置及方法，中国，发明专利， 申请号: 202210964944.5
- 郑龙、**<ins>王庆刚</ins>**、胡澳、金海，一种面向超图处理的硬件加速器及其运行方法，中国，发明专利，申请号: 202210990115.4
- 廖小飞, 赵杰山, 郑龙, 金海, **<ins>王庆刚</ins>**，一种基于OpenCL的FPGA图处理加速方法和系统，中国，发明专利，专利号: ZL201911029448.5
- Long Zheng, **<ins>Qinggang Wang</ins>**, Xiaofei Liao, Zhaozeng An, Hai Jin. Dynamic Memory Management Apparatus and Method for HLS. 美国, 发明专利, 专利号: US 12,189,950 B2
- Long Zheng, **<ins>Qinggang Wang</ins>**, Xiaofei Liao, Ao Hu, Hai Jin. Hardware Accelerator For Hypergraph Processing and Operating Method Thereof. 美国, 发明专利, 申请号: US 12,339,775 B2
