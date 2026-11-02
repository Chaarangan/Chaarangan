<div align="center">

# Hi, I'm Charangan

**Software Engineering Manager at [Iterate.ai](https://www.iterate.ai/)** · I lead the 12-person team building Generate, an enterprise AI platform

[![LinkedIn](https://img.shields.io/badge/LinkedIn-charangan-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/charangan/) [![Google Scholar](https://img.shields.io/badge/Google_Scholar-profile-4285F4?logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=-tDp1vUAAAAJ) [![Hugging Face](https://img.shields.io/badge/Hugging_Face-Charangan-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/Charangan) [![Website](https://img.shields.io/badge/Website-chaarangan.github.io-222?logo=githubpages)](https://chaarangan.github.io)

</div>

I architected Generate from scratch and now manage its team through 2 tech leads and 2 project managers. We run AI-native: every change starts as a spec, and AI agents write the code. Generate ships as multi-tenant SaaS and installs air-gapped inside regulated industries, built alongside NetApp, AMD, Intel, HP, and IBM. It has won AI Product of the Year from both Pinnacle and TMC, and put Iterate.ai on the CRN AI 100.

## How I lead

- **Team building**: grew the team from 6 to 12 in a year, sourcing and closing 6 hires and promoting 2 engineers to Senior Applied AI Engineer
- **AI-native delivery**: moved the team from Windsurf to Claude Code with spec-driven development, so 100% of production code is now written by AI and work that took a month ships in a week
- **One engineer, end to end**: consolidated separate repos and per-customer branches into one monorepo with GitHub Projects automation, so each engineer ships a feature without cross-repo handoffs
- **Customer solution architecture**: I design solutions with customers and work directly with product, design, data/analytics, and partner engineers, bringing engineers in when the work needs them
- **Model governance**: a 12-point compatibility suite certifies every model before it reaches production

## What I build

- **RAG and multi-agent orchestration** on LangGraph, with 94% extraction accuracy on documents that break naive RAG
- **Cloud, on-prem, and edge deployment** from one codebase, holding 99.8% uptime at 50,000+ requests/second with infrastructure cost cut 33%
- **Tenant isolation**, with permission-filtered vector search and sandboxed code execution

<details>
<summary>More on the platform work</summary>

- Deployment targets are AWS and IBM Cloud, on-prem racks, and quantized models (GGUF, INT8/FP16) on Intel, AMD, and NVIDIA.
- The backend runs on Kafka, FastAPI, and Kubernetes, observed through OpenTelemetry and Prometheus/Grafana.
- SSO identities resolve to POSIX UID/GID, so vector search is permission-filtered before it runs. Model-generated code executes under gVisor or Kata.

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

Happy to talk about building AI-native engineering teams, spec-driven development, or enterprise AI that ships air-gapped.
