<div align="center">

<a href="https://github.com/HarshShroff">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=26&duration=3000&pause=1000&color=0EA5E9&center=true&vCenter=true&width=640&lines=Hi%2C+I'm+Harsh+Shroff;AI+Engineer+%E2%80%A2+Agentic+Systems+%E2%80%A2+Edge+VLMs;LangGraph+%E2%80%A2+vLLM+%E2%80%A2+Jetson+%E2%80%A2+MCP" alt="Harsh Shroff: AI engineer, agentic systems, edge VLMs" />
</a>

<br />

<p>
  <img src="https://img.shields.io/badge/Focus-Agentic_AI_%2B_Edge_VLMs-8B5CF6?style=flat-square" alt="Focus: agentic AI and edge VLMs" />
  <img src="https://img.shields.io/badge/Open_to-AI%2FML_Roles-10B981?style=flat-square" alt="Open to AI/ML roles" />
  <a href="https://harshshroff.github.io"><img src="https://img.shields.io/badge/Portfolio-0EA5E9?style=flat-square" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/harshroff"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:harshrofff@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

</div>

---

## About Me

I build agentic systems and on-device vision-language models, and I measure them. Multi-agent pipelines with quality checks that catch their own mistakes, and offline models that run on the hardware a person actually carries.

- M.S. Data Science, **UMBC** (3.8 GPA), AWS Certified Machine Learning
- Applied AI research engineer, UMBC AI and Robotics Center: multimodal perception and multi-agent orchestration for field robots
- Reviewing inference-tooling PRs in the vLLM ecosystem, with checks I reproduce first

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [MARS](https://github.com/HarshShroff/multi-agent-researcher)
*Research reports that check their own sources*

Eleven LangGraph agents turn a topic into a citation-grounded report. A QC agent scores each draft and sends weak ones back for another pass, and a verifier checks every source. Runs as a Streamlit app and as an MCP server other clients can call.

**Stack:** Python · LangGraph · Pydantic · MCP · Gemini · Streamlit

`#agents` `#evals` `#mcp`

</td>
<td width="50%" valign="top">

### [vLLM benchmark](https://github.com/HarshShroff/vllm-inference-benchmark)
*Testing the vendor claim instead of repeating it*

vLLM's continuous batching against a naive Hugging Face generate loop on one T4 with Qwen2.5-3B: roughly 1.6x to 2.2x the throughput on matched workloads. Harness, prompts, raw results and plots are all in the repo.

**Stack:** Python · vLLM · PyTorch · Colab

`#inference` `#benchmarks`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Bio-Oracle](https://github.com/HarshShroff/Bio-Oracle)
*Drug-discovery screening with a reasoning agent on top*

Cellpose segments microscopy images, then a PydanticAI agent answers questions like "which compounds hit the cytoskeleton" using outlier statistics over the extracted features. Validated on the public BBBC021 dataset.

**Stack:** Python · Cellpose · PydanticAI · Gemini · Docker

`#agents` `#vision` `#biotech`

</td>
<td width="50%" valign="top">

### [Silicon Oracle](https://github.com/HarshShroff/Silicon-Oracle)
*Stock analysis with a scoring engine you can audit*

A 15-factor scoring engine, a paper-trading tracker and Gemini-written alerts, with encrypted bring-your-own-key access. Educational, not investment advice.

**Stack:** Flask · PostgreSQL · Supabase · Gemini · pytest

`#fullstack` `#llm`

</td>
</tr>
</table>

---

## Journey

```mermaid
timeline
    title My Path So Far
    2022 : Started M.S. in Data Science at UMBC
    2023 : Joined the UMBC AI and Robotics Center as an applied AI research engineer
         : Built a YOLOv8 vision pipeline at 92% accuracy on edge hardware
    2024 : Finished the M.S.
         : AI Engineer building a production RAG platform on AWS Bedrock
    2026 : Shipped Bio-Oracle, Silicon Oracle, the vLLM benchmark and MARS
         : Started reviewing vLLM-ecosystem PRs
```

---

## Tech I Reach For

<div align="center">

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/vLLM-30A2FF?style=for-the-badge" alt="vLLM" />
  <img src="https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="NVIDIA Jetson" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
</p>

<sub>Also: MCP · PydanticAI · Ollama · YOLOv8 · CLIP · DINOv2 · Cellpose · Flask · JavaScript · C · Bash</sub>

</div>

---

<div align="center">
  <sub>Open-source reviews: <a href="https://github.com/vllm-project/guidellm/pull/1194">guidellm #1194</a> · <a href="https://github.com/vllm-project/vllm/pull/56918">vLLM #56918</a> · <a href="https://github.com/vllm-project/guidellm/pull/1182">guidellm #1182</a></sub>
</div>
