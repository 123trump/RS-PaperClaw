# Daily Reports

最近三天日报（最新在前）：

# [20261105](./202611/20261105.md)
## 📌 今日概况

今日共检索候选论文 14 篇；关键词+LLM 智能匹配遥感交叉论文 6 篇；最终纳入日报 6 篇。

今日研究覆盖天气系统检测、树种组成制图、开放词汇分割、地基模型基准、跨视角三维重建与空间物理边界检测。趋势上，多模态数据融合与基础模型适配成为主流，如结合卫星与再分析数据、航空影像与激光扫描；同时，针对高分辨率影像的基准评测与开放词汇分割数据集建设受到关注，显示社区对模型泛化与可迁移性的重视。

## ✨ 今日亮点

- 再分析数据对卫星天气锋检测的增益被系统评估，强调多源融合价值。
- 瑞士全国树种组成制图融合高分辨率航空影像与多模态数据，展示大尺度应用。
- TerraMesh-Masks发布开放词汇分割基准，推动对地观测分割的泛化评测。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261105] Detecting Weather Fronts from Satellite Observations: What Does Reanalysis Add? | Dravilas Ioannis, Stoicescu Miruna, Tervo Roope, Horn Carlos, Oriol Hinojo Comellas, Montazeri Sina, Meraner Andrea, Lucic Ana | University of Amsterdam | 对比卫星观测与再分析数据在天气锋检测中的表现，量化再分析信息的附加价值。 | [#51](https://github.com/123trump/RS-PaperClaw/issues/51) |
| [20261105] National-scale mapping of tree species composition in Switzerland from high-resolution aerial imagery and multimodal data | Zhou Yixin, Ferrari Luca, Verena C. Griess, Rehush Nataliia, Schindler Konrad, Beloiu Mirela | ETH Swiss Geo Lab；Ecosystem Ecology Group, Swiss Federal Research Institute WSL | 利用高分辨率航空影像与多模态数据实现瑞士全国树种组成制图。 | [#52](https://github.com/123trump/RS-PaperClaw/issues/52) |
| [20261105] TerraMesh-Masks: Open-Vocabulary Segmentation for Earth Observation | Blumenstiel Benedikt, Devimeux Hugues, Jakubik Johannes, Schindler Konrad | IBM Research | 提出TerraMesh-Masks开放词汇分割数据集与基准，面向对地观测场景。 | [#53](https://github.com/123trump/RS-PaperClaw/issues/53) |
| [20261105] When GeoFMs Meet VHR: Benchmarking Foundation Models on Very High Resolution Earth Observation Imagery | Kshitij Raj Sharma, Adorni Pierre, Pham Minh-Tan, Tiede Dirk, Lefèvre Sébastien | Universit\'e Bretagne Sud, IRISA, France；University of Salzburg, Department of Geoinformatics, Austria；UiT The Arctic University of Norway, Troms, Norway | 系统评测地理空间基础模型在甚高分辨率对地观测影像上的迁移性能。 | [#54](https://github.com/123trump/RS-PaperClaw/issues/54) |
| [20261105] Georeferenced Cross-View 3D Reconstruction from Ground and Satellite Images | David G. Shatwell, Shah Mubarak | Institute of Artificial Intelligence, University of Central Florida；only the local scene geometry, but also localizing every camera center and 3 D | 融合地面与卫星影像实现带地理参考的跨视角三维重建与相机定位。 | [#55](https://github.com/123trump/RS-PaperClaw/issues/55) |
| [20261105] MP-DualNet: A Dual-Branch Deep Learning Approach for Magnetopause Boundary Detection Using Simulated SXI Images | Zhong Cheng, Yang Zhongwei, Sun Tianran, Huang Chengyan, Liu Jiajia, Guo Jingnan, Wang Yuming, Wang Chi | National Key Laboratory of Deep Space Exploration/School of Earth and Space Sciences, University of；State Key Laboratory of Solar Activity and Space Weather, National Space Science Center, Chinese；Academy of Sciences, Beijing 100190, China；CAS Center for Excellence in Comparative Planetology/CAS Key Laboratory of Geospace；Environment/Mengcheng National Geophysical Observatory, University of Science and Technology of | 设计双分支网络从模拟SXI图像中检测磁层顶边界，服务空间天气监测。 | [#56](https://github.com/123trump/RS-PaperClaw/issues/56) |

## 🔎 观察

- 基础模型评测从通用场景转向甚高分辨率对地观测，暴露出预训练迁移在细节任务上的适配需求。
- 多模态融合成为提升遥感任务精度的共性路径，但数据对齐与模态缺失鲁棒性仍是待解问题。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261105", "source": "oai", "checked_at": "2026-11-06T12:50:09+00:00", "source_complete": true, "candidate_count": 14, "paper_count": 6} -->

---

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
