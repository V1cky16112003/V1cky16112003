### Hi, I'm Vignesh Ram Sivakumar 👋

MSc Data Science graduate from King's College London (Distinction, 72%). AI/ML Engineer focused on agentic systems, RAG and AI safety.

🔍 Based in London, open to AI/ML Engineer roles across the UK. Available to join immediately.

#### What I've been building

- **[Pointwise: Fast, Calibrated Decision Model](https://github.com/V1cky16112003/pointwise)** ([live demo](https://v1cky16112003--pointwise-demo-web.us-east.modal.run/)) — LoRA fine-tuned Qwen3-1.7B with a pointer head that answers up to 32 multiple-choice questions about one input in a single forward pass, returning calibrated confidence scores with no generated text. Scores 67.8% vs 64.0% for the untrained base on 2,000 unseen questions, cuts calibration error (ECE) from 0.109 to 0.056, and uses 6.4x fewer tokens than generate-and-parse. Served on Modal with FastAPI, OpenTelemetry metrics and GitHub Actions CI.
- **[ArXiv Research Intelligence Agent](https://github.com/V1cky16112003/research-intelligence-agent)** ([live demo](https://frontend-vert-eight-61.vercel.app/)) — Agentic RAG over 50K ArXiv papers: hybrid search (vector + BM25 RRF + LLM rerank) on pgvector and a four-node LangGraph agent (Planner/Executor/Critic/Reporter) with RAG, SQL, web search and Neo4j tools. Merges are gated by a RAGAS pipeline (latest main run: faithfulness 1.00, answer relevancy 0.91, context precision 0.93). Deployed on Hugging Face Spaces + Vercel.
- **[Kensal House Mama: Agentic Household Automation via MCP](https://github.com/V1cky16112003/chore-manager)** — Custom MCP server (10 tools) for chore management, deployed serverless on Vercel with bearer-token auth hardened against DNS-rebinding, giving direct LLM control from Claude Desktop/Web.
- **MSc Dissertation: Multimodal Emotion Recognition on SEED-VII (Awarded Distinction)** — Replicated the MAET benchmark (IEEE TAFFC 2025) on KCL's A100 cluster and showed its 71.28% headline accuracy is an evaluation-leakage artefact (paired Wilcoxon W=0, p<2e-6). Honest leak-free methods reach 42–48%, and the same leakage inflated accuracy by 13.81 pp on an independent dataset (MultiPhysio-HRC).

Earlier: [Conversational Multimodal Chatbot](https://github.com/V1cky16112003/Conversational-Image-Recognition-Chatbot) — real-time image recognition + OCR + voice I/O across English, Tamil, Hindi, Telugu; FastAPI + React.

#### Experience

- **AI Security Researcher / Policy Architect, Stealth Startup** (London, Jun–Jul 2026) — Designed and stress-tested the authorization policy layer for Guard AI, a runtime security system that allows, denies, transforms, sandboxes or escalates every action an autonomous agent proposes. Authored a Cedar-ready policy spec covering the OWASP Agentic Top 10 and LLM Top 10, and an information-flow model validated against six real production incidents including EchoLeak (CVE-2025-32711).
- **AI Intern / Data Science Intern, 4i Apps Solutions** (Chennai, Jun 2023–Jan 2024) — K-Means customer segmentation on ~3–4 GB of purchase data; TensorFlow/Keras models served with FastAPI and tracked in MLflow; end-to-end Scikit-Learn classification pipelines.

#### Education

- **MSc Data Science, King's College London** (2025–2026) — Distinction (72%)
- **B.Tech Computer Science and Engineering, SRM Institute of Science & Technology** (2021–2025) — 8.73/10, First Class with Distinction

#### What I work with

**Programming:** Python · SQL · JavaScript · Git · Agentic Coding (Claude Code)
**ML & AI:** Agentic AI & Multi-agent Systems · PyTorch · TensorFlow · Scikit-Learn · GNNs · Transformers · HuggingFace · Multimodal AI · NLP · Computer Vision
**LLM Training & Evaluation:** Fine-Tuning (LoRA, QLoRA, PEFT) · Multi-GPU Training (DDP) · Mixed Precision (fp16) · Attention Masking & KV Caching · Model Calibration (ECE, Temperature Scaling) · RAGAS · Zero-Shot Evaluation
**Engineering & Backend:** Agentic RAG · Hybrid Search & Reranking · MCP (Model Context Protocol) · AI observability & tracing · LangGraph · FastAPI · Pydantic · Docker · pgvector · MySQL · Pytest · Production AI
**Frontend & Deployment:** React.js · Vite · Vercel · Hugging Face Spaces · Kaggle GPU · GitHub Actions · MLflow
**Signals & Modelling:** EEG/EDA/BVP signal processing · Multimodal fusion · Uncertainty quantification · Transfer learning
**AI Security:** Agentic authorization policy design (Cedar) · OWASP Agentic Top 10 / LLM Top 10 threat modelling

#### Certifications

- Model Context Protocol: Advanced Topics — Anthropic (Jul 2026)
- AI Fluency Framework & Foundations — Anthropic (Jul 2026)

📫 [LinkedIn](https://linkedin.com/in/vignesh-ram-sivakumar) · [Portfolio](https://vigneshramsivakumar.me)
