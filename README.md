# site-audit-agent

> AI agent that audits a website — crawls it, runs real SEO, accessibility and performance checks as tools, and writes a prioritised fix report. With evals.

![status](https://img.shields.io/badge/status-in%20progress-yellow) ![area](https://img.shields.io/badge/area-AI%20Engineering-blue) ![license](https://img.shields.io/badge/license-MIT-green)

🚧 **Work in progress.** This repo is part of my public learning roadmap (**Phase 4 — AI engineering**). I build in the open — follow the commits and the roadmap below.

## Why this project

Agentic AI on a task I do for clients every week: turn a URL into a clear, prioritised list of fixes — grounded in real tool results, not guesses.

## What I'm learning

- Agent loops and tool calling
- Structured output and validation
- Wrapping real tools: crawler, Lighthouse, accessibility checker
- Evals: measuring report accuracy against known issues
- Tracking cost and latency

## Planned stack

Python · LLM API (tool use) · Playwright · Lighthouse · axe-core · pydantic · pytest

## Roadmap

- [ ] Crawler tool: pages, titles, meta tags, links, status codes
- [ ] Checks as tools: SEO, accessibility, performance
- [ ] Agent loop that decides which checks to run
- [ ] Structured report (issue, evidence, impact, fix)
- [ ] Eval set: test sites with known issues + scoring
- [ ] CLI + Markdown/HTML report output
- [ ] Cost and latency tracking
- [ ] README: example report and eval results

## Part of a 10-repo learning roadmap

I'm a full-stack developer in Vilnius ([armansalek.com](https://armansalek.com)) growing into **Python, Go, DevOps, cloud and AI engineering**. These repos connect: the Python and Go services are containerised, deployed and monitored by the DevOps and cloud repos, and the AI projects run on that infrastructure.

| # | Repo | Area | Phase |
|---|---|---|---|
| 1 | [lt-jobs-scraper](https://github.com/arman-aru/lt-jobs-scraper) | Python | 1 |
| 2 | [lt-vocab-api](https://github.com/arman-aru/lt-vocab-api) | Python | 1 |
| 3 | [parcel-locker-api](https://github.com/arman-aru/parcel-locker-api) | Golang | 1 |
| 4 | [go-uptime](https://github.com/arman-aru/go-uptime) | Golang | 1 |
| 5 | [ci-cd-pipelines](https://github.com/arman-aru/ci-cd-pipelines) | DevOps | 2 |
| 6 | [k8s-gitops-lab](https://github.com/arman-aru/k8s-gitops-lab) | DevOps | 2 |
| 7 | [terraform-aws-platform](https://github.com/arman-aru/terraform-aws-platform) | Cloud Computing | 3 |
| 8 | [serverless-media-pipeline](https://github.com/arman-aru/serverless-media-pipeline) | Cloud Computing | 3 |
| 9 | **site-audit-agent** (this repo) | AI Engineering | 4 |
| 10 | [migration-rag-assistant](https://github.com/arman-aru/migration-rag-assistant) | AI Engineering | 4 |

## License

[MIT](LICENSE) © Arman Salek
