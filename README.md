![240624_llm_roadmap.drawio](./assets/240624_llm_roadmap.drawio.png)

## Description

WhysAI--**LLMFS**项目是由一系列mini-projects组成、围绕大模型主题的系列课程。主要包括三个系列：

1. [CB](https://github.com/LloydS827/WhysAI-LLMFS-CB)：深度学习基础，包括神经网络、反向传播、PyTorch等；
2. [4S](https://github.com/LloydS827/WhysAI-LLMFS-4S)：以从零到一训练/微调大语言模型为核心；
3. [4E(This Repo)](https://github.com/LloydS827/WhysAI-LLMFS-4E)：以LLM应用为核心，涵盖RAG、Agent、MAS、Inference等。

本项目受到许多优秀的开源课程与资料启发，制作的课程资料包括Slides、Code、Video等，既用来记录学习现代人工智能技术的过程，又希望与大家共同探索AI技术的最佳学习路径。

## 4E(For Engineer)系列课程内容（V0.2, 持续更新中）

### 简介

**对象**：Software Engineers

**设计理念**：

1. PBL(Project-Based Learning): 通过实际操作来解决现实世界中的问题
2. TBL(Teaching is the Best Learning): 鼓励用自己的话来总结、教授所学的知识
3. UCW(The Unchanged in the Changing World)：讲解基本原理和核心算法，适应技术快速变化
4. SC(Self-Contained)：内容不依赖前置AI知识

### 课程内容

| Theme                                 | Contents                                                     | Project & Keywords                | Articles | Main References                                              |
| ------------------------------------- | ------------------------------------------------------------ | --------------------------------- | -------- | ------------------------------------------------------------ |
| 4E01<br />工程师视角下的AI/GenAI      | 1. AI简要历史、技术范围<br />2. 多角度理解GenAI/LLM：任务/数据/CS<br />3. LLM能力边界<br />4. LLM全生命周期技术简介<br />5. LLM融入日常工作<br />6. LLM应用方法论与团队角色 | /                                 |          | 1. **Highly Recommanded**: Karpathy's Lecture on [ Intro to Large Language Models - YouTube](https://www.youtube.com/watch?v=zjkBMFhNj_g&t=2882s)<br />2. **Our CB-series**: [LloydS827/WhysAI-LLMFS-CB (github.com)](https://github.com/LloydS827/WhysAI-LLMFS-CB)<br />3. **GenAI Course by Andrew**: [Generative AI for Everyone - DeepLearning.AI](https://www.deeplearning.ai/courses/generative-ai-for-everyone/)<br />4. Sum of all short courses on deeplearnin.ai, cutoff-Aug.15.2024: [Resources - DeepLearning.AI](https://www.deeplearning.ai/resources/)<br />5. First DL end2end prject introduced by Andrej Karpathy: [Deep Neural Nets: 33 years ago and 33 years from now (karpathy.github.io)](https://karpathy.github.io/2022/03/14/lecun1989/)<br />6. The Bitter Lesson by Rich Sutton |
| 4E02-1<br />实用Prompt Engineeing技巧 | 通过实际案例，掌握PE基本结构与方法论，进而试验PE实用技巧与最佳实践。同时介绍如COT/DSPY等前沿方法。 | P1: Prompt Engineering            |          |                                                              |
| 4E02-2<br />ChatBot APP               | 1. langchain整体架构与安装使用方法 <br />2. Streamlit快速构建Web应用 <br />3. 接入闭源模<br /型API、本机部署开源模型 <br />4. 使用langchain创建含有对话历史的ChatBot应用 | P2：对话机器人ChatBot             |          |                                                              |
| 4E02-3<br />检索增强RAG项目           | 1. RAG项目整体Pipeline<br />2. 建立知识库：文档解析、Embedding模型与向量数据库接入<br />3. 使用langchain实现RAG问答流程<br />4. 使用Streamlit创建RAG应用 | P3: 私有知识问答的检索增强RAG项目 |          |                                                              |
| 4E02-4<br />Agent 项目                | 1. 认识LLM-Based Agent关键模块：规划、工具、记忆等<br />2. 通过langchain实现工具调用/text2Json功能，并了解自定义工具的创建方法<br />3. 创建能够自动化执行任务的Agent智能体<br />4. 使用streamlit创建智能体应用 | P4：基于langchain的Agent项目      |          |                                                              |
| 4E03 Series<br />RAG In Depth<br />   | 基于4E02-3内容，深入理解RAG技术与实践，包括Agentic RAG、知识图谱+RAG、RAG架构Llamaindex等 |                                   |          |                                                              |
| 4E04 Series<br />Agent In Depth       | 基于4E02-4内容，深入理解Agent技术与实践，包括MAS架构CrewAI、langgraph、Autogen等 |                                   |          |                                                              |
| 4E05 Series<br />前沿技术赏析         | LLM-based Agent前沿成果展示，例如AutoGPT、ChatDev、Agent Q等项目<br />具身智能机器人前沿成果展示，例如Aloha、RT-H、无人机等 |                                   |          |                                                              |

重要参考：[deeplearning.ai -- Short Courses](https://github.com/LloydS827/WhysAI-LLMFS-4E/blob/main/deeplearning.ai-ShortCourses.md)

## Key Resources

>每期参考/推荐资料见“课程内容”

**Key Roadmap & Resources:**

- [GenAI Handbook (genai-handbook.github.io)](https://genai-handbook.github.io/)
- [https://github.com/mlabonne/llm-course](https://github.com/mlabonne/llm-course)
- [karpathy/LLM101n: LLM101n: Let's build a Storyteller (github.com)](https://github.com/karpathy/LLM101n)

**Important：**
- [StatQuest](https://space.bilibili.com/3546620985608836?spm_id_from=333.337.0.0)
- Deeplearning.ai
- Andrej Karparthy: Zero 2 Hero Series
- 3B1B: NN series
- VisualizeML(Iris Series)

**Others**：

- AI Infrastructure [https://github.com/chenzomi12/AISystem/](https://github.com/chenzomi12/AISystem/)
- ML-data engineering [https://github.com/GokuMohandas/Made-With-ML](https://github.com/GokuMohandas/Made-With-ML)
- NN-deeplearning [https://zh.d2l.ai/](https://zh.d2l.ai/)
- Math & Python & ML [https://github.com/Visualize-ML](https://github.com/Visualize-ML)
- AI Papers w/ code [https://github.com/labmlai/annotated_deep_learning_paper_implementations](https://github.com/labmlai/annotated_deep_learning_paper_implementations
- Rag From Stratch by langchain: [https://github.com/langchain-ai/rag-from-scratch](https://github.com/langchain-ai/rag-from-scratch)
- Qwen Docs: [https://qwen.readthedocs.io/zh-cn/latest/index.html#](https://qwen.readthedocs.io/zh-cn/latest/index.html#)
- the bitter lesson: [https://cloud.tencent.com/developer/article/2119875](https://cloud.tencent.com/developer/article/2119875)
- [datawhalechina/llm-cookbook: 面向开发者的 LLM 入门教程，吴恩达大模型系列课程中文版 (github.com)](https://github.com/datawhalechina/llm-cookbook)
- langchain master class: [hw_dungeonrooms4q_h_en_115 (youtube.com)](https://www.youtube.com/watch?v=yF9kGESAi3M)

**Fundalmentals**

1. Python: [30 days of Python](https://github.com/Asabeneh/30-Days-Of-Python)
2. Math & Machine Learning:[Visualize-ML (Iris Series)](https://github.com/Visualize-ML)
3. Deep Learning: [D2l](https://courses.d2l.ai/zh-v2/)

## WhysAI

WhysAI由复旦大学几位在读博士发起，希望通过持续探索，来迈向卓越。Learn all we can，do the experiments，embrace the failures，then succeed。同时，欢迎关注公众号“WhysAI怀思智合”。

