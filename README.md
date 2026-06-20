# In the World of Papers

> A curated reading archive on **visual social relationship understanding, contextual reasoning, and group perception**.

本仓库用于整理视觉社会关系理解方向的论文与个人汇报材料，覆盖从社会心理学启发的关系建模，到知识图谱、时空推理、超图推理，以及视觉基础模型与大语言模型等方法。

仓库目前收录：

- **8 篇论文**
- **8 份汇报 PDF**
- 主题包括：社会关系识别、上下文理解、图推理、视频时空建模、群体感知与多模态大模型

---

## Repository Structure

```text
In-the-World-of-Papers/
├── 论文集/          # 原始论文 PDF
├── 论文汇报PPT/    # 个人汇报材料（PDF 导出版）
└── README.md
```

---

## Paper Index

| # | Paper | Focus | Resources |
|---:|---|---|---|
| 1 | [From a Social Cognitive Perspective: Context-aware Visual Social Relationship Recognition](https://arxiv.org/abs/2406.08358) | 从社会认知视角建模场景、人物交互与细粒度社会线索 | [Paper](./论文集/From%20a%20Social%20Cognitive%20Perspective%EF%BC%9A%20Context-aware%20Visual%20Social%20Relationship%20Recognition.pdf) · [Report I](./论文汇报PPT/READ1_From%20a%20Social%20Cognitive%20Perspective_yixuan.pdf) · [Report II](./论文汇报PPT/READ2_From%20a%20Social%20Cognitive%20Perspective_yixuan.pdf) |
| 2 | [A Domain Based Approach to Social Relation Recognition](https://arxiv.org/abs/1704.06456) | 基于社会心理学领域理论构建社会关系层级与识别方法 | [Paper](./论文集/A%20Domain%20Based%20Approach%20to%20Social%20Relation%20Recognition.pdf) · [Report](./论文汇报PPT/READ3_A%20Domain%20Based%20Approach%20to%20Social%20Relation%20Recognition_yixuan.pdf) |
| 3 | [Social Relation Recognition From Videos via Multi-Scale Spatial-Temporal Reasoning](https://openaccess.thecvf.com/content_CVPR_2019/html/Liu_Social_Relation_Recognition_From_Videos_via_Multi-Scale_Spatial-Temporal_Reasoning_CVPR_2019_paper.html) | 利用视频中的人物交互、上下文物体与多尺度时序信息进行关系推理 | [Paper](./论文集/Social%20Relation%20Recognition%20from%20Videos.pdf) · [Report](./论文汇报PPT/READ4_Social%20Relation%20Recognition%20from%20Videos_yixuan.pdf) |
| 4 | [Deep Reasoning with Knowledge Graph for Social Relationship Understanding](https://arxiv.org/abs/1807.00504) | 通过知识图谱、消息传播与注意力机制联合推理人物和上下文物体 | [Paper](./论文集/Deep%20Reasoning%20with%20Knowledge%20Graph%20for%20Social%20Relationship%20Understanding.pdf) · Report pending |
| 5 | [Multi-Granularity Reasoning for Social Relation Recognition from Images](https://arxiv.org/abs/1901.03067) | 融合场景、人物/物体区域与姿态交互等多粒度信息 | [Paper](./论文集/MULTI-GRANULARITY%20REASONING%20FOR%20SOCIAL%20RELATION.pdf) · [Report](./论文汇报PPT/READ6_Multi-Granularity%20Reasoning_yixuan.pdf) |
| 6 | [SocialGPT: Prompting LLMs for Social Relation Reasoning via Greedy Segment Optimization](https://arxiv.org/abs/2410.21411) | 结合视觉基础模型与大语言模型，并通过 GSPO 优化长提示 | [Paper](./论文集/SocialGPT%20Prompting%20LLMs%20for%20Social%20Relation%20Reasoning%20via%20Greedy%20Segment%20Optimization.pdf) · [Report](./论文汇报PPT/READ5_SocialGPT_yixuan.pdf) |
| 7 | [Toward Grouping in Large Scenes With Occlusion-Aware Spatio–Temporal Transformers](https://ieeexplore.ieee.org/document/10286297/) | 面向大场景与遮挡问题的群体检测和时空关系建模 | [Paper](./论文集/Toward%20Grouping%20in%20Large%20Scenes%20With%20Occlusion-Aware%20Spatio%E2%80%93Temporal%20Transformers.pdf) · [Report](./论文汇报PPT/READ7_Toward%20Grouping_yixuan.pdf) |
| 8 | [Reconstructing Groups of People with Hypergraph Relational Reasoning](https://arxiv.org/abs/2308.15844) | 使用超图建模拥挤场景中的高阶群体关系，辅助多人三维重建 | [Paper](./论文集/Reconstructing%20Groups%20of%20People%20with%20Hypergraph%20Relational%20Reasoning.pdf) · [Report](./论文汇报PPT/READ8_Hypergraph%20Relational%20Reasoning_yixuan.pdf) |

---

## Suggested Reading Paths

### 1. Social relation recognition foundations

```text
A Domain Based Approach
        ↓
From a Social Cognitive Perspective
        ↓
SocialGPT
```

适合了解社会关系标签如何建立、视觉上下文为何重要，以及基础模型和 LLM 如何被引入这一任务。

### 2. Context and graph reasoning

```text
Deep Reasoning with Knowledge Graph
        ↓
Multi-Granularity Reasoning
        ↓
Hypergraph Relational Reasoning
```

适合关注人物—物体交互、图神经网络、多粒度特征和高阶群体关系建模的读者。

### 3. From individual relations to group understanding

```text
Social Relation Recognition from Videos
        ↓
Toward Grouping in Large Scenes
        ↓
Reconstructing Groups of People
```

适合关注视频时序信息、遮挡条件下的群体检测，以及拥挤场景多人理解的读者。

---

## How to Use

### Browse online

直接点击上方表格中的 **Paper** 或 **Report** 链接，即可在 GitHub 中查看或下载对应材料。

### Clone locally

```bash
git clone https://github.com/yhe8479-ship-it/In-the-World-of-Papers.git
cd In-the-World-of-Papers
```

### Recommended workflow

1. 先阅读论文摘要、引言和方法概览。
2. 对照对应汇报梳理论文动机、模型结构和实验结论。
3. 回到原文核对公式、数据集、指标与消融实验。
4. 对同一研究路线中的论文进行横向比较。

---

## Contributing

欢迎通过 Issue 或 Pull Request：

- 推荐相关论文、综述、数据集或开源实现
- 修正失效链接与文件命名
- 补充论文汇报、阅读笔记或方法对比
- 改进仓库分类和阅读路线

---

## Disclaimer

本仓库用于个人学习与学术交流。

- 论文版权归原作者及出版机构所有。
- 仓库中的汇报材料属于个人阅读整理，不代表原论文作者观点。
- 使用、转载或引用相关内容时，请优先引用原论文，并遵守相应版权与许可要求。

---

## Acknowledgements

感谢所有原论文作者及开源社区对视觉社会关系理解、群体感知与多模态推理研究的贡献。
