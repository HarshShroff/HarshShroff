# Harsh Shroff

I build agentic systems and on-device vision-language models, and I measure them. Multi-agent pipelines with quality checks that catch their own mistakes, and offline models that run on the hardware a person actually carries.

Currently: open to AI/ML engineering roles, especially forward-deployed and applied-agent work. Reviewing inference-tooling PRs in the vLLM ecosystem in my spare time.

[Portfolio](https://harshshroff.github.io) · [LinkedIn](https://linkedin.com/in/harshroff) · [Email](mailto:harshrofff@gmail.com)

## Projects

**[MARS](https://github.com/HarshShroff/multi-agent-researcher): multi-agent research system** ([live demo](https://mars-multi-agent-researcher.streamlit.app))
Eleven LangGraph agents produce a citation-grounded report on any topic. A QC agent scores the draft and sends it back for another pass when it falls short, and a citation verifier checks sources. Runs as a Streamlit app and as an MCP server other clients can call.

**[vLLM vs. naive Hugging Face: inference benchmark](https://github.com/HarshShroff/vllm-inference-benchmark)**
Tested the vendor claim instead of repeating it. On one T4 with Qwen2.5-3B, vLLM's continuous batching gave roughly 1.6x to 2.2x the throughput of a naive generate loop on matched workloads. The harness, prompt set, raw results and plots are in the repo.

**[Bio-Oracle](https://github.com/HarshShroff/Bio-Oracle): agent for drug-discovery screening**
Cellpose segments microscopy images and a PydanticAI agent reasons over the extracted cell features. Validated on the public BBBC021 drug-screen data; results are in the README.

**[Silicon Oracle](https://github.com/HarshShroff/Silicon-Oracle): stock analysis platform**
A 15-factor scoring engine, a paper-trading tracker and Gemini-written alerts, on Flask and Postgres with a pytest suite. An educational tool, not investment advice.

## Open-source reviews

Recent substantive reviews on vLLM-project repos, each with reproduced checks. AI assistance is disclosed on every one.

- [guidellm #1194](https://github.com/vllm-project/guidellm/pull/1194): confirmed a percentile off-by-one fix and found the same bug in the HTML report's JavaScript
- [vLLM #56918](https://github.com/vllm-project/vllm/pull/56918): verified a per-user throughput fix and pointed out when the bug actually triggers
- [guidellm #1182](https://github.com/vllm-project/guidellm/pull/1182): found gaps in the secret redaction for captured server config

## Stack

**Agents and LLMs:** LangGraph, PydanticAI, MCP, RAG, evals, Claude and Gemini APIs
**Inference and edge:** vLLM, Ollama, NVIDIA Jetson Orin, on-device VLMs, offline speech pipelines
**Vision:** YOLOv8, DINOv2, CLIP, Cellpose
**Everything else:** Python, JavaScript, C, Bash, AWS (Bedrock, Lambda, S3), Docker, PostgreSQL

MS Data Science, UMBC · AWS Certified Machine Learning · ITU Kaleidoscope 2021, TinyML
