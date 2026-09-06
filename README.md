# Hi, I'm Charangan

I am an Engineering Manager at [Iterate.ai](https://www.iterate.ai/), where I lead a 12-member
cross-functional team building Generate, our enterprise AI platform. Generate runs as
multi-tenant SaaS, and it also installs air-gapped inside regulated industries. It is the same
system in both places, which is most of what makes it hard. We build it alongside IBM, NetApp,
Intel, AMD, and HP.

## What I work on

- RAG, multi-agent orchestration on LangGraph, and document intelligence at production scale.
  We get 94% extraction accuracy on the documents that break naive RAG.
- Multi-cloud, on-prem, and edge deployment. That means AWS and IBM Cloud, on-prem racks, and
  quantized models (GGUF, INT8/FP16) running on Intel, AMD, and NVIDIA. Private document search
  runs entirely local on an Intel AI PC.
- An event-driven backend on Kafka, FastAPI, and Kubernetes. It holds 99.8% uptime at a peak of
  50,000+ requests/second, observed through OpenTelemetry and Prometheus/Grafana.
- Tenant isolation and multi-tenant security. SSO identities resolve to POSIX UID/GID, so vector
  search is permission-filtered before it runs, and model-generated code executes sandboxed
  under gVisor or Kata.
- Engineering leadership. I do hiring, mentorship, roadmap, and partnership engineering. The
  team has grown from 6 to 12, including 2 tech leads and 2 project managers, and I have
  promoted engineers into senior roles.

## About me

Before management I spent years as a researcher and ML engineer. I hold an MASc in Electrical
& Computer Engineering from McMaster University, where my thesis was a retrieval-focused
fine-tuning strategy for scientific documents, and a BSc (Hons.) in Computer Science &
Engineering from the University of Moratuwa.

A few things from that stretch are still in use:

- [MedBERT](https://huggingface.co/Charangan/MedBERT), a biomedical language model I
  pre-trained, has passed 569,000+ downloads.
- [NERP](https://github.com/Chaarangan/NERP), an open-source Python framework for
  transformer-based named entity recognition, has 71,000+ PyPI downloads.
- I co-invented 4 filed US patents in document extraction and multi-agent AI workflows.
- My published research has 248+ citations across NLP, biomedical NER, and low-resource
  languages (Tamil and Sinhala).
- Edge AI work shipped to 10,000+ Intel AI PCs through the Intel Software Advantage Program,
  and was demoed at the Intel Vision 2024 keynote.

Generate has since won AI Product of the Year from both Pinnacle and TMC, and it put Iterate.ai
on the CRN AI 100 as a top-20 hottest AI software company.

## Elsewhere

Happy to talk about applied AI, RAG at scale, edge and air-gapped deployment, or building and
leading engineering teams.

- [LinkedIn](https://www.linkedin.com/in/charangan/)
- [Google Scholar](https://scholar.google.com/citations?user=-tDp1vUAAAAJ)
- [Hugging Face](https://huggingface.co/Charangan)
- [chaarangan.github.io](https://chaarangan.github.io)
