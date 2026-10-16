# site-audit-agent

> AI agent that audits a website — crawls it, runs real SEO, accessibility and performance checks as tools, and writes a prioritised fix report. With evals.

![status](https://img.shields.io/badge/status-in%20development-yellow) ![license](https://img.shields.io/badge/license-MIT-green)

## Overview

An AI agent that audits a website. Give it a URL: it crawls the site, runs real SEO, accessibility and performance checks as tools, and writes a prioritised report of what to fix — grounded in tool results, not guesses.

## Features

- Site crawler: pages, titles, meta tags, links, status codes
- SEO, accessibility (axe-core) and performance (Lighthouse) checks as agent tools
- Agent decides which checks to run for each site
- Prioritised report: issue, evidence, impact and fix
- Evaluation suite measuring report accuracy on test sites
- CLI with Markdown and HTML report output

## Tech stack

Python · LLM API (tool use) · Playwright · Lighthouse · axe-core · pydantic · pytest

## License

[MIT](LICENSE) © Arman Salek
