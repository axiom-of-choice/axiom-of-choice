# Isaac Hernandez

## Staff AI Engineer | ML Engineer | Data Engineer

AI Engineer with 5+ years of experience building end-to-end AI and data solutions across fintech, healthtech, and e-commerce. Specialized in taking ML models from research to production at scale.

**Bachelor of Mathematics** — UNAM (GPA: 92/100)

---

### Currently

- **Staff AI Engineer** @ [VerveMarket](https://shop.vervemarket.com) — Working directly with the CTO to own AI/Data strategy and infrastructure. Leading hybrid search, LLM fine-tuning, multimodal image generation pipelines, and evaluation infrastructure (deterministic, statistical, LLM-as-judge) for batch and real-time serving.
- Previously: **Lead AI Engineer** @ Contpaqi | **Lead R&D** @ SoftServe | **Sr ML Engineer** @ [Nubank](https://nubank.com.br/en/) | **Sr Data Engineer** @ [Citigroup](https://www.citigroup.com)

### Highlights

- End-to-end real-time risk models at **Nubank** (Top LATAM Fintech) deployed on K8s
- Petabyte-scale Data Lake migration at **Citigroup** (S3, Snowflake, Spark on EKS)
- Agentic AI platforms for healthcare (SoftServe) and accounting (Contpaqi)
- RAG pipelines and LLM fine-tuning (GPT, LLaMA) at **Botco AI**
- Anti-fraud graph ML models at **BBVA AI Factory**

### Tech Stack

**Languages:** Python, Scala, SQL, Rust (learning)  
**AI/ML:** TensorFlow, PyTorch, LLMs, RAG, Agents, NLP, MLFlow  
**Data:** Spark, Airflow, Kafka, Hadoop, dbt  
**Cloud:** AWS (S3, EKS, SageMaker, Glue, Lambda), GCP (BigQuery, VertexAI), Azure (AZ-900)  
**Infra:** Docker, Kubernetes, FastAPI, PostgreSQL, MongoDB, Snowflake, Pinecone  

### Certifications

- [TensorFlow Developer Certificate](https://www.credential.net/257ddb28-b131-4b23-ac07-ebd029b271be)
- [Apache Airflow Fundamentals](https://www.credly.com/badges/9d7d4bea-83c1-4dd2-9c2a-f61137f111d5)
- [Microsoft Azure Fundamentals (AZ-900)](https://portal.certiport.com/Portal/Pages/PrintTranscriptInfo.aspx?action=Cert&id=414&cvid=jlqG6GsGh69aqvgbIui9eg==)
- [Deep Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/certificate/6Q6PBHW8AUYH)
- [MLOps Specialization (Duke University)](https://coursera.org/share/95479c26b1e6b75b83aba2d0cb1722fb)
- TOEFL (C1 English)

### Open Source Contributions

Contributions to LLM serving, inference, and agent frameworks — vLLM, Apple MLX, HuggingFace, LangChain, CrewAI, and MCP.

| Project | Framework | Status | Description |
|---------|-----------|--------|-------------|
| [langchain-searchapi](https://github.com/axiom-of-choice/langchain-searchapi) | LangChain | Published | Standalone PyPI package — multi-engine search tool + RAG retriever for SearchApi.io |
| [vllm-gguf-plugin #73](https://github.com/vllm-project/vllm-gguf-plugin/pull/73) | vLLM | Merged | Removed the Blackwell bf16 restriction to unblock GGUF inference on RTX 50-series / B200 — root-caused from a docs bug and fixed at the plugin level at a maintainer's request |
| [LangChain Docs #4703](https://github.com/langchain-ai/docs/pull/4703) | LangChain | Merged | Official integration docs for SearchApi.io |
| [mlx-lm #1634](https://github.com/ml-explore/mlx-lm/pull/1634) | Apple MLX | Open | Incremental shard materialization in `save_model` to avoid GPU watchdog timeouts on large checkpoints |
| [smolagents #2453](https://github.com/huggingface/smolagents/pull/2453) | HuggingFace | Open | `SearchApiSearchTool` with multi-engine support |
| [smolagents #2454](https://github.com/huggingface/smolagents/pull/2454) | HuggingFace | Open | Memory summarization to prevent context-window overflow on long runs |
| [smolagents #2455](https://github.com/huggingface/smolagents/pull/2455) | HuggingFace | Open | `chat_history` parameter on `agent.run()` for multi-turn conversations |
| [smolagents #2460](https://github.com/huggingface/smolagents/pull/2460) | HuggingFace | Open | Preserve successful results when parallel tool calls partially fail |
| [smolagents #2459](https://github.com/huggingface/smolagents/pull/2459) | HuggingFace | Open | Replaced `assert` with an explicit check in `_validate_final_answer` |
| [smolagents #2461](https://github.com/huggingface/smolagents/pull/2461) | HuggingFace | Open | Respect an explicit `max_steps=0` via an `is not None` check |
| [CrewAI #6434](https://github.com/crewAIInc/crewAI/pull/6434) | CrewAI | Open | `SearchApiSearchTool` with multi-engine support for agent workflows |
| [CrewAI #6440](https://github.com/crewAIInc/crewAI/pull/6440) | CrewAI | Open | Hardened error handling in config parsing, callbacks, and async execution |
| [MCP Servers #4459](https://github.com/modelcontextprotocol/servers/pull/4459) | MCP | Open | Configurable request timeout for long-running tool calls |
| [gpt-researcher #1849](https://github.com/assafelovic/gpt-researcher/pull/1849) | gpt-researcher | Open | Use a session for PDF downloads so the configured User-Agent is respected |

### Featured Projects

| Project | Description |
|---------|-------------|
| [LLM Chatbot](https://github.com/axiom-of-choice/LLM-Chatbot) | Generative QA with Vector DB (Pinecone) + Streamlit |
| [AI Disease Diagnoser](https://github.com/axiom-of-choice/ai-disease-diagnoser) | Symptom analysis with LLMs on GCP serverless |
| [GEC System](https://github.com/axiom-of-choice/GEC-system) | Grammar Error Correction with T5 and OpenAI |
| [CONAGUA ELT](https://github.com/axiom-of-choice/etl-conagua) | Weather data pipeline (Airflow, Docker, S3, BigQuery) |
| [CONAGUA Scala](https://github.com/axiom-of-choice/etl-conagua-scala) | Same pipeline in Scala/Spark |

### Languages

- English (C1, TOEFL) | Spanish (Native) | Portuguese (Learning)

### Connect

- [LinkedIn](https://www.linkedin.com/in/isaac-hernandez-garcia-9905/)
- [Website](https://axiom-of-choice.github.io)

---

![Leetcode Stats](https://leetcard.jacoblin.cool/axiom-of-choice)
