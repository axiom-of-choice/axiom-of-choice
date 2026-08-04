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
**Training Data:** synthetic dataset generation, distillation, SFT curation, quantization  
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

Work across LLM serving, on-device inference, observability, and agent frameworks. Datasets and quantized models on [Hugging Face](https://huggingface.co/axiom-of-choice).

| Project | Area | Status | Contribution |
|---------|------|--------|--------------|
| [Bespoke-Stratos-ES](https://huggingface.co/datasets/axiom-of-choice/bespoke-stratos-es) | Dataset / distillation | Published | 16K-row Spanish reasoning dataset for SFT, distilled from DeepSeek V4 Flash. Traces natively generated in Spanish, not machine-translated, gated on language dominance and truncation |
| [mlx-community](https://huggingface.co/mlx-community/AREX-Turbo-4bit) | Quantization | Published | 4/6/8-bit MLX quantizations of a 4.5B agentic VLM, each evaluated against the bf16 source on perplexity, KL divergence, task accuracy, and blind pairwise LLM-judge quality |
| [ANEForge](https://github.com/sbryngelson/ANEForge) | Apple Neural Engine | 9 merged | Ongoing contributor: ONNX operator coverage, `linalg` (matrix norms, `matrix_power`, `solve`, `expm`), einsum diagonal extraction, int8 quantization gated on activation-encoding range, and the roofline benchmark harness |
| [vLLM](https://github.com/vllm-project/vllm-gguf-plugin/pull/73) | LLM serving | Merged | Enabled bf16 GGUF inference on Blackwell (sm_100) by removing a stale device-capability guard, after verifying the Triton and CUDA dequantization backends handle bf16 output |
| [OpenInference](https://github.com/Arize-ai/openinference) | LLM observability | Merged | Recorded Anthropic cache read/write token details on streaming instrumentation paths |
| [langchain-searchapi](https://github.com/axiom-of-choice/langchain-searchapi) | LangChain | Published | Standalone PyPI package: multi-engine search tool and RAG retriever for SearchApi.io, plus the official integration docs upstream |
| [smolagents](https://github.com/huggingface/smolagents/pulls?q=author%3Aaxiom-of-choice) | HuggingFace agents | In review | Multi-engine search tool, memory summarization for long runs, multi-turn `chat_history`, and partial-failure handling for parallel tool calls |
| [LiteLLM](https://github.com/BerriAI/litellm/pulls?q=author%3Aaxiom-of-choice) | LLM gateway | In review | Bedrock error handling for malformed tool-call arguments; router pre-call checks counting embedding input as text |
| [MLX](https://github.com/ml-explore/mlx-lm/pull/1634) | Apple Silicon inference | In review | Incremental weight materialization when saving large checkpoints, to avoid the Metal GPU watchdog timeout |
| [CrewAI](https://github.com/crewAIInc/crewAI/pulls?q=author%3Aaxiom-of-choice) | Agent framework | In review | Multi-engine search tool; error handling in config parsing, callbacks, and async execution |
| [MCP Servers](https://github.com/modelcontextprotocol/servers/pull/4459) | Agent tooling | In review | Configurable request timeout in the fetch server for long-running tool calls |
| [gpt-researcher](https://github.com/assafelovic/gpt-researcher/pull/1849) | Research agents | In review | Session-based PDF downloads so the configured User-Agent is respected |

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
