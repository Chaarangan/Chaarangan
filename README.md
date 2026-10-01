<div align="center">

# Hi, I'm Charangan

**Engineering Manager at [Iterate.ai](https://www.iterate.ai/)** · I lead the 12-member team building Generate, an enterprise AI platform

[![LinkedIn](https://img.shields.io/badge/LinkedIn-charangan-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/charangan/) [![Google Scholar](https://img.shields.io/badge/Google_Scholar-profile-4285F4?logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=-tDp1vUAAAAJ) [![Hugging Face](https://img.shields.io/badge/Hugging_Face-Charangan-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/Charangan) [![Website](https://img.shields.io/badge/Website-chaarangan.github.io-222?logo=githubpages)](https://chaarangan.github.io)

</div>

Generate runs as multi-tenant SaaS and also installs air-gapped inside regulated industries, as one system in both places. We build it alongside NetApp, AMD, Intel, IBM, and HP. It has won AI Product of the Year from both Pinnacle and TMC, and put Iterate.ai on the CRN AI 100.

## What I work on

- **RAG and multi-agent orchestration** on LangGraph, with 94% extraction accuracy on documents that break naive RAG
- **Multi-cloud, on-prem, and edge deployment**, including quantized models running fully local on an Intel AI PC
- **Event-driven backend** on Kafka, FastAPI, and Kubernetes, holding 99.8% uptime at 50,000+ requests/second
- **Tenant isolation**, with permission-filtered vector search and sandboxed code execution
- **Engineering leadership**: hiring, mentorship, and roadmap for a team grown from 6 to 12

<details>
<summary>More on the platform work</summary>

- Deployment targets are AWS and IBM Cloud, on-prem racks, and quantized models (GGUF, INT8/FP16) on Intel, AMD, and NVIDIA.
- The backend is observed through OpenTelemetry and Prometheus/Grafana.
- SSO identities resolve to POSIX UID/GID, so vector search is permission-filtered before it runs. Model-generated code executes under gVisor or Kata.
- The team includes 2 tech leads and 2 project managers, and I have promoted engineers into senior roles.

</details>

## Open source

| Project | What it is | Traction |
|---|---|---|
| [Stepgate](https://github.com/Chaarangan/stepgate) | MCP server that shows an agent one step at a time and moves on only when mechanical checks pass | [![Stars](https://img.shields.io/github/stars/Chaarangan/stepgate?style=flat)](https://github.com/Chaarangan/stepgate/stargazers) [![Forks](https://img.shields.io/github/forks/Chaarangan/stepgate?style=flat)](https://github.com/Chaarangan/stepgate/forks) [![npm downloads](https://img.shields.io/npm/d18m/stepgate?style=flat)](https://www.npmjs.com/package/stepgate) |
| [MedBERT](https://huggingface.co/Charangan/MedBERT) | Biomedical language model for named entity recognition | [![Hugging Face downloads](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fhuggingface.co%2Fapi%2Fmodels%2FCharangan%2FMedBERT%3Fexpand%3DdownloadsAllTime&query=%24.downloadsAllTime&label=downloads&style=flat)](https://huggingface.co/Charangan/MedBERT) |
| [NERP](https://github.com/Chaarangan/NERP) | Python framework for transformer-based named entity recognition | [![PyPI downloads](https://static.pepy.tech/badge/nerp)](https://pepy.tech/project/nerp) |

## Research

- MASc in Electrical & Computer Engineering, McMaster University, and BSc (Hons.) in Computer Science & Engineering, University of Moratuwa
- 254+ citations across NLP, biomedical NER, and low-resource languages (Tamil and Sinhala)
- Co-inventor on 4 filed US patents in document extraction and multi-agent AI workflows
- Edge AI work shipped to 10,000+ Intel AI PCs and was demoed at the Intel Vision 2024 keynote

Happy to talk about applied AI, RAG at scale, edge and air-gapped deployment, or building engineering teams.
