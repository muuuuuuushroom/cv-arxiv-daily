根据您上传的材料，我将14篇论文提出的缓偏方法按照其作用阶段（预处理阶段缓偏、训练阶段缓偏、后处理阶段缓偏）进行分类，并提供相应信息如下：

### 一、 预处理阶段缓偏

该阶段的缓偏方法侧重于**数据层面**的修改或增强，用于准备模型的训练数据。

| 论文编号 | 缓偏方法名称 | 偏见类型 | 缓偏效果 (20字以内) | 引用来源 |
| :---: | :--- | :--- | :--- | :--- |
| **96.pdf** | Counterfactual Data Augmentation (CDA) (反事实数据增强) | 性别、职业 | **CDA有效减偏，保持模型性能**。 | |
| **98.pdf** | Healthy Data Diet (GE score ranking/pruning) (健康数据筛选) | 性别 (性别歧视) | **减少数据量，实现更好公平性**。 | |
| **108.pdf** | Backward Augmentation / Round-trip Augmentation (逆向/往返数据增强) | 性别 | **提高性别公平，优于强基线**。 | |

***

### 二、 训练阶段缓偏

该阶段的缓偏方法侧重于**模型训练或微调阶段**的参数、损失函数或架构修改。

| 论文编号 | 缓偏方法名称 | 偏见类型 | 缓偏效果 (20字以内) | 引用来源 |
| :---: | :--- | :--- | :--- | :--- |
| **97.pdf** | Gender-tuning (性别微调) | 性别 | **缓偏性能优越，同时提升准确率**。 | |
| **101.pdf** | GEn-der Equality Prompt (GEEP) (性别平等提示) | 性别、职业 | **提升公平性，避免灾难性遗忘**。 | |
| **102.pdf** | ADEPT (A DEbiasing PrompT Framework) (缓偏提示框架) | 性别、宗教 | **竞争性缓偏，保持表示能力**。 | |
| **103.pdf** | ADELE (Adapter-Based Debiasing) (基于适配器的缓偏) | 性别 | **有效缓解性别偏见，成本低**。 | |
| **104.pdf** | Mutual Information Minimization based on Importance Sampling + Distillation (互信息最小化与蒸馏) | 性别 | **提升公平性和生成流畅性**。 | |
| **105.pdf** | Efficient Fine-Tuning (高效微调) (使用LN + WPE模型) | 性别、职业、种族、宗教 | **微调少量参数，有效减弱偏见**。 | |
| **106.pdf** | PCGU (Partitioned Contrastive Gradient Unlearning) (分区对比梯度遗忘) | 性别、职业、种族、宗教 | **低成本减轻偏见，跨域泛化**。 | |
| **109.pdf** | Demographic-Aware Language Model Fine-tuning (人口统计学感知语言模型微调) | 性别、种族 | **通过特定群体数据微调来减偏**。 | |

***

### 三、 后处理阶段缓偏

该阶段的缓偏方法侧重于**模型输出或推理阶段**的修改或指导。

| 论文编号 | 缓偏方法名称 | 偏见类型 | 缓偏效果 (20字以内) | 引用来源 |
| :---: | :--- | :--- | :--- | :--- |
| **99.pdf** | INTERFAIR (Interactive Fair Debiasing) (交互式公平缓偏) | 性别、职业 | **用户交互优化公平性与性能**。 | |
| **100.pdf** | Adversarial Triggers (对抗性触发词) | 种族、宗教、残障、性别 (通过地名或群体指称体现) | **显著降低有害内容和偏见**。 | |
| **107.pdf** | Post-hoc Debiasing using Chain-of-Thought Prompting and SHAP Analysis (后处理缓偏/思维链提示) | 性取向 (性身份刻板印象) | **提高输出文本的自尊分数**。 | |