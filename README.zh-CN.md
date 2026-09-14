<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6&height=200&section=header&text=You%20Wu&fontSize=80&fontAlignY=38&desc=Reinforcement%20Learning%20%E2%80%A2%20LLM%20Agents%20%E2%80%A2%20Computer%20Vision&descSize=18&descAlignY=62&animation=fadeIn" />
</div>

<div align="center">

[English](README.md) | **简体中文**

  [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=7AA2F7&center=true&vCenter=true&width=640&lines=CS+undergrad+at+NUIST%2C+Mitacs+Globalink+intern+%40+UBC;Teaching+agents+to+act+%E2%80%94+RL%2C+LLM+agents%2C+affective+vision;Ongoing+research+code+lives+in+a+private+repo)](https://git.io/typing-svg)

</div>

---

## 🔍 研究方向

- **强化学习** —— 面向三维连续控制的 PPO-Clip（Isaac Sim 中的无人机导航）；面向不完全信息卡牌博弈的自博弈 + 行为克隆
- **大模型与 Agent** —— 基于 LangGraph 的多 Agent 编排、Hybrid RAG（BM25 + 稠密检索 + RRF）、MCP 兼容工具层；LoRA / 全参数微调、NER 与结构化输出
- **计算机视觉** —— 基于冻结自监督视频编码器（V-JEPA 2）的连续情感预测；3D Gaussian Splatting；医学影像分割
- **可信机器学习** —— 面向音频版权保护的不可学习样本、对抗扰动设计
- **机器学习系统** —— 分布式流式推理（Kafka / Spark / HDFS）、GPU 推理微服务、SLURM 集群实验管线

## 🛠 技术栈

<div align="center">

  <img src="https://skillicons.dev/icons?i=py,cpp,c,java,ts,js,html,css,pytorch,sklearn,opencv,fastapi,flask,vue,react,threejs,nodejs,mysql,sqlite,docker,linux,git,qt,matlab,latex,bash&theme=dark&perline=13" />

</div>

<div align="center">
  <sub>此外：Apache Spark · Apache Kafka · HDFS · Hugging Face Transformers · LangGraph · Chroma · SLURM · NVIDIA Isaac Sim · COLMAP</sub>
</div>

## ⭐ 精选项目

- [`grad-school-agent`](https://github.com/xiaowenhao404/grad-school-agent) —— 基于 LangGraph 的多 Agent 问答助手：8 节点 `StateGraph` 将每轮对话路由至五个专职 Agent，底层是 Hybrid RAG（BM25 + BGE + RRF）与 MCP 兼容工具层，配合全链路优雅降级与 SSE 流式输出
- [`uav-ppo-navigation`](https://github.com/xiaowenhao404/uav-ppo-navigation) —— 基于 PPO 的无人机自主导航深度强化学习：18 项复合奖励（14 项启用）、2,048 并行环境、四阶段课程学习。在「一次碰撞即终止」的约束下，任务成功率由 <1% 提升至 85–95%。*国家级三等奖*
- [`realtime-sentiment-analysis`](https://github.com/xiaowenhao404/realtime-sentiment-analysis) —— 8 容器 Kafka/Spark/HDFS 流式管线 + 微调 Chinese-RoBERTa + 带动态批处理的 FastAPI GPU 微服务（289 条/秒，84 ms → 3.5 ms）
- [`unlearnable-audio-protection`](https://github.com/xiaowenhao404/unlearnable-audio-protection) —— 面向音频的 min-min 不可学习样本，通过「梅尔频谱图即图像」的跨模态迁移桥接到图像域，并在 GTZAN 上完成验证

## 📂 按方向索引

### 🤖 强化学习
- [`uav-ppo-navigation`](https://github.com/xiaowenhao404/uav-ppo-navigation) —— Isaac Sim 中三维连续控制 POMDP 任务的 PPO-Clip 训练管线 `2026.04 – 2026.06`
- [The Pokémon Company – PTCG AI Battle Challenge](https://www.kaggle.com/xiaowenhao404) *(Kaggle)* —— 以天梯高分回放挖掘的 115 万条决策做行为克隆冷启动的自博弈对战 Agent —— **铜牌，372 / 6,807** `2026.06 – 2026.08`

### 🧠 大模型与 Agent
- [`grad-school-agent`](https://github.com/xiaowenhao404/grad-school-agent) —— 基于 LangGraph、含 Hybrid RAG 与 MCP 兼容工具层的多 Agent 问答助手 `2026.04 – 2026.06`

### 👁 计算机视觉
- [`3d-gaussian-splatting-viewer`](https://github.com/xiaowenhao404/3d-gaussian-splatting-viewer) —— COLMAP SfM + 自研 gsplat 训练器，FastAPI 后端与 React/Three.js 查看器 `2026.06 – 2026.07`
- [`deepfocus-face-detection`](https://github.com/xiaowenhao404/deepfocus-face-detection) —— 课堂人脸定位，三套可互换引擎（HOG+SVM / CNN MMOD / YuNet+SFace） `2025.09 – 2025.12`

### 🛡 可信机器学习
- [`unlearnable-audio-protection`](https://github.com/xiaowenhao404/unlearnable-audio-protection) —— 面向音频的 min-min 不可学习扰动 + 超声波频段互补防御 `2025.04 – 2026.04`

### ⚙️ 机器学习系统与数据
- [`realtime-sentiment-analysis`](https://github.com/xiaowenhao404/realtime-sentiment-analysis) —— 基于 Kafka / Spark / HDFS 的实时评论情感分析管线，含 GPU 推理微服务 `2026.05 – 2026.06`

### 🧩 系统与软件工程
- [`mini-c-compiler`](https://github.com/xiaowenhao404/mini-c-compiler) —— Flex/Bison → 三地址码中间表示 → x86-64 汇编，配 Flask 可视化器 `2025.11 – 2026.01`
- [`counselor-student-system`](https://github.com/xiaowenhao404/counselor-student-system) —— JavaFX + MySQL 辅导员—学生管理系统 `2025.03 – 2025.06`
- [`counselor-student-system-testing`](https://github.com/xiaowenhao404/counselor-student-system-testing) —— 上述系统的集成测试工程 `2025.09 – 2025.12`
- [`tetris-ai`](https://github.com/xiaowenhao404/tetris-ai) —— 带遗传算法 AI 对手的网页版俄罗斯方块 `2025.02 – 2025.05`

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6&height=120&section=footer" />
</div>
