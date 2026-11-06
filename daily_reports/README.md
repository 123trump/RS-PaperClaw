# Daily Reports

最近三天日报（最新在前）：

# [20261104](./202611/20261104.md)
## 📌 今日概况

今日共检索候选论文 14 篇；关键词+LLM 智能匹配遥感交叉论文 5 篇；最终纳入日报 5 篇。

今日论文总体呈现出遥感与AI交叉深化趋势。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261104] Benchmarking Fine-Grained Visual Reasoning for Remote Sensing in Urban Management | Zhang Jiawei, Cai Rizhao, Guan Dayan | School of Electronics and Information Engineering, Harbin Institute of Technology | 聚焦Remote Sensing、Fine-Grained Visual Reasoning，给出可复现的模型与评测方案。 | [#45](https://github.com/123trump/RS-PaperClaw/issues/45) |
| [20261104] TOP: Transmission-Oriented Remote Sensing Pansharpening | Cao Zi-Han, Liang Jing-Ze, Wu Shao-Jie, Di Jin-Cheng, Deng Liang-Jian, Vivone Gemine | University of Electronic Science and Technology of China, Chengdu, Sichuan, China (；University of Electronic Science and Technology of China, Chengdu, Sichuan, China；the Multi-Hazard Early Warning Key Laboratory of Sichuan Province, Chengdu, Sichuan, China (；the National Research Council of Italy, Institute of Integrated Methodologies for Earth Observation (CNR-IMIOT), Tito, Italy ( | 聚焦Remote Sensing、Pansharpening，给出可复现的模型与评测方案。 | [#46](https://github.com/123trump/RS-PaperClaw/issues/46) |
| [20261104] CAPE-JEPA - Cross-modal Adversarial Probabilistic Embedding JEPA | Junghare Aniket, Banerjee Biplab | Biplab Banerjee；Indian Institute of Technology Bombay | 聚焦Remote Sensing、Cross-Modal Retrieval，给出可复现的模型与评测方案。 | [#47](https://github.com/123trump/RS-PaperClaw/issues/47) |
| [20261104] Generative AI for urban planning: synthesizing land-use maps with satellite imagery via DualControlNet | Song Qingqi, Chen Yuzhou, Hu Lingqian, Wang Shenhao | Department of Urban and Regional Planning, University of Florida；College of Architecture, Texas A&M University | 聚焦Satellite Imagery、Generative AI，给出可复现的模型与评测方案。 | [#48](https://github.com/123trump/RS-PaperClaw/issues/48) |
| [20261104] ReTailor: A Residual Feature Tailoring Framework for Real-Time Cross-Sensor Pansharpening Adaptation | Liang Jing-Ze, Xiao Wei-Jie, Cao Zi-Han, Li Yang-Dong, Hu Tian-Yi, Deng Liang-Jian | University of Electronic Science and Technology of China；Multi-Hazard Early Warning Key Laboratory of Sichuan Province | 聚焦Self-Supervised Learning、Pansharpening，给出可复现的模型与评测方案。 | [#49](https://github.com/123trump/RS-PaperClaw/issues/49) |

## 🔎 观察

- 基础模型与遥感任务结合持续增强，评测与推理能力成为关键。
- 多数工作关注算法有效性与泛化，而非硬件实现。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261104", "source": "oai", "checked_at": "2026-11-06T12:42:07+00:00", "source_complete": true, "candidate_count": 14, "paper_count": 5} -->

---

# [20261103](./202611/20261103.md)
## 📌 今日概况

今日共检索候选论文 23 篇；关键词+LLM 智能匹配遥感交叉论文 6 篇；最终纳入日报 6 篇。

今日研究呈现多模态融合与任务专用化趋势。遥感问答引入图推理增强时空约束理解；在线高精地图构建利用卫星先验提升鲁棒性；土地覆盖与光伏制图分别探索时序机器学习与免训练视觉基础模型；洪水预测融合地球观测嵌入与气象强迫；热带作物分割发布新基准。整体体现从通用模型向领域适配与数据高效方向演进。

## ✨ 今日亮点

- 遥感问答采用观测支持图推理，强化时空关系与关系条件定位。
- 在线高精地图构建重铸卫星先验，提升传感器冗余下的鲁棒性。
- 免训练光伏制图与热带作物分割基准，推动数据高效与区域适配。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261103] OSGR: Observation-Support Graph Reasoning for Earth Observation Question Answering | Yu Dazhou, Wang Zerong, Bao Riyang, Li Longxiang, Liu Yang, Zhao Liang | Emory University；Georgia State University | 提出观测支持图推理框架，用于地球观测问答中的时空约束与关系条件定位。 | [#36](https://github.com/123trump/RS-PaperClaw/issues/36) |
| [20261103] ReSMap: Recasting Satellite Priors for Robust and Accurate Online HD Map Construction | Kim Kyungmin, Lee Sumin, Jeong Sungoh, Lim DoHyun, Park Seonghyun, Hwang Soonmin | Department of Automotive Engineering (Automotive-Computer Convergence)；Department of Computer Science；Department of Electrical Engineering；Department of Automotive Engineering；Hanyang University, Seoul, South Korea | 将卫星先验重铸为在线高精地图构建的鲁棒融合线索，提升感知冗余与精度。 | [#37](https://github.com/123trump/RS-PaperClaw/issues/37) |
| [20261103] Using GeoAI and machine learning tools for consistent high-resolution land cover mapping based on time-series NAIP imagery | Liu Jie, Tang Xusheng, Wang Chao, Yan Zhengxiao, Dai Yuchen, Zhang Qi, Song Conghe | Department of Geography and Environment, University；Department of City and Regional Planning, University；Department of Geography, Hong Kong Baptist University；Department of Earth, Marine and Environmental Sciences；University of North Carolina at Chapel Hill, Chapel Hill | 结合GeoAI与机器学习，基于时序NAIP影像实现一致的高分辨率土地覆盖制图。 | [#38](https://github.com/123trump/RS-PaperClaw/issues/38) |
| [20261103] High-fidelity training-free photovoltaic module mapping from multi-view UAV imagery | Duana WenHao, Chena Qi, Zhang Penglei, Deng Ruizhe, Guo Zhiling, Zhang Haoran, Chen Yuntian | School of Geography and Information Engineering, China University of Geosciences；Ningbo Institute of Digital Twin, Eastern Institute of；Zhejiang Key Laboratory of Industrial Intelligence and Digital Twin, Eastern Institute of；Department of Building Environment and Energy Engineering, The Hong Kong；Polytechnic University, Kowloon, Hong Kong, China；School of Urban Planning and Design, Peking University, Shenzhen, 518055, China | 利用多视角无人机影像与视觉基础模型，实现免训练的高保真光伏组件制图。 | [#39](https://github.com/123trump/RS-PaperClaw/issues/39) |
| [20261103] Fusing Earth observation embeddings and spaceborne terrain with meteorological forcing for flood peak depth prediction from high-water marks | Zhou Wen, Wang Shaowen, Lall Upmanu, Merwade Venkatesh, Ye Dingqi | Department of Geography and Geographic Information Science；CyberGIS Center for Advanced Digital and Spatial Studies, and；Siebel School of Computing and Data Science；University of Illinois Urbana--Champaign, Urbana, IL, USA；School of Complex Adaptive Systems, College of Global Futures；Arizona State University, Tempe, AZ, USA；Lyles School of Civil and Construction Engineering；Purdue University, West Lafayette, IN, USA | 融合地球观测嵌入、星载地形与气象强迫，由高水位标记预测洪峰深度。 | [#40](https://github.com/123trump/RS-PaperClaw/issues/40) |
| [20261103] PLANTEUR: A Crop-Type Segmentation Benchmark for Tropical Regions | Wolters Piper, Tseng Gabriel, Bastani Favyen, Redmon Joseph, Zhang Yawen, Sablon Hadrien, Shah Ando | Allen Institute for AI | 发布PLANTEUR基准，面向热带地区基于Sentinel-2的作物类型分割评估。 | [#41](https://github.com/123trump/RS-PaperClaw/issues/41) |

## 🔎 观察

- 遥感任务正从通用大模型转向领域专用推理与融合，图推理和卫星先验成为提升鲁棒性的关键。
- 免训练框架与区域基准并行发展，反映对数据高效和热带等欠代表区域适配的迫切需求。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261103", "source": "oai", "checked_at": "2026-11-04T07:41:45+00:00", "source_complete": true, "candidate_count": 23, "paper_count": 6} -->

---

# [20261102](./202611/20261102.md)
## 📌 今日概况

今日共检索候选论文 26 篇；关键词+LLM 智能匹配遥感交叉论文 10 篇；最终纳入日报 10 篇。

今日论文聚焦多源遥感分类与跨模态融合，多篇工作围绕特征协同与频域注意力展开；视觉-语言模型向地球观测决策与地理文本定位延伸，强调工具增强与校准；测试时训练、扩散模型及类增量学习被用于高光谱分类、水下图像恢复与语义变化检测，域泛化与低层融合-高层理解衔接亦受关注。

## ✨ 今日亮点

- 多源遥感分类密集出现，共享模式与跨层频域融合成为主流思路。
- 视觉-语言模型向地球观测决策与阿拉伯地理文本定位拓展。
- 测试时训练与扩散模型分别用于高光谱分类和水下图像恢复。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261102] Spectral-spatial vision test-time training for hyperspectral image classification | Zhao Xiang | College of Mathematical Sciences, Harbin Engineering University | 提出光谱-空间视觉测试时训练方法，用于高光谱图像分类。 | [#25](https://github.com/123trump/RS-PaperClaw/issues/25) |
| [20261102] Performance evaluation of super-resolution techniques for characterization and phenotyping of commodity crops using multispectral imagery | Karukayil Abhiram, João F. C. Mota, Vásquez-Guevara Mateo, Arevalo-Ramirez Tito, Fernando Auat Cheein | School of Engineering and Physical Sciences, Heriot-Watt University, Edinburgh, UK；Department of Electrical Engineering, Department of Mechanical Engineering and Metallurgy, School of Engineering, Faculty of；School of Mathematical and Computer Sciences, Heriot-Watt University, Edinburgh, UK；Harper Adams University, England, UK | 评估超分辨率技术对多光谱作物表型表征的性能影响。 | [#26](https://github.com/123trump/RS-PaperClaw/issues/26) |
| [20261102] Bridging Low-Level Image Fusion and High-Level Semantic Understanding | Dong Guangyuan, Shen Lingdong, Zhang Xudong, Jing Haodong, Wang Haoyu, Li Zihao, Ying Zonghao, Song Ziyu, Liu Shenghao, Luo Jiachen, Zhang Hao | Peking University；Xi'an Jiaotong University；Nankai University；Institute of Automation, Chinese Academy of Sciences | 衔接低层图像融合与高层语义理解，引入视觉-语言模型。 | [#27](https://github.com/123trump/RS-PaperClaw/issues/27) |
| [20261102] Shared-Pattern Collaborative Network for Multi-Source Remote Sensing Data Classification | Yang Chenfang, Gong Chuanzheng, Gao Feng, Dong Junyu, Du Qian | State Key Laboratory of Physical Oceanography, Ocean University of China, Qingdao, China. (；Department of Electrical and Computer Engineering, Mississippi State University, Starkville, MS USA | 构建共享模式协同网络，实现多源遥感数据分类。 | [#28](https://github.com/123trump/RS-PaperClaw/issues/28) |
| [20261102] Cross-Layer Refinement and Frequency-aware Fusion Network for Multi-Source Remote Sensing Image Classification | Xiao Wenhan, Gong Chuanzheng, Gao Feng, Dong Junyu, Du Qian | State Key Laboratory of Physical Oceanography, Ocean University of China, Qingdao, China；Department of Electrical and Computer Engineering, Mississippi State University, Starkville, MS USA. and elevation information [4] | 提出跨层细化与频率感知融合网络用于多源遥感分类。 | [#29](https://github.com/123trump/RS-PaperClaw/issues/29) |
| [20261102] KAUSTics-Net: Diffusion-Based Through-Water UAV Restoration with a Semi-Synthetic Dataset | Scilla Dario, Omar A. Lopez, Johansen Kasper, Brian O. Nieuwenhuis, Matthew F. McCabe | and Livability Initiative, King Abdullah University of Science and Technology；Red Sea Research Center, Biological and Environmental Science and；Engineering Division, King Abdullah University of Science and Technology | 基于扩散模型与半合成数据集恢复穿水无人机图像。 | [#30](https://github.com/123trump/RS-PaperClaw/issues/30) |
| [20261102] HyperFlow: Class-Incremental Semantic Change Detection via Hyperbolic Flow | Béchaz Manon, Buecher Léo, Dalsasso Emanuele, Tomoiaga Ciprian, Jayet Patrick, Detyniecki Marcin, Chapel Laetitia, Drumetz Lucas, Courty Nicolas, Tuia Devis | University of the Witwatersrand；Université de Bretagne Sud, France；Institut Agro Rennes-Angers, France；Lab-STICC | 利用双曲流实现类增量语义变化检测。 | [#31](https://github.com/123trump/RS-PaperClaw/issues/31) |
| [20261102] ArabGeoText: Tool-Augmented Vision-Language Models for Arabic Geospatial Text Spotting | Bazi Yakoub, Alsaleh Sarah, Mohamad M. Al Rahhal, Mohamed A. Mekhtiche, Zuair Mansour | the Computer Engineering Department, College of Computer and Information Sciences, King Saud University, Riyadh, Saudi Arabia (；the Applied Computer Science Department, College of Applied Computer Science, King Saud University, Riyadh, Saudi Arabia ( | 构建工具增强视觉-语言模型用于阿拉伯地理文本定位。 | [#32](https://github.com/123trump/RS-PaperClaw/issues/32) |
| [20261102] EO-Jev: Decision Model for Earth Observation | Mohamed Atef Abouelhadid, Diaa Addeen Abuhani, Muhammad Akhtar Munir, Fahad Shahbaz Khan, Khan Salman | Mohamed Bin Zayed University of Artificial Intelligence；Massachusetts Institute of Technology；Australian National University；Linköping University Sweden | 提出面向地球观测的决策模型，关注校准与低秩微调。 | [#33](https://github.com/123trump/RS-PaperClaw/issues/33) |
| [20261102] ASCoR: Asymmetric Semantic-Spatial Learning for Remote Sensing Domain Generalization | Wang Zitong, Lyu Shuchang, Li Meng, Wang Qiang, Cheng Guangliang, Shi Zhenwei | Beihang University；University of Science and Technology Beijing；University of Liverpool；Guangdong Electronic Information Engineering Research Institute, University of Electronic Science and Technology of China | 采用非对称语义-空间学习提升遥感域泛化分割性能。 | [#34](https://github.com/123trump/RS-PaperClaw/issues/34) |

## 🔎 观察

- 多源融合研究从简单拼接转向共享模式与频域协同，强调跨模态特征对齐。
- 视觉-语言模型在遥感中从描述生成走向决策与文本定位，工具增强成新方向。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261102", "source": "oai", "checked_at": "2026-11-04T07:35:09+00:00", "source_complete": true, "candidate_count": 26, "paper_count": 10} -->

---
