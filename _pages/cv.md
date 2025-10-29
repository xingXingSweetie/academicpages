---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育经历
======

北京大学，深圳研究生院 — 智慧城市与大数据方向（研二在读）

2024.08 — 2027.05（在读）

研究方向：城市规划大模型，MLLM Benchmark

华东师范大学，地理科学学院 — 地理信息科学（学士）

2020.09 — 2024.06

GPA 3.81/4.00（排名 1/26），获申万宏源奖学金及校特等奖学金

加州大学伯克利分校，Department of City and Regional Planning（交换）

2022.08 — 2022.12

课程：Data Science for Human Mobility and Socio-Technical Systems（成绩 A+）

科研经历
======

PlanGPT-VL: Enhancing Urban Planning with Domain-Specific Vision-Language Models

2024.12 — 2025.05

共同第一作者（EMNLP 2025 Industry Track） — https://arxiv.org/abs/2505.14481

• 负责 VLM 训练数据收集，协助开发人员测试（测试通道：https://modelscope.cn/studios/chichi56/PlanGPT-VL/summary）
• 建立国土空间规划图的 Benchmark，以评估 MLLMs 在规划图理解方面的能力（https://behavioral-spatial-ai-lab.github.io/planvlm-bench/）

短视频驱动下的上海市城市意象感知

2023.09 — 2024.05

• 利用 Python 爬虫及浏览器插件进行视频批量采集，抽帧并格式化整理视频与图像数据库
• 基于 U-Net 进行语义分割识别，使用 SlowFast 框架做人物动作识别
• 提取视频地理位置信息；对于缺少签到地点的视频，采用文本地点提取、人工解译或视频理解方法

Mapping public opinion dynamics on Weibo: a case study on epidemic prevention policy discussion

2022.10 — 2023.05

第一作者；指导老师：Marta Gonzalez（UC Berkeley） — CUPUM 会议论文

• 爬取 2022 年 10–12 月与防疫政策相关的微博与发布者信息，构建以政策出台为时间点的时序网络，研究信息茧房与负面情绪传播
• 使用核密度分析探究用户社群的地理相关性
• 利用 SnowNLP 对预处理文本做情感分析与观点提取，计算高影响力用户的情感支持度及热门话题的情绪距离/争议度

项目与实习经历
======

LandRover 市场区域网络规划与未来零售设计 WebGIS 项目（Boston Consulting Group 校企合作）

2021.03 — 2021.06

• 基于客户提供的捷豹路虎经销商 POI 与销量数据，重新划分大中华市场分区并诊断门店分布热点，支持关店/选址决策
• 负责前端开发（CSS 设计、API 调用等）

上海纽约大学 Mapping Global China 项目（线上兼职研究助理）

2023.08 — 2024.05

• 负责地理数据采集、整理与数据库维护；与前后端负责人对接，制作在线与静态地图（https://mapglobalchina.com/team/）

上海人工智能实验室 — AI 数据产品经理实习生

2025.07 — 至今

• 大模型工作流产品原型设计（MinerU）：梳理数据筛选、标注、训练、评测、上线全流程，绘制系统原型图，优化模型迭代效率与可视化体验
• 图书/论文/教材 PDF 元数据提取 benchmark 质检：调研工具与数据集、制定质检标准并执行样本审查
• 内部数据产品建设（星河图书馆）：参与数据结构设计、EDA 撰写、需求评审与供应商采购
• Extract Agent 产品研究：总结技术壁垒、开发者生态、产品成熟度与商业化落地，撰写 PRD
• 参与 AI-ready Common Crawl 数据集发布（网页 vibe coding 与 logo 设计），推动数据集上线

其他信息
======

学生工作：华东师范大学学生会 学术发展中心 负责人

证书：IELTS 7.0；CET-4（669）；CET-6（637）；Python 程序设计（二级）优秀

竞赛：2022 美国大学生数学建模竞赛 Honorable Mention；2023 上海市计算机应用能力大赛 三等奖

技能：
• 地理信息类：ArcGIS、ENVI、QGIS
• 数据与数据库：SQL
• 可视化与图像处理：Photoshop、Excel（lookup、pivot table）
• 编程：Python、JavaScript、C#

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
