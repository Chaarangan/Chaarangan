<div align="center">

# Hi, I'm Charangan

**Engineering Manager, AI Platform Architecture, at [Iterate.ai](https://www.iterate.ai/)** · I architect Generate, an enterprise agentic AI platform, and lead the team that builds it

[![LinkedIn](https://img.shields.io/badge/LinkedIn-charangan-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/charangan/) [![Google Scholar](https://img.shields.io/badge/Google_Scholar-profile-4285F4?logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=-tDp1vUAAAAJ) [![Hugging Face](https://img.shields.io/badge/Hugging_Face-Charangan-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/Charangan) [![Website](https://img.shields.io/badge/Website-chaarangan.github.io-222?logo=githubpages)](https://chaarangan.github.io)

</div>

I architected Generate from scratch, still own its architecture, and lead the team that builds it. We run an AI-native SDLC, where every change starts as a spec and AI agents write the code. Generate ships as multi-tenant SaaS and installs air-gapped, down to STIG-hardened, FIPS-enabled RHEL for a U.S. Federal Defense Agency. Hospitals run it on claims data through Cerner, and Vuori runs scheduled retail agents on it. It is built alongside NetApp, AMD, Intel, HP, and IBM. It has won AI Product of the Year from both Pinnacle and TMC, and put Iterate.ai on the CRN AI 100.

## How I lead

- **Team building**: doubled the team in a year, sourcing and closing 6 hires and promoting 2 engineers to Senior Applied AI Engineer
- **AI-native delivery**: moved the team from Windsurf to Claude Code in VS Code with spec-driven development. AI writes 100% of production code, a task that took 4 to 5 weeks now ships in a week, and merged PRs are up 65% to 95%
- **One engineer, end to end**: consolidated separate repos and per-customer branches into one monorepo with GitHub Projects automation, so each engineer ships a feature without cross-repo handoffs
- **Customer solution architecture**: I design solutions with customers and work directly with product, design, data/analytics, and partner engineers, bringing engineers in when the work needs them
- **Model governance**: every model passes a compatibility suite before it serves a platform AI service, and versioned policies and DLP attach to any project, agent, or workflow

## What I build

- **Permission-aware file search** over 400 TB+ of enterprise storage at p95 under 1 s, with no embeddings and no content index (patent pending)
- **Agent runtime** on LangGraph with human-in-the-loop approval, per-session gVisor or Kata sandboxes, and graph memory on Neo4j or Amazon Neptune
- **Generate Sentinel**, the release plane: one-command online and air-gapped installs, with releases published from GitHub Actions through OIDC roles into AWS
- **Document intelligence**, with 94% extraction accuracy on documents that break naive RAG
- **Cloud, on-prem, and edge deployment** from one codebase, holding 99.8% uptime at 50,000+ requests/second with infrastructure cost cut 33%
- **Storage editions with NetApp**, where retrieval over customer data on ONTAP respects each user's file permissions

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
- 261+ citations across NLP, biomedical NER, and low-resource languages (Tamil and Sinhala)
- Co-inventor on 5 pending US patent applications in permission-aware search, document extraction, and multi-agent AI workflows
- Edge AI work shipped to 10,000+ Intel AI PCs and was demoed at the Intel Vision 2024 keynote

Happy to talk about agent infrastructure, AI-native engineering teams, or enterprise AI that ships air-gapped.
