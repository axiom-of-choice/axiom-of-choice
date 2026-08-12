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

Work across LLM serving, on-device inference, observability, and agent frameworks. Datasets, fine-tuned adapters and quantized models on [Hugging Face](https://huggingface.co/axiom-of-choice).

| Project | Area | Status | Contribution |
|---------|------|--------|--------------|
| [Bespoke-Stratos-ES](https://huggingface.co/datasets/axiom-of-choice/bespoke-stratos-es) | Dataset / distillation | Published | 16K-row Spanish reasoning dataset for SFT, distilled from DeepSeek V4 Flash. Traces natively generated in Spanish, not machine-translated, gated on language dominance and truncation |
| [es-reasoning adapters](https://huggingface.co/axiom-of-choice) | Fine-tuning / distillation | Published | LoRA and QLoRA adapters that make Qwen3-4B, Qwen3-1.7B and Gemma-3-4B reason in Spanish, trained on the dataset above and published for MLX, PEFT and GGUF. Measured on a held-out Spanish GSM8K split with paired McNemar tests: Qwen3-4B gains 7.4 accuracy points alongside perfect Spanish (p = 0.0031), Gemma-3-4B gains 27.9 and a thinking mode it did not have, Qwen3-1.7B trades 5.7 points for it and the model card says so |
| [mlx-community](https://huggingface.co/mlx-community/AREX-Turbo-4bit) | Quantization | Published | 4/6/8-bit MLX quantizations of a 4.5B agentic VLM, each evaluated against the bf16 source on perplexity, KL divergence, task accuracy, and blind pairwise LLM-judge quality |
| [ANEForge](https://github.com/sbryngelson/ANEForge) | Apple Neural Engine | 17 merged, in review | Ongoing contributor: ONNX operator coverage, `linalg` (matrix norms, `matrix_power`, `solve`, `expm`, `inv`, QR-based least squares), einsum diagonal extraction, int8 quantization gating, `erf` as its own polynomial, and the roofline benchmark harness. In review: `layer_norm`'s affine moved off the rank-4 body, which failed to compile on M1/M2 for any real trained affine |
| [coremltools](https://github.com/apple/coremltools/pull/2814) | Apple Neural Engine | In review | Decompose `Softplus` in the TF frontend to avoid fp16 overflow on ANE |
| [vLLM GGUF plugin](https://github.com/vllm-project/vllm-gguf-plugin/pulls?q=author%3Aaxiom-of-choice) | LLM serving | 1 merged, in review | Merged: enabled bf16 GGUF inference on Blackwell (sm_100) by removing a stale device-capability guard, after verifying the Triton and CUDA dequantization backends handle bf16 output. In review: the merged-column and QKV weight loaders read the tensor-parallel rank from a kwarg the v2 loader never passes, so every rank kept rank 0's shard under TP>1 |
| [OpenInference](https://github.com/Arize-ai/openinference) | LLM observability | 2 merged | Anthropic instrumentor: recorded cache read/write token details on the streaming paths, and derived `llm.token_count.total` on the non-streaming path so both paths report the same totals |
| [langchain-searchapi](https://github.com/axiom-of-choice/langchain-searchapi) | LangChain | Published | Standalone PyPI package: multi-engine search tool and RAG retriever for SearchApi.io |
| [llama-index-tools-searchapi](https://github.com/axiom-of-choice/llama-index-tools-searchapi) | LlamaIndex | Published | Standalone PyPI package: LlamaIndex tool integration for the same six SearchApi.io engines |
| [LangChain Docs](https://github.com/langchain-ai/docs/pull/4703) | LangChain | Merged | Official SearchApi.io integration docs: tool, RAG retriever, and agent examples |
| [langchain-google](https://github.com/langchain-ai/langchain-google/pulls?q=author%3Aaxiom-of-choice) | LangChain | In review | `service_tier` support on `ChatGoogleGenerativeAI`, plus the [accompanying docs page](https://github.com/langchain-ai/docs/pull/5452); and schema-aware decoding of the JSON-encoded list and dict tool arguments Gemini returns, which broke Pydantic validation before the tool ever ran |
| [smolagents](https://github.com/huggingface/smolagents/pulls?q=author%3Aaxiom-of-choice) | HuggingFace agents | In review | Multi-engine search tool, memory summarization for long runs, multi-turn `chat_history`, and partial-failure handling for parallel tool calls |
| [LiteLLM](https://github.com/BerriAI/litellm/pulls?q=author%3Aaxiom-of-choice) | LLM gateway | In review | Bedrock error handling for malformed tool-call arguments; router pre-call checks counting embedding input as text |
| [mlx-lm](https://github.com/ml-explore/mlx-lm/pulls?q=author%3Aaxiom-of-choice) | Apple Silicon inference | 1 merged, in review | Merged: LoRA trainer honors `seed=0` in batch shuffling, silently ignored despite being the CLI default. In review: incremental weight materialization to avoid the Metal GPU watchdog timeout, optional gradient clipping and a non-finite guard, best-validation-loss adapter saving with early stopping |
| [mlx](https://github.com/ml-explore/mlx/pulls?q=author%3Aaxiom-of-choice) | Apple Silicon inference | 1 merged, in review | Merged: `hadamard_transform` failed to compile on the GPU for n = 12/20/28, where a missing guard left a divide-by-zero in the step count. In review: `from_fp8` decoded the only two e4m3 NaN encodings as ±480, a value the format cannot represent, on both the CPU and Metal backends |
| [CrewAI](https://github.com/crewAIInc/crewAI/pulls?q=author%3Aaxiom-of-choice) | Agent framework | In review | Multi-engine search tool; error handling in config parsing, callbacks, and async execution |
| [MCP Servers](https://github.com/modelcontextprotocol/servers/pull/4459) | Agent tooling | In review | Configurable request timeout in the fetch server for long-running tool calls |
| [tokenizers](https://github.com/huggingface/tokenizers/pull/2333) | Tokenization / Rust | In review | `BpeBuilder::build()` sized its scratch buffer to the longest vocab token, but a merge writes the concatenation of two, so a crafted `tokenizer.json` panicked on load. Fixed alongside a usize underflow in the same loop |
| [inspect_ai](https://github.com/UKGovernmentBEIS/inspect_ai/pull/4832) | Model evaluation | In review | Tools with an empty or all-optional schema failed to parse when a model emitted the empty argument body with stray quotes. Traced to the wire, not the client, which is where the issue had placed it |
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
