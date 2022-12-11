# DiagramQA

### Geometric Diagram QA

大致分为2步：1）将题干和几何示意图转换为形式描述。文本解析，示意图解析，二者互补对齐，构建形式化描述
2）通过演绎推理，得到问题的答案。推理过程及定理选择，赋值及计算。
难点1：当示意图不符合比例时，题干与示意图的对齐及互补增强。
①识别示意图中的几何元素，比如点，线，面。其中线分为直线，线段，圆等。面分为三角形，正方形，菱形等。
②识别集合元素之间的关系，比如相交，平行，比例关系（倍数关系）。
③识别元素的数量。线段的长度，相交直线间的角度，平行线间的距离等等。

难点2：演绎推理过程中的辅助线的做法及匹配的演绎推理。

特点：从2022年开始，使用预训练模型进行文本和图像解析。

几何示意图解析（无问题解析和对齐）：Plane Geometry Diagram Parsing IJCAI 2022，
https://github.com/mingliangzhang2018/PGDP
源码目录geo_parse标注Facebook，但是不知道是那个工程

GeoQA: A Geometric Question Answering Benchmark Towards Multimodal Numerical Reasoning ACL21
https://github.com/chen-judge/GeoQA

Inter-GPS: Interpretable Geometry Problem Solving with Formal Language and Symbolic Reasoning ACL20.   
https://github.com/lupantech/InterGPS

Solving Geometry Problems: Combining Text and Diagram Interpretation EMNLP15  
geosover:https://github.com/seominjoon/geosolver
http://geometry.allenai.org/ 

FCOS: Fully Convolutional One-Stage Object Detection --- 类似算法YOLO

A neural network solves, explains, and generates university math problems by program synthesis and few-shot learning
at human level. PNAS22
创新：
https://github.com/idrori/mathQ，代码量好少

中考平面几何真题：图形外辅助线

![image.png](assets/image.png)

高考没有平面几何，有立体几何和解析几何。


## 相关研究VQA

### CVPR22

* SimVQA: Exploring Simulated Environments for Visual Question Answering
* A Thousand Words Are Worth More Than a Picture: Natural Language-Centric Outside-Knowledge Visual Question Answering
* SwapMix: Diagnosing and Regularizing the Over-reliance on Visual Context in Visual Question Answering
* Dual-Key Multimodal Backdoors for Visual Question Answering （后门程序）
* MuKEA: Multimodal Knowledge Extraction and Accumulation for Knowledge-based Visual Question Answering
* Maintaining Reasoning Consistency in Compositional Visual Question Answering
*
* LaTr: Layout-Aware Transformer for Scene-Text VQA
*
* Visual Abductive Reasoning
* VisualHow: Multimodal Problem Solving
*
* Pseudo-Q: Generating Pseudo Language Queries for Visual Grounding
* Grounding Answers for Visual Questions Asked by Visually Impaired People
*
* Episodic Memory Question Answering（未下载到）

### ACL22

* Hypergraph Transformer: Weakly-Supervised Multi-hop Reasoning for Knowledge-based Visual Question Answering. ACL22
* DuReader_vis: A Chinese Dataset for Open-domain Document Visual Question Answering
* xGQA: Cross-Lingual Visual Question Answering
*
* CARETS: A Consistency And Robustness Evaluative Test Suite for VQA
* CLIP Models are Few-Shot Learners: Empirical Studies on VQA and Visual Entailment
* Co-VQA : Answering by Interactive Sub Question Sequence
*
* ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning
* Multilevel Hierarchical Network with Multiscale Sampling for Video Question Answering

### AAAI22

* Dynamic Key-Value Memory Enhanced Multi-Step Graph Reasoning for Knowledge-Based Visual Question Answering
*
* MuMuQA: Multimedia Multi-Hop News Question Answering via Cross-Media Knowledge Extraction and  Grounding
*
* An Empirical Study of GPT-3 for Few-Shot Knowledge-Based VQA
* Multi-Modal Answer Validation for Knowledge-Based VQA
*
* Learning the Dynamics of Visual Relational Reasoning via Reinforced Path Routing AAAI2022
*
*
* TempoQR: Temporal Question Reasoning over Knowledge Graphs
*
* Generation-Focused Table-Based Intermediate Pre-Training for Free-Form Question Answering
*
* Video as Conditional Graph Hierarchy for Multi-Granular Question Answering

### IJCAI22

* Declaration-based Prompt Tuning for Visual Question Answering   https://github.com/weibifan/eval_DPT
  所使用的VinVL并没有在HuggingFace网站中。
  ![img.png](images/img.png)
* Multilevel Hierarchical Network with Multiscale Sampling for Video Question Answering
*
