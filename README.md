<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6&height=200&section=header&text=You%20Wu&fontSize=80&fontAlignY=38&desc=Reinforcement%20Learning%20%E2%80%A2%20LLM%20Agents%20%E2%80%A2%20Computer%20Vision&descSize=18&descAlignY=62&animation=fadeIn" />
</div>

<div align="center">

**English** | [简体中文](README.zh-CN.md)

  [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=7AA2F7&center=true&vCenter=true&width=640&lines=CS+undergrad+at+NUIST%2C+Mitacs+Globalink+intern+%40+UBC;Teaching+agents+to+act+%E2%80%94+RL%2C+LLM+agents%2C+affective+vision;Ongoing+research+code+lives+in+a+private+repo)](https://git.io/typing-svg)

</div>

---

## 🔍 Focus

- **Reinforcement Learning** — PPO-Clip for 3D continuous control (UAV navigation in Isaac Sim); self-play + behaviour cloning for imperfect-information card games
- **LLM & Agents** — multi-agent orchestration on LangGraph, hybrid RAG (BM25 + dense + RRF), MCP-compatible tool layers; LoRA / full-parameter fine-tuning, NER and structured output
- **Computer Vision** — continuous affect prediction with frozen self-supervised video encoders (V-JEPA 2); 3D Gaussian Splatting; medical image segmentation
- **Trustworthy ML** — unlearnable examples for audio copyright protection, adversarial perturbation design
- **ML Systems** — distributed streaming inference (Kafka / Spark / HDFS), GPU serving microservices, SLURM cluster experiment pipelines

## 🛠 Tech Stack

<div align="center">

  <img src="https://skillicons.dev/icons?i=py,cpp,c,java,ts,js,html,css,pytorch,sklearn,opencv,fastapi,flask,vue,react,threejs,nodejs,mysql,sqlite,docker,linux,git,qt,matlab,latex,bash&theme=dark&perline=13" />

</div>

<div align="center">
  <sub>Also: Apache Spark · Apache Kafka · HDFS · Hugging Face Transformers · LangGraph · Chroma · SLURM · NVIDIA Isaac Sim · COLMAP</sub>
</div>

## ⭐ Featured

- [`grad-school-agent`](https://github.com/xiaowenhao404/grad-school-agent) — Multi-agent QA assistant on LangGraph: an 8-node `StateGraph` routes each turn through five specialist agents over hybrid RAG (BM25 + BGE + RRF) and an MCP-compatible tool layer, with full-chain graceful degradation and SSE streaming
- [`uav-ppo-navigation`](https://github.com/xiaowenhao404/uav-ppo-navigation) — PPO-based deep RL for autonomous UAV navigation: 18-term composite reward (14 active), 2,048 parallel envs, four-stage curriculum. Success rate <1% → 85–95% under a one-collision-ends-the-episode rule. *National Third Prize*
- [`realtime-sentiment-analysis`](https://github.com/xiaowenhao404/realtime-sentiment-analysis) — 8-container Kafka/Spark/HDFS streaming pipeline + fine-tuned Chinese-RoBERTa + FastAPI GPU microservice with dynamic batching (289 samples/s, 84 ms → 3.5 ms)
- [`unlearnable-audio-protection`](https://github.com/xiaowenhao404/unlearnable-audio-protection) — Min-min unlearnable examples for audio, bridged to the image domain via a "mel-spectrogram-as-image" transfer and validated on GTZAN

## 📂 Projects by Domain

### 🤖 Reinforcement Learning
- [`uav-ppo-navigation`](https://github.com/xiaowenhao404/uav-ppo-navigation) — PPO-Clip pipeline for a 3D continuous-control POMDP in Isaac Sim `2026.04 – 2026.06`
- [`pokemon-tcg-ai-battle`](https://www.kaggle.com/competitions/pokemon-tcg-ai-battle) *(Kaggle · The Pokémon Company)* — self-play battle agent bootstrapped from behaviour cloning on 1.15M decisions mined from top-ladder replays — **Bronze Medal, 372 / 6,807** `2026.06 – 2026.08`

### 🧠 LLM & Agents
- [`grad-school-agent`](https://github.com/xiaowenhao404/grad-school-agent) — LangGraph multi-agent QA assistant with hybrid RAG and an MCP-compatible tool layer `2026.04 – 2026.06`

### 👁 Computer Vision
- [`3d-gaussian-splatting-viewer`](https://github.com/xiaowenhao404/3d-gaussian-splatting-viewer) — COLMAP SfM + custom gsplat trainer, FastAPI backend and React/Three.js viewer `2026.06 – 2026.07`
- [`deepfocus-face-detection`](https://github.com/xiaowenhao404/deepfocus-face-detection) — classroom face localization with three interchangeable engines (HOG+SVM / CNN MMOD / YuNet+SFace) `2025.09 – 2025.12`

### 🛡 Trustworthy ML
- [`unlearnable-audio-protection`](https://github.com/xiaowenhao404/unlearnable-audio-protection) — min-min unlearnable perturbations for audio + ultrasonic-band complementary defense `2025.04 – 2026.04`

### ⚙️ ML Systems & Data
- [`realtime-sentiment-analysis`](https://github.com/xiaowenhao404/realtime-sentiment-analysis) — real-time comment sentiment pipeline over Kafka / Spark / HDFS with a GPU inference microservice `2026.05 – 2026.06`

### 🧩 Systems & Software Engineering
- [`mini-c-compiler`](https://github.com/xiaowenhao404/mini-c-compiler) — Flex/Bison → three-address-code IR → x86-64 assembly, with a Flask visualizer `2025.11 – 2026.01`
- [`counselor-student-system`](https://github.com/xiaowenhao404/counselor-student-system) — JavaFX + MySQL counselor–student management system `2025.03 – 2025.06`
- [`counselor-student-system-testing`](https://github.com/xiaowenhao404/counselor-student-system-testing) — integration-testing build of the system above `2025.09 – 2025.12`
- [`tetris-ai`](https://github.com/xiaowenhao404/tetris-ai) — web Tetris with a genetic-algorithm AI player `2025.02 – 2025.05`

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6&height=120&section=footer" />
</div>
