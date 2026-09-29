# Harsh Shroff

AI/ML engineer focused on agentic systems and on-device vision-language models. I build things that have to work outside a notebook: multi-agent pipelines with quality checks, and offline models running on constrained edge hardware.

MS Data Science, University of Maryland, Baltimore County. AWS Certified Machine Learning (valid through April 2028).

[Portfolio](https://harshshroff.github.io) · [LinkedIn](https://linkedin.com/in/harshroff) · [Email](mailto:harshrofff@gmail.com)

## Selected work

**[MARS: Multi-Agent Research System](https://github.com/HarshShroff/multi-agent-researcher)**
An autonomous research pipeline built on LangGraph with 11 specialized agents, a quality-control retry loop, and citation grounding. Ships as a Streamlit app and as an MCP server that other clients can call. Python, LangGraph, Pydantic, MCP.

**[vLLM inference benchmark](https://github.com/HarshShroff/vllm-inference-benchmark)**
A controlled comparison of vLLM's continuous batching against a naive Hugging Face generate loop, run on a single T4 with Qwen2.5-3B. Measured roughly a 1.6x to 2.2x throughput gain on matched workloads. The repo includes the harness, fixed prompt set, raw results and plots so the numbers can be reproduced.

**[Bio-Oracle](https://github.com/HarshShroff/Bio-Oracle)**
A neuro-symbolic agent for phenotypic screening in drug discovery. Cellpose handles segmentation and a PydanticAI agent reasons over the extracted cell features. Validated on the public BBBC021 drug-screen dataset; the README reports the segmentation and outlier-detection results.

**[Silicon Oracle](https://github.com/HarshShroff/Silicon-Oracle)**
A full-stack stock analysis platform with a 15-factor scoring engine, a paper-trading portfolio tracker and Gemini-generated alerts. Flask, PostgreSQL (Supabase), and a pytest suite. Built as an educational tool, not investment advice.

## What I work with

- **Agents and LLM systems:** LangGraph, PydanticAI, MCP, RAG, evaluation and QC loops, Claude and Gemini APIs
- **Inference and edge:** vLLM, Ollama, Jetson (Orin), on-device VLMs, speech-to-text and text-to-speech pipelines
- **Computer vision:** YOLOv8, DINOv2, CLIP, Cellpose
- **Languages and infrastructure:** Python, JavaScript, C, Bash, AWS (Bedrock, Lambda, S3), Docker, PostgreSQL

## Publications

- ITU Kaleidoscope 2021, TinyML

## Open source

I review and contribute to the projects I use, currently in the vLLM ecosystem. AI assistance is disclosed wherever I use it.
