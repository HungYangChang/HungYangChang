# Technical Writing Strategy

> Option C: Authority Track — Build long-term brand through regular technical content.

---

## Goal

Publish 2 technical articles per month that reinforce the brand: **AI Software Engineer who ships production LLM systems.** Each piece should be useful to practitioners and demonstrate both depth and clarity.

## Content Pillars

### Pillar 1: LLM Systems in Production (Primary)
Topics drawn from real work and hard-won lessons.

- How we designed the function-calling orchestration pipeline
- Multi-agent coordination patterns for automotive AI
- gRPC vs REST for LLM service architectures
- Error handling and fallback strategies in agentic systems
- Prompt engineering patterns that survived production

### Pillar 2: Inference Optimization & Edge AI
Topics drawn from research and engineering overlap.

- Pipeline parallelism for transformer inference on edge devices
- Neural architecture search for deployment-aware models
- Latency vs throughput trade-offs in real-time AI
- Lessons from PipeBERT: what worked, what didn't

### Pillar 3: Engineering Craft (Secondary)
Shorter pieces on software engineering practices.

- Testing strategies for LLM-powered applications
- CI/CD patterns for ML projects
- Async Python patterns for high-throughput services
- Building reliable microservices with gRPC

## Publishing Schedule

| Week | Activity |
|------|----------|
| Week 1 | Outline + research for article A |
| Week 2 | Draft + publish article A |
| Week 3 | Outline + research for article B |
| Week 4 | Draft + publish article B |

## Publishing Platforms

| Platform | Purpose | Frequency |
|----------|---------|-----------|
| **GitHub Blog Repo** | Canonical home, SEO, portfolio link | Every article |
| **Dev.to** | Developer community reach | Cross-post |
| **Medium** | Broader professional reach | Cross-post selected |
| **LinkedIn** | Professional network visibility | Summary + link |

## Article Template

Use the blog post template at `templates/writing/blog-post-template.md`.

## Quality Bar

Every article must have:
- A clear problem statement in the first paragraph
- At least one concrete code example or architecture diagram
- A "what I'd do differently" or "lessons learned" section
- Proofread by at least one person (or AI-assisted review)

## Metrics to Track

- Article views / reads (Dev.to analytics, Medium stats)
- GitHub stars on blog repo
- Inbound messages referencing articles
- Shares on LinkedIn / Twitter

## 90-Day Launch Plan

| Month | Articles | Topics |
|-------|----------|--------|
| Month 1 | 2 | "LLM orchestration patterns" + "Testing agentic systems" |
| Month 2 | 2 | "gRPC for AI microservices" + "Edge inference lessons from PipeBERT" |
| Month 3 | 2 | "Multi-agent coordination" + "CI/CD for ML projects" |
