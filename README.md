# Isaac Hernandez

## Staff AI Engineer | ML Engineer | Data Engineer

AI Engineer with 5+ years of experience building end-to-end AI and data solutions across fintech, healthtech, and e-commerce. Specialized in taking ML models from research to production at scale.

**Bachelor of Mathematics**, UNAM (GPA: 92/100)

---

### Currently

- **Staff AI Engineer** @ [VerveMarket](https://shop.vervemarket.com). Working directly with the CTO to own AI/Data strategy and infrastructure. Leading hybrid search, a customer-facing autonomous agent that acts on the live catalog and cart, LLM fine-tuning, multimodal image generation pipelines, and evaluation infrastructure (deterministic, statistical, LLM-as-judge) for batch and real-time serving.
- Previously: **Lead AI Engineer** @ [Contpaqi](https://www.contpaqi.com) | **Lead R&D** @ [SoftServe](https://www.softserveinc.com/en-us) | **Sr ML Engineer** @ [Nubank](https://nubank.com.br/en/) | **Sr Data Engineer** @ [Citigroup](https://www.citigroup.com) | **AI Engineer** @ [Botco AI](https://botco.ai) | **Sr ML Engineer** @ [BBVA AI Factory](https://www.bbvaaifactory.com)

### Highlights

- Hybrid search at **VerveMarket** driving a 27% add-to-cart conversion lift at ~100K requests/day
- Real-time underwriting risk models at **Nubank** (Top LATAM Fintech), 3M+ monthly credit decisions on K8s
- 4+ PB Data Lake migration at **Citigroup** (S3, Snowflake, Spark on EKS)
- Agentic AI platforms for healthcare (**SoftServe**) and accounting (**Contpaqi**)
- RAG pipelines and LLM fine-tuning (GPT, LLaMA) at **Botco AI**, 1M+ documents indexed
- Anti-fraud graph ML models at **BBVA AI Factory**

### Tech Stack

**Languages:** Python, Scala, SQL, Golang, Rust (familiar)  
**AI/ML & Agents:** PyTorch, TensorFlow, HuggingFace, LangGraph, LlamaIndex, CrewAI, MCP, RAG  
**Serving & Optimization:** vLLM, TGI, Ollama, MLX, Apple Neural Engine, quantization (GGUF, MLX), LoRA / QLoRA, Unsloth  
**Training Data:** synthetic dataset generation, distillation, SFT curation, quality gating  
**Evaluation:** LLM-as-judge, significance testing, Arize, LangSmith, OpenTelemetry  
**Data:** Spark, Airflow, Kafka, Hadoop, dbt, Databricks  
**Cloud:** AWS (S3, EKS, SageMaker, Glue, Lambda), GCP (BigQuery, VertexAI), Azure (AZ-900)  
**Infra:** Docker, Kubernetes, FastAPI, PostgreSQL/pgvector, MongoDB, Cassandra, Firebase, Snowflake, Pinecone  

### Certifications

- [TensorFlow Developer Certificate](https://www.credential.net/257ddb28-b131-4b23-ac07-ebd029b271be)
- [Apache Airflow Fundamentals](https://www.credly.com/badges/9d7d4bea-83c1-4dd2-9c2a-f61137f111d5)
- [Microsoft Azure Fundamentals (AZ-900)](https://portal.certiport.com/Portal/Pages/PrintTranscriptInfo.aspx?action=Cert&id=414&cvid=jlqG6GsGh69aqvgbIui9eg==)
- [Deep Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/certificate/6Q6PBHW8AUYH)
- [MLOps Specialization (Duke University)](https://coursera.org/share/95479c26b1e6b75b83aba2d0cb1722fb)
- TOEFL (C1 English)

### Open Source

#### Published work

| Project | Area | What it is |
|---------|------|------------|
| [Bespoke-Stratos-ES](https://huggingface.co/datasets/axiom-of-choice/bespoke-stratos-es) | Dataset / distillation | 16K-row Spanish reasoning dataset for SFT, distilled from DeepSeek V4 Flash. Traces are generated natively in Spanish rather than machine-translated, and gated on language dominance and truncation |
| [es-reasoning adapters](https://huggingface.co/axiom-of-choice) | Fine-tuning | LoRA and QLoRA adapters that make [Qwen3-4B](https://huggingface.co/axiom-of-choice/qwen3-4b-es-reasoning-qlora), Qwen3-1.7B and [Gemma-3-4B](https://huggingface.co/axiom-of-choice/gemma-3-4b-es-reasoning-qlora) reason in Spanish, trained on the dataset above and published for MLX, PEFT and GGUF. Measured on a held-out Spanish GSM8K split with paired McNemar tests: Qwen3-4B gains 7.4 accuracy points alongside perfect Spanish (p = 0.0031), Gemma-3-4B gains 27.9 and a thinking mode it did not have, Qwen3-1.7B trades 5.7 points for it and its model card says so |
| [mlx-community](https://huggingface.co/mlx-community) | Quantization | MLX quantizations for Apple Silicon, including the first MLX port of NVIDIA's Nemotron-Parse OCR architecture, published with measured OCR fidelity. |
| [langchain-searchapi](https://github.com/axiom-of-choice/langchain-searchapi) · [llama-index-tools-searchapi](https://github.com/axiom-of-choice/llama-index-tools-searchapi) | Agent tooling | Two standalone PyPI packages bringing multi-engine web search to LangChain and LlamaIndex |

#### Contributions

Links go to the pull requests.

| Project | Area | Status |
|---------|------|--------|
| [ANEForge](https://github.com/sbryngelson/ANEForge/pulls?q=author%3Aaxiom-of-choice) | Apple Neural Engine | Ongoing contributor |
| [mlx](https://github.com/ml-explore/mlx/pulls?q=author%3Aaxiom-of-choice) | Apple Silicon inference | Contributor |
| [mlx-lm](https://github.com/ml-explore/mlx-lm/pulls?q=author%3Aaxiom-of-choice) | Apple Silicon inference | Contributor |
| [vLLM GGUF plugin](https://github.com/vllm-project/vllm-gguf-plugin/pulls?q=author%3Aaxiom-of-choice) | LLM serving | Contributor |
| [OpenInference](https://github.com/Arize-ai/openinference/pulls?q=author%3Aaxiom-of-choice) | LLM observability | Contributor |
| [LangChain Docs](https://github.com/langchain-ai/docs/pulls?q=author%3Aaxiom-of-choice) | Documentation | Contributor |
| [coremltools](https://github.com/apple/coremltools/pull/2814) | Apple Neural Engine | In review |
| [tokenizers](https://github.com/huggingface/tokenizers/pull/2333) | Tokenization / Rust | In review |
| [inspect_ai](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4832) | Model evaluation | In review |
| [LiteLLM](https://github.com/BerriAI/litellm/pulls?q=author%3Aaxiom-of-choice) | LLM gateway | In review |
| [langchain-google](https://github.com/langchain-ai/langchain-google/pulls?q=author%3Aaxiom-of-choice) | LangChain | In review |
| [smolagents](https://github.com/huggingface/smolagents/pulls?q=author%3Aaxiom-of-choice) | Agent framework | In review |
| [CrewAI](https://github.com/crewAIInc/crewAI/pulls?q=author%3Aaxiom-of-choice) | Agent framework | In review |
| [MCP Servers](https://github.com/modelcontextprotocol/servers/pull/4459) | Agent tooling | In review |
| [gpt-researcher](https://github.com/assafelovic/gpt-researcher/pull/1849) | Research agents | In review |

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
