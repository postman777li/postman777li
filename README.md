<p align="center">
  <img src="https://raw.githubusercontent.com/postman777li/postman777li/main/assets/profile-banner.png" alt="11an · 争者留其名 · Aspiring LLM Algorithm Engineer" width="100%" />
</p>

以 **大模型算法工程师** 为目标，聚焦大模型在专业场景中的应用、Agent 工作流与文本信息提取。

### 核心项目

#### [层次化控制法律翻译实验](https://github.com/postman777li/hierarchical_control_legal_transaltion_experiment)

我的主要项目。围绕法律文本翻译，构建 **术语 → 句法 → 篇章** 三层 Agent 工作流，将领域约束、检索与质量评估接入翻译过程。

- **分层控制**：逐层处理术语一致性、句法保真与篇章风格，通过评估反馈改进译文。
- **检索支持**：结合术语库、翻译记忆、Milvus 向量检索与 BM25，为生成提供领域参考。
- **实验评估**：设置纯 LLM 基线与渐进式消融配置，包含 BLEU、chrF、BERTScore、COMET 等评估模块及翻译轨迹记录。

[项目说明](https://github.com/postman777li/hierarchical_control_legal_transaltion_experiment/blob/master/hierarchical_control_legal_transaltion_experiment/README_zh.md) · [消融实验设计](https://github.com/postman777li/hierarchical_control_legal_transaltion_experiment/blob/master/hierarchical_control_legal_transaltion_experiment/ABLATION_EXPERIMENTS.md)

#### [Keyword Extractor · 中文关键词提取](https://github.com/postman777li/keyword_extractor)

面向中文与长文本的信息提取工具，包含 **KeyBERT、BERT + 记忆机制、本地 LLM** 等实现路线。

- **长文本处理**：滑动窗口编码，结合全局主题记忆（GTM）与实体状态记忆（ESM）汇总跨片段信息。
- **模型方案**：支持多种 Embedding 模型，并提供基于 MLX 的本地 LLM 提取实现。
- **工程接口**：提供 Python API、命令行与批量处理，支持自定义词典、停用词及模型对比。

[使用说明](https://github.com/postman777li/keyword_extractor/blob/master/README.md) · [代码实现](https://github.com/postman777li/keyword_extractor/tree/master/src/keyword_extractor)

### 模型学习与实现

[**Transformer Learning**](https://github.com/postman777li/transformer-learning) — 按天整理的中文图文笔记与代码，覆盖 Attention、MiniGPT、训练与生成、KV Cache，以及 Llama 风格组件。代码按天归档并持续补齐。

[MiniGPT 训练](https://github.com/postman777li/transformer-learning/blob/main/day12/notes.md) · [KV Cache](https://github.com/postman777li/transformer-learning/blob/main/day14/notes.md) · [Llama 风格 Block](https://github.com/postman777li/transformer-learning/blob/main/day15/code.py)

### 其他工程实践

| 项目 | 内容 |
|---|---|
| [MyFirst](https://github.com/postman777li/MyFirst) | React / TypeScript、NestJS、Prisma 与 MySQL 全栈实践 |
| [8cards](https://github.com/postman777li/8cards) | 永城八张在线游戏的规则梳理、工程结构与交互原型 |

### 当前关注

**专业场景中的 LLM 应用** · **Agent 与检索工作流** · **中文长文本信息提取** · **模型训练与推理实践**
