---
layout: archive
title: "简历"
permalink: /cv_chinese/
author_profile: true
redirect_from:
  - /resume_chinese
---

{% include base_path %}

[PDF简历](https://jurengithub.github.io/cv_ljr_latex.pdf)
<div align="center">
<font size="5"> 李举仁</font>
</div>

- 邮箱: jrlee{at}zju{dot}edu{dot}cn
- 地址: 杭州市，浙江大学玉泉校区 

## 教育背景
* ​**计算机技术**, **博士**, 浙江大学, 2021–至今  
  * 导师: [杨洋教授](http://yangy.org)  
* ​**计算机科学与技术**, **学士**, 浙江大学, 2017–2021  
* ​**重庆育才中学**, 2014–2017  


## 研究方向
数据挖掘，时间序列分析，机器学习

## 项目经历
**序列数据的泛化性研究**，研究主线: *从领域内泛化到跨域泛化，最终构建垂直领域基础模型，实现序列数据的多对多泛化*。

- **基于同源相似性的染色体结构异常诊断方法** (2021.6-2022.4，杭州德适生物科技有限公司)
  -  提出基于同源相似性的自监督预训练框架HomNet，利用正常染色体构造人工异常样本，通过对比学习捕捉染色体结构异常的共性特征；
  -  在4家医院的真实临床数据集上微调模型，实现跨机构泛；算法通过三期临床试验验证

- **时间序列分类中的域与通用表示解耦方法**
  - 提出解耦域相关与域无关表示的CADT框架，结合类级超球体损失提升分类器判别能力，显著增强跨域分类任务的泛化性。

- **标签偏移下的时间序列域自适应** (2022.4-2023.12，华为)
  - 针对时序域自适应的标签偏移问题，提出可学习二次赋权方法，结合时域与频域对齐策略，显著提升模型鲁棒性。
  - 在工业场景中，显著提升异常检测(误报率降低10倍）与安全预警（精确度提升7%)任务性能

- **锂离子电池基础模型研究** (2024.1-2025.2，华为)
  - 提出首个面向锂离子电池的物理规律驱动基础模型LiPM，设计混合尺度时间编码器处理不规则采样序列，实现跨电池类型、跨采样协议的泛化性。

- **结合历史信息的锂电池建模** (2025.3-至今)
  - 融合物理原理构建锂离子电池通用建模框架，结合历史信息提取锂离子电池衰老特征，从而帮助下游任务获得更好性能。

## 论文情况

* ​**李举仁**, 杨洋, 陈友民, 张建锋, 赖泽宇, 潘璐佳. ​**DWLR: 面向可穿戴设备的标签偏移域适应方法**. 第33届国际人工智能联合会议 ([IJCAI'24](https://ijcai24.org/)), 2024, **CCF-A**. 
  [![论文PDF](https://img.shields.io/badge/论文-PDF-red)](https://www.ijcai.org/proceedings/2024/489) 
  [![推文](https://img.shields.io/badge/推文-中文-green)](https://mp.weixin.qq.com/s/8OtVcMLxWYC4eGMOb8-T3w)
  [![代码](https://img.shields.io/badge/代码-Github-black)](https://github.com/JuRenGithub/DWLR)  

* ​**李举仁**, 傅凡哲, 韦然, 孙逸飞, 赖泽宇, 宋宁, 陈信, 杨洋. ​**基于同源相似性的染色体结构异常诊断方法**. 第30届ACM SIGKDD知识发现与数据挖掘会议 ([KDD'24](https://kdd2024.kdd.org/)), 2024, **CCF-A**. 
  [![论文PDF](https://img.shields.io/badge/论文-PDF-red)](https://dl.acm.org/doi/10.1145/3637528.3671642) 
  [![视频](https://img.shields.io/badge/视频-Bilibili-pink)](https://www.bilibili.com/video/BV1JE421w7xq/?share_source=copy_web&vd_source=be23edf0a59711d53a8b7b6fabdf23fb) 
  [![视频](https://img.shields.io/badge/视频-ACM-FF8C00)](https://files.atypon.com/acm/0a1fb334f4d07744950577ba288726af) 
  [![推文](https://img.shields.io/badge/推文-中文-green)](https://mp.weixin.qq.com/s/tPk0RMm0NUd4WHC2RjFvtQ) 
  [![代码](https://img.shields.io/badge/代码-Github-black)](https://github.com/JuRenGithub/HomNet)  

* 陈友民, 严欣宇, 杨洋, 张建锋, 张静, 潘璐佳, ​**李举仁**. ​**时间序列分类中的域与通用表示解耦方法**. 第33届国际人工智能联合会议 ([IJCAI'24](https://ijcaai24.org/)), 2024, **CCF-A**.  
  [![论文PDF](https://img.shields.io/badge/论文-PDF-red)](https://www.ijcai.org/proceedings/2024/424) 
  [![推文](https://img.shields.io/badge/推文-中文-green)](https://mp.weixin.qq.com/s/8OtVcMLxWYC4eGMOb8-T3w) 
  [![代码](https://img.shields.io/badge/代码-Github-black)](https://github.com/IJCAI-CADT/cadt)  

* 黄铉纹, 杨洋, 程自强, 范申, 王中尧, ​**李举仁**, 张军, 陈静敏. ​**兴趣扩散在购买预测中的有效性研究: 以Taocode为例**. 第44届国际信息检索研究与发展会议 (SIGIR'21), 2021, **CCF-A**. 
  [![论文PDF](https://img.shields.io/badge/论文-PDF-red)](https://arxiv.org/pdf/2112.14446)  

## 荣誉与奖项
* **2025**: 杰出审稿人 (Outstanding Reviewers), KDD 2025 (授予前10%的审稿人)
* ​**2024**: 优秀研究生; 五好研究生
* ​**2021**: 优秀毕业生 (本科)  
* ​**2020**: 二等奖学金 (前8%) 
* ​**2019**: 优秀学生; 一等奖学金 (前3%)  
* ​**2018**: 优秀学生; 一等奖学金 (前3%)  

## 学术服务
* ​**科研小组组长**, Noah 小组 (隶属于[AINet](yangy.org)), 2021–至今  
  * 领导7人研究小组与华为合作。  
* **审稿人**
  * 国际知识发现和数据挖掘会议(KDD): 2022, 2025。
  * IEEE Transactions on Big Data (TBD): 2022, 2023。
* ​**系统管理员**, 2021–至今  
  * 负责服务器安全与资源分配。  
* ​**志愿者**, [SMP 2020](https://smp2020.aconf.cn/index.html), 2020年9月  
  * 协助会议组织与参会者协调。  

## 受邀演讲
* ​**2024.08**: 在 [IJCAI 2024](https://ijcai24.org/) 上口头报告论文 ​**DWLR**。  
* ​**2024.08**: 在 [KDD 2024](https://kdd2024.kdd.org/) 上口头报告论文 ​**HomNet**。  
* ​**2024.08**: 作为嘉宾在 [AITIME](https://www.aitime.cn/) 介绍 ​**HomNet**​ 工作。  


## 技能
* ​**编程语言**​  
  * **Python** (PyTorch, NumPy, Pandas)  
  * 具有C、C++ 编程经历
* ​**外语**​    
  * 英语 (CET-6)  