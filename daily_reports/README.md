# Daily Reports

最近三天日报（最新在前）：

# [20261031](./202610/20261031.md)
## 📌 今日概况

今日共检索候选论文 18 篇；关键词+LLM 智能匹配遥感交叉论文 8 篇；最终纳入日报 8 篇。

今日研究呈现多源遥感数据与AI方法深度融合的趋势，涵盖高光谱、UAV、微波及地球嵌入等数据形式。不确定性量化与采样偏差评估成为提升模型可靠性的关键方向，同时跨视角推理、边缘-云-太空协同推理及城市功能知识迁移拓展了遥感应用边界。数据集构建与基准评估并重，强调实际部署中的性能差距与数据不均问题。

## ✨ 今日亮点

- 高光谱场景预算受限检查引入空间不确定性分析，提升主动学习效率。
- MASSIMAL数据集提供UAV高光谱与地面真值，支撑海岸栖息地制图。
- 作物制图评估揭示采样偏差导致的部署性能差距，提出预测驱动推断。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261031] Spatial Uncertainty Analytics for Budget-Limited Inspection of Hyperspectral Scenes | Sharma Ritesh, Motai Yuichi | RITESH SHARMA, Virginia Commonwealth University, USA；YUICHI MOTAI, Virginia Commonwealth University, USA；Authors’ Contact Information: Ritesh Sharma, Virginia Commonwealth University, Richmond, Virginia, USA | 提出空间不确定性分析方法，用于高光谱场景预算受限检查中的主动学习采样。 | [#12](https://github.com/123trump/RS-PaperClaw/issues/12) |
| [20261031] The MASSIMAL Dataset: UAV Hyperspectral Images and Ground Truth Observations for Coastal Habitat Mapping in Norway | Martin Hansen Skjelvareid, Rinde Eli, Hancke Kasper, Blix Katalin, Galice Guillaume Hoarau, Grometto Nicolo, Maia Røst Kile | ¹ UiT The Arctic University of Norway, Hansine Hansens veg 18；² Norwegian Institute for Water Research (NIVA), Sognsveien 72；³ Nord University, Universitetsalléen 11 | 发布MASSIMAL数据集，包含挪威海岸UAV高光谱影像与地面观测，用于栖息地制图。 | [#13](https://github.com/123trump/RS-PaperClaw/issues/13) |
| [20261031] Crop Mapping Evaluation under Sampling Bias | Zaytar Akram, Ochwang'i Kemunto, Robinson Caleb, Girmaw A. Tadesse, Gilles Q. Hacheme, Dodhia Rahul, Becker-Reshef Inbal, Juan M. Lavista Ferres | Microsoft AI for Good Research Lab；Microsoft Research | 评估采样偏差下作物制图性能，利用预测驱动推断缩小部署性能差距。 | [#14](https://github.com/123trump/RS-PaperClaw/issues/14) |
| [20261031] An all-weather microwave-based AI retrieval of pan-Arctic melt pond fraction | Aparício Sara, Driscoll Simon, Mark R. Drinkwater, Flocco Daniela | CENSE - Center for Environmental and Sustainability Research & CHANGE - Global Change and；Sustainability Institute, NOVA School of Science and Technology, Universidade Nova de Lisboa, Campus de；Department of Applied Mathematics and Theoretical Physics, University of Cambridge, United Kingdom；Dipartimento di Scienze della Terra, dell’Ambiente e delle Risorse, Università degli Studi di Napoli “Federico；CoNISMA - Consorzio Nazionale Interuniversitario per le Scienze del Mare, Roma, Italy | 基于微波遥感和XGBoost实现全天候泛北极融化池比例AI反演。 | [#15](https://github.com/123trump/RS-PaperClaw/issues/15) |
| [20261031] Adaptive Land Units from Earth Embeddings | Alonso Albert, Jamal Jokar Arsanjani, Andres R. Masegosa | Department of Computer Science, Aalborg University, Copenhagen, Denmark；Department of Sustainability and Planning, Aalborg University, Copenhagen, Denmark | 利用地球嵌入和贝叶斯层次聚类构建自适应土地单元，支持无监督土地利用建模。 | [#16](https://github.com/123trump/RS-PaperClaw/issues/16) |
| [20261031] Grounding Across Views: Cross-View Referring Reasoning for Visual Grounding | Gan Hao, Wang Liuqian, Li Shuang, Gao Yufei, Chao Wentao, Fu Chong, Liu Chengming, Shi Lei | Zhengzhou University, Henan, China | 提出跨视角指代推理方法，实现视觉 grounding 中的对象地理定位与视角感知推理。 | [#17](https://github.com/123trump/RS-PaperClaw/issues/17) |
| [20261031] STLT: A Novel System for Energy-Aware Distributed Inference in the Edge-Cloud-Space Continuum | Stanisic Andrija, Gravara Milos, Juan Luis Herrera, Nastic Stefan | University of Extremadura Spain | 设计STLT系统，在边缘-云-太空连续体中实现能耗感知的分布式DNN推理。 | [#18](https://github.com/123trump/RS-PaperClaw/issues/18) |
| [20261031] Urban functional knowledge transfer through global representations amid uneven data | Liu Junyuan, Wang Xinglei, Dong Guangsheng, Sha Hao, Zeng Zichao, Deng Zhicheng, Feng Jiazhuang, Wang Xiang, Cheng Tao | SpaceTimeLab, Department of Civil, Environmental and Geomatic Engineering, University；College London, London, WC1 E 6 BT, United Kingdom；State Key Laboratory of Information Engineering in Surveying, Mapping and Remote；Sensing, Wuhan University, Wuhan, 430079, China | 通过全局表示和POI对齐嵌入，在数据不均条件下实现城市功能知识迁移。 | [#19](https://github.com/123trump/RS-PaperClaw/issues/19) |

## 🔎 观察

- 不确定性量化与采样偏差评估正从辅助分析转变为核心建模环节，反映遥感AI对可靠性的迫切需求。
- 跨域知识迁移与分布式推理架构并行发展，表明遥感应用正同时向数据高效利用和计算资源协同优化演进。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261031", "source": "oai", "checked_at": "2026-11-04T07:27:27+00:00", "source_complete": true, "candidate_count": 18, "paper_count": 8} -->

---

# [20261030](./202610/20261030.md)
## 📌 今日概况

今日共检索候选论文 8 篇；关键词+LLM 智能匹配遥感交叉论文 3 篇；最终纳入日报 3 篇。

今日三篇论文分别聚焦屋顶光伏潜力估计、SAR时序作物分类与受限视场跨视角地理定位。整体趋势显示，遥感AI正从依赖显式几何或完整观测转向端到端学习与自监督预训练，以降低对人工特征和理想条件的依赖。同时，研究注重物理引导与真实场景约束，如极化特征融合和有限视场定位，推动模型在数据稀缺或观测不完整条件下的实用性。

## ✨ 今日亮点

- 端到端学习直接从卫星影像预测屋顶光伏潜力，跳过显式几何建模。
- 物理引导自监督预训练结合极化特征，提升SAR时序作物分类性能。
- 针对有限视场观测的跨视角地理定位，构建大规模数据集应对GNSS拒止场景。

## 🗂 今日文章列表

| 标题 | 作者 | 单位 | 一句话概括 | Issue |
|---|---|---|---|---|
| [20261030] An Empirical Study on Learning Rooftop Solar Potential from Satellite Imagery Directly Without Explicit Geometry | Lee Joshua | Skyline High School | 实证研究探索不依赖显式几何、直接从卫星影像端到端学习屋顶光伏潜力的可行性。 | [#8](https://github.com/123trump/RS-PaperClaw/issues/8) |
| [20261030] SAR-TS-BERT: Physics-Guided Self-Supervised Pre-Training With Polarimetric Features for SAR Time-Series Crop Classification | Wang Jieqiu, Zhang Yuhan, Zheng Bo, Zhang Shaoming | College of Surveying and Geo-Informatics, Tongji University, Shanghai, China ( | 提出SAR-TS-BERT，融合极化特征与物理引导自监督预训练，用于SAR时序作物分类。 | [#9](https://github.com/123trump/RS-PaperClaw/issues/9) |
| [20261030] Seeing Less in a Sparse World: Cross-View Geolocalization from Limited Field-of-View Observations | Aleem Fahimul, Vyas Shruti | University of Central Florida Orlando, FL United States | 研究有限视场观测下的跨视角地理定位，构建大规模数据集支持GNSS拒止场景。 | [#10](https://github.com/123trump/RS-PaperClaw/issues/10) |

## 🔎 观察

- 端到端学习减少对显式几何的依赖，但可解释性与泛化能力仍需进一步验证。
- 物理引导与自监督结合在SAR时序任务中显现潜力，有限视场定位反映真实约束受关注。

---

Powered by OpenClaw🦞

<!-- rs-pipeline: {"date": "20261030", "source": "oai", "checked_at": "2026-11-03T02:02:41+00:00", "source_complete": true, "candidate_count": 8, "paper_count": 3} -->

---
