# Awesome MCP Security Ratings

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Independent security ratings for MCP servers and skills.
> Powered by [spiderrating.com](https://spiderrating.com) |
> Scanned by [SpiderShield](https://github.com/teehooai/spidershield)

**26 servers scanned** | Avg score: **3.06/10** | 0.0% Grade A/B | 65.4% Grade F | 23.1% have critical issues

## The State of MCP Security

The MCP ecosystem is growing fast, but security hasn't kept up.
Our automated scans reveal systemic issues across 26 popular MCP servers:

- **Average security score: 3.06/10** -- most servers ship with unvalidated inputs, missing access controls, and poor tool descriptions
- **65.4% received an F grade** -- SSRF, dangerous eval, path traversal, and SQL injection are common
- **Tool descriptions are inadequate** -- LLMs need clear intent, scope boundaries, and error guidance to select tools safely. Most descriptions lack these signals.

This isn't a criticism -- it's an opportunity. Every server here can improve, and we provide [detailed reports](https://spiderrating.com) showing exactly how.

> Want to check your own server? `pip install spidershield && spidershield scan .`

## Contents

- [Database](#database-6-servers)
- [Search](#search-3-servers)
- [AI](#ai-4-servers)
- [Web](#web-1-servers)
- [Filesystem](#filesystem-1-servers)
- [Cloud](#cloud-4-servers)
- [Communication](#communication-1-servers)
- [Devtools](#devtools-2-servers)
- [Utility](#utility-1-servers)
- [Monitoring](#monitoring-2-servers)
- [Reference](#reference-1-servers)
- [Critical Security Issues](#%EF%B8%8F-critical-security-issues)
- [Methodology](#methodology)
- [Contributing](#contributing)

---

## Database (6 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) | C | 5.5 | 11 | 0 | [Details](https://spiderrating.com/s/kiliczsh/mcp-mongo-server) |
| [mcp-server-neon](https://github.com/neondatabase/mcp-server-neon) | D | 4.8 | 0 | 0 | [Details](https://spiderrating.com/s/neondatabase/mcp-server-neon) |
| [supabase-mcp](https://github.com/supabase-community/supabase-mcp) | D | 4.5 | 0 | 0 | [Details](https://spiderrating.com/s/supabase-community/supabase-mcp) |
| [mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp) | F | 2.0 | 0 | 0 | [Details](https://spiderrating.com/s/QuantGeekDev/mongo-mcp) |
| [mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) | F | 2.0 | 2 | 2 (2 crit) | [Details](https://spiderrating.com/s/benborla/mcp-server-mysql) |
| [postgres-mcp](https://github.com/crystaldba/postgres-mcp) | F | 2.0 | 0 | 1 (1 crit) | [Details](https://spiderrating.com/s/crystaldba/postgres-mcp) |

## Search (3 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [tavily-mcp](https://github.com/tavily-ai/tavily-mcp) | C | 5.4 | 6 | 0 | [Details](https://spiderrating.com/s/tavily-ai/tavily-mcp) |
| [exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) | F | 2.0 | 0 | 0 | [Details](https://spiderrating.com/s/exa-labs/exa-mcp-server) |
| [context7](https://github.com/upstash/context7) | F | 2.0 | 1 | 24 (5 crit) | [Details](https://spiderrating.com/s/upstash/context7) |

## AI (4 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [langchain-mcp-adapters](https://github.com/langchain-ai/langchain-mcp-adapters) | C | 5.4 | 18 | 0 | [Details](https://spiderrating.com/s/langchain-ai/langchain-mcp-adapters) |
| [mcp-server-openai](https://github.com/pierrebrunelle/mcp-server-openai) | F | 2.0 | 0 | 0 | [Details](https://spiderrating.com/s/pierrebrunelle/mcp-server-openai) |
| [ai](https://github.com/vercel/ai) | F | 1.8 | 125 | 23 (5 crit) | [Details](https://spiderrating.com/s/vercel/ai) |
| [pydantic-ai](https://github.com/pydantic/pydantic-ai) | F | 1.7 | 24 | 11 | [Details](https://spiderrating.com/s/pydantic/pydantic-ai) |

## Web (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-playwright](https://github.com/executeautomation/mcp-playwright) | C | 5.2 | 33 | 0 | [Details](https://spiderrating.com/s/executeautomation/mcp-playwright) |

## Filesystem (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) | F | 2.0 | 0 | 0 | [Details](https://spiderrating.com/s/mark3labs/mcp-filesystem-server) |

## Cloud (4 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-server-cloudflare](https://github.com/Cloudflare/mcp-server-cloudflare) | F | 2.0 | 29 | 122 (43 crit) | [Details](https://spiderrating.com/s/Cloudflare/mcp-server-cloudflare) |
| [terraform-mcp-server](https://github.com/hashicorp/terraform-mcp-server) | F | 2.0 | 0 | 0 | [Details](https://spiderrating.com/s/hashicorp/terraform-mcp-server) |
| [tfmcp](https://github.com/nwiizo/tfmcp) | F | 2.0 | 0 | 0 | [Details](https://spiderrating.com/s/nwiizo/tfmcp) |
| [agent-toolkit](https://github.com/stripe/agent-toolkit) | F | 1.9 | 12 | 4 (2 crit) | [Details](https://spiderrating.com/s/stripe/agent-toolkit) |

## Communication (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [slack-mcp-server](https://github.com/korotovsky/slack-mcp-server) | F | 2.0 | 0 | 0 | [Details](https://spiderrating.com/s/korotovsky/slack-mcp-server) |

## Devtools (2 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) | C | 5.6 | 19 | 0 | [Details](https://spiderrating.com/s/ckreiling/mcp-server-docker) |
| [github-mcp-server](https://github.com/github/github-mcp-server) | F | 2.0 | 0 | 0 | [Details](https://spiderrating.com/s/github/github-mcp-server) |

## Utility (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [todoist-mcp-server](https://github.com/abhiz123/todoist-mcp-server) | C | 5.6 | 5 | 0 | [Details](https://spiderrating.com/s/abhiz123/todoist-mcp-server) |

## Monitoring (2 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-grafana](https://github.com/grafana/mcp-grafana) | F | 2.0 | 0 | 0 | [Details](https://spiderrating.com/s/grafana/mcp-grafana) |
| [metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server) | F | 2.0 | 0 | 0 | [Details](https://spiderrating.com/s/metoro-io/metoro-mcp-server) |

## Reference (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [servers](https://github.com/modelcontextprotocol/servers) | D | 4.2 | 0 | 0 | [Details](https://spiderrating.com/s/modelcontextprotocol/servers) |

## Critical Security Issues

These servers have critical security issues that may pose risks.

| Server | Score | Critical | High | Report |
|--------|-------|----------|------|--------|
| [mcp-server-cloudflare](https://github.com/Cloudflare/mcp-server-cloudflare) | 2.0 | 43 | 2 | [Details](https://spiderrating.com/s/Cloudflare/mcp-server-cloudflare) |
| [context7](https://github.com/upstash/context7) | 2.0 | 5 | 0 | [Details](https://spiderrating.com/s/upstash/context7) |
| [ai](https://github.com/vercel/ai) | 1.8 | 5 | 2 | [Details](https://spiderrating.com/s/vercel/ai) |
| [mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) | 2.0 | 2 | 0 | [Details](https://spiderrating.com/s/benborla/mcp-server-mysql) |
| [agent-toolkit](https://github.com/stripe/agent-toolkit) | 1.9 | 2 | 2 | [Details](https://spiderrating.com/s/stripe/agent-toolkit) |
| [postgres-mcp](https://github.com/crystaldba/postgres-mcp) | 2.0 | 1 | 0 | [Details](https://spiderrating.com/s/crystaldba/postgres-mcp) |

---

## Why These Scores Matter

MCP servers act as **capability bridges** between LLMs and real systems -- databases, APIs, file systems, cloud infrastructure.
A poorly described tool can cause an LLM to invoke the wrong action. A security vulnerability can be exploited by prompt injection.

The low average score across the ecosystem is not surprising -- MCP is a young protocol and security tooling is still catching up.
That's exactly why this list exists: **transparent, reproducible ratings help the ecosystem improve**.

## Methodology

Ratings are generated by [SpiderShield](https://github.com/teehooai/spidershield), an open-source static analysis tool for MCP servers.
Each server is scored on three dimensions:

| Dimension | Weight | What it measures |
|-----------|--------|-----------------|
| **Security** | 40% | 46 standardized issue codes (TS-E/W/C/P): malware, SSRF, eval injection, path traversal, prompt injection |
| **Description Quality** | 35% | How well tool descriptions guide LLM tool selection: intent clarity, scope boundaries, error guidance |
| **Metadata** | 25% | GitHub signals: maintenance frequency, provenance, popularity, licensing |

Grades: **A** (9.0+) | **B** (7.0+) | **C** (5.0+) | **D** (3.0+) | **F** (<3.0)

All scans are deterministic and reproducible. Same input always produces the same score.

## Improve Your Score

1. **Install SpiderShield**: `pip install spidershield`
2. **Scan your server**: `spidershield scan /path/to/your/server`
3. **Fix issues**: Follow the report's recommendations
4. **Submit for re-scan**: Open an issue or submit at [spiderrating.com](https://spiderrating.com/submit)

## Contributing

We welcome contributions:

- **Add a server**: Open an issue with the GitHub repo URL and we'll scan it
- **Request a re-scan**: If you've fixed issues, open an issue to request a re-scan
- **Report inaccuracies**: If a rating seems wrong, open an issue with details
- **Improve methodology**: PRs to [SpiderShield](https://github.com/teehooai/spidershield) are welcome

All ratings are auto-generated by the [SpiderRating pipeline](https://spiderrating.com). Manual edits to the table will be overwritten on the next scan cycle.

## Links

- [spiderrating.com](https://spiderrating.com) -- Full reports with tool-level scores and issue details
- [SpiderShield](https://github.com/teehooai/spidershield) -- Open-source scanner
- [Trust Registry API](https://spiderrating.com/api/docs) -- Query ratings programmatically
- [PyPI](https://pypi.org/project/spidershield/) -- `pip install spidershield`

## License

[CC0 1.0 Universal](LICENSE)

*Last updated: 2026-03-10 | Generated by [SpiderRating pipeline](https://github.com/teehooai/spiderrating)*
