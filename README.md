# Awesome MCP Security Ratings

> Independent security ratings for MCP servers and skills.
> Powered by [spiderrating.com](https://spiderrating.com) |
> Scanned by [SpiderShield](https://github.com/teehooai/spidershield)

**1278 servers scanned** | Avg score: **5.47/10** | 2.2% Grade A/B | 6.3% Grade F | 13.8% have critical issues

## The State of MCP Security

The MCP ecosystem is growing fast, but security hasn't kept up.
Our automated scans reveal systemic issues across 1278 popular MCP servers:

- **Average security score: 5.47/10** -- most servers ship with unvalidated inputs, missing access controls, and poor tool descriptions
- **6.3% received an F grade** -- SSRF, dangerous eval, path traversal, and SQL injection are common
- **Tool descriptions are inadequate** -- LLMs need clear intent, scope boundaries, and error guidance to select tools safely. Most descriptions lack these signals.

This isn't a criticism -- it's an opportunity. Every server here can improve, and we provide [detailed reports](https://spiderrating.com) showing exactly how.

> Want to check your own server? `pip install spidershield && spidershield scan .`

## Contents

<!-- TOC is auto-generated -->

---

## Database (11 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [supabase-mcp](https://github.com/supabase-community/supabase-mcp) | 🟡 C | 6.9 | 31 | 0 | [Details →](https://spiderrating.com/servers/supabase-community/supabase-mcp) |
| [nocturne_memory](https://github.com/Dataojitori/nocturne_memory) | 🟡 C | 6.9 | 7 | 2 | [Details →](https://spiderrating.com/servers/Dataojitori/nocturne_memory) |
| [mcp-server-neon](https://github.com/neondatabase/mcp-server-neon) | 🟡 C | 6.5 | 30 | 0 | [Details →](https://spiderrating.com/servers/neondatabase/mcp-server-neon) |
| [postgres-mcp](https://github.com/crystaldba/postgres-mcp) | 🟡 C | 6.4 | 7 | 0 | [Details →](https://spiderrating.com/servers/crystaldba/postgres-mcp) |
| [mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) | 🟠 D | 5.7 | 2 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/benborla/mcp-server-mysql) |
| [mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) | 🟠 D | 5.7 | 11 | 0 | [Details →](https://spiderrating.com/servers/kiliczsh/mcp-mongo-server) |
| [npcpy](https://github.com/NPC-Worldwide/npcpy) | 🟠 D | 5.2 | 6 | 16 (2 crit) | [Details →](https://spiderrating.com/servers/NPC-Worldwide/npcpy) |
| [mcp-gateway-registry](https://github.com/agentic-community/mcp-gateway-registry) | 🔴 F | 5.2 | 41 | 26 (4 crit) | [Details →](https://spiderrating.com/servers/agentic-community/mcp-gateway-registry) |
| [pg-aiguide](https://github.com/timescale/pg-aiguide) | 🔴 F | 5.2 | 2 | 40 (38 crit) | [Details →](https://spiderrating.com/servers/timescale/pg-aiguide) |
| [project-mcp-server](https://github.com/WilliamPinto-Olmos/project-mcp-server) | 🟠 D | 4.9 | 15 | 0 | [Details →](https://spiderrating.com/servers/WilliamPinto-Olmos/project-mcp-server) |
| [dbhub](https://github.com/bytebase/dbhub) | 🔴 F | 4.8 | 6 | 19 (19 crit) | [Details →](https://spiderrating.com/servers/bytebase/dbhub) |

## Search (7 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [context7](https://github.com/upstash/context7) | 🟢 B | 8.1 | 2 | 0 | [Details →](https://spiderrating.com/servers/upstash/context7) |
| [exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) | 🟡 C | 6.5 | 10 | 0 | [Details →](https://spiderrating.com/servers/exa-labs/exa-mcp-server) |
| [ddgs](https://github.com/deedy5/ddgs) | 🟡 C | 6.5 | 5 | 0 | [Details →](https://spiderrating.com/servers/deedy5/ddgs) |
| [tavily-mcp](https://github.com/tavily-ai/tavily-mcp) | 🟡 C | 6.3 | 5 | 0 | [Details →](https://spiderrating.com/servers/tavily-ai/tavily-mcp) |
| [gpt-researcher](https://github.com/assafelovic/gpt-researcher) | 🟠 D | 6.2 | 4 | 0 | [Details →](https://spiderrating.com/servers/assafelovic/gpt-researcher) |
| [web-search-mcp](https://github.com/mrkrsl/web-search-mcp) | 🟡 C | 6.1 | 3 | 0 | [Details →](https://spiderrating.com/servers/mrkrsl/web-search-mcp) |
| [mcp-server-serper](https://github.com/marcopesani/mcp-server-serper) | 🟠 D | 5.4 | 15 | 0 | [Details →](https://spiderrating.com/servers/marcopesani/mcp-server-serper) |

## Ai (2 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [ai](https://github.com/vercel/ai) | 🟠 D | 6.7 | 54 | 0 | [Details →](https://spiderrating.com/servers/vercel/ai) |
| [langchain-mcp-adapters](https://github.com/langchain-ai/langchain-mcp-adapters) | 🟠 D | 6.5 | 2 | 0 | [Details →](https://spiderrating.com/servers/langchain-ai/langchain-mcp-adapters) |

## Web (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-playwright](https://github.com/executeautomation/mcp-playwright) | 🟠 D | 5.9 | 33 | 0 | [Details →](https://spiderrating.com/servers/executeautomation/mcp-playwright) |

## Filesystem (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) | 🟠 D | 3.8 | 14 | 0 | [Details →](https://spiderrating.com/servers/mark3labs/mcp-filesystem-server) |

## Cloud (3 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-server-cloudflare](https://github.com/Cloudflare/mcp-server-cloudflare) | 🟢 B | 7.2 | 131 | 0 | [Details →](https://spiderrating.com/servers/Cloudflare/mcp-server-cloudflare) |
| [terraform-mcp-server](https://github.com/hashicorp/terraform-mcp-server) | 🟠 D | 5.8 | 15 | 0 | [Details →](https://spiderrating.com/servers/hashicorp/terraform-mcp-server) |
| [agent-toolkit](https://github.com/stripe/agent-toolkit) | 🟠 D | 4.4 | 5 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/stripe/agent-toolkit) |

## Devtools (3 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [github-mcp-server](https://github.com/github/github-mcp-server) | 🟡 C | 6.9 | 81 | 0 | [Details →](https://spiderrating.com/servers/github/github-mcp-server) |
| [mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) | 🟡 C | 5.7 | 19 | 0 | [Details →](https://spiderrating.com/servers/ckreiling/mcp-server-docker) |
| [goose](https://github.com/block/goose) | 🔴 F | 5.3 | 63 | 14 (14 crit) | [Details →](https://spiderrating.com/servers/block/goose) |

## Utility (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [todoist-mcp-server](https://github.com/abhiz123/todoist-mcp-server) | 🟡 C | 5.5 | 5 | 0 | [Details →](https://spiderrating.com/servers/abhiz123/todoist-mcp-server) |

## Biology, Medicine And Bioinformatics (5 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [fhir-mcp-server](https://github.com/wso2/fhir-mcp-server) | 🟡 C | 6.7 | 12 | 0 | [Details →](https://spiderrating.com/servers/wso2/fhir-mcp-server) |
| [omop_mcp](https://github.com/OHNLP/omop_mcp) | 🟡 C | 6.3 | 2 | 2 | [Details →](https://spiderrating.com/servers/OHNLP/omop_mcp) |
| [fulcra-context-mcp](https://github.com/fulcradynamics/fulcra-context-mcp) | 🟡 C | 6.0 | 8 | 0 | [Details →](https://spiderrating.com/servers/fulcradynamics/fulcra-context-mcp) |
| [ucsc-genome-mcp](https://github.com/hlydecker/ucsc-genome-mcp) | 🟡 C | 5.1 | 12 | 0 | [Details →](https://spiderrating.com/servers/hlydecker/ucsc-genome-mcp) |
| [medical-mcp](https://github.com/JamesANZ/medical-mcp) | 🟠 D | 4.2 | 16 | 0 | [Details →](https://spiderrating.com/servers/JamesANZ/medical-mcp) |

## Dev-Tools (2 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [git-mcp](https://github.com/idosal/git-mcp) | 🟠 D | 6.1 | 7 | 0 | [Details →](https://spiderrating.com/servers/idosal/git-mcp) |
| [Skill_Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) | 🟠 D | 5.9 | 19 | 1 | [Details →](https://spiderrating.com/servers/yusufkaraaslan/Skill_Seekers) |

## Frameworks (5 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [flompt](https://github.com/Nyrok/flompt) | 🟡 C | 6.0 | 3 | 2 | [Details →](https://spiderrating.com/servers/Nyrok/flompt) |
| [fastmcp](https://github.com/punkpeye/fastmcp) | 🟠 D | 6.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/punkpeye/fastmcp) |
| [fastmcp](https://github.com/jlowin/fastmcp) | 🟠 D | 4.0 | 97 | 10 | [Details →](https://spiderrating.com/servers/jlowin/fastmcp) |
| [mcp-fusion](https://github.com/vinkius-labs/mcp-fusion) | 🟠 D | 3.9 | 13 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/vinkius-labs/mcp-fusion) |
| [turbomcp](https://github.com/Epistates/turbomcp) | 🟠 D | 3.8 | 25 | 0 | [Details →](https://spiderrating.com/servers/Epistates/turbomcp) |

## Monitoring (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-grafana](https://github.com/grafana/mcp-grafana) | 🟡 C | 6.7 | 60 | 0 | [Details →](https://spiderrating.com/servers/grafana/mcp-grafana) |

## Reference (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [servers](https://github.com/modelcontextprotocol/servers) | 🟡 C | 6.8 | 54 | 0 | [Details →](https://spiderrating.com/servers/modelcontextprotocol/servers) |

## Skill-Scenario (5 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [multi-vector](https://github.com/skill-scenario/multi-vector) | 🔴 F | 3.4 | 3 | 0 | [Details →](https://spiderrating.com/servers/skill-scenario/multi-vector) |
| [prompt-injection](https://github.com/skill-scenario/prompt-injection) | 🔴 F | 3.4 | 2 | 0 | [Details →](https://spiderrating.com/servers/skill-scenario/prompt-injection) |
| [typosquat](https://github.com/skill-scenario/typosquat) | 🔴 F | 3.4 | 3 | 0 | [Details →](https://spiderrating.com/servers/skill-scenario/typosquat) |
| [with-skills](https://github.com/skill-scenario/with-skills) | 🔴 F | 3.4 | 4 | 0 | [Details →](https://spiderrating.com/servers/skill-scenario/with-skills) |
| [exfil-ast](https://github.com/skill-scenario/exfil-ast) | 🔴 F | 1.7 | 2 | 0 | [Details →](https://spiderrating.com/servers/skill-scenario/exfil-ast) |

## ☁️ Cloud Platforms (38 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [aws-pricing-mcp](https://github.com/trilogy-group/aws-pricing-mcp) | 🟢 B | 7.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/trilogy-group/aws-pricing-mcp) |
| [mcp](https://github.com/awslabs/mcp) | 🔴 F | 6.7 | 365 | 134 (3 crit) | [Details →](https://spiderrating.com/servers/awslabs/mcp) |
| [kubefwd](https://github.com/txn2/kubefwd) | 🟡 C | 6.5 | 28 | 0 | [Details →](https://spiderrating.com/servers/txn2/kubefwd) |
| [mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) | 🟠 D | 6.4 | 146 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/cloudflare/mcp-server-cloudflare) |
| [pythonanywhere-mcp-server](https://github.com/pythonanywhere/pythonanywhere-mcp-server) | 🟡 C | 6.4 | 20 | 13 | [Details →](https://spiderrating.com/servers/pythonanywhere/pythonanywhere-mcp-server) |
| [k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) | 🟡 C | 6.3 | 4 | 0 | [Details →](https://spiderrating.com/servers/alexei-led/k8s-mcp-server) |
| [kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) | 🟠 D | 6.1 | 47 | 9 | [Details →](https://spiderrating.com/servers/rohitg00/kubectl-mcp-server) |
| [mcp-server-python](https://github.com/kestra-io/mcp-server-python) | 🟡 C | 6.1 | 35 | 0 | [Details →](https://spiderrating.com/servers/kestra-io/mcp-server-python) |
| [esp-rainmaker-mcp](https://github.com/espressif/esp-rainmaker-mcp) | 🟡 C | 6.1 | 13 | 8 | [Details →](https://spiderrating.com/servers/espressif/esp-rainmaker-mcp) |
| [localstack-mcp-server](https://github.com/localstack/localstack-mcp-server) | 🟠 D | 5.9 | 9 | 0 | [Details →](https://spiderrating.com/servers/localstack/localstack-mcp-server) |
| [rancher-mcp-server](https://github.com/mrostamii/rancher-mcp-server) | 🟡 C | 5.8 | 57 | 0 | [Details →](https://spiderrating.com/servers/mrostamii/rancher-mcp-server) |
| [liveblocks-mcp-server](https://github.com/liveblocks/liveblocks-mcp-server) | 🟠 D | 5.8 | 39 | 0 | [Details →](https://spiderrating.com/servers/liveblocks/liveblocks-mcp-server) |
| [k8s-mcp-server](https://github.com/reza-gholizade/k8s-mcp-server) | 🟠 D | 5.8 | 22 | 0 | [Details →](https://spiderrating.com/servers/reza-gholizade/k8s-mcp-server) |
| [qiniu-mcp-server](https://github.com/qiniu/qiniu-mcp-server) | 🟡 C | 5.8 | 24 | 0 | [Details →](https://spiderrating.com/servers/qiniu/qiniu-mcp-server) |
| [spaceship-mcp](https://github.com/bartwaardenburg/spaceship-mcp) | 🟡 C | 5.7 | 48 | 0 | [Details →](https://spiderrating.com/servers/bartwaardenburg/spaceship-mcp) |
| [oci-pricing-mcp](https://github.com/jasonwilbur/oci-pricing-mcp) | 🟡 C | 5.7 | 44 | 0 | [Details →](https://spiderrating.com/servers/jasonwilbur/oci-pricing-mcp) |
| [adls-mcp-server](https://github.com/erikhoward/adls-mcp-server) | 🟠 D | 5.7 | 16 | 0 | [Details →](https://spiderrating.com/servers/erikhoward/adls-mcp-server) |
| [mcp-k8s](https://github.com/silenceper/mcp-k8s) | 🟠 D | 5.7 | 16 | 0 | [Details →](https://spiderrating.com/servers/silenceper/mcp-k8s) |
| [kom](https://github.com/weibaohui/kom) | 🟠 D | 5.6 | 60 | 0 | [Details →](https://spiderrating.com/servers/weibaohui/kom) |
| [cloud-cost-mcp](https://github.com/jasonwilbur/cloud-cost-mcp) | 🟠 D | 5.5 | 42 | 0 | [Details →](https://spiderrating.com/servers/jasonwilbur/cloud-cost-mcp) |
| [mcp-redis-cloud](https://github.com/redis/mcp-redis-cloud) | 🟠 D | 5.5 | 18 | 0 | [Details →](https://spiderrating.com/servers/redis/mcp-redis-cloud) |
| [azure-resource-graph-mcp-server](https://github.com/hardik-id/azure-resource-graph-mcp-server) | 🟡 C | 5.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/hardik-id/azure-resource-graph-mcp-server) |
| [alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server) | 🟠 D | 5.4 | 41 | 2 (1 crit) | [Details →](https://spiderrating.com/servers/aliyun/alibaba-cloud-ops-mcp-server) |
| [cert-manager-mcp-server](https://github.com/pibblokto/cert-manager-mcp-server) | 🟡 C | 5.4 | 8 | 0 | [Details →](https://spiderrating.com/servers/pibblokto/cert-manager-mcp-server) |
| [lumino-mcp-server](https://github.com/spre-sre/lumino-mcp-server) | 🔴 F | 5.4 | 35 | 16 (8 crit) | [Details →](https://spiderrating.com/servers/spre-sre/lumino-mcp-server) |
| [agent-deploy-dashboard-mcp](https://github.com/aparajithn/agent-deploy-dashboard-mcp) | 🟡 C | 5.4 | 9 | 8 | [Details →](https://spiderrating.com/servers/aparajithn/agent-deploy-dashboard-mcp) |
| [mcp-server-cloudflare](https://github.com/ofershap/mcp-server-cloudflare) | 🟡 C | 5.4 | 13 | 0 | [Details →](https://spiderrating.com/servers/ofershap/mcp-server-cloudflare) |
| [tilt-mcp](https://github.com/rrmistry/tilt-mcp) | 🟡 C | 5.3 | 7 | 0 | [Details →](https://spiderrating.com/servers/rrmistry/tilt-mcp) |
| [sitelauncher-mcp-server](https://github.com/trackerfitness729-jpg/sitelauncher-mcp-server) | 🟡 C | 5.2 | 7 | 0 | [Details →](https://spiderrating.com/servers/trackerfitness729-jpg/sitelauncher-mcp-server) |
| [mcp-server-s3](https://github.com/ofershap/mcp-server-s3) | 🟡 C | 5.1 | 7 | 0 | [Details →](https://spiderrating.com/servers/ofershap/mcp-server-s3) |
| [esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server) | 🟠 D | 5.1 | 7 | 0 | [Details →](https://spiderrating.com/servers/bright8192/esxi-mcp-server) |
| [mcp-cyclops](https://github.com/cyclops-ui/mcp-cyclops) | 🟠 D | 5.0 | 10 | 0 | [Details →](https://spiderrating.com/servers/cyclops-ui/mcp-cyclops) |
| [mcp-nutanix](https://github.com/thunderboltsid/mcp-nutanix) | 🟠 D | 4.9 | 13 | 0 | [Details →](https://spiderrating.com/servers/thunderboltsid/mcp-nutanix) |
| [mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) | 🟠 D | 4.7 | 27 | 0 | [Details →](https://spiderrating.com/servers/Flux159/mcp-server-kubernetes) |
| [kubernetes-mcp-server](https://github.com/manusa/kubernetes-mcp-server) | 🟠 D | 4.7 | 30 | 0 | [Details →](https://spiderrating.com/servers/manusa/kubernetes-mcp-server) |
| [books-mcp-server](https://github.com/VmLia/books-mcp-server) | 🟠 D | 4.5 | 1 | 1 | [Details →](https://spiderrating.com/servers/VmLia/books-mcp-server) |
| [4everland-hosting-mcp](https://github.com/4everland/4everland-hosting-mcp) | 🟠 D | 4.2 | 3 | 0 | [Details →](https://spiderrating.com/servers/4everland/4everland-hosting-mcp) |
| [CloudBase-AI-ToolKit](https://github.com/TencentCloudBase/CloudBase-AI-ToolKit) | 🔴 F | 2.9 | 22 | 5 (2 crit) | [Details →](https://spiderrating.com/servers/TencentCloudBase/CloudBase-AI-ToolKit) |

## ⚖️ Legal (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [us-legal-mcp](https://github.com/JamesANZ/us-legal-mcp) | 🟠 D | 4.4 | 8 | 0 | [Details →](https://spiderrating.com/servers/JamesANZ/us-legal-mcp) |

## 🌎 Translation Services (2 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [weblate-mcp](https://github.com/mmntm/weblate-mcp) | 🟡 C | 5.8 | 20 | 0 | [Details →](https://spiderrating.com/servers/mmntm/weblate-mcp) |
| [lara-mcp](https://github.com/translated/lara-mcp) | 🟡 C | 5.6 | 12 | 0 | [Details →](https://spiderrating.com/servers/translated/lara-mcp) |

## 🌐 Social Media (9 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [facebook-mcp-server](https://github.com/HagaiHen/facebook-mcp-server) | 🟡 C | 6.2 | 35 | 30 | [Details →](https://spiderrating.com/servers/HagaiHen/facebook-mcp-server) |
| [reddit-mcp-buddy](https://github.com/karanb192/reddit-mcp-buddy) | 🟡 C | 6.2 | 5 | 3 | [Details →](https://spiderrating.com/servers/karanb192/reddit-mcp-buddy) |
| [reddit-research-mcp](https://github.com/king-of-the-grackles/reddit-research-mcp) | 🟡 C | 5.7 | 3 | 0 | [Details →](https://spiderrating.com/servers/king-of-the-grackles/reddit-research-mcp) |
| [vk-mcp-server](https://github.com/bulatko/vk-mcp-server) | 🟡 C | 5.6 | 10 | 0 | [Details →](https://spiderrating.com/servers/bulatko/vk-mcp-server) |
| [bluesky-social-mcp](https://github.com/gwbischof/bluesky-social-mcp) | 🟠 D | 5.4 | 25 | 0 | [Details →](https://spiderrating.com/servers/gwbischof/bluesky-social-mcp) |
| [macrocosmos-mcp](https://github.com/macrocosm-os/macrocosmos-mcp) | 🟠 D | 5.2 | 7 | 0 | [Details →](https://spiderrating.com/servers/macrocosm-os/macrocosmos-mcp) |
| [mcp-twitter](https://github.com/LuniaKunal/mcp-twitter) | 🟡 C | 5.2 | 7 | 4 | [Details →](https://spiderrating.com/servers/LuniaKunal/mcp-twitter) |
| [fitness-influencer-mcp](https://github.com/MarceauSolutions/fitness-influencer-mcp) | 🟡 C | 5.0 | 6 | 2 | [Details →](https://spiderrating.com/servers/MarceauSolutions/fitness-influencer-mcp) |
| [reddit-summarizer-mcp](https://github.com/sinanefeozler/reddit-summarizer-mcp) | 🟠 D | 5.0 | 3 | 0 | [Details →](https://spiderrating.com/servers/sinanefeozler/reddit-summarizer-mcp) |

## 🌳 Environment & Nature (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [wildfire-mcp-server](https://github.com/aliafsahnoudeh/wildfire-mcp-server) | 🟠 D | 5.0 | 6 | 6 | [Details →](https://spiderrating.com/servers/aliafsahnoudeh/wildfire-mcp-server) |

## 🎓 Education (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [brightspace-mcp-server](https://github.com/RohanMuppa/brightspace-mcp-server) | 🟠 D | 6.1 | 13 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/RohanMuppa/brightspace-mcp-server) |

## 🎥 Multimedia Process (14 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [torrentclaw-mcp](https://github.com/torrentclaw/torrentclaw-mcp) | 🟡 C | 5.9 | 11 | 0 | [Details →](https://spiderrating.com/servers/torrentclaw/torrentclaw-mcp) |
| [imagesorcery-mcp](https://github.com/sunriseapps/imagesorcery-mcp) | 🟡 C | 5.7 | 17 | 0 | [Details →](https://spiderrating.com/servers/sunriseapps/imagesorcery-mcp) |
| [mcp-video-analyzer](https://github.com/guimatheus92/mcp-video-analyzer) | 🟠 D | 5.5 | 7 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/guimatheus92/mcp-video-analyzer) |
| [media-gen-mcp](https://github.com/strato-space/media-gen-mcp) | 🟠 D | 5.4 | 15 | 0 | [Details →](https://spiderrating.com/servers/strato-space/media-gen-mcp) |
| [exif-mcp](https://github.com/stass/exif-mcp) | 🟡 C | 5.2 | 7 | 0 | [Details →](https://spiderrating.com/servers/stass/exif-mcp) |
| [gif-creator-mcp](https://github.com/ananddtyagi/gif-creator-mcp) | 🟡 C | 5.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/ananddtyagi/gif-creator-mcp) |
| [topaz-mcp](https://github.com/TopazLabs/topaz-mcp) | 🟠 D | 5.2 | 3 | 0 | [Details →](https://spiderrating.com/servers/TopazLabs/topaz-mcp) |
| [barevalue-mcp](https://github.com/quietnotion/barevalue-mcp) | 🟡 C | 5.2 | 13 | 0 | [Details →](https://spiderrating.com/servers/quietnotion/barevalue-mcp) |
| [video-edit-mcp](https://github.com/Aditya2755/video-edit-mcp) | 🟠 D | 5.1 | 34 | 30 | [Details →](https://spiderrating.com/servers/Aditya2755/video-edit-mcp) |
| [sonos-ts-mcp](https://github.com/Tommertom/sonos-ts-mcp) | 🟡 C | 5.0 | 62 | 0 | [Details →](https://spiderrating.com/servers/Tommertom/sonos-ts-mcp) |
| [atsurae](https://github.com/1000ri-jp/atsurae) | 🟠 D | 4.8 | 10 | 0 | [Details →](https://spiderrating.com/servers/1000ri-jp/atsurae) |
| [zapcap-mcp-server](https://github.com/bogdan01m/zapcap-mcp-server) | 🟠 D | 4.6 | 5 | 0 | [Details →](https://spiderrating.com/servers/bogdan01m/zapcap-mcp-server) |
| [vap-showcase](https://github.com/elestirelbilinc-sketch/vap-showcase) | 🟠 D | 4.3 | 15 | 3 | [Details →](https://spiderrating.com/servers/elestirelbilinc-sketch/vap-showcase) |
| [Pixelle-MCP](https://github.com/AIDC-AI/Pixelle-MCP) | 🟠 D | 4.1 | 1 | 0 | [Details →](https://spiderrating.com/servers/AIDC-AI/Pixelle-MCP) |

## 🎧 Support & Service Management (4 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [yandex-tracker-mcp](https://github.com/aikts/yandex-tracker-mcp) | 🟠 D | 6.3 | 33 | 0 | [Details →](https://spiderrating.com/servers/aikts/yandex-tracker-mcp) |
| [jira-mcp](https://github.com/nguyenvanduocit/jira-mcp) | 🟡 C | 5.9 | 23 | 0 | [Details →](https://spiderrating.com/servers/nguyenvanduocit/jira-mcp) |
| [freshdesk_mcp](https://github.com/effytech/freshdesk_mcp) | 🟠 D | 5.8 | 59 | 12 | [Details →](https://spiderrating.com/servers/effytech/freshdesk_mcp) |
| [bugherd-mcp](https://github.com/Berckan/bugherd-mcp) | 🟠 D | 4.5 | 37 | 0 | [Details →](https://spiderrating.com/servers/Berckan/bugherd-mcp) |

## 🎧 Text-To-Speech (5 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [kokoro-tts-mcp](https://github.com/mberg/kokoro-tts-mcp) | 🟡 C | 5.5 | 1 | 1 | [Details →](https://spiderrating.com/servers/mberg/kokoro-tts-mcp) |
| [daisys-mcp](https://github.com/daisys-ai/daisys-mcp) | 🟡 C | 5.5 | 2 | 0 | [Details →](https://spiderrating.com/servers/daisys-ai/daisys-mcp) |
| [brainiall-mcp-server](https://github.com/fasuizu-br/brainiall-mcp-server) | 🟠 D | 5.3 | 4 | 0 | [Details →](https://spiderrating.com/servers/fasuizu-br/brainiall-mcp-server) |
| [claude-code-tts](https://github.com/ybouhjira/claude-code-tts) | 🟠 D | 4.8 | 5 | 0 | [Details →](https://spiderrating.com/servers/ybouhjira/claude-code-tts) |
| [voice-mcp](https://github.com/mbailey/voice-mcp) | 🟠 D | 3.4 | 27 | 5 (2 crit) | [Details →](https://spiderrating.com/servers/mbailey/voice-mcp) |

## 🎨 Art & Culture (26 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-alphabanana](https://github.com/tasopen/mcp-alphabanana) | 🟢 B | 7.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/tasopen/mcp-alphabanana) |
| [MeiGen-AI-Design-MCP](https://github.com/jau123/MeiGen-AI-Design-MCP) | 🟡 C | 6.3 | 8 | 0 | [Details →](https://spiderrating.com/servers/jau123/MeiGen-AI-Design-MCP) |
| [fal-mcp-server](https://github.com/raveenb/fal-mcp-server) | 🟡 C | 6.3 | 18 | 0 | [Details →](https://spiderrating.com/servers/raveenb/fal-mcp-server) |
| [smithsonian-mcp](https://github.com/molanojustin/smithsonian-mcp) | 🟡 C | 6.3 | 28 | 0 | [Details →](https://spiderrating.com/servers/molanojustin/smithsonian-mcp) |
| [discogs-mcp-server](https://github.com/cswkim/discogs-mcp-server) | 🟠 D | 6.2 | 53 | 0 | [Details →](https://spiderrating.com/servers/cswkim/discogs-mcp-server) |
| [wizzy-mcp-tmdb](https://github.com/drakonkat/wizzy-mcp-tmdb) | 🟡 C | 6.1 | 23 | 0 | [Details →](https://spiderrating.com/servers/drakonkat/wizzy-mcp-tmdb) |
| [blender-mcp](https://github.com/ahujasid/blender-mcp) | 🟡 C | 6.0 | 22 | 16 | [Details →](https://spiderrating.com/servers/ahujasid/blender-mcp) |
| [davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) | 🟠 D | 5.9 | 368 | 218 | [Details →](https://spiderrating.com/servers/samuelgursky/davinci-resolve-mcp) |
| [mcp-apple-music](https://github.com/Cifero74/mcp-apple-music) | 🟡 C | 5.8 | 11 | 2 | [Details →](https://spiderrating.com/servers/Cifero74/mcp-apple-music) |
| [jupytercad-mcp](https://github.com/asmith26/jupytercad-mcp) | 🟡 C | 5.6 | 1 | 1 | [Details →](https://spiderrating.com/servers/asmith26/jupytercad-mcp) |
| [isaac-sim-mcp](https://github.com/omni-mcp/isaac-sim-mcp) | 🟡 C | 5.6 | 3 | 7 | [Details →](https://spiderrating.com/servers/omni-mcp/isaac-sim-mcp) |
| [rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp) | 🟡 C | 5.5 | 12 | 0 | [Details →](https://spiderrating.com/servers/r-huijts/rijksmuseum-mcp) |
| [anilist-mcp](https://github.com/yuna0x0/anilist-mcp) | 🟠 D | 5.5 | 44 | 0 | [Details →](https://spiderrating.com/servers/yuna0x0/anilist-mcp) |
| [aseprite-mcp](https://github.com/diivi/aseprite-mcp) | 🟠 D | 5.5 | 9 | 8 | [Details →](https://spiderrating.com/servers/diivi/aseprite-mcp) |
| [bazi-mcp](https://github.com/cantian-ai/bazi-mcp) | 🟠 D | 5.5 | 3 | 0 | [Details →](https://spiderrating.com/servers/cantian-ai/bazi-mcp) |
| [ani-mcp](https://github.com/gavxm/ani-mcp) | 🟠 D | 5.5 | 72 | 0 | [Details →](https://spiderrating.com/servers/gavxm/ani-mcp) |
| [oorlogsbronnen-mcp](https://github.com/r-huijts/oorlogsbronnen-mcp) | 🟡 C | 5.5 | 2 | 0 | [Details →](https://spiderrating.com/servers/r-huijts/oorlogsbronnen-mcp) |
| [icogenie-mcp](https://github.com/albertnahas/icogenie-mcp) | 🟡 C | 5.5 | 12 | 0 | [Details →](https://spiderrating.com/servers/albertnahas/icogenie-mcp) |
| [quran-mcp-server](https://github.com/djalal/quran-mcp-server) | 🟠 D | 5.4 | 3 | 0 | [Details →](https://spiderrating.com/servers/djalal/quran-mcp-server) |
| [manim-mcp-server](https://github.com/abhiemj/manim-mcp-server) | 🟠 D | 5.3 | 2 | 2 | [Details →](https://spiderrating.com/servers/abhiemj/manim-mcp-server) |
| [reaper-mcp](https://github.com/TwelveTake-Studios/reaper-mcp) | 🟠 D | 5.1 | 130 | 15 | [Details →](https://spiderrating.com/servers/TwelveTake-Studios/reaper-mcp) |
| [spotify-bulk-actions-mcp](https://github.com/khglynn/spotify-bulk-actions-mcp) | 🟡 C | 5.0 | 33 | 13 | [Details →](https://spiderrating.com/servers/khglynn/spotify-bulk-actions-mcp) |
| [mcp-open-library](https://github.com/8enSmith/mcp-open-library) | 🟠 D | 4.8 | 6 | 0 | [Details →](https://spiderrating.com/servers/8enSmith/mcp-open-library) |
| [shahnameh-mcp-server](https://github.com/aliafsahnoudeh/shahnameh-mcp-server) | 🟠 D | 4.6 | 6 | 0 | [Details →](https://spiderrating.com/servers/aliafsahnoudeh/shahnameh-mcp-server) |
| [svgmaker-mcp](https://github.com/GenWaveLLC/svgmaker-mcp) | 🟠 D | 4.5 | 3 | 0 | [Details →](https://spiderrating.com/servers/GenWaveLLC/svgmaker-mcp) |
| [myinstants-mcp](https://github.com/austenstone/myinstants-mcp) | 🟠 D | 4.3 | 4 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/austenstone/myinstants-mcp) |

## 🎮 Gaming (12 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [opendota-mcp-server](https://github.com/hkaanengin/opendota-mcp-server) | 🟡 C | 6.5 | 14 | 4 | [Details →](https://spiderrating.com/servers/hkaanengin/opendota-mcp-server) |
| [bgg-mcp](https://github.com/kkjdaniel/bgg-mcp) | 🟡 C | 6.0 | 10 | 0 | [Details →](https://spiderrating.com/servers/kkjdaniel/bgg-mcp) |
| [chess-mcp](https://github.com/pab1it0/chess-mcp) | 🟡 C | 5.9 | 10 | 8 | [Details →](https://spiderrating.com/servers/pab1it0/chess-mcp) |
| [fantasy-pl-mcp](https://github.com/rishijatia/fantasy-pl-mcp) | 🟡 C | 5.7 | 16 | 1 | [Details →](https://spiderrating.com/servers/rishijatia/fantasy-pl-mcp) |
| [mcp-chess](https://github.com/jiayao/mcp-chess) | 🟡 C | 5.4 | 6 | 2 | [Details →](https://spiderrating.com/servers/jiayao/mcp-chess) |
| [Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) | 🔴 F | 5.4 | 55 | 3 (3 crit) | [Details →](https://spiderrating.com/servers/IvanMurzak/Unity-MCP) |
| [pyxel-mcp](https://github.com/kitao/pyxel-mcp) | 🟡 C | 5.3 | 14 | 1 | [Details →](https://spiderrating.com/servers/kitao/pyxel-mcp) |
| [better-godot-mcp](https://github.com/n24q02m/better-godot-mcp) | 🟠 D | 5.0 | 18 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/n24q02m/better-godot-mcp) |
| [godot-mcp-runtime](https://github.com/Erodenn/godot-mcp-runtime) | 🟠 D | 5.0 | 15 | 0 | [Details →](https://spiderrating.com/servers/Erodenn/godot-mcp-runtime) |
| [mcp-server-runescape](https://github.com/stefan-xyz/mcp-server-runescape) | 🟠 D | 4.8 | 6 | 0 | [Details →](https://spiderrating.com/servers/stefan-xyz/mcp-server-runescape) |
| [godot-mcp](https://github.com/Coding-Solo/godot-mcp) | 🟠 D | 4.5 | 14 | 0 | [Details →](https://spiderrating.com/servers/Coding-Solo/godot-mcp) |
| [mcp-tic-tac-toe](https://github.com/tomholford/mcp-tic-tac-toe) | 🟠 D | 4.2 | 8 | 0 | [Details →](https://spiderrating.com/servers/tomholford/mcp-tic-tac-toe) |

## 🎯 Marketing (14 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [osp_marketing_tools](https://github.com/open-strategy-partners/osp_marketing_tools) | 🟡 C | 5.9 | 6 | 0 | [Details →](https://spiderrating.com/servers/open-strategy-partners/osp_marketing_tools) |
| [facebook-ads-mcp-server](https://github.com/gomarble-ai/facebook-ads-mcp-server) | 🟡 C | 5.9 | 21 | 6 | [Details →](https://spiderrating.com/servers/gomarble-ai/facebook-ads-mcp-server) |
| [google-tag-manager-mcp-server](https://github.com/stape-io/google-tag-manager-mcp-server) | 🟠 D | 5.9 | 19 | 0 | [Details →](https://spiderrating.com/servers/stape-io/google-tag-manager-mcp-server) |
| [citedy-seo-agent](https://github.com/Citedy/citedy-seo-agent) | 🟡 C | 5.8 | 7 | 2 | [Details →](https://spiderrating.com/servers/Citedy/citedy-seo-agent) |
| [google-ads-mcp-server](https://github.com/gomarble-ai/google-ads-mcp-server) | 🟡 C | 5.7 | 3 | 3 | [Details →](https://spiderrating.com/servers/gomarble-ai/google-ads-mcp-server) |
| [mailchimp-mcp-server](https://github.com/damientilman/mailchimp-mcp-server) | 🟡 C | 5.6 | 53 | 44 | [Details →](https://spiderrating.com/servers/damientilman/mailchimp-mcp-server) |
| [tomba-mcp-server](https://github.com/tomba-io/tomba-mcp-server) | 🟠 D | 5.6 | 61 | 0 | [Details →](https://spiderrating.com/servers/tomba-io/tomba-mcp-server) |
| [google-ad-manager-mcp](https://github.com/MatiousCorp/google-ad-manager-mcp) | 🟡 C | 5.6 | 35 | 1 | [Details →](https://spiderrating.com/servers/MatiousCorp/google-ad-manager-mcp) |
| [stape-mcp-server](https://github.com/stape-io/stape-mcp-server) | 🟠 D | 5.6 | 18 | 0 | [Details →](https://spiderrating.com/servers/stape-io/stape-mcp-server) |
| [lhremote](https://github.com/alexey-pelykh/lhremote) | 🟡 C | 5.5 | 50 | 0 | [Details →](https://spiderrating.com/servers/alexey-pelykh/lhremote) |
| [apollo-io-mcp](https://github.com/louis030195/apollo-io-mcp) | 🟠 D | 5.0 | 7 | 0 | [Details →](https://spiderrating.com/servers/louis030195/apollo-io-mcp) |
| [tiktok-ads-mcp-server](https://github.com/AdsMCP/tiktok-ads-mcp-server) | 🟠 D | 4.7 | 9 | 0 | [Details →](https://spiderrating.com/servers/AdsMCP/tiktok-ads-mcp-server) |
| [searchatlas-mcp-server](https://github.com/Search-Atlas-Group/searchatlas-mcp-server) | 🟠 D | 4.7 | 6 | 0 | [Details →](https://spiderrating.com/servers/Search-Atlas-Group/searchatlas-mcp-server) |
| [blogburst-mcp-server](https://github.com/shensi8312/blogburst-mcp-server) | 🟠 D | 4.0 | 26 | 5 (2 crit) | [Details →](https://spiderrating.com/servers/shensi8312/blogburst-mcp-server) |

## 🏃 Sports (12 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [strava-mcp](https://github.com/r-huijts/strava-mcp) | 🟡 C | 6.3 | 22 | 0 | [Details →](https://spiderrating.com/servers/r-huijts/strava-mcp) |
| [balldontlie-mcp](https://github.com/mikechao/balldontlie-mcp) | 🟡 C | 5.9 | 3 | 0 | [Details →](https://spiderrating.com/servers/mikechao/balldontlie-mcp) |
| [mlb-api-mcp](https://github.com/guillochon/mlb-api-mcp) | 🟡 C | 5.5 | 24 | 2 | [Details →](https://spiderrating.com/servers/guillochon/mlb-api-mcp) |
| [wc26-mcp](https://github.com/jordanlyall/wc26-mcp) | 🟠 D | 5.4 | 18 | 0 | [Details →](https://spiderrating.com/servers/jordanlyall/wc26-mcp) |
| [musclesworked-mcp](https://github.com/csjoblom/musclesworked-mcp) | 🟡 C | 5.3 | 6 | 0 | [Details →](https://spiderrating.com/servers/csjoblom/musclesworked-mcp) |
| [arvo-mcp](https://github.com/khaoss85/arvo-mcp) | 🟡 C | 5.3 | 29 | 0 | [Details →](https://spiderrating.com/servers/khaoss85/arvo-mcp) |
| [nba_mcp_server](https://github.com/labeveryday/nba_mcp_server) | 🟠 D | 5.0 | 30 | 0 | [Details →](https://spiderrating.com/servers/labeveryday/nba_mcp_server) |
| [trainingpeaks-mcp](https://github.com/JamsusMaximus/trainingpeaks-mcp) | 🟠 D | 4.8 | 9 | 0 | [Details →](https://spiderrating.com/servers/JamsusMaximus/trainingpeaks-mcp) |
| [sports-mcp-server](https://github.com/cloudbet/sports-mcp-server) | 🟠 D | 4.8 | 2 | 0 | [Details →](https://spiderrating.com/servers/cloudbet/sports-mcp-server) |
| [xert-mcp](https://github.com/Milofax/xert-mcp) | 🟠 D | 4.7 | 7 | 0 | [Details →](https://spiderrating.com/servers/Milofax/xert-mcp) |
| [firstcycling-mcp](https://github.com/r-huijts/firstcycling-mcp) | 🟠 D | 4.6 | 18 | 4 | [Details →](https://spiderrating.com/servers/r-huijts/firstcycling-mcp) |
| [mvf1](https://github.com/RobSpectre/mvf1) | 🟠 D | 4.4 | 21 | 0 | [Details →](https://spiderrating.com/servers/RobSpectre/mvf1) |

## 🏠 Home Automation (2 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [wemo-mcp-server](https://github.com/apiarya/wemo-mcp-server) | 🟡 C | 5.8 | 11 | 4 | [Details →](https://spiderrating.com/servers/apiarya/wemo-mcp-server) |
| [fritzbox-mcp-server](https://github.com/kambriso/fritzbox-mcp-server) | 🟡 C | 5.6 | 4 | 0 | [Details →](https://spiderrating.com/servers/kambriso/fritzbox-mcp-server) |

## 🏠 Real Estate (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [propstack-mcp](https://github.com/ashev87/propstack-mcp) | 🟡 C | 5.7 | 53 | 0 | [Details →](https://spiderrating.com/servers/ashev87/propstack-mcp) |

## 🏢 Workplace & Productivity (25 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) | 🟢 B | 7.0 | 2 | 0 | [Details →](https://spiderrating.com/servers/taylorwilsdon/google_workspace_mcp) |
| [claude-desktop-extension-bear-notes](https://github.com/vasylenko/claude-desktop-extension-bear-notes) | 🟡 C | 6.2 | 12 | 0 | [Details →](https://spiderrating.com/servers/vasylenko/claude-desktop-extension-bear-notes) |
| [google-calendar-mcp](https://github.com/takumi0706/google-calendar-mcp) | 🟡 C | 5.9 | 12 | 0 | [Details →](https://spiderrating.com/servers/takumi0706/google-calendar-mcp) |
| [google-mcp](https://github.com/vakharwalad23/google-mcp) | 🟠 D | 5.7 | 35 | 0 | [Details →](https://spiderrating.com/servers/vakharwalad23/google-mcp) |
| [Google-Workspace-MCP-Server](https://github.com/giuseppe-coco/Google-Workspace-MCP-Server) | 🟡 C | 5.4 | 12 | 9 | [Details →](https://spiderrating.com/servers/giuseppe-coco/Google-Workspace-MCP-Server) |
| [UpTier](https://github.com/foxintheloop/UpTier) | 🟡 C | 5.4 | 39 | 0 | [Details →](https://spiderrating.com/servers/foxintheloop/UpTier) |
| [better-notion-mcp](https://github.com/n24q02m/better-notion-mcp) | 🟠 D | 5.4 | 9 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/n24q02m/better-notion-mcp) |
| [reclaim-mcp-server](https://github.com/universalamateur/reclaim-mcp-server) | 🟡 C | 5.4 | 49 | 5 | [Details →](https://spiderrating.com/servers/universalamateur/reclaim-mcp-server) |
| [TexMCP](https://github.com/devroopsaha744/TexMCP) | 🟡 C | 5.2 | 5 | 0 | [Details →](https://spiderrating.com/servers/devroopsaha744/TexMCP) |
| [huly-mcp](https://github.com/dearlordylord/huly-mcp) | 🟠 D | 5.2 | 173 | 0 | [Details →](https://spiderrating.com/servers/dearlordylord/huly-mcp) |
| [prompeteer-mcp](https://github.com/prompeteer/prompeteer-mcp) | 🟠 D | 5.2 | 5 | 0 | [Details →](https://spiderrating.com/servers/prompeteer/prompeteer-mcp) |
| [calendar-mcp](https://github.com/wyattjoh/calendar-mcp) | 🟡 C | 5.1 | 6 | 0 | [Details →](https://spiderrating.com/servers/wyattjoh/calendar-mcp) |
| [fizzy-mcp](https://github.com/davegomez/fizzy-mcp) | 🟠 D | 5.1 | 7 | 2 (1 crit) | [Details →](https://spiderrating.com/servers/davegomez/fizzy-mcp) |
| [keepsake-mcp](https://github.com/nicolascroce/keepsake-mcp) | 🟠 D | 5.1 | 58 | 0 | [Details →](https://spiderrating.com/servers/nicolascroce/keepsake-mcp) |
| [mcp-altegio](https://github.com/moro3k/mcp-altegio) | 🟠 D | 5.1 | 18 | 0 | [Details →](https://spiderrating.com/servers/moro3k/mcp-altegio) |
| [kanboard-mcp](https://github.com/bivex/kanboard-mcp) | 🟠 D | 5.0 | 171 | 0 | [Details →](https://spiderrating.com/servers/bivex/kanboard-mcp) |
| [toggl-mcp](https://github.com/louis030195/toggl-mcp) | 🟠 D | 5.0 | 8 | 0 | [Details →](https://spiderrating.com/servers/louis030195/toggl-mcp) |
| [quip-mcp](https://github.com/bug-breeder/quip-mcp) | 🟠 D | 4.8 | 8 | 0 | [Details →](https://spiderrating.com/servers/bug-breeder/quip-mcp) |
| [mcp-orchestro](https://github.com/khaoss85/mcp-orchestro) | 🟠 D | 4.8 | 62 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/khaoss85/mcp-orchestro) |
| [mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite) | 🟠 D | 4.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/MarkusPfundstein/mcp-gsuite) |
| [sparksheets-mcp](https://github.com/saikiyusuke/sparksheets-mcp) | 🟠 D | 4.6 | 37 | 0 | [Details →](https://spiderrating.com/servers/saikiyusuke/sparksheets-mcp) |
| [mcp-server](https://github.com/UnMarkdown/mcp-server) | 🟠 D | 4.5 | 7 | 4 (2 crit) | [Details →](https://spiderrating.com/servers/UnMarkdown/mcp-server) |
| [jobgpt-mcp-server](https://github.com/6figr-com/jobgpt-mcp-server) | 🟠 D | 4.4 | 39 | 0 | [Details →](https://spiderrating.com/servers/6figr-com/jobgpt-mcp-server) |
| [amazon-seller-mcp](https://github.com/MarceauSolutions/amazon-seller-mcp) | 🟠 D | 4.3 | 8 | 0 | [Details →](https://spiderrating.com/servers/MarceauSolutions/amazon-seller-mcp) |
| [claudia](https://github.com/yuvalsuede/claudia) | 🔴 F | 4.1 | 48 | 3 (3 crit) | [Details →](https://spiderrating.com/servers/yuvalsuede/claudia) |

## 👤 Customer Data Platforms (7 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-server-chart](https://github.com/antvis/mcp-server-chart) | 🟡 C | 7.0 | 30 | 0 | [Details →](https://spiderrating.com/servers/antvis/mcp-server-chart) |
| [mcp-echarts](https://github.com/hustcc/mcp-echarts) | 🟡 C | 6.6 | 18 | 0 | [Details →](https://spiderrating.com/servers/hustcc/mcp-echarts) |
| [mcp-mermaid](https://github.com/hustcc/mcp-mermaid) | 🟡 C | 6.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/hustcc/mcp-mermaid) |
| [mcp-server-iaptic](https://github.com/iaptic/mcp-server-iaptic) | 🟡 C | 5.9 | 17 | 0 | [Details →](https://spiderrating.com/servers/iaptic/mcp-server-iaptic) |
| [inoyu-mcp-unomi-server](https://github.com/sergehuber/inoyu-mcp-unomi-server) | 🟡 C | 5.3 | 9 | 0 | [Details →](https://spiderrating.com/servers/sergehuber/inoyu-mcp-unomi-server) |
| [search-console-mcp](https://github.com/saurabhsharma2u/search-console-mcp) | 🟠 D | 5.3 | 93 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/saurabhsharma2u/search-console-mcp) |
| [quackback](https://github.com/QuackbackIO/quackback) | 🟠 D | 4.8 | 80 | 3 (2 crit) | [Details →](https://spiderrating.com/servers/QuackbackIO/quackback) |

## 👨‍💻 Code Execution (6 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [outsource-mcp](https://github.com/gwbischof/outsource-mcp) | 🟡 C | 6.9 | 2 | 2 | [Details →](https://spiderrating.com/servers/gwbischof/outsource-mcp) |
| [mcp-js](https://github.com/r33drichards/mcp-js) | 🟡 C | 6.6 | 10 | 0 | [Details →](https://spiderrating.com/servers/r33drichards/mcp-js) |
| [mcp-server-js](https://github.com/yepcode/mcp-server-js) | 🟡 C | 6.3 | 36 | 0 | [Details →](https://spiderrating.com/servers/yepcode/mcp-server-js) |
| [piston-mcp](https://github.com/alvii147/piston-mcp) | 🟡 C | 5.8 | 1 | 1 | [Details →](https://spiderrating.com/servers/alvii147/piston-mcp) |
| [node-code-sandbox-mcp](https://github.com/alfonsograziano/node-code-sandbox-mcp) | 🟡 C | 5.7 | 7 | 0 | [Details →](https://spiderrating.com/servers/alfonsograziano/node-code-sandbox-mcp) |
| [PRIMS](https://github.com/hileamlakB/PRIMS) | 🟠 D | 4.7 | 5 | 0 | [Details →](https://spiderrating.com/servers/hileamlakB/PRIMS) |

## 💬 Communication (48 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [line-bot-mcp-server](https://github.com/line/line-bot-mcp-server) | 🟡 C | 6.5 | 11 | 0 | [Details →](https://spiderrating.com/servers/line/line-bot-mcp-server) |
| [joinly](https://github.com/joinly-ai/joinly) | 🟠 D | 6.3 | 10 | 0 | [Details →](https://spiderrating.com/servers/joinly-ai/joinly) |
| [discourse-mcp](https://github.com/discourse/discourse-mcp) | 🟡 C | 6.3 | 23 | 0 | [Details →](https://spiderrating.com/servers/discourse/discourse-mcp) |
| [inbox-zero](https://github.com/elie222/inbox-zero) | 🟠 D | 6.3 | 18 | 0 | [Details →](https://spiderrating.com/servers/elie222/inbox-zero) |
| [apple-mail-mcp](https://github.com/imdinu/apple-mail-mcp) | 🟠 D | 6.3 | 6 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/imdinu/apple-mail-mcp) |
| [ms-365-mcp-server](https://github.com/softeria/ms-365-mcp-server) | 🟠 D | 6.2 | 20 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/softeria/ms-365-mcp-server) |
| [ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp) | 🟡 C | 6.1 | 1 | 0 | [Details →](https://spiderrating.com/servers/teddyzxcv/ntfy-mcp) |
| [didlogic_mcp](https://github.com/UserAd/didlogic_mcp) | 🟡 C | 6.1 | 22 | 0 | [Details →](https://spiderrating.com/servers/UserAd/didlogic_mcp) |
| [ntfy-me-mcp](https://github.com/gitmotion/ntfy-me-mcp) | 🟡 C | 6.0 | 2 | 0 | [Details →](https://spiderrating.com/servers/gitmotion/ntfy-me-mcp) |
| [acp-mcp](https://github.com/i-am-bee/acp-mcp) | 🟡 C | 5.9 | 3 | 0 | [Details →](https://spiderrating.com/servers/i-am-bee/acp-mcp) |
| [gtasks-mcp](https://github.com/zcaceres/gtasks-mcp) | 🟡 C | 5.9 | 7 | 0 | [Details →](https://spiderrating.com/servers/zcaceres/gtasks-mcp) |
| [jmap-mcp](https://github.com/wyattjoh/jmap-mcp) | 🟡 C | 5.9 | 9 | 0 | [Details →](https://spiderrating.com/servers/wyattjoh/jmap-mcp) |
| [whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) | 🟡 C | 5.9 | 12 | 12 | [Details →](https://spiderrating.com/servers/lharries/whatsapp-mcp) |
| [joltsms-mcp-server](https://github.com/rchanllc/joltsms-mcp-server) | 🟡 C | 5.8 | 10 | 0 | [Details →](https://spiderrating.com/servers/rchanllc/joltsms-mcp-server) |
| [imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server) | 🟡 C | 5.8 | 2 | 0 | [Details →](https://spiderrating.com/servers/hannesrudolph/imessage-query-fastmcp-mcp-server) |
| [imessage-mcp](https://github.com/wyattjoh/imessage-mcp) | 🟡 C | 5.8 | 6 | 0 | [Details →](https://spiderrating.com/servers/wyattjoh/imessage-mcp) |
| [outlook-assistant](https://github.com/littlebearapps/outlook-assistant) | 🟠 D | 5.8 | 20 | 0 | [Details →](https://spiderrating.com/servers/littlebearapps/outlook-assistant) |
| [agentmail-toolkit](https://github.com/agentmail-to/agentmail-toolkit) | 🟡 C | 5.7 | 11 | 0 | [Details →](https://spiderrating.com/servers/agentmail-to/agentmail-toolkit) |
| [mac_messages_mcp](https://github.com/carterlasalle/mac_messages_mcp) | 🟡 C | 5.7 | 9 | 3 | [Details →](https://spiderrating.com/servers/carterlasalle/mac_messages_mcp) |
| [vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp) | 🟡 C | 5.7 | 5 | 0 | [Details →](https://spiderrating.com/servers/sawa-zen/vrchat-mcp) |
| [mcp-twikit](https://github.com/adhikasp/mcp-twikit) | 🟠 D | 5.7 | 8 | 5 | [Details →](https://spiderrating.com/servers/adhikasp/mcp-twikit) |
| [mcp-googletasks](https://github.com/arpitbatra123/mcp-googletasks) | 🟠 D | 5.6 | 15 | 0 | [Details →](https://spiderrating.com/servers/arpitbatra123/mcp-googletasks) |
| [telegram-mcp](https://github.com/chaindead/telegram-mcp) | 🟡 C | 5.6 | 5 | 0 | [Details →](https://spiderrating.com/servers/chaindead/telegram-mcp) |
| [mattermost-mcp-host](https://github.com/jagan-shanmugam/mattermost-mcp-host) | 🟡 C | 5.5 | 9 | 5 | [Details →](https://spiderrating.com/servers/jagan-shanmugam/mattermost-mcp-host) |
| [callcenter.js-mcp](https://github.com/gerkensm/callcenter.js-mcp) | 🟠 D | 5.5 | 13 | 0 | [Details →](https://spiderrating.com/servers/gerkensm/callcenter.js-mcp) |
| [whatsapp-mcp-stream](https://github.com/loglux/whatsapp-mcp-stream) | 🟡 C | 5.5 | 27 | 0 | [Details →](https://spiderrating.com/servers/loglux/whatsapp-mcp-stream) |
| [open-feishu-mcp-server](https://github.com/ztxtxwd/open-feishu-mcp-server) | 🟠 D | 5.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/ztxtxwd/open-feishu-mcp-server) |
| [mcp-server](https://github.com/multimail-dev/mcp-server) | 🟡 C | 5.5 | 35 | 0 | [Details →](https://spiderrating.com/servers/multimail-dev/mcp-server) |
| [mcp-server](https://github.com/wazionapps/mcp-server) | 🟠 D | 5.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/wazionapps/mcp-server) |
| [calcom-mcp](https://github.com/Danielpeter-99/calcom-mcp) | 🟡 C | 5.4 | 8 | 7 | [Details →](https://spiderrating.com/servers/Danielpeter-99/calcom-mcp) |
| [better-email-mcp](https://github.com/n24q02m/better-email-mcp) | 🟠 D | 5.3 | 5 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/n24q02m/better-email-mcp) |
| [email-mcp](https://github.com/marlinjai/email-mcp) | 🟠 D | 5.2 | 24 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/marlinjai/email-mcp) |
| [mcp-server](https://github.com/FastAlertNow/mcp-server) | 🟠 D | 4.9 | 2 | 0 | [Details →](https://spiderrating.com/servers/FastAlertNow/mcp-server) |
| [slack-mcp-server](https://github.com/jtalk22/slack-mcp-server) | 🔴 F | 4.8 | 24 | 9 (9 crit) | [Details →](https://spiderrating.com/servers/jtalk22/slack-mcp-server) |
| [ycloud-whatsapp-mcp-server](https://github.com/YCloud-Developers/ycloud-whatsapp-mcp-server) | 🟠 D | 4.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/YCloud-Developers/ycloud-whatsapp-mcp-server) |
| [mcp-server](https://github.com/PostcardBot/mcp-server) | 🟠 D | 4.6 | 8 | 0 | [Details →](https://spiderrating.com/servers/PostcardBot/mcp-server) |
| [mcp-teams-server](https://github.com/InditexTech/mcp-teams-server) | 🟠 D | 4.6 | 6 | 0 | [Details →](https://spiderrating.com/servers/InditexTech/mcp-teams-server) |
| [chatterboxio-mcp-server](https://github.com/OverQuotaAI/chatterboxio-mcp-server) | 🟠 D | 4.6 | 3 | 0 | [Details →](https://spiderrating.com/servers/OverQuotaAI/chatterboxio-mcp-server) |
| [cv-mcp-server](https://github.com/PhononX/cv-mcp-server) | 🟠 D | 4.5 | 28 | 0 | [Details →](https://spiderrating.com/servers/PhononX/cv-mcp-server) |
| [caldav-mcp](https://github.com/madbonez/caldav-mcp) | 🟠 D | 4.5 | 8 | 0 | [Details →](https://spiderrating.com/servers/madbonez/caldav-mcp) |
| [telegram-bot-mcp](https://github.com/FantomaSkaRus1/telegram-bot-mcp) | 🟠 D | 4.5 | 170 | 0 | [Details →](https://spiderrating.com/servers/FantomaSkaRus1/telegram-bot-mcp) |
| [leximo-ai-call-assistant-mcp-server](https://github.com/Leximo-AI/leximo-ai-call-assistant-mcp-server) | 🟠 D | 4.5 | 13 | 0 | [Details →](https://spiderrating.com/servers/Leximo-AI/leximo-ai-call-assistant-mcp-server) |
| [mcp_server_notify](https://github.com/Cactusinhand/mcp_server_notify) | 🔴 F | 4.5 | 1 | 4 (4 crit) | [Details →](https://spiderrating.com/servers/Cactusinhand/mcp_server_notify) |
| [mattermost-mcp](https://github.com/conarti/mattermost-mcp) | 🟠 D | 4.5 | 9 | 0 | [Details →](https://spiderrating.com/servers/conarti/mattermost-mcp) |
| [email-mcp](https://github.com/codefuturist/email-mcp) | 🔴 F | 4.4 | 43 | 6 (6 crit) | [Details →](https://spiderrating.com/servers/codefuturist/email-mcp) |
| [nostr-mcp](https://github.com/AbdelStark/nostr-mcp) | 🟠 D | 4.2 | 2 | 0 | [Details →](https://spiderrating.com/servers/AbdelStark/nostr-mcp) |
| [tsgram-mcp](https://github.com/areweai/tsgram-mcp) | 🔴 F | 4.2 | 35 | 7 (7 crit) | [Details →](https://spiderrating.com/servers/areweai/tsgram-mcp) |
| [bluesky-context-server](https://github.com/keturiosakys/bluesky-context-server) | 🟠 D | 4.2 | 8 | 0 | [Details →](https://spiderrating.com/servers/keturiosakys/bluesky-context-server) |

## 💰 Finance & Fintech (133 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [chainlist-mcp](https://github.com/kukapay/chainlist-mcp) | 🟢 B | 7.7 | 2 | 1 | [Details →](https://spiderrating.com/servers/kukapay/chainlist-mcp) |
| [wallet-inspector-mcp](https://github.com/kukapay/wallet-inspector-mcp) | 🟢 B | 7.5 | 3 | 3 | [Details →](https://spiderrating.com/servers/kukapay/wallet-inspector-mcp) |
| [twitter-username-changes-mcp](https://github.com/kukapay/twitter-username-changes-mcp) | 🟢 B | 7.4 | 1 | 1 | [Details →](https://spiderrating.com/servers/kukapay/twitter-username-changes-mcp) |
| [web3-jobs-mcp](https://github.com/kukapay/web3-jobs-mcp) | 🟢 B | 7.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/kukapay/web3-jobs-mcp) |
| [hyperliquid-info-mcp](https://github.com/kukapay/hyperliquid-info-mcp) | 🟢 B | 7.3 | 17 | 13 | [Details →](https://spiderrating.com/servers/kukapay/hyperliquid-info-mcp) |
| [freqtrade-mcp](https://github.com/kukapay/freqtrade-mcp) | 🟢 B | 7.3 | 17 | 4 | [Details →](https://spiderrating.com/servers/kukapay/freqtrade-mcp) |
| [crypto-sentiment-mcp](https://github.com/kukapay/crypto-sentiment-mcp) | 🟢 B | 7.3 | 5 | 6 | [Details →](https://spiderrating.com/servers/kukapay/crypto-sentiment-mcp) |
| [blockbeats-mcp](https://github.com/kukapay/blockbeats-mcp) | 🟢 B | 7.2 | 2 | 0 | [Details →](https://spiderrating.com/servers/kukapay/blockbeats-mcp) |
| [hive-crypto-mcp](https://github.com/hive-intel/hive-crypto-mcp) | 🟡 C | 6.9 | 2 | 0 | [Details →](https://spiderrating.com/servers/hive-intel/hive-crypto-mcp) |
| [crypto-rss-mcp](https://github.com/kukapay/crypto-rss-mcp) | 🟡 C | 6.9 | 2 | 1 | [Details →](https://spiderrating.com/servers/kukapay/crypto-rss-mcp) |
| [funding-rates-mcp](https://github.com/kukapay/funding-rates-mcp) | 🟡 C | 6.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/kukapay/funding-rates-mcp) |
| [cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server) | 🟡 C | 6.8 | 1 | 1 | [Details →](https://spiderrating.com/servers/kukapay/cryptopanic-mcp-server) |
| [rug-check-mcp](https://github.com/kukapay/rug-check-mcp) | 🟡 C | 6.8 | 1 | 2 | [Details →](https://spiderrating.com/servers/kukapay/rug-check-mcp) |
| [crypto-whitepapers-mcp](https://github.com/kukapay/crypto-whitepapers-mcp) | 🟡 C | 6.8 | 4 | 3 | [Details →](https://spiderrating.com/servers/kukapay/crypto-whitepapers-mcp) |
| [stargate-bridge-mcp](https://github.com/kukapay/stargate-bridge-mcp) | 🟡 C | 6.7 | 4 | 2 | [Details →](https://spiderrating.com/servers/kukapay/stargate-bridge-mcp) |
| [pancakeswap-poolspy-mcp](https://github.com/kukapay/pancakeswap-poolspy-mcp) | 🟡 C | 6.7 | 1 | 0 | [Details →](https://spiderrating.com/servers/kukapay/pancakeswap-poolspy-mcp) |
| [cointelegraph-mcp](https://github.com/kukapay/cointelegraph-mcp) | 🟡 C | 6.6 | 2 | 1 | [Details →](https://spiderrating.com/servers/kukapay/cointelegraph-mcp) |
| [crypto-news-mcp](https://github.com/kukapay/crypto-news-mcp) | 🟡 C | 6.5 | 2 | 1 | [Details →](https://spiderrating.com/servers/kukapay/crypto-news-mcp) |
| [crypto-portfolio-mcp](https://github.com/kukapay/crypto-portfolio-mcp) | 🟡 C | 6.5 | 4 | 2 | [Details →](https://spiderrating.com/servers/kukapay/crypto-portfolio-mcp) |
| [etf-flow-mcp](https://github.com/kukapay/etf-flow-mcp) | 🟡 C | 6.5 | 1 | 1 | [Details →](https://spiderrating.com/servers/kukapay/etf-flow-mcp) |
| [blocknative-mcp](https://github.com/kukapay/blocknative-mcp) | 🟡 C | 6.4 | 3 | 0 | [Details →](https://spiderrating.com/servers/kukapay/blocknative-mcp) |
| [crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp) | 🟡 C | 6.4 | 3 | 0 | [Details →](https://spiderrating.com/servers/kukapay/crypto-feargreed-mcp) |
| [dao-proposals-mcp](https://github.com/kukapay/dao-proposals-mcp) | 🟡 C | 6.4 | 3 | 2 | [Details →](https://spiderrating.com/servers/kukapay/dao-proposals-mcp) |
| [mcp-klever-vm](https://github.com/klever-io/mcp-klever-vm) | 🟡 C | 6.4 | 33 | 0 | [Details →](https://spiderrating.com/servers/klever-io/mcp-klever-vm) |
| [uniswap-poolspy-mcp](https://github.com/kukapay/uniswap-poolspy-mcp) | 🟡 C | 6.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/kukapay/uniswap-poolspy-mcp) |
| [braintree-mcp-server](https://github.com/QuentinCody/braintree-mcp-server) | 🟡 C | 6.3 | 4 | 2 | [Details →](https://spiderrating.com/servers/QuentinCody/braintree-mcp-server) |
| [mcp-server](https://github.com/finmap-org/mcp-server) | 🟡 C | 6.3 | 9 | 0 | [Details →](https://spiderrating.com/servers/finmap-org/mcp-server) |
| [yfinance-mcp](https://github.com/narumiruna/yfinance-mcp) | 🟡 C | 6.2 | 5 | 0 | [Details →](https://spiderrating.com/servers/narumiruna/yfinance-mcp) |
| [thegraph-mcp](https://github.com/kukapay/thegraph-mcp) | 🟡 C | 6.1 | 2 | 2 | [Details →](https://spiderrating.com/servers/kukapay/thegraph-mcp) |
| [base-mcp](https://github.com/base/base-mcp) | 🟠 D | 6.0 | 10 | 0 | [Details →](https://spiderrating.com/servers/base/base-mcp) |
| [crypto-stocks-mcp](https://github.com/kukapay/crypto-stocks-mcp) | 🟡 C | 6.0 | 3 | 2 | [Details →](https://spiderrating.com/servers/kukapay/crypto-stocks-mcp) |
| [bicscan-mcp](https://github.com/ahnlabio/bicscan-mcp) | 🟡 C | 6.0 | 2 | 2 | [Details →](https://spiderrating.com/servers/ahnlabio/bicscan-mcp) |
| [alpha-vantage-mcp](https://github.com/berlinbra/alpha-vantage-mcp) | 🟡 C | 6.0 | 12 | 0 | [Details →](https://spiderrating.com/servers/berlinbra/alpha-vantage-mcp) |
| [mcp-server](https://github.com/payclaw/mcp-server) | 🟡 C | 6.0 | 6 | 0 | [Details →](https://spiderrating.com/servers/payclaw/mcp-server) |
| [mcp](https://github.com/getAlby/mcp) | 🟠 D | 5.9 | 11 | 0 | [Details →](https://spiderrating.com/servers/getAlby/mcp) |
| [debridge-mcp](https://github.com/debridge-finance/debridge-mcp) | 🟡 C | 5.9 | 6 | 0 | [Details →](https://spiderrating.com/servers/debridge-finance/debridge-mcp) |
| [mcp-server-ccxt](https://github.com/doggybee/mcp-server-ccxt) | 🟡 C | 5.9 | 24 | 0 | [Details →](https://spiderrating.com/servers/doggybee/mcp-server-ccxt) |
| [bridge-metrics-mcp](https://github.com/kukapay/bridge-metrics-mcp) | 🟡 C | 5.9 | 5 | 2 | [Details →](https://spiderrating.com/servers/kukapay/bridge-metrics-mcp) |
| [crypto-trending-mcp](https://github.com/kukapay/crypto-trending-mcp) | 🟡 C | 5.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/kukapay/crypto-trending-mcp) |
| [armor-crypto-mcp](https://github.com/armorwallet/armor-crypto-mcp) | 🟡 C | 5.9 | 37 | 1 | [Details →](https://spiderrating.com/servers/armorwallet/armor-crypto-mcp) |
| [defi-yields-mcp](https://github.com/kukapay/defi-yields-mcp) | 🟡 C | 5.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/kukapay/defi-yields-mcp) |
| [mcp-client](https://github.com/nullpath-labs/mcp-client) | 🟡 C | 5.9 | 6 | 0 | [Details →](https://spiderrating.com/servers/nullpath-labs/mcp-client) |
| [evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) | 🟠 D | 5.9 | 25 | 0 | [Details →](https://spiderrating.com/servers/mcpdotdirect/evm-mcp-server) |
| [crypto-orderbook-mcp](https://github.com/kukapay/crypto-orderbook-mcp) | 🟡 C | 5.8 | 2 | 2 | [Details →](https://spiderrating.com/servers/kukapay/crypto-orderbook-mcp) |
| [crypto-projects-mcp](https://github.com/kukapay/crypto-projects-mcp) | 🟡 C | 5.8 | 1 | 1 | [Details →](https://spiderrating.com/servers/kukapay/crypto-projects-mcp) |
| [builders-sodax-mcp-server](https://github.com/gosodax/builders-sodax-mcp-server) | 🟡 C | 5.8 | 14 | 0 | [Details →](https://spiderrating.com/servers/gosodax/builders-sodax-mcp-server) |
| [dexpaprika-mcp](https://github.com/coinpaprika/dexpaprika-mcp) | 🟡 C | 5.8 | 13 | 0 | [Details →](https://spiderrating.com/servers/coinpaprika/dexpaprika-mcp) |
| [whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp) | 🟡 C | 5.8 | 2 | 1 | [Details →](https://spiderrating.com/servers/kukapay/whale-tracker-mcp) |
| [wsb-analyst-mcp](https://github.com/ferdousbhai/wsb-analyst-mcp) | 🟡 C | 5.8 | 6 | 1 | [Details →](https://spiderrating.com/servers/ferdousbhai/wsb-analyst-mcp) |
| [korea-stock-mcp](https://github.com/jjlabsio/korea-stock-mcp) | 🟠 D | 5.7 | 8 | 0 | [Details →](https://spiderrating.com/servers/jjlabsio/korea-stock-mcp) |
| [fec-mcp-server](https://github.com/sh-patterson/fec-mcp-server) | 🟡 C | 5.7 | 8 | 0 | [Details →](https://spiderrating.com/servers/sh-patterson/fec-mcp-server) |
| [dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp) | 🟡 C | 5.7 | 2 | 0 | [Details →](https://spiderrating.com/servers/kukapay/dune-analytics-mcp) |
| [mcp-server-insumer](https://github.com/douglasborthwick-crypto/mcp-server-insumer) | 🟡 C | 5.7 | 27 | 0 | [Details →](https://spiderrating.com/servers/douglasborthwick-crypto/mcp-server-insumer) |
| [djd-agent-score-mcp](https://github.com/jacobsd32-cpu/djd-agent-score-mcp) | 🟡 C | 5.7 | 9 | 0 | [Details →](https://spiderrating.com/servers/jacobsd32-cpu/djd-agent-score-mcp) |
| [bitcoin-mcp](https://github.com/Bortlesboat/bitcoin-mcp) | 🟡 C | 5.7 | 43 | 14 | [Details →](https://spiderrating.com/servers/Bortlesboat/bitcoin-mcp) |
| [blockchain-mcp](https://github.com/tatumio/blockchain-mcp) | 🟡 C | 5.7 | 13 | 0 | [Details →](https://spiderrating.com/servers/tatumio/blockchain-mcp) |
| [metatrader-mcp-server](https://github.com/ariadng/metatrader-mcp-server) | 🟠 D | 5.7 | 25 | 8 | [Details →](https://spiderrating.com/servers/ariadng/metatrader-mcp-server) |
| [crypto-pegmon-mcp](https://github.com/kukapay/crypto-pegmon-mcp) | 🟡 C | 5.7 | 4 | 3 | [Details →](https://spiderrating.com/servers/kukapay/crypto-pegmon-mcp) |
| [alpaca-mcp](https://github.com/laukikk/alpaca-mcp) | 🟡 C | 5.7 | 8 | 3 | [Details →](https://spiderrating.com/servers/laukikk/alpaca-mcp) |
| [uniswap-trader-mcp](https://github.com/kukapay/uniswap-trader-mcp) | 🟡 C | 5.7 | 2 | 0 | [Details →](https://spiderrating.com/servers/kukapay/uniswap-trader-mcp) |
| [coin-mcp-server](https://github.com/pwh-pwh/coin-mcp-server) | 🟡 C | 5.6 | 3 | 0 | [Details →](https://spiderrating.com/servers/pwh-pwh/coin-mcp-server) |
| [crypto-liquidations-mcp](https://github.com/kukapay/crypto-liquidations-mcp) | 🟡 C | 5.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/kukapay/crypto-liquidations-mcp) |
| [lightning-enable-mcp](https://github.com/refined-element/lightning-enable-mcp) | 🟡 C | 5.6 | 3 | 0 | [Details →](https://spiderrating.com/servers/refined-element/lightning-enable-mcp) |
| [hyperliquid-whalealert-mcp](https://github.com/kukapay/hyperliquid-whalealert-mcp) | 🟡 C | 5.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/kukapay/hyperliquid-whalealert-mcp) |
| [crossfin](https://github.com/bubilife1202/crossfin) | 🟡 C | 5.6 | 34 | 0 | [Details →](https://spiderrating.com/servers/bubilife1202/crossfin) |
| [mcp](https://github.com/twelvedata/mcp) | 🟠 D | 5.6 | 184 | 1 | [Details →](https://spiderrating.com/servers/twelvedata/mcp) |
| [crypto-signals-mcp](https://github.com/MarcinDudekDev/crypto-signals-mcp) | 🟡 C | 5.5 | 6 | 2 | [Details →](https://spiderrating.com/servers/MarcinDudekDev/crypto-signals-mcp) |
| [web3-research-mcp](https://github.com/aaronjmars/web3-research-mcp) | 🟠 D | 5.5 | 11 | 0 | [Details →](https://spiderrating.com/servers/aaronjmars/web3-research-mcp) |
| [investor-agent](https://github.com/ferdousbhai/investor-agent) | 🟠 D | 5.5 | 13 | 3 | [Details →](https://spiderrating.com/servers/ferdousbhai/investor-agent) |
| [openmm-mcp](https://github.com/qbt-labs/openmm-mcp) | 🟠 D | 5.5 | 17 | 0 | [Details →](https://spiderrating.com/servers/qbt-labs/openmm-mcp) |
| [mcp-server-agentpay](https://github.com/joepangallo/mcp-server-agentpay) | 🟡 C | 5.5 | 13 | 0 | [Details →](https://spiderrating.com/servers/joepangallo/mcp-server-agentpay) |
| [dolar-mcp](https://github.com/dan1d/dolar-mcp) | 🟡 C | 5.5 | 6 | 0 | [Details →](https://spiderrating.com/servers/dan1d/dolar-mcp) |
| [hledger-mcp](https://github.com/iiAtlas/hledger-mcp) | 🟠 D | 5.5 | 25 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/iiAtlas/hledger-mcp) |
| [frihet-mcp](https://github.com/berthelius/frihet-mcp) | 🟠 D | 5.4 | 31 | 0 | [Details →](https://spiderrating.com/servers/berthelius/frihet-mcp) |
| [starknet-mcp-server](https://github.com/mcpdotdirect/starknet-mcp-server) | 🟠 D | 5.4 | 25 | 0 | [Details →](https://spiderrating.com/servers/mcpdotdirect/starknet-mcp-server) |
| [mcp-server-ledger](https://github.com/minhyeoky/mcp-server-ledger) | 🟡 C | 5.4 | 9 | 0 | [Details →](https://spiderrating.com/servers/minhyeoky/mcp-server-ledger) |
| [coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server) | 🟡 C | 5.4 | 2 | 2 | [Details →](https://spiderrating.com/servers/anjor/coinmarket-mcp-server) |
| [crypto-funds-mcp](https://github.com/kukapay/crypto-funds-mcp) | 🟡 C | 5.4 | 5 | 0 | [Details →](https://spiderrating.com/servers/kukapay/crypto-funds-mcp) |
| [crypto-indicators-mcp](https://github.com/kukapay/crypto-indicators-mcp) | 🟠 D | 5.4 | 78 | 0 | [Details →](https://spiderrating.com/servers/kukapay/crypto-indicators-mcp) |
| [mcp-server](https://github.com/azeth-protocol/mcp-server) | 🟠 D | 5.3 | 45 | 0 | [Details →](https://spiderrating.com/servers/azeth-protocol/mcp-server) |
| [finbud-data-mcp](https://github.com/glaksmono/finbud-data-mcp) | 🟠 D | 5.3 | 36 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/glaksmono/finbud-data-mcp) |
| [mcp_polygon](https://github.com/polygon-io/mcp_polygon) | 🟠 D | 5.3 | 4 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/polygon-io/mcp_polygon) |
| [systemr-python](https://github.com/System-R-AI/systemr-python) | 🟡 C | 5.3 | 1 | 1 | [Details →](https://spiderrating.com/servers/System-R-AI/systemr-python) |
| [w3ledger-mcp-server](https://github.com/baskcart/w3ledger-mcp-server) | 🟠 D | 5.3 | 6 | 0 | [Details →](https://spiderrating.com/servers/baskcart/w3ledger-mcp-server) |
| [jupiter-mcp](https://github.com/kukapay/jupiter-mcp) | 🟡 C | 5.3 | 2 | 0 | [Details →](https://spiderrating.com/servers/kukapay/jupiter-mcp) |
| [subscription-tracker-mcp](https://github.com/nckhemanth0/subscription-tracker-mcp) | 🟡 C | 5.3 | 16 | 0 | [Details →](https://spiderrating.com/servers/nckhemanth0/subscription-tracker-mcp) |
| [monarch-mcp-server](https://github.com/carsol/monarch-mcp-server) | 🟡 C | 5.3 | 6 | 0 | [Details →](https://spiderrating.com/servers/carsol/monarch-mcp-server) |
| [pumpswap-mcp](https://github.com/kukapay/pumpswap-mcp) | 🟡 C | 5.3 | 4 | 0 | [Details →](https://spiderrating.com/servers/kukapay/pumpswap-mcp) |
| [ethereum-validator-queue-mcp](https://github.com/kukapay/ethereum-validator-queue-mcp) | 🟡 C | 5.2 | 3 | 1 | [Details →](https://spiderrating.com/servers/kukapay/ethereum-validator-queue-mcp) |
| [dexscreener-trending-mcp](https://github.com/kukapay/dexscreener-trending-mcp) | 🟡 C | 5.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/kukapay/dexscreener-trending-mcp) |
| [chainlink-feeds-mcp](https://github.com/kukapay/chainlink-feeds-mcp) | 🟡 C | 5.2 | 5 | 0 | [Details →](https://spiderrating.com/servers/kukapay/chainlink-feeds-mcp) |
| [binance-alpha-mcp](https://github.com/kukapay/binance-alpha-mcp) | 🟡 C | 5.2 | 2 | 0 | [Details →](https://spiderrating.com/servers/kukapay/binance-alpha-mcp) |
| [uniswap-price-mcp](https://github.com/kukapay/uniswap-price-mcp) | 🟡 C | 5.2 | 2 | 0 | [Details →](https://spiderrating.com/servers/kukapay/uniswap-price-mcp) |
| [japan-corporate-mcp](https://github.com/yamariki-hub/japan-corporate-mcp) | 🟡 C | 5.2 | 8 | 6 | [Details →](https://spiderrating.com/servers/yamariki-hub/japan-corporate-mcp) |
| [bridge-rates-mcp](https://github.com/kukapay/bridge-rates-mcp) | 🟡 C | 5.2 | 3 | 0 | [Details →](https://spiderrating.com/servers/kukapay/bridge-rates-mcp) |
| [sui-trader-mcp](https://github.com/kukapay/sui-trader-mcp) | 🟡 C | 5.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/kukapay/sui-trader-mcp) |
| [token-revoke-mcp](https://github.com/kukapay/token-revoke-mcp) | 🟡 C | 5.2 | 4 | 0 | [Details →](https://spiderrating.com/servers/kukapay/token-revoke-mcp) |
| [bitcoin-utxo-mcp](https://github.com/kukapay/bitcoin-utxo-mcp) | 🟡 C | 5.2 | 2 | 1 | [Details →](https://spiderrating.com/servers/kukapay/bitcoin-utxo-mcp) |
| [token-minter-mcp](https://github.com/kukapay/token-minter-mcp) | 🟠 D | 5.1 | 6 | 0 | [Details →](https://spiderrating.com/servers/kukapay/token-minter-mcp) |
| [mcp-wallet-signer](https://github.com/nikicat/mcp-wallet-signer) | 🟠 D | 5.1 | 12 | 0 | [Details →](https://spiderrating.com/servers/nikicat/mcp-wallet-signer) |
| [primordia](https://github.com/oerc-s/primordia) | 🟠 D | 5.1 | 10 | 0 | [Details →](https://spiderrating.com/servers/oerc-s/primordia) |
| [polymarket-predictions-mcp](https://github.com/kukapay/polymarket-predictions-mcp) | 🟡 C | 5.1 | 3 | 0 | [Details →](https://spiderrating.com/servers/kukapay/polymarket-predictions-mcp) |
| [vibetrader-mcp](https://github.com/etbars/vibetrader-mcp) | 🟡 C | 5.1 | 30 | 18 | [Details →](https://spiderrating.com/servers/etbars/vibetrader-mcp) |
| [raydium-launchlab-mcp](https://github.com/kukapay/raydium-launchlab-mcp) | 🟡 C | 5.0 | 3 | 0 | [Details →](https://spiderrating.com/servers/kukapay/raydium-launchlab-mcp) |
| [baozi-mcp](https://github.com/bolivian-peru/baozi-mcp) | 🟠 D | 5.0 | 68 | 0 | [Details →](https://spiderrating.com/servers/bolivian-peru/baozi-mcp) |
| [debtstack-python](https://github.com/debtstack-ai/debtstack-python) | 🟠 D | 4.9 | 1 | 4 | [Details →](https://spiderrating.com/servers/debtstack-ai/debtstack-python) |
| [nwc-mcp-server](https://github.com/getalby/nwc-mcp-server) | 🟠 D | 4.9 | 6 | 0 | [Details →](https://spiderrating.com/servers/getalby/nwc-mcp-server) |
| [decide](https://github.com/decidefyi/decide) | 🟠 D | 4.9 | 8 | 0 | [Details →](https://spiderrating.com/servers/decidefyi/decide) |
| [tradememory-protocol](https://github.com/mnemox-ai/tradememory-protocol) | 🔴 F | 4.9 | 10 | 6 (6 crit) | [Details →](https://spiderrating.com/servers/mnemox-ai/tradememory-protocol) |
| [graph-aave-mcp](https://github.com/PaulieB14/graph-aave-mcp) | 🟠 D | 4.9 | 16 | 0 | [Details →](https://spiderrating.com/servers/PaulieB14/graph-aave-mcp) |
| [LNbits-MCP-Server](https://github.com/lnbits/LNbits-MCP-Server) | 🟠 D | 4.8 | 12 | 0 | [Details →](https://spiderrating.com/servers/lnbits/LNbits-MCP-Server) |
| [cryptodataapi-mcp](https://github.com/VENTURE-AI-LABS/cryptodataapi-mcp) | 🟠 D | 4.8 | 1 | 0 | [Details →](https://spiderrating.com/servers/VENTURE-AI-LABS/cryptodataapi-mcp) |
| [mcp-xrpl](https://github.com/RomThpt/mcp-xrpl) | 🟠 D | 4.7 | 71 | 0 | [Details →](https://spiderrating.com/servers/RomThpt/mcp-xrpl) |
| [octagon-mcp-server](https://github.com/OctagonAI/octagon-mcp-server) | 🟠 D | 4.7 | 3 | 0 | [Details →](https://spiderrating.com/servers/OctagonAI/octagon-mcp-server) |
| [graph-polymarket-mcp](https://github.com/PaulieB14/graph-polymarket-mcp) | 🟠 D | 4.7 | 24 | 0 | [Details →](https://spiderrating.com/servers/PaulieB14/graph-polymarket-mcp) |
| [substrate-mcp-rs](https://github.com/ThomasMarches/substrate-mcp-rs) | 🟠 D | 4.6 | 15 | 0 | [Details →](https://spiderrating.com/servers/ThomasMarches/substrate-mcp-rs) |
| [solscan-mcp](https://github.com/wowinter13/solscan-mcp) | 🟠 D | 4.6 | 36 | 0 | [Details →](https://spiderrating.com/servers/wowinter13/solscan-mcp) |
| [beeper-mcp](https://github.com/intentos-labs/beeper-mcp) | 🟠 D | 4.6 | 12 | 10 | [Details →](https://spiderrating.com/servers/intentos-labs/beeper-mcp) |
| [Reddit-Options-Trader-ROT-](https://github.com/Mattbusel/Reddit-Options-Trader-ROT-) | 🔴 F | 4.6 | 14 | 17 (11 crit) | [Details →](https://spiderrating.com/servers/Mattbusel/Reddit-Options-Trader-ROT-) |
| [clawpay-mcp](https://github.com/up2itnow0822/clawpay-mcp) | 🟠 D | 4.6 | 11 | 0 | [Details →](https://spiderrating.com/servers/up2itnow0822/clawpay-mcp) |
| [cardano-mcp](https://github.com/IndigoProtocol/cardano-mcp) | 🟠 D | 4.6 | 6 | 0 | [Details →](https://spiderrating.com/servers/IndigoProtocol/cardano-mcp) |
| [mcp-server](https://github.com/lightningfaucet/mcp-server) | 🟠 D | 4.5 | 43 | 0 | [Details →](https://spiderrating.com/servers/lightningfaucet/mcp-server) |
| [mcp-server](https://github.com/QuantConnect/mcp-server) | 🟠 D | 4.5 | 64 | 0 | [Details →](https://spiderrating.com/servers/QuantConnect/mcp-server) |
| [pix-mcp](https://github.com/Regenerating-World/pix-mcp) | 🟠 D | 4.5 | 4 | 0 | [Details →](https://spiderrating.com/servers/Regenerating-World/pix-mcp) |
| [mcp](https://github.com/BitteProtocol/mcp) | 🟠 D | 4.5 | 5 | 0 | [Details →](https://spiderrating.com/servers/BitteProtocol/mcp) |
| [prediction-market-mcp](https://github.com/JamesANZ/prediction-market-mcp) | 🟠 D | 4.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/JamesANZ/prediction-market-mcp) |
| [evm-mcp](https://github.com/JamesANZ/evm-mcp) | 🟠 D | 4.4 | 19 | 0 | [Details →](https://spiderrating.com/servers/JamesANZ/evm-mcp) |
| [bitcoin-mcp](https://github.com/JamesANZ/bitcoin-mcp) | 🟠 D | 4.3 | 5 | 0 | [Details →](https://spiderrating.com/servers/JamesANZ/bitcoin-mcp) |
| [indigo-mcp](https://github.com/IndigoProtocol/indigo-mcp) | 🟠 D | 4.3 | 59 | 0 | [Details →](https://spiderrating.com/servers/IndigoProtocol/indigo-mcp) |
| [onchain-mcp](https://github.com/Bankless/onchain-mcp) | 🟠 D | 4.3 | 10 | 0 | [Details →](https://spiderrating.com/servers/Bankless/onchain-mcp) |
| [dex-pools-mcp](https://github.com/kukapay/dex-pools-mcp) | 🟠 D | 4.2 | 10 | 11 | [Details →](https://spiderrating.com/servers/kukapay/dex-pools-mcp) |
| [rug-munch-mcp](https://github.com/CryptoRugMunch/rug-munch-mcp) | 🟠 D | 4.1 | 1 | 0 | [Details →](https://spiderrating.com/servers/CryptoRugMunch/rug-munch-mcp) |
| [spraay-x402-mcp](https://github.com/plagtech/spraay-x402-mcp) | 🟠 D | 4.0 | 67 | 36 | [Details →](https://spiderrating.com/servers/plagtech/spraay-x402-mcp) |

## 💻 Developer Tools (164 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [gitingest-mcp](https://github.com/narumiruna/gitingest-mcp) | 🟢 B | 7.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/narumiruna/gitingest-mcp) |
| [opslevel-mcp](https://github.com/opslevel/opslevel-mcp) | 🟡 C | 6.8 | 16 | 0 | [Details →](https://spiderrating.com/servers/opslevel/opslevel-mcp) |
| [Rootly-MCP-server](https://github.com/Rootly-AI-Labs/Rootly-MCP-server) | 🟡 C | 6.5 | 14 | 1 | [Details →](https://spiderrating.com/servers/Rootly-AI-Labs/Rootly-MCP-server) |
| [mindmap-mcp-server](https://github.com/YuChenSSR/mindmap-mcp-server) | 🟡 C | 6.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/YuChenSSR/mindmap-mcp-server) |
| [deploy-mcp](https://github.com/alexpota/deploy-mcp) | 🟡 C | 6.4 | 5 | 0 | [Details →](https://spiderrating.com/servers/alexpota/deploy-mcp) |
| [currents-mcp](https://github.com/currents-dev/currents-mcp) | 🟠 D | 6.4 | 28 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/currents-dev/currents-mcp) |
| [mcp-language-server](https://github.com/isaacphi/mcp-language-server) | 🟡 C | 6.4 | 8 | 0 | [Details →](https://spiderrating.com/servers/isaacphi/mcp-language-server) |
| [augments-mcp-server](https://github.com/augmnt/augments-mcp-server) | 🟡 C | 6.4 | 8 | 0 | [Details →](https://spiderrating.com/servers/augmnt/augments-mcp-server) |
| [testdino-mcp](https://github.com/testdino-hq/testdino-mcp) | 🟡 C | 6.4 | 12 | 0 | [Details →](https://spiderrating.com/servers/testdino-hq/testdino-mcp) |
| [just-mcp](https://github.com/promptexecution/just-mcp) | 🟡 C | 6.4 | 4 | 0 | [Details →](https://spiderrating.com/servers/promptexecution/just-mcp) |
| [mobile-mcp](https://github.com/mobile-next/mobile-mcp) | 🟠 D | 6.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/mobile-next/mobile-mcp) |
| [mcp-design-system-extractor](https://github.com/freema/mcp-design-system-extractor) | 🟡 C | 6.3 | 10 | 0 | [Details →](https://spiderrating.com/servers/freema/mcp-design-system-extractor) |
| [mcp](https://github.com/picahq/mcp) | 🟡 C | 6.3 | 4 | 0 | [Details →](https://spiderrating.com/servers/picahq/mcp) |
| [PiloTY](https://github.com/yiwenlu66/PiloTY) | 🟡 C | 6.3 | 16 | 5 | [Details →](https://spiderrating.com/servers/yiwenlu66/PiloTY) |
| [opik-mcp](https://github.com/comet-ml/opik-mcp) | 🟠 D | 6.3 | 10 | 0 | [Details →](https://spiderrating.com/servers/comet-ml/opik-mcp) |
| [ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp) | 🟠 D | 6.3 | 13 | 0 | [Details →](https://spiderrating.com/servers/joshuayoes/ios-simulator-mcp) |
| [buildkite-mcp-server](https://github.com/buildkite/buildkite-mcp-server) | 🟡 C | 6.2 | 27 | 0 | [Details →](https://spiderrating.com/servers/buildkite/buildkite-mcp-server) |
| [mcp-server-sql-analyzer](https://github.com/j4c0bs/mcp-server-sql-analyzer) | 🟡 C | 6.2 | 4 | 1 | [Details →](https://spiderrating.com/servers/j4c0bs/mcp-server-sql-analyzer) |
| [postman-mcp-server](https://github.com/delano/postman-mcp-server) | 🟠 D | 6.1 | 109 | 0 | [Details →](https://spiderrating.com/servers/delano/postman-mcp-server) |
| [next-devtools-mcp](https://github.com/vercel/next-devtools-mcp) | 🟡 C | 6.1 | 25 | 0 | [Details →](https://spiderrating.com/servers/vercel/next-devtools-mcp) |
| [kolibri](https://github.com/public-ui/kolibri) | 🔴 F | 6.1 | 3 | 9 (7 crit) | [Details →](https://spiderrating.com/servers/public-ui/kolibri) |
| [auto-mobile](https://github.com/zillow/auto-mobile) | 🟠 D | 6.1 | 10 | 0 | [Details →](https://spiderrating.com/servers/zillow/auto-mobile) |
| [memcord](https://github.com/ukkit/memcord) | 🟠 D | 6.0 | 24 | 0 | [Details →](https://spiderrating.com/servers/ukkit/memcord) |
| [Figma-Flutter-MCP](https://github.com/mhmzdev/Figma-Flutter-MCP) | 🟡 C | 6.0 | 13 | 0 | [Details →](https://spiderrating.com/servers/mhmzdev/Figma-Flutter-MCP) |
| [mindpilot-mcp](https://github.com/abrinsmead/mindpilot-mcp) | 🟡 C | 6.0 | 2 | 0 | [Details →](https://spiderrating.com/servers/abrinsmead/mindpilot-mcp) |
| [mcp-text-editor](https://github.com/tumf/mcp-text-editor) | 🟠 D | 6.0 | 6 | 5 | [Details →](https://spiderrating.com/servers/tumf/mcp-text-editor) |
| [FileScopeMCP](https://github.com/admica/FileScopeMCP) | 🟡 C | 6.0 | 19 | 0 | [Details →](https://spiderrating.com/servers/admica/FileScopeMCP) |
| [mcp-server-langfuse](https://github.com/langfuse/mcp-server-langfuse) | 🟡 C | 6.0 | 2 | 0 | [Details →](https://spiderrating.com/servers/langfuse/mcp-server-langfuse) |
| [bitrise-mcp](https://github.com/bitrise-io/bitrise-mcp) | 🟠 D | 6.0 | 67 | 0 | [Details →](https://spiderrating.com/servers/bitrise-io/bitrise-mcp) |
| [tools](https://github.com/golang/tools) | 🟠 D | 5.9 | 12 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/golang/tools) |
| [mcp-server-atlassian-bitbucket](https://github.com/aashari/mcp-server-atlassian-bitbucket) | 🟠 D | 5.9 | 6 | 1 | [Details →](https://spiderrating.com/servers/aashari/mcp-server-atlassian-bitbucket) |
| [mcp-server](https://github.com/configcat/mcp-server) | 🟠 D | 5.9 | 79 | 0 | [Details →](https://spiderrating.com/servers/configcat/mcp-server) |
| [sourcerer-mcp](https://github.com/st3v3nmw/sourcerer-mcp) | 🟡 C | 5.9 | 5 | 0 | [Details →](https://spiderrating.com/servers/st3v3nmw/sourcerer-mcp) |
| [k6-mcp-server](https://github.com/QAInsights/k6-mcp-server) | 🟡 C | 5.9 | 2 | 2 | [Details →](https://spiderrating.com/servers/QAInsights/k6-mcp-server) |
| [xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server) | 🟠 D | 5.9 | 70 | 0 | [Details →](https://spiderrating.com/servers/r-huijts/xcode-mcp-server) |
| [octocode-mcp](https://github.com/bgauryy/octocode-mcp) | 🟠 D | 5.8 | 413 | 0 | [Details →](https://spiderrating.com/servers/bgauryy/octocode-mcp) |
| [globalping-mcp-server](https://github.com/jsdelivr/globalping-mcp-server) | 🟡 C | 5.8 | 11 | 0 | [Details →](https://spiderrating.com/servers/jsdelivr/globalping-mcp-server) |
| [repocrunch](https://github.com/kimwwk/repocrunch) | 🟡 C | 5.8 | 1 | 0 | [Details →](https://spiderrating.com/servers/kimwwk/repocrunch) |
| [BifrostMCP](https://github.com/biegehydra/BifrostMCP) | 🟠 D | 5.8 | 19 | 0 | [Details →](https://spiderrating.com/servers/biegehydra/BifrostMCP) |
| [swift-patterns-mcp](https://github.com/efremidze/swift-patterns-mcp) | 🟡 C | 5.8 | 8 | 0 | [Details →](https://spiderrating.com/servers/efremidze/swift-patterns-mcp) |
| [fetch-mcp](https://github.com/zcaceres/fetch-mcp) | 🟡 C | 5.8 | 6 | 0 | [Details →](https://spiderrating.com/servers/zcaceres/fetch-mcp) |
| [edgeone-pages-mcp](https://github.com/TencentEdgeOne/edgeone-pages-mcp) | 🟡 C | 5.8 | 3 | 0 | [Details →](https://spiderrating.com/servers/TencentEdgeOne/edgeone-pages-mcp) |
| [xray](https://github.com/srijanshukla18/xray) | 🟠 D | 5.8 | 4 | 3 (1 crit) | [Details →](https://spiderrating.com/servers/srijanshukla18/xray) |
| [higress-ops-mcp-server](https://github.com/higress-group/higress-ops-mcp-server) | 🟡 C | 5.8 | 10 | 9 | [Details →](https://spiderrating.com/servers/higress-group/higress-ops-mcp-server) |
| [package-registry-mcp](https://github.com/artmann/package-registry-mcp) | 🟠 D | 5.7 | 19 | 0 | [Details →](https://spiderrating.com/servers/artmann/package-registry-mcp) |
| [multi-ai-advisor-mcp](https://github.com/YuChenSSR/multi-ai-advisor-mcp) | 🟡 C | 5.7 | 2 | 0 | [Details →](https://spiderrating.com/servers/YuChenSSR/multi-ai-advisor-mcp) |
| [ros-mcp](https://github.com/Yutarop/ros-mcp) | 🟡 C | 5.7 | 24 | 9 | [Details →](https://spiderrating.com/servers/Yutarop/ros-mcp) |
| [mcp-package-version](https://github.com/sammcj/mcp-package-version) | 🟡 C | 5.7 | 11 | 0 | [Details →](https://spiderrating.com/servers/sammcj/mcp-package-version) |
| [claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) | 🟠 D | 5.7 | 2 | 0 | [Details →](https://spiderrating.com/servers/jasonjmcghee/claude-debugs-for-you) |
| [codewiki-mcp](https://github.com/izzzzzi/codewiki-mcp) | 🟡 C | 5.6 | 3 | 0 | [Details →](https://spiderrating.com/servers/izzzzzi/codewiki-mcp) |
| [apisix-mcp](https://github.com/api7/apisix-mcp) | 🟠 D | 5.6 | 32 | 0 | [Details →](https://spiderrating.com/servers/api7/apisix-mcp) |
| [postmancer](https://github.com/hijaz/postmancer) | 🟡 C | 5.6 | 7 | 0 | [Details →](https://spiderrating.com/servers/hijaz/postmancer) |
| [devplan-mcp-server](https://github.com/mmorris35/devplan-mcp-server) | 🟡 C | 5.6 | 25 | 0 | [Details →](https://spiderrating.com/servers/mmorris35/devplan-mcp-server) |
| [mcp](https://github.com/Webvizio/mcp) | 🟡 C | 5.6 | 12 | 0 | [Details →](https://spiderrating.com/servers/Webvizio/mcp) |
| [context-rot-detection](https://github.com/milos-product-maker/context-rot-detection) | 🟡 C | 5.6 | 3 | 0 | [Details →](https://spiderrating.com/servers/milos-product-maker/context-rot-detection) |
| [flowbite-mcp](https://github.com/themesberg/flowbite-mcp) | 🟠 D | 5.6 | 70 | 0 | [Details →](https://spiderrating.com/servers/themesberg/flowbite-mcp) |
| [mcp-server-atlassian-jira](https://github.com/aashari/mcp-server-atlassian-jira) | 🟠 D | 5.6 | 5 | 1 | [Details →](https://spiderrating.com/servers/aashari/mcp-server-atlassian-jira) |
| [mcp-server-atlassian-confluence](https://github.com/aashari/mcp-server-atlassian-confluence) | 🟠 D | 5.6 | 5 | 1 | [Details →](https://spiderrating.com/servers/aashari/mcp-server-atlassian-confluence) |
| [higress](https://github.com/alibaba/higress) | 🟠 D | 5.6 | 1 | 4 | [Details →](https://spiderrating.com/servers/alibaba/higress) |
| [mcp-swagger-server](https://github.com/zaizaizhao/mcp-swagger-server) | 🟠 D | 5.5 | 62 | 0 | [Details →](https://spiderrating.com/servers/zaizaizhao/mcp-swagger-server) |
| [SpaceBridge-MCP](https://github.com/spacecode-ai/SpaceBridge-MCP) | 🟡 C | 5.5 | 4 | 1 | [Details →](https://spiderrating.com/servers/spacecode-ai/SpaceBridge-MCP) |
| [jira-github-mcp](https://github.com/TamarEngel/jira-github-mcp) | 🟡 C | 5.5 | 8 | 4 | [Details →](https://spiderrating.com/servers/TamarEngel/jira-github-mcp) |
| [unified-diff-mcp](https://github.com/gorosun/unified-diff-mcp) | 🟡 C | 5.5 | 5 | 0 | [Details →](https://spiderrating.com/servers/gorosun/unified-diff-mcp) |
| [agent-skill-loader](https://github.com/back1ply/agent-skill-loader) | 🟡 C | 5.4 | 5 | 0 | [Details →](https://spiderrating.com/servers/back1ply/agent-skill-loader) |
| [mcp-server-scraper](https://github.com/ofershap/mcp-server-scraper) | 🟡 C | 5.4 | 5 | 0 | [Details →](https://spiderrating.com/servers/ofershap/mcp-server-scraper) |
| [src-to-kb](https://github.com/vezlo/src-to-kb) | 🟠 D | 5.4 | 6 | 0 | [Details →](https://spiderrating.com/servers/vezlo/src-to-kb) |
| [awesome-ionic-mcp](https://github.com/Tommertom/awesome-ionic-mcp) | 🟡 C | 5.4 | 42 | 0 | [Details →](https://spiderrating.com/servers/Tommertom/awesome-ionic-mcp) |
| [skill-ninja-mcp-server](https://github.com/aktsmm/skill-ninja-mcp-server) | 🟡 C | 5.4 | 9 | 0 | [Details →](https://spiderrating.com/servers/aktsmm/skill-ninja-mcp-server) |
| [figma-use](https://github.com/dannote/figma-use) | 🟠 D | 5.4 | 9 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/dannote/figma-use) |
| [mcp-server-docker](https://github.com/ofershap/mcp-server-docker) | 🟡 C | 5.4 | 10 | 0 | [Details →](https://spiderrating.com/servers/ofershap/mcp-server-docker) |
| [srclight](https://github.com/srclight/srclight) | 🔴 F | 5.4 | 32 | 42 (29 crit) | [Details →](https://spiderrating.com/servers/srclight/srclight) |
| [bruno-mcp](https://github.com/hungthai1401/bruno-mcp) | 🟡 C | 5.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/hungthai1401/bruno-mcp) |
| [mcp-nixos](https://github.com/utensils/mcp-nixos) | 🟡 C | 5.4 | 2 | 9 | [Details →](https://spiderrating.com/servers/utensils/mcp-nixos) |
| [claude-task-master](https://github.com/eyaltoledano/claude-task-master) | 🔴 F | 5.3 | 73 | 6 (6 crit) | [Details →](https://spiderrating.com/servers/eyaltoledano/claude-task-master) |
| [conan-mcp](https://github.com/conan-io/conan-mcp) | 🟠 D | 5.3 | 7 | 0 | [Details →](https://spiderrating.com/servers/conan-io/conan-mcp) |
| [website-downloader](https://github.com/pskill9/website-downloader) | 🟡 C | 5.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/pskill9/website-downloader) |
| [lldb-mcp](https://github.com/stass/lldb-mcp) | 🟠 D | 5.3 | 28 | 26 | [Details →](https://spiderrating.com/servers/stass/lldb-mcp) |
| [DevDocs-MCP](https://github.com/madhan-g-p/DevDocs-MCP) | 🟡 C | 5.3 | 5 | 0 | [Details →](https://spiderrating.com/servers/madhan-g-p/DevDocs-MCP) |
| [claude-critical-rules-mcp](https://github.com/optimaquantum/claude-critical-rules-mcp) | 🟡 C | 5.3 | 5 | 0 | [Details →](https://spiderrating.com/servers/optimaquantum/claude-critical-rules-mcp) |
| [locust-mcp-server](https://github.com/QAInsights/locust-mcp-server) | 🟡 C | 5.3 | 1 | 1 | [Details →](https://spiderrating.com/servers/QAInsights/locust-mcp-server) |
| [testcollab-mcp-server](https://github.com/TCSoftInc/testcollab-mcp-server) | 🟡 C | 5.3 | 17 | 0 | [Details →](https://spiderrating.com/servers/TCSoftInc/testcollab-mcp-server) |
| [bugsnag-mcp](https://github.com/tgeselle/bugsnag-mcp) | 🟡 C | 5.3 | 11 | 0 | [Details →](https://spiderrating.com/servers/tgeselle/bugsnag-mcp) |
| [npm-package-docs-mcp](https://github.com/meanands/npm-package-docs-mcp) | 🟡 C | 5.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/meanands/npm-package-docs-mcp) |
| [mcp-server-boilerplate](https://github.com/shellsage-ai/mcp-server-boilerplate) | 🟠 D | 5.2 | 2 | 0 | [Details →](https://spiderrating.com/servers/shellsage-ai/mcp-server-boilerplate) |
| [jsr-mcp](https://github.com/wyattjoh/jsr-mcp) | 🟠 D | 5.2 | 40 | 0 | [Details →](https://spiderrating.com/servers/wyattjoh/jsr-mcp) |
| [mcp-claude-code](https://github.com/SDGLBL/mcp-claude-code) | 🟠 D | 5.2 | 16 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/SDGLBL/mcp-claude-code) |
| [time-node-mcp](https://github.com/davidan90/time-node-mcp) | 🟡 C | 5.2 | 4 | 0 | [Details →](https://spiderrating.com/servers/davidan90/time-node-mcp) |
| [simctl-mcp](https://github.com/ambar/simctl-mcp) | 🟡 C | 5.2 | 29 | 0 | [Details →](https://spiderrating.com/servers/ambar/simctl-mcp) |
| [mcp-code-runner](https://github.com/axliupore/mcp-code-runner) | 🟡 C | 5.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/axliupore/mcp-code-runner) |
| [mcp-server-github-actions](https://github.com/ofershap/mcp-server-github-actions) | 🟡 C | 5.2 | 9 | 0 | [Details →](https://spiderrating.com/servers/ofershap/mcp-server-github-actions) |
| [react-analyzer-mcp](https://github.com/azer/react-analyzer-mcp) | 🟡 C | 5.2 | 3 | 0 | [Details →](https://spiderrating.com/servers/azer/react-analyzer-mcp) |
| [gradle-mcp-server](https://github.com/IlyaGulya/gradle-mcp-server) | 🟡 C | 5.2 | 2 | 0 | [Details →](https://spiderrating.com/servers/IlyaGulya/gradle-mcp-server) |
| [jmeter-mcp-server](https://github.com/QAInsights/jmeter-mcp-server) | 🟡 C | 5.2 | 6 | 6 | [Details →](https://spiderrating.com/servers/QAInsights/jmeter-mcp-server) |
| [mcp-server-markdown](https://github.com/ofershap/mcp-server-markdown) | 🟡 C | 5.2 | 6 | 0 | [Details →](https://spiderrating.com/servers/ofershap/mcp-server-markdown) |
| [pox-mcp-server](https://github.com/davidlin2k/pox-mcp-server) | 🟡 C | 5.2 | 5 | 4 | [Details →](https://spiderrating.com/servers/davidlin2k/pox-mcp-server) |
| [pantheon-mcp](https://github.com/valado/pantheon-mcp) | 🟡 C | 5.2 | 3 | 0 | [Details →](https://spiderrating.com/servers/valado/pantheon-mcp) |
| [claude-mermaid](https://github.com/veelenga/claude-mermaid) | 🟠 D | 5.1 | 2 | 0 | [Details →](https://spiderrating.com/servers/veelenga/claude-mermaid) |
| [char-index-mcp](https://github.com/agent-hanju/char-index-mcp) | 🟠 D | 5.1 | 12 | 0 | [Details →](https://spiderrating.com/servers/agent-hanju/char-index-mcp) |
| [llm-token-tracker](https://github.com/wn01011/llm-token-tracker) | 🟡 C | 5.1 | 6 | 0 | [Details →](https://spiderrating.com/servers/wn01011/llm-token-tracker) |
| [mcp-server-circleci](https://github.com/CircleCI-Public/mcp-server-circleci) | 🟡 C | 5.1 | 14 | 0 | [Details →](https://spiderrating.com/servers/CircleCI-Public/mcp-server-circleci) |
| [mcp-server-npm-plus](https://github.com/ofershap/mcp-server-npm-plus) | 🟡 C | 5.1 | 8 | 0 | [Details →](https://spiderrating.com/servers/ofershap/mcp-server-npm-plus) |
| [asc-mcp](https://github.com/zelentsov-dev/asc-mcp) | 🟠 D | 5.1 | 162 | 0 | [Details →](https://spiderrating.com/servers/zelentsov-dev/asc-mcp) |
| [ai-distiller](https://github.com/janreges/ai-distiller) | 🔴 F | 5.1 | 16 | 7 (7 crit) | [Details →](https://spiderrating.com/servers/janreges/ai-distiller) |
| [swarmia-mcp](https://github.com/mattjegan/swarmia-mcp) | 🟡 C | 5.1 | 6 | 0 | [Details →](https://spiderrating.com/servers/mattjegan/swarmia-mcp) |
| [mcp-codebase-index](https://github.com/MikeRecognex/mcp-codebase-index) | 🟠 D | 5.1 | 18 | 2 (1 crit) | [Details →](https://spiderrating.com/servers/MikeRecognex/mcp-codebase-index) |
| [cursor-usage](https://github.com/ofershap/cursor-usage) | 🟡 C | 5.1 | 18 | 0 | [Details →](https://spiderrating.com/servers/ofershap/cursor-usage) |
| [ios-mcp-code-quality-server](https://github.com/a-25/ios-mcp-code-quality-server) | 🔴 F | 5.0 | 3 | 8 (8 crit) | [Details →](https://spiderrating.com/servers/a-25/ios-mcp-code-quality-server) |
| [agent-utils-mcp](https://github.com/aparajithn/agent-utils-mcp) | 🟡 C | 5.0 | 18 | 16 | [Details →](https://spiderrating.com/servers/aparajithn/agent-utils-mcp) |
| [code-rag-golang](https://github.com/nullptr-z/code-rag-golang) | 🟠 D | 5.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/nullptr-z/code-rag-golang) |
| [mcp-server-github-gist](https://github.com/ofershap/mcp-server-github-gist) | 🟡 C | 5.0 | 8 | 0 | [Details →](https://spiderrating.com/servers/ofershap/mcp-server-github-gist) |
| [mac-monitor-mcp](https://github.com/Pratyay/mac-monitor-mcp) | 🟠 D | 5.0 | 3 | 1 | [Details →](https://spiderrating.com/servers/Pratyay/mac-monitor-mcp) |
| [RulesetMCP](https://github.com/n8daniels/RulesetMCP) | 🟠 D | 5.0 | 5 | 0 | [Details →](https://spiderrating.com/servers/n8daniels/RulesetMCP) |
| [mcp-server-dns](https://github.com/ofershap/mcp-server-dns) | 🟠 D | 5.0 | 5 | 0 | [Details →](https://spiderrating.com/servers/ofershap/mcp-server-dns) |
| [stacksfinder-mcp](https://github.com/hoklims/stacksfinder-mcp) | 🟠 D | 5.0 | 53 | 0 | [Details →](https://spiderrating.com/servers/hoklims/stacksfinder-mcp) |
| [atest-mcp-server](https://github.com/LinuxSuRen/atest-mcp-server) | 🟠 D | 5.0 | 16 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/LinuxSuRen/atest-mcp-server) |
| [user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp) | 🟠 D | 5.0 | 1 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/mrexodia/user-feedback-mcp) |
| [twitterapi-docs-mcp](https://github.com/dorukardahan/twitterapi-docs-mcp) | 🟠 D | 4.9 | 11 | 1 | [Details →](https://spiderrating.com/servers/dorukardahan/twitterapi-docs-mcp) |
| [jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server) | 🟠 D | 4.9 | 9 | 5 (2 crit) | [Details →](https://spiderrating.com/servers/xzq-xu/jvm-mcp-server) |
| [dotnet-template-mcp](https://github.com/YuliiaKovalova/dotnet-template-mcp) | 🟠 D | 4.9 | 14 | 0 | [Details →](https://spiderrating.com/servers/YuliiaKovalova/dotnet-template-mcp) |
| [MCP_AI_SOC_Sher](https://github.com/akramIOT/MCP_AI_SOC_Sher) | 🟠 D | 4.9 | 3 | 4 | [Details →](https://spiderrating.com/servers/akramIOT/MCP_AI_SOC_Sher) |
| [mcp-server-devutils](https://github.com/ofershap/mcp-server-devutils) | 🟠 D | 4.9 | 17 | 0 | [Details →](https://spiderrating.com/servers/ofershap/mcp-server-devutils) |
| [shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server) | 🔴 F | 4.9 | 44 | 4 (4 crit) | [Details →](https://spiderrating.com/servers/Jpisnice/shadcn-ui-mcp-server) |
| [codelogic-mcp-server](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server) | 🟠 D | 4.9 | 5 | 0 | [Details →](https://spiderrating.com/servers/CodeLogicIncEngineering/codelogic-mcp-server) |
| [garmin-documentation-mcp-server](https://github.com/ztuskes/garmin-documentation-mcp-server) | 🟠 D | 4.9 | 8 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/ztuskes/garmin-documentation-mcp-server) |
| [hub-mcp](https://github.com/docker/hub-mcp) | 🟠 D | 4.8 | 13 | 6 | [Details →](https://spiderrating.com/servers/docker/hub-mcp) |
| [callout](https://github.com/fantasieleven-code/callout) | 🟠 D | 4.8 | 19 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/fantasieleven-code/callout) |
| [pylon-mcp](https://github.com/pylonapi/pylon-mcp) | 🟠 D | 4.8 | 10 | 0 | [Details →](https://spiderrating.com/servers/pylonapi/pylon-mcp) |
| [mcp_server_ros_2](https://github.com/wise-vision/mcp_server_ros_2) | 🟠 D | 4.8 | 1 | 0 | [Details →](https://spiderrating.com/servers/wise-vision/mcp_server_ros_2) |
| [gptzero-mcp](https://github.com/louis030195/gptzero-mcp) | 🟠 D | 4.8 | 2 | 0 | [Details →](https://spiderrating.com/servers/louis030195/gptzero-mcp) |
| [firefly-mcp](https://github.com/gofireflyio/firefly-mcp) | 🟠 D | 4.8 | 6 | 0 | [Details →](https://spiderrating.com/servers/gofireflyio/firefly-mcp) |
| [editorconfig_mcp](https://github.com/neilberkman/editorconfig_mcp) | 🟠 D | 4.8 | 3 | 0 | [Details →](https://spiderrating.com/servers/neilberkman/editorconfig_mcp) |
| [claude-faf-mcp](https://github.com/Wolfe-Jam/claude-faf-mcp) | 🟠 D | 4.8 | 73 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/Wolfe-Jam/claude-faf-mcp) |
| [Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) | 🟠 D | 4.7 | 2 | 0 | [Details →](https://spiderrating.com/servers/GLips/Figma-Context-MCP) |
| [spreadsheet-mcp](https://github.com/PSU3D0/spreadsheet-mcp) | 🟠 D | 4.7 | 54 | 0 | [Details →](https://spiderrating.com/servers/PSU3D0/spreadsheet-mcp) |
| [jenkins-mcp-server](https://github.com/avisangle/jenkins-mcp-server) | 🔴 F | 4.6 | 14 | 18 (6 crit) | [Details →](https://spiderrating.com/servers/avisangle/jenkins-mcp-server) |
| [mcp-adr-analysis-server](https://github.com/tosin2013/mcp-adr-analysis-server) | 🔴 F | 4.6 | 152 | 9 (9 crit) | [Details →](https://spiderrating.com/servers/tosin2013/mcp-adr-analysis-server) |
| [codebase-context](https://github.com/PatrickSys/codebase-context) | 🟠 D | 4.6 | 10 | 0 | [Details →](https://spiderrating.com/servers/PatrickSys/codebase-context) |
| [token-optimizer-mcp](https://github.com/ooples/token-optimizer-mcp) | 🔴 F | 4.6 | 103 | 21 (19 crit) | [Details →](https://spiderrating.com/servers/ooples/token-optimizer-mcp) |
| [clarifyprompt-mcp](https://github.com/LumabyteCo/clarifyprompt-mcp) | 🟠 D | 4.6 | 7 | 0 | [Details →](https://spiderrating.com/servers/LumabyteCo/clarifyprompt-mcp) |
| [mcp-gitlab-jira](https://github.com/HainanZhao/mcp-gitlab-jira) | 🟠 D | 4.5 | 57 | 0 | [Details →](https://spiderrating.com/servers/HainanZhao/mcp-gitlab-jira) |
| [octomind-mcp](https://github.com/OctoMind-dev/octomind-mcp) | 🟠 D | 4.5 | 21 | 0 | [Details →](https://spiderrating.com/servers/OctoMind-dev/octomind-mcp) |
| [faf-mcp](https://github.com/Wolfe-Jam/faf-mcp) | 🟠 D | 4.5 | 71 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/Wolfe-Jam/faf-mcp) |
| [teamcity-mcp](https://github.com/Daghis/teamcity-mcp) | 🟠 D | 4.5 | 91 | 0 | [Details →](https://spiderrating.com/servers/Daghis/teamcity-mcp) |
| [app-store-connect-mcp-server](https://github.com/JoshuaRileyDev/app-store-connect-mcp-server) | 🟠 D | 4.5 | 27 | 0 | [Details →](https://spiderrating.com/servers/JoshuaRileyDev/app-store-connect-mcp-server) |
| [claudecodenavi-mcp](https://github.com/saikiyusuke/claudecodenavi-mcp) | 🟠 D | 4.5 | 27 | 0 | [Details →](https://spiderrating.com/servers/saikiyusuke/claudecodenavi-mcp) |
| [vercel-ai-docs-mcp](https://github.com/IvanAmador/vercel-ai-docs-mcp) | 🟠 D | 4.5 | 3 | 0 | [Details →](https://spiderrating.com/servers/IvanAmador/vercel-ai-docs-mcp) |
| [addon-mcp](https://github.com/storybookjs/addon-mcp) | 🟠 D | 4.5 | 4 | 0 | [Details →](https://spiderrating.com/servers/storybookjs/addon-mcp) |
| [fastmcp-sonarqube-metrics](https://github.com/ArchAI-Labs/fastmcp-sonarqube-metrics) | 🟠 D | 4.5 | 8 | 0 | [Details →](https://spiderrating.com/servers/ArchAI-Labs/fastmcp-sonarqube-metrics) |
| [AiDex](https://github.com/CSCSoftware/AiDex) | 🟠 D | 4.4 | 27 | 0 | [Details →](https://spiderrating.com/servers/CSCSoftware/AiDex) |
| [scriptflow-mcp](https://github.com/yanmxa/scriptflow-mcp) | 🟠 D | 4.4 | 6 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/yanmxa/scriptflow-mcp) |
| [qasphere-mcp](https://github.com/Hypersequent/qasphere-mcp) | 🟠 D | 4.4 | 17 | 0 | [Details →](https://spiderrating.com/servers/Hypersequent/qasphere-mcp) |
| [CodeMCP](https://github.com/SimplyLiz/CodeMCP) | 🟠 D | 4.4 | 3 | 0 | [Details →](https://spiderrating.com/servers/SimplyLiz/CodeMCP) |
| [xcodebuild](https://github.com/ShenghaiWang/xcodebuild) | 🟠 D | 4.3 | 2 | 0 | [Details →](https://spiderrating.com/servers/ShenghaiWang/xcodebuild) |
| [openapi-mcp-server](https://github.com/snaggle-ai/openapi-mcp-server) | 🟠 D | 4.3 | 3 | 0 | [Details →](https://spiderrating.com/servers/snaggle-ai/openapi-mcp-server) |
| [promptarchitect-mcp](https://github.com/MerabyLabs/promptarchitect-mcp) | 🟠 D | 4.3 | 4 | 0 | [Details →](https://spiderrating.com/servers/MerabyLabs/promptarchitect-mcp) |
| [rust-docs-mcp-server](https://github.com/Govcraft/rust-docs-mcp-server) | 🟠 D | 4.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/Govcraft/rust-docs-mcp-server) |
| [ros-mcp-server](https://github.com/lpigeon/ros-mcp-server) | 🟠 D | 4.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/lpigeon/ros-mcp-server) |
| [simulator-mcp-server](https://github.com/JoshuaRileyDev/simulator-mcp-server) | 🟠 D | 4.2 | 5 | 0 | [Details →](https://spiderrating.com/servers/JoshuaRileyDev/simulator-mcp-server) |
| [vibealive](https://github.com/skullzarmy/vibealive) | 🔴 F | 4.2 | 1 | 14 (14 crit) | [Details →](https://spiderrating.com/servers/skullzarmy/vibealive) |
| [pmpt-cli](https://github.com/pmptwiki/pmpt-cli) | 🔴 F | 4.1 | 14 | 5 (5 crit) | [Details →](https://spiderrating.com/servers/pmptwiki/pmpt-cli) |
| [mcp-gopls](https://github.com/hloiseaufcms/mcp-gopls) | 🟠 D | 4.1 | 14 | 0 | [Details →](https://spiderrating.com/servers/hloiseaufcms/mcp-gopls) |
| [mcp-openapi](https://github.com/ReAPI-com/mcp-openapi) | 🟠 D | 4.1 | 8 | 0 | [Details →](https://spiderrating.com/servers/ReAPI-com/mcp-openapi) |
| [system-prompts-mcp-server](https://github.com/JamesANZ/system-prompts-mcp-server) | 🟠 D | 4.0 | 2 | 0 | [Details →](https://spiderrating.com/servers/JamesANZ/system-prompts-mcp-server) |
| [mcp-image-compression](https://github.com/InhiblabCore/mcp-image-compression) | 🟠 D | 4.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/InhiblabCore/mcp-image-compression) |

## 📂 Browser Automation (29 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [playwright-mcp](https://github.com/microsoft/playwright-mcp) | 🟠 D | 6.4 | 34 | 0 | [Details →](https://spiderrating.com/servers/microsoft/playwright-mcp) |
| [mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) | 🟡 C | 6.2 | 9 | 0 | [Details →](https://spiderrating.com/servers/browserbase/mcp-server-browserbase) |
| [mcp-server-youtube-transcript](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript) | 🟡 C | 6.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/kimtaeyoon83/mcp-server-youtube-transcript) |
| [firefox-devtools-mcp](https://github.com/freema/firefox-devtools-mcp) | 🟡 C | 6.1 | 25 | 0 | [Details →](https://spiderrating.com/servers/freema/firefox-devtools-mcp) |
| [browser-control-mcp](https://github.com/eyalzh/browser-control-mcp) | 🟡 C | 6.0 | 8 | 0 | [Details →](https://spiderrating.com/servers/eyalzh/browser-control-mcp) |
| [gomcp](https://github.com/lightpanda-io/gomcp) | 🟡 C | 5.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/lightpanda-io/gomcp) |
| [DOMShell](https://github.com/apireno/DOMShell) | 🟡 C | 5.8 | 38 | 2 | [Details →](https://spiderrating.com/servers/apireno/DOMShell) |
| [olostep-mcp-server](https://github.com/olostep/olostep-mcp-server) | 🟡 C | 5.7 | 10 | 0 | [Details →](https://spiderrating.com/servers/olostep/olostep-mcp-server) |
| [servers-archived](https://github.com/modelcontextprotocol/servers-archived) | 🟡 C | 5.7 | 78 | 1 | [Details →](https://spiderrating.com/servers/modelcontextprotocol/servers-archived) |
| [agent-scraper-mcp](https://github.com/aparajithn/agent-scraper-mcp) | 🟡 C | 5.6 | 6 | 5 | [Details →](https://spiderrating.com/servers/aparajithn/agent-scraper-mcp) |
| [selenium-mcp-server](https://github.com/PhungXuanAnh/selenium-mcp-server) | 🟡 C | 5.5 | 19 | 8 | [Details →](https://spiderrating.com/servers/PhungXuanAnh/selenium-mcp-server) |
| [playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp) | 🟡 C | 5.5 | 8 | 0 | [Details →](https://spiderrating.com/servers/blackwhite084/playwright-plus-python-mcp) |
| [ashra-mcp](https://github.com/getrupt/ashra-mcp) | 🟡 C | 5.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/getrupt/ashra-mcp) |
| [chrome-mcp-secure](https://github.com/Pantheon-Security/chrome-mcp-secure) | 🟠 D | 5.4 | 22 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/Pantheon-Security/chrome-mcp-secure) |
| [UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop) | 🔴 F | 5.3 | 74 | 11 (11 crit) | [Details →](https://spiderrating.com/servers/bytedance/UI-TARS-desktop) |
| [web-search](https://github.com/pskill9/web-search) | 🟡 C | 5.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/pskill9/web-search) |
| [mcp-server-apple-shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) | 🟠 D | 5.2 | 2 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/recursechat/mcp-server-apple-shortcuts) |
| [mcp-browser-agent](https://github.com/imprvhub/mcp-browser-agent) | 🟠 D | 5.2 | 13 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/imprvhub/mcp-browser-agent) |
| [comet-mcp](https://github.com/hanzili/comet-mcp) | 🟠 D | 5.0 | 6 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/hanzili/comet-mcp) |
| [snaprender-integrations](https://github.com/User0856/snaprender-integrations) | 🟠 D | 5.0 | 7 | 2 | [Details →](https://spiderrating.com/servers/User0856/snaprender-integrations) |
| [Retio-pagemap](https://github.com/Retio-ai/Retio-pagemap) | 🟠 D | 4.8 | 13 | 0 | [Details →](https://spiderrating.com/servers/Retio-ai/Retio-pagemap) |
| [real-browser-mcp](https://github.com/ofershap/real-browser-mcp) | 🟠 D | 4.8 | 18 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/ofershap/real-browser-mcp) |
| [iwdp-mcp](https://github.com/nnemirovsky/iwdp-mcp) | 🟠 D | 4.8 | 116 | 0 | [Details →](https://spiderrating.com/servers/nnemirovsky/iwdp-mcp) |
| [freshcontext-mcp](https://github.com/PrinceGabriel-lgtm/freshcontext-mcp) | 🟠 D | 4.6 | 11 | 0 | [Details →](https://spiderrating.com/servers/PrinceGabriel-lgtm/freshcontext-mcp) |
| [mcp-immostage](https://github.com/LarryWalkerDEV/mcp-immostage) | 🟠 D | 4.5 | 5 | 0 | [Details →](https://spiderrating.com/servers/LarryWalkerDEV/mcp-immostage) |
| [mcp-server-apple-reminders](https://github.com/FradSer/mcp-server-apple-reminders) | 🟠 D | 4.4 | 9 | 0 | [Details →](https://spiderrating.com/servers/FradSer/mcp-server-apple-reminders) |
| [bilibili-mcp-js](https://github.com/34892002/bilibili-mcp-js) | 🟠 D | 4.1 | 8 | 0 | [Details →](https://spiderrating.com/servers/34892002/bilibili-mcp-js) |
| [browser-use-mcp-server](https://github.com/co-browser/browser-use-mcp-server) | 🟠 D | 4.1 | 2 | 0 | [Details →](https://spiderrating.com/servers/co-browser/browser-use-mcp-server) |
| [simple-mcp-selenium](https://github.com/brutalzinn/simple-mcp-selenium) | 🔴 F | 3.9 | 17 | 8 (8 crit) | [Details →](https://spiderrating.com/servers/brutalzinn/simple-mcp-selenium) |

## 📂 File Systems (14 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [filestash](https://github.com/mickael-kerjean/filestash) | 🟢 B | 7.5 | 9 | 0 | [Details →](https://spiderrating.com/servers/mickael-kerjean/filestash) |
| [markitdown](https://github.com/microsoft/markitdown) | 🟡 C | 6.9 | 1 | 1 | [Details →](https://spiderrating.com/servers/microsoft/markitdown) |
| [mcp-server-opendal](https://github.com/Xuanwo/mcp-server-opendal) | 🟡 C | 6.8 | 3 | 3 | [Details →](https://spiderrating.com/servers/Xuanwo/mcp-server-opendal) |
| [smart-tree](https://github.com/8b-is/smart-tree) | 🟠 D | 5.9 | 1 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/8b-is/smart-tree) |
| [mcp-gdrive](https://github.com/isaacphi/mcp-gdrive) | 🟡 C | 5.8 | 4 | 0 | [Details →](https://spiderrating.com/servers/isaacphi/mcp-gdrive) |
| [fast-filesystem-mcp](https://github.com/efforthye/fast-filesystem-mcp) | 🟠 D | 5.8 | 25 | 0 | [Details →](https://spiderrating.com/servers/efforthye/fast-filesystem-mcp) |
| [plsreadme](https://github.com/FacundoLucci/plsreadme) | 🟡 C | 5.6 | 5 | 0 | [Details →](https://spiderrating.com/servers/FacundoLucci/plsreadme) |
| [Chisel](https://github.com/ckanthony/Chisel) | 🟡 C | 5.6 | 9 | 0 | [Details →](https://spiderrating.com/servers/ckanthony/Chisel) |
| [box-mcp-server](https://github.com/hmk/box-mcp-server) | 🟡 C | 5.5 | 2 | 0 | [Details →](https://spiderrating.com/servers/hmk/box-mcp-server) |
| [mcp-file-merger](https://github.com/exoticknight/mcp-file-merger) | 🟡 C | 5.5 | 2 | 0 | [Details →](https://spiderrating.com/servers/exoticknight/mcp-file-merger) |
| [large-file-mcp](https://github.com/willianpinho/large-file-mcp) | 🟡 C | 5.4 | 6 | 0 | [Details →](https://spiderrating.com/servers/willianpinho/large-file-mcp) |
| [llm-context.py](https://github.com/cyberchitta/llm-context.py) | 🔴 F | 5.2 | 5 | 10 (5 crit) | [Details →](https://spiderrating.com/servers/cyberchitta/llm-context.py) |
| [filesystem-context-mcp-server](https://github.com/j0hanz/filesystem-context-mcp-server) | 🟠 D | 4.5 | 18 | 0 | [Details →](https://spiderrating.com/servers/j0hanz/filesystem-context-mcp-server) |
| [md-to-pdf-mcp](https://github.com/MarceauSolutions/md-to-pdf-mcp) | 🟠 D | 4.4 | 3 | 0 | [Details →](https://spiderrating.com/servers/MarceauSolutions/md-to-pdf-mcp) |

## 📊 Data Platforms (11 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [dbt-mcp](https://github.com/dbt-labs/dbt-mcp) | 🟡 C | 6.3 | 3 | 3 | [Details →](https://spiderrating.com/servers/dbt-labs/dbt-mcp) |
| [agrobr-mcp](https://github.com/bruno-portfolio/agrobr-mcp) | 🟡 C | 5.9 | 10 | 7 | [Details →](https://spiderrating.com/servers/bruno-portfolio/agrobr-mcp) |
| [mercadolibre-mcp](https://github.com/dan1d/mercadolibre-mcp) | 🟡 C | 5.7 | 8 | 0 | [Details →](https://spiderrating.com/servers/dan1d/mercadolibre-mcp) |
| [qlik-mcp](https://github.com/jwaxman19/qlik-mcp) | 🟡 C | 5.6 | 4 | 0 | [Details →](https://spiderrating.com/servers/jwaxman19/qlik-mcp) |
| [kafka-schema-reg-mcp](https://github.com/aywengo/kafka-schema-reg-mcp) | 🟠 D | 5.5 | 1 | 1 | [Details →](https://spiderrating.com/servers/aywengo/kafka-schema-reg-mcp) |
| [mcp-flowcore-platform](https://github.com/flowcore-io/mcp-flowcore-platform) | 🟠 D | 5.2 | 22 | 0 | [Details →](https://spiderrating.com/servers/flowcore-io/mcp-flowcore-platform) |
| [oyemi-mcp](https://github.com/Osseni94/oyemi-mcp) | 🟡 C | 5.1 | 7 | 5 | [Details →](https://spiderrating.com/servers/Osseni94/oyemi-mcp) |
| [registep-mcp](https://github.com/saikiyusuke/registep-mcp) | 🟡 C | 5.0 | 67 | 0 | [Details →](https://spiderrating.com/servers/saikiyusuke/registep-mcp) |
| [keyneg-mcp](https://github.com/Osseni94/keyneg-mcp) | 🟠 D | 4.9 | 7 | 0 | [Details →](https://spiderrating.com/servers/Osseni94/keyneg-mcp) |
| [mcp-databricks-server](https://github.com/JordiNeil/mcp-databricks-server) | 🟠 D | 4.8 | 4 | 3 | [Details →](https://spiderrating.com/servers/JordiNeil/mcp-databricks-server) |
| [databricks-genie-MCP](https://github.com/yashshingvi/databricks-genie-MCP) | 🟠 D | 4.3 | 3 | 10 | [Details →](https://spiderrating.com/servers/yashshingvi/databricks-genie-MCP) |

## 📊 Monitoring (16 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [sentry-mcp](https://github.com/getsentry/sentry-mcp) | 🟡 C | 7.1 | 3 | 0 | [Details →](https://spiderrating.com/servers/getsentry/sentry-mcp) |
| [langfuse-mcp](https://github.com/avivsinai/langfuse-mcp) | 🟡 C | 7.0 | 8 | 0 | [Details →](https://spiderrating.com/servers/avivsinai/langfuse-mcp) |
| [mcp-server](https://github.com/metrxbots/mcp-server) | 🟡 C | 6.6 | 23 | 0 | [Details →](https://spiderrating.com/servers/metrxbots/mcp-server) |
| [datadog-mcp-server](https://github.com/TANTIOPE/datadog-mcp-server) | 🟡 C | 6.5 | 20 | 0 | [Details →](https://spiderrating.com/servers/TANTIOPE/datadog-mcp-server) |
| [zabbix-mcp-server](https://github.com/mpeirone/zabbix-mcp-server) | 🟠 D | 6.3 | 44 | 17 | [Details →](https://spiderrating.com/servers/mpeirone/zabbix-mcp-server) |
| [llmkit](https://github.com/smigolsmigol/llmkit) | 🟡 C | 5.9 | 7 | 0 | [Details →](https://spiderrating.com/servers/smigolsmigol/llmkit) |
| [webmin-mcp-server](https://github.com/gjenkins20/webmin-mcp-server) | 🟡 C | 5.8 | 1 | 0 | [Details →](https://spiderrating.com/servers/gjenkins20/webmin-mcp-server) |
| [mcp-status-observer](https://github.com/imprvhub/mcp-status-observer) | 🟠 D | 5.8 | 8 | 0 | [Details →](https://spiderrating.com/servers/imprvhub/mcp-status-observer) |
| [measure-mcp-server](https://github.com/Turbo-Puffin/measure-mcp-server) | 🟡 C | 5.7 | 6 | 0 | [Details →](https://spiderrating.com/servers/Turbo-Puffin/measure-mcp-server) |
| [mcp-monitor](https://github.com/seekrays/mcp-monitor) | 🟡 C | 5.5 | 6 | 0 | [Details →](https://spiderrating.com/servers/seekrays/mcp-monitor) |
| [unofficial-fortimonitor-mcp-server](https://github.com/gjenkins20/unofficial-fortimonitor-mcp-server) | 🟠 D | 5.4 | 6 | 0 | [Details →](https://spiderrating.com/servers/gjenkins20/unofficial-fortimonitor-mcp-server) |
| [lucidity-mcp](https://github.com/hyperb1iss/lucidity-mcp) | 🟠 D | 5.3 | 3 | 0 | [Details →](https://spiderrating.com/servers/hyperb1iss/lucidity-mcp) |
| [grafana-loki-mcp](https://github.com/tumf/grafana-loki-mcp) | 🟡 C | 5.1 | 5 | 8 | [Details →](https://spiderrating.com/servers/tumf/grafana-loki-mcp) |
| [alog-mcp](https://github.com/saikiyusuke/alog-mcp) | 🟠 D | 4.9 | 19 | 0 | [Details →](https://spiderrating.com/servers/saikiyusuke/alog-mcp) |
| [pmcp](https://github.com/yshngg/pmcp) | 🟠 D | 4.1 | 4 | 0 | [Details →](https://spiderrating.com/servers/yshngg/pmcp) |
| [mcp-victoriametrics](https://github.com/VictoriaMetrics-Community/mcp-victoriametrics) | 🟠 D | 4.0 | 30 | 0 | [Details →](https://spiderrating.com/servers/VictoriaMetrics-Community/mcp-victoriametrics) |

## 📋 Product Management (2 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [saga-mcp](https://github.com/spranab/saga-mcp) | 🟡 C | 5.7 | 31 | 0 | [Details →](https://spiderrating.com/servers/spranab/saga-mcp) |
| [pm-copilot](https://github.com/dkships/pm-copilot) | 🟠 D | 5.5 | 3 | 0 | [Details →](https://spiderrating.com/servers/dkships/pm-copilot) |

## 📐 Architecture & Design (3 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [excalidraw-architect-mcp](https://github.com/BV-Venky/excalidraw-architect-mcp) | 🟡 C | 6.4 | 4 | 1 | [Details →](https://spiderrating.com/servers/BV-Venky/excalidraw-architect-mcp) |
| [mermaid-mcp](https://github.com/Narasimhaponnada/mermaid-mcp) | 🟠 D | 5.3 | 10 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/Narasimhaponnada/mermaid-mcp) |
| [mermaid_grammer_inspector_mcp](https://github.com/betterhyq/mermaid_grammer_inspector_mcp) | 🟠 D | 4.9 | 1 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/betterhyq/mermaid_grammer_inspector_mcp) |

## 📟 Embedded System (7 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [opcua-mcp](https://github.com/kukapay/opcua-mcp) | 🟢 B | 7.9 | 5 | 3 | [Details →](https://spiderrating.com/servers/kukapay/opcua-mcp) |
| [modbus-mcp](https://github.com/kukapay/modbus-mcp) | 🟡 C | 7.0 | 6 | 0 | [Details →](https://spiderrating.com/servers/kukapay/modbus-mcp) |
| [stack-chan](https://github.com/stack-chan/stack-chan) | 🟠 D | 6.5 | 4 | 0 | [Details →](https://spiderrating.com/servers/stack-chan/stack-chan) |
| [esp-mcp](https://github.com/horw/esp-mcp) | 🟡 C | 5.5 | 7 | 12 | [Details →](https://spiderrating.com/servers/horw/esp-mcp) |
| [serial-mcp-server](https://github.com/adancurusul/serial-mcp-server) | 🟠 D | 4.8 | 5 | 0 | [Details →](https://spiderrating.com/servers/adancurusul/serial-mcp-server) |
| [embedded-debugger-mcp](https://github.com/adancurusul/embedded-debugger-mcp) | 🟠 D | 4.7 | 22 | 0 | [Details →](https://spiderrating.com/servers/adancurusul/embedded-debugger-mcp) |
| [matter-controller-mcp](https://github.com/0x1abin/matter-controller-mcp) | 🟠 D | 4.1 | 1 | 0 | [Details →](https://spiderrating.com/servers/0x1abin/matter-controller-mcp) |

## 🔄 Version Control (10 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [github-graphql-mcp-server](https://github.com/QuentinCody/github-graphql-mcp-server) | 🟢 B | 7.5 | 1 | 1 | [Details →](https://spiderrating.com/servers/QuentinCody/github-graphql-mcp-server) |
| [mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops) | 🟡 C | 6.3 | 44 | 0 | [Details →](https://spiderrating.com/servers/Tiberriver256/mcp-server-azure-devops) |
| [gitlab-mr-mcp](https://github.com/kopfrechner/gitlab-mr-mcp) | 🟡 C | 6.1 | 10 | 0 | [Details →](https://spiderrating.com/servers/kopfrechner/gitlab-mr-mcp) |
| [mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest) | 🟡 C | 5.8 | 2 | 2 | [Details →](https://spiderrating.com/servers/adhikasp/mcp-git-ingest) |
| [tod](https://github.com/theonedev/tod) | 🟠 D | 5.5 | 36 | 0 | [Details →](https://spiderrating.com/servers/theonedev/tod) |
| [forgejo-mcp](https://github.com/raohwork/forgejo-mcp) | 🟡 C | 5.4 | 48 | 0 | [Details →](https://spiderrating.com/servers/raohwork/forgejo-mcp) |
| [atomgit-mcp-server](https://github.com/kaiyuanxiaobing/atomgit-mcp-server) | 🟠 D | 5.3 | 25 | 0 | [Details →](https://spiderrating.com/servers/kaiyuanxiaobing/atomgit-mcp-server) |
| [git-context-mcp](https://github.com/TamiShaks-2/git-context-mcp) | 🟠 D | 4.8 | 5 | 5 | [Details →](https://spiderrating.com/servers/TamiShaks-2/git-context-mcp) |
| [bbkt](https://github.com/zach-snell/bbkt) | 🟠 D | 4.7 | 9 | 0 | [Details →](https://spiderrating.com/servers/zach-snell/bbkt) |
| [mcp-server-bitbucket](https://github.com/JaviMaligno/mcp-server-bitbucket) | 🟠 D | 4.4 | 70 | 0 | [Details →](https://spiderrating.com/servers/JaviMaligno/mcp-server-bitbucket) |

## 🔎 End To End Rag Platforms (3 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [vectara-mcp](https://github.com/vectara/vectara-mcp) | 🟡 C | 6.3 | 6 | 0 | [Details →](https://spiderrating.com/servers/vectara/vectara-mcp) |
| [mcp-ragchat](https://github.com/gogabrielordonez/mcp-ragchat) | 🟡 C | 5.2 | 5 | 0 | [Details →](https://spiderrating.com/servers/gogabrielordonez/mcp-ragchat) |
| [customgpt-mcp](https://github.com/Poll-The-People/customgpt-mcp) | 🟠 D | 5.2 | 50 | 14 | [Details →](https://spiderrating.com/servers/Poll-The-People/customgpt-mcp) |

## 🔎 Search & Data Extraction (83 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [serpapi-mcp](https://github.com/serpapi/serpapi-mcp) | 🟢 B | 7.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/serpapi/serpapi-mcp) |
| [mcp-opennutrition](https://github.com/deadletterq/mcp-opennutrition) | 🟢 B | 7.5 | 5 | 0 | [Details →](https://spiderrating.com/servers/deadletterq/mcp-opennutrition) |
| [duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server) | 🟡 C | 6.7 | 2 | 2 | [Details →](https://spiderrating.com/servers/nickclyde/duckduckgo-mcp-server) |
| [agentql-mcp](https://github.com/tinyfish-io/agentql-mcp) | 🟡 C | 6.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/tinyfish-io/agentql-mcp) |
| [fetcher-mcp](https://github.com/jae-jae/fetcher-mcp) | 🟡 C | 6.5 | 3 | 0 | [Details →](https://spiderrating.com/servers/jae-jae/fetcher-mcp) |
| [kagimcp](https://github.com/kagisearch/kagimcp) | 🟡 C | 6.4 | 2 | 0 | [Details →](https://spiderrating.com/servers/kagisearch/kagimcp) |
| [scrapeless-mcp-server](https://github.com/scrapeless-ai/scrapeless-mcp-server) | 🟡 C | 6.3 | 21 | 0 | [Details →](https://spiderrating.com/servers/scrapeless-ai/scrapeless-mcp-server) |
| [mcp-searxng](https://github.com/ihor-sokoliuk/mcp-searxng) | 🟠 D | 6.3 | 2 | 0 | [Details →](https://spiderrating.com/servers/ihor-sokoliuk/mcp-searxng) |
| [trieve](https://github.com/devflowinc/trieve) | 🟡 C | 6.3 | 7 | 0 | [Details →](https://spiderrating.com/servers/devflowinc/trieve) |
| [mcp-local-rag](https://github.com/nkapila6/mcp-local-rag) | 🟡 C | 6.2 | 5 | 3 | [Details →](https://spiderrating.com/servers/nkapila6/mcp-local-rag) |
| [driflyte-mcp-server](https://github.com/serkan-ozal/driflyte-mcp-server) | 🟡 C | 6.2 | 11 | 0 | [Details →](https://spiderrating.com/servers/serkan-ozal/driflyte-mcp-server) |
| [arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) | 🟡 C | 6.2 | 4 | 1 | [Details →](https://spiderrating.com/servers/blazickjp/arxiv-mcp-server) |
| [brave-search-mcp-server](https://github.com/brave/brave-search-mcp-server) | 🟠 D | 6.2 | 6 | 0 | [Details →](https://spiderrating.com/servers/brave/brave-search-mcp-server) |
| [mcp-claude-hackernews](https://github.com/imprvhub/mcp-claude-hackernews) | 🟡 C | 6.1 | 5 | 0 | [Details →](https://spiderrating.com/servers/imprvhub/mcp-claude-hackernews) |
| [arxiv-latex-mcp](https://github.com/takashiishida/arxiv-latex-mcp) | 🟡 C | 6.1 | 4 | 0 | [Details →](https://spiderrating.com/servers/takashiishida/arxiv-latex-mcp) |
| [kagi-ken-mcp](https://github.com/czottmann/kagi-ken-mcp) | 🟡 C | 6.1 | 2 | 0 | [Details →](https://spiderrating.com/servers/czottmann/kagi-ken-mcp) |
| [json-mcp-filter](https://github.com/kehvinbehvin/json-mcp-filter) | 🟡 C | 6.1 | 5 | 0 | [Details →](https://spiderrating.com/servers/kehvinbehvin/json-mcp-filter) |
| [bing-search-mcp](https://github.com/leehanchung/bing-search-mcp) | 🟡 C | 6.1 | 3 | 0 | [Details →](https://spiderrating.com/servers/leehanchung/bing-search-mcp) |
| [mcp_zoomeye](https://github.com/zoomeye-ai/mcp_zoomeye) | 🟡 C | 6.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/zoomeye-ai/mcp_zoomeye) |
| [mcp-domain-availability](https://github.com/imprvhub/mcp-domain-availability) | 🟡 C | 6.0 | 2 | 1 | [Details →](https://spiderrating.com/servers/imprvhub/mcp-domain-availability) |
| [youtube-summarize](https://github.com/zlatkoc/youtube-summarize) | 🟡 C | 6.0 | 3 | 1 | [Details →](https://spiderrating.com/servers/zlatkoc/youtube-summarize) |
| [decompose](https://github.com/echology-io/decompose) | 🟡 C | 5.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/echology-io/decompose) |
| [overseerr-mcp](https://github.com/jhomen368/overseerr-mcp) | 🟡 C | 5.9 | 4 | 0 | [Details →](https://spiderrating.com/servers/jhomen368/overseerr-mcp) |
| [google-researcher-mcp](https://github.com/zoharbabin/google-researcher-mcp) | 🟡 C | 5.9 | 23 | 0 | [Details →](https://spiderrating.com/servers/zoharbabin/google-researcher-mcp) |
| [unsplash-mcp-server](https://github.com/hellokaton/unsplash-mcp-server) | 🟡 C | 5.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/hellokaton/unsplash-mcp-server) |
| [brave-search-mcp](https://github.com/mikechao/brave-search-mcp) | 🟠 D | 5.8 | 1 | 0 | [Details →](https://spiderrating.com/servers/mikechao/brave-search-mcp) |
| [vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server) | 🟡 C | 5.8 | 3 | 0 | [Details →](https://spiderrating.com/servers/vectorize-io/vectorize-mcp-server) |
| [dappier-mcp](https://github.com/DappierAI/dappier-mcp) | 🟡 C | 5.8 | 2 | 0 | [Details →](https://spiderrating.com/servers/DappierAI/dappier-mcp) |
| [g-search-mcp](https://github.com/jae-jae/g-search-mcp) | 🟡 C | 5.8 | 1 | 0 | [Details →](https://spiderrating.com/servers/jae-jae/g-search-mcp) |
| [mcp-rss-aggregator](https://github.com/imprvhub/mcp-rss-aggregator) | 🟠 D | 5.7 | 1 | 0 | [Details →](https://spiderrating.com/servers/imprvhub/mcp-rss-aggregator) |
| [unsplash-mcp](https://github.com/cevatkerim/unsplash-mcp) | 🟡 C | 5.7 | 3 | 1 | [Details →](https://spiderrating.com/servers/cevatkerim/unsplash-mcp) |
| [search1api-mcp](https://github.com/fatwang2/search1api-mcp) | 🟠 D | 5.7 | 6 | 0 | [Details →](https://spiderrating.com/servers/fatwang2/search1api-mcp) |
| [naver-search-mcp](https://github.com/isnow890/naver-search-mcp) | 🟠 D | 5.7 | 21 | 0 | [Details →](https://spiderrating.com/servers/isnow890/naver-search-mcp) |
| [mcp-screenshot-website-fast](https://github.com/just-every/mcp-screenshot-website-fast) | 🟡 C | 5.7 | 3 | 0 | [Details →](https://spiderrating.com/servers/just-every/mcp-screenshot-website-fast) |
| [nexus](https://github.com/adawalli/nexus) | 🟠 D | 5.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/adawalli/nexus) |
| [mcp-server-tavily](https://github.com/Tomatio13/mcp-server-tavily) | 🟡 C | 5.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/Tomatio13/mcp-server-tavily) |
| [opentk-mcp](https://github.com/r-huijts/opentk-mcp) | 🟡 C | 5.6 | 18 | 0 | [Details →](https://spiderrating.com/servers/r-huijts/opentk-mcp) |
| [nyt](https://github.com/angheljf/nyt) | 🟡 C | 5.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/angheljf/nyt) |
| [webpage-screenshot-mcp](https://github.com/ananddtyagi/webpage-screenshot-mcp) | 🟡 C | 5.6 | 5 | 0 | [Details →](https://spiderrating.com/servers/ananddtyagi/webpage-screenshot-mcp) |
| [newsmcp](https://github.com/pranciskus/newsmcp) | 🟠 D | 5.5 | 8 | 0 | [Details →](https://spiderrating.com/servers/pranciskus/newsmcp) |
| [baseline-mcp-server](https://github.com/yamanoku/baseline-mcp-server) | 🟠 D | 5.5 | 2 | 0 | [Details →](https://spiderrating.com/servers/yamanoku/baseline-mcp-server) |
| [searchcraft-mcp-server](https://github.com/searchcraft-inc/searchcraft-mcp-server) | 🟡 C | 5.5 | 48 | 2 | [Details →](https://spiderrating.com/servers/searchcraft-inc/searchcraft-mcp-server) |
| [mcp-read-website-fast](https://github.com/just-every/mcp-read-website-fast) | 🟠 D | 5.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/just-every/mcp-read-website-fast) |
| [mcp-webresearch](https://github.com/mzxrai/mcp-webresearch) | 🟠 D | 5.5 | 5 | 0 | [Details →](https://spiderrating.com/servers/mzxrai/mcp-webresearch) |
| [catalysishub-mcp-server](https://github.com/QuentinCody/catalysishub-mcp-server) | 🟡 C | 5.4 | 1 | 1 | [Details →](https://spiderrating.com/servers/QuentinCody/catalysishub-mcp-server) |
| [mcp_pearch](https://github.com/Pearch-ai/mcp_pearch) | 🟡 C | 5.4 | 2 | 0 | [Details →](https://spiderrating.com/servers/Pearch-ai/mcp_pearch) |
| [mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi) | 🟠 D | 5.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/ac3xx/mcp-servers-kagi) |
| [semanticapi-mcp](https://github.com/peter-j-thompson/semanticapi-mcp) | 🟡 C | 5.3 | 3 | 3 | [Details →](https://spiderrating.com/servers/peter-j-thompson/semanticapi-mcp) |
| [NyxDocs](https://github.com/nyxn-ai/NyxDocs) | 🟡 C | 5.3 | 8 | 0 | [Details →](https://spiderrating.com/servers/nyxn-ai/NyxDocs) |
| [mcp-hn](https://github.com/erithwik/mcp-hn) | 🟡 C | 5.3 | 4 | 5 | [Details →](https://spiderrating.com/servers/erithwik/mcp-hn) |
| [mcp-paperswithcode](https://github.com/hbg/mcp-paperswithcode) | 🟠 D | 5.3 | 20 | 19 | [Details →](https://spiderrating.com/servers/hbg/mcp-paperswithcode) |
| [rescuedogs-mcp-server](https://github.com/ssatama/rescuedogs-mcp-server) | 🟡 C | 5.2 | 8 | 0 | [Details →](https://spiderrating.com/servers/ssatama/rescuedogs-mcp-server) |
| [web-analyzer-mcp](https://github.com/kimdonghwi94/web-analyzer-mcp) | 🟠 D | 5.2 | 2 | 2 | [Details →](https://spiderrating.com/servers/kimdonghwi94/web-analyzer-mcp) |
| [opengraph-io-mcp](https://github.com/securecoders/opengraph-io-mcp) | 🟠 D | 5.2 | 9 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/securecoders/opengraph-io-mcp) |
| [mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser) | 🟠 D | 5.2 | 2 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/apify/mcp-server-rag-web-browser) |
| [mineru-mcp](https://github.com/linxule/mineru-mcp) | 🟡 C | 5.2 | 6 | 0 | [Details →](https://spiderrating.com/servers/linxule/mineru-mcp) |
| [shopsavvy-mcp-server](https://github.com/shopsavvy/shopsavvy-mcp-server) | 🟠 D | 5.2 | 9 | 0 | [Details →](https://spiderrating.com/servers/shopsavvy/shopsavvy-mcp-server) |
| [agent-toolbox](https://github.com/Vincentwei1021/agent-toolbox) | 🟠 D | 5.1 | 29 | 0 | [Details →](https://spiderrating.com/servers/Vincentwei1021/agent-toolbox) |
| [content-core](https://github.com/lfnovo/content-core) | 🔴 F | 5.1 | 4 | 6 (3 crit) | [Details →](https://spiderrating.com/servers/lfnovo/content-core) |
| [agent-domain-service-mcp](https://github.com/gregm711/agent-domain-service-mcp) | 🟡 C | 5.1 | 6 | 0 | [Details →](https://spiderrating.com/servers/gregm711/agent-domain-service-mcp) |
| [enrichr-mcp-server](https://github.com/tianqitang1/enrichr-mcp-server) | 🟡 C | 5.0 | 2 | 0 | [Details →](https://spiderrating.com/servers/tianqitang1/enrichr-mcp-server) |
| [octagon-deep-research-mcp](https://github.com/OctagonAI/octagon-deep-research-mcp) | 🟠 D | 4.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/OctagonAI/octagon-deep-research-mcp) |
| [urlbox-mcp-server](https://github.com/urlbox/urlbox-mcp-server) | 🟠 D | 4.9 | 3 | 0 | [Details →](https://spiderrating.com/servers/urlbox/urlbox-mcp-server) |
| [gopher-mcp](https://github.com/cameronrye/gopher-mcp) | 🟠 D | 4.8 | 4 | 4 (2 crit) | [Details →](https://spiderrating.com/servers/cameronrye/gopher-mcp) |
| [mcp-server](https://github.com/StripFeed/mcp-server) | 🟠 D | 4.7 | 3 | 0 | [Details →](https://spiderrating.com/servers/StripFeed/mcp-server) |
| [domain-search-mcp](https://github.com/dorukardahan/domain-search-mcp) | 🟠 D | 4.7 | 28 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/dorukardahan/domain-search-mcp) |
| [activitypub-mcp](https://github.com/cameronrye/activitypub-mcp) | 🔴 F | 4.7 | 18 | 3 (3 crit) | [Details →](https://spiderrating.com/servers/cameronrye/activitypub-mcp) |
| [MCP-searxng](https://github.com/SecretiveShell/MCP-searxng) | 🟠 D | 4.7 | 1 | 0 | [Details →](https://spiderrating.com/servers/SecretiveShell/MCP-searxng) |
| [melrose-mcp](https://github.com/emicklei/melrose-mcp) | 🟠 D | 4.7 | 4 | 0 | [Details →](https://spiderrating.com/servers/emicklei/melrose-mcp) |
| [webpeel](https://github.com/webpeel/webpeel) | 🟠 D | 4.7 | 17 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/webpeel/webpeel) |
| [Clojars-MCP-Server](https://github.com/Bigsy/Clojars-MCP-Server) | 🟠 D | 4.6 | 3 | 0 | [Details →](https://spiderrating.com/servers/Bigsy/Clojars-MCP-Server) |
| [mcp-server-dumplingai](https://github.com/Dumpling-AI/mcp-server-dumplingai) | 🟠 D | 4.6 | 27 | 0 | [Details →](https://spiderrating.com/servers/Dumpling-AI/mcp-server-dumplingai) |
| [server-google-news](https://github.com/ChanMeng666/server-google-news) | 🟠 D | 4.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/ChanMeng666/server-google-news) |
| [Crawleo-MCP](https://github.com/Crawleo/Crawleo-MCP) | 🟠 D | 4.5 | 2 | 0 | [Details →](https://spiderrating.com/servers/Crawleo/Crawleo-MCP) |
| [youtube_mcp](https://github.com/format37/youtube_mcp) | 🟠 D | 4.5 | 2 | 4 (2 crit) | [Details →](https://spiderrating.com/servers/format37/youtube_mcp) |
| [aeo-cli](https://github.com/hanselhansel/aeo-cli) | 🟠 D | 4.4 | 12 | 8 | [Details →](https://spiderrating.com/servers/hanselhansel/aeo-cli) |
| [wet-mcp](https://github.com/n24q02m/wet-mcp) | 🔴 F | 4.4 | 5 | 5 (5 crit) | [Details →](https://spiderrating.com/servers/n24q02m/wet-mcp) |
| [brightdata-mcp](https://github.com/luminati-io/brightdata-mcp) | 🟠 D | 4.4 | 20 | 0 | [Details →](https://spiderrating.com/servers/luminati-io/brightdata-mcp) |
| [tat-mcp-server](https://github.com/theagenttimes/tat-mcp-server) | 🟠 D | 4.3 | 14 | 3 (1 crit) | [Details →](https://spiderrating.com/servers/theagenttimes/tat-mcp-server) |
| [job-searchoor](https://github.com/0xDAEF0F/job-searchoor) | 🟠 D | 4.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/0xDAEF0F/job-searchoor) |
| [openai-websearch-mcp](https://github.com/ConechoAI/openai-websearch-mcp) | 🟠 D | 4.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/ConechoAI/openai-websearch-mcp) |
| [linkedapi-mcp](https://github.com/Linked-API/linkedapi-mcp) | 🟠 D | 4.1 | 5 | 0 | [Details →](https://spiderrating.com/servers/Linked-API/linkedapi-mcp) |
| [duckduckgo-mpc-server](https://github.com/zhsama/duckduckgo-mpc-server) | 🟠 D | 4.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/zhsama/duckduckgo-mpc-server) |

## 🔒 Delivery (2 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [DragonMCP](https://github.com/arthurpanhku/DragonMCP) | 🟠 D | 5.7 | 17 | 0 | [Details →](https://spiderrating.com/servers/arthurpanhku/DragonMCP) |
| [shipi-mcp-server](https://github.com/aarsiv-groups/shipi-mcp-server) | 🟡 C | 5.2 | 18 | 0 | [Details →](https://spiderrating.com/servers/aarsiv-groups/shipi-mcp-server) |

## 🔒 Security (50 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-panther](https://github.com/panther-labs/mcp-panther) | 🟡 C | 6.6 | 37 | 0 | [Details →](https://spiderrating.com/servers/panther-labs/mcp-panther) |
| [Wireshark-MCP](https://github.com/bx33661/Wireshark-MCP) | 🟡 C | 6.6 | 26 | 20 | [Details →](https://spiderrating.com/servers/bx33661/Wireshark-MCP) |
| [binary_ninja_mcp](https://github.com/fosdickio/binary_ninja_mcp) | 🟡 C | 6.3 | 54 | 45 | [Details →](https://spiderrating.com/servers/fosdickio/binary_ninja_mcp) |
| [mcp](https://github.com/semgrep/mcp) | 🟠 D | 6.3 | 1 | 3 (2 crit) | [Details →](https://spiderrating.com/servers/semgrep/mcp) |
| [mcp-server](https://github.com/rad-security/mcp-server) | 🟡 C | 6.2 | 69 | 0 | [Details →](https://spiderrating.com/servers/rad-security/mcp-server) |
| [ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) | 🟡 C | 6.2 | 7 | 1 | [Details →](https://spiderrating.com/servers/mrexodia/ida-pro-mcp) |
| [authenticator_mcp](https://github.com/firstorderai/authenticator_mcp) | 🟡 C | 6.1 | 3 | 0 | [Details →](https://spiderrating.com/servers/firstorderai/authenticator_mcp) |
| [cyntrisec-cli](https://github.com/cyntrisec/cyntrisec-cli) | 🟡 C | 6.1 | 15 | 2 | [Details →](https://spiderrating.com/servers/cyntrisec/cyntrisec-cli) |
| [dawshund_mcp](https://github.com/samvas-codes/dawshund_mcp) | 🟡 C | 6.0 | 3 | 2 | [Details →](https://spiderrating.com/servers/samvas-codes/dawshund_mcp) |
| [csl-core](https://github.com/Chimera-Protocol/csl-core) | 🟠 D | 6.0 | 4 | 3 (1 crit) | [Details →](https://spiderrating.com/servers/Chimera-Protocol/csl-core) |
| [intruder-mcp](https://github.com/intruder-io/intruder-mcp) | 🟡 C | 6.0 | 18 | 5 | [Details →](https://spiderrating.com/servers/intruder-io/intruder-mcp) |
| [thales-cdsp-cakm-mcp-server](https://github.com/sanyambassi/thales-cdsp-cakm-mcp-server) | 🟠 D | 6.0 | 10 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/sanyambassi/thales-cdsp-cakm-mcp-server) |
| [secretctl](https://github.com/forest6511/secretctl) | 🟡 C | 5.9 | 11 | 0 | [Details →](https://spiderrating.com/servers/forest6511/secretctl) |
| [air-blackbox-mcp](https://github.com/airblackbox/air-blackbox-mcp) | 🟡 C | 5.9 | 10 | 8 | [Details →](https://spiderrating.com/servers/airblackbox/air-blackbox-mcp) |
| [mcp_vms](https://github.com/jyjune/mcp_vms) | 🟡 C | 5.9 | 13 | 0 | [Details →](https://spiderrating.com/servers/jyjune/mcp_vms) |
| [apktool-mcp-server](https://github.com/zinja-coder/apktool-mcp-server) | 🟡 C | 5.8 | 16 | 7 | [Details →](https://spiderrating.com/servers/zinja-coder/apktool-mcp-server) |
| [GhidraMCP](https://github.com/LaurieWired/GhidraMCP) | 🟡 C | 5.7 | 27 | 19 | [Details →](https://spiderrating.com/servers/LaurieWired/GhidraMCP) |
| [zitadel-mcp](https://github.com/takleb3rry/zitadel-mcp) | 🟡 C | 5.7 | 27 | 0 | [Details →](https://spiderrating.com/servers/takleb3rry/zitadel-mcp) |
| [mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit) | 🟠 D | 5.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/qianniuspace/mcp-security-audit) |
| [ida-headless-mcp](https://github.com/zboralski/ida-headless-mcp) | 🟠 D | 5.5 | 52 | 0 | [Details →](https://spiderrating.com/servers/zboralski/ida-headless-mcp) |
| [mcp-server-wazuh](https://github.com/gbrigandi/mcp-server-wazuh) | 🟡 C | 5.4 | 14 | 0 | [Details →](https://spiderrating.com/servers/gbrigandi/mcp-server-wazuh) |
| [mobsf-mcp-server](https://github.com/pullkitsan/mobsf-mcp-server) | 🟡 C | 5.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/pullkitsan/mobsf-mcp-server) |
| [secops-mcp](https://github.com/securityfortech/secops-mcp) | 🟠 D | 5.4 | 18 | 1 | [Details →](https://spiderrating.com/servers/securityfortech/secops-mcp) |
| [OPNSenseMCP](https://github.com/vespo92/OPNSenseMCP) | 🟠 D | 5.4 | 200 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/vespo92/OPNSenseMCP) |
| [roadrecon_mcp_server](https://github.com/atomicchonk/roadrecon_mcp_server) | 🟡 C | 5.4 | 9 | 0 | [Details →](https://spiderrating.com/servers/atomicchonk/roadrecon_mcp_server) |
| [shieldapi-mcp](https://github.com/alberthild/shieldapi-mcp) | 🟠 D | 5.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/alberthild/shieldapi-mcp) |
| [clawguard-mcp](https://github.com/joergmichno/clawguard-mcp) | 🟡 C | 5.3 | 5 | 1 | [Details →](https://spiderrating.com/servers/joergmichno/clawguard-mcp) |
| [cve-search_mcp](https://github.com/roadwy/cve-search_mcp) | 🟠 D | 5.2 | 6 | 3 | [Details →](https://spiderrating.com/servers/roadwy/cve-search_mcp) |
| [mcp](https://github.com/agntor/mcp) | 🟡 C | 5.2 | 14 | 0 | [Details →](https://spiderrating.com/servers/agntor/mcp) |
| [entraid-mcp-server](https://github.com/hieuttmmo/entraid-mcp-server) | 🟠 D | 5.1 | 41 | 30 | [Details →](https://spiderrating.com/servers/hieuttmmo/entraid-mcp-server) |
| [mcp-server-cortex](https://github.com/gbrigandi/mcp-server-cortex) | 🟡 C | 5.1 | 5 | 0 | [Details →](https://spiderrating.com/servers/gbrigandi/mcp-server-cortex) |
| [mcp-server-thehive](https://github.com/gbrigandi/mcp-server-thehive) | 🟠 D | 5.1 | 7 | 0 | [Details →](https://spiderrating.com/servers/gbrigandi/mcp-server-thehive) |
| [MCP_Security](https://github.com/fr0gger/MCP_Security) | 🟠 D | 5.0 | 6 | 0 | [Details →](https://spiderrating.com/servers/fr0gger/MCP_Security) |
| [cyberchef-api-mcp-server](https://github.com/slouchd/cyberchef-api-mcp-server) | 🟠 D | 4.9 | 3 | 3 | [Details →](https://spiderrating.com/servers/slouchd/cyberchef-api-mcp-server) |
| [vuln-nist-mcp-server](https://github.com/HaroldFinchIFT/vuln-nist-mcp-server) | 🟠 D | 4.8 | 6 | 0 | [Details →](https://spiderrating.com/servers/HaroldFinchIFT/vuln-nist-mcp-server) |
| [moltrust-mcp-server](https://github.com/MoltyCel/moltrust-mcp-server) | 🟠 D | 4.8 | 33 | 0 | [Details →](https://spiderrating.com/servers/MoltyCel/moltrust-mcp-server) |
| [thales-cdsp-crdp-mcp-server](https://github.com/sanyambassi/thales-cdsp-crdp-mcp-server) | 🟠 D | 4.8 | 16 | 0 | [Details →](https://spiderrating.com/servers/sanyambassi/thales-cdsp-crdp-mcp-server) |
| [mcp-dnstwist](https://github.com/BurtTheCoder/mcp-dnstwist) | 🟠 D | 4.7 | 1 | 0 | [Details →](https://spiderrating.com/servers/BurtTheCoder/mcp-dnstwist) |
| [agent-bom](https://github.com/msaad00/agent-bom) | 🔴 F | 4.7 | 5 | 3 (3 crit) | [Details →](https://spiderrating.com/servers/msaad00/agent-bom) |
| [mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan) | 🟠 D | 4.7 | 7 | 0 | [Details →](https://spiderrating.com/servers/BurtTheCoder/mcp-shodan) |
| [mcp-maigret](https://github.com/BurtTheCoder/mcp-maigret) | 🟠 D | 4.6 | 2 | 0 | [Details →](https://spiderrating.com/servers/BurtTheCoder/mcp-maigret) |
| [MCP-Dandan](https://github.com/82ch/MCP-Dandan) | 🔴 F | 4.6 | 14 | 5 (3 crit) | [Details →](https://spiderrating.com/servers/82ch/MCP-Dandan) |
| [mcp-virustotal](https://github.com/BurtTheCoder/mcp-virustotal) | 🟠 D | 4.6 | 7 | 0 | [Details →](https://spiderrating.com/servers/BurtTheCoder/mcp-virustotal) |
| [bugsy](https://github.com/mobb-dev/bugsy) | 🔴 F | 4.6 | 1 | 19 (19 crit) | [Details →](https://spiderrating.com/servers/mobb-dev/bugsy) |
| [mcp-recon](https://github.com/nickpending/mcp-recon) | 🟠 D | 4.5 | 3 | 0 | [Details →](https://spiderrating.com/servers/nickpending/mcp-recon) |
| [AIM-MCP](https://github.com/AIM-Intelligence/AIM-MCP) | 🟠 D | 4.5 | 12 | 0 | [Details →](https://spiderrating.com/servers/AIM-Intelligence/AIM-MCP) |
| [attestable-mcp-server](https://github.com/co-browser/attestable-mcp-server) | 🟠 D | 4.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/co-browser/attestable-mcp-server) |
| [skylos](https://github.com/duriantaco/skylos) | 🔴 F | 4.3 | 1 | 12 (10 crit) | [Details →](https://spiderrating.com/servers/duriantaco/skylos) |
| [agent-os](https://github.com/imran-siddique/agent-os) | 🔴 F | 4.1 | 113 | 3 (3 crit) | [Details →](https://spiderrating.com/servers/imran-siddique/agent-os) |
| [solvitor-mcp](https://github.com/Adeptus-Innovatio/solvitor-mcp) | 🟠 D | 3.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/Adeptus-Innovatio/solvitor-mcp) |

## 🔗 Aggregators (29 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [anyquery](https://github.com/julien040/anyquery) | 🟠 D | 6.1 | 14 | 0 | [Details →](https://spiderrating.com/servers/julien040/anyquery) |
| [pluggedin-mcp-proxy](https://github.com/VeriTeknik/pluggedin-mcp-proxy) | 🟡 C | 5.9 | 28 | 0 | [Details →](https://spiderrating.com/servers/VeriTeknik/pluggedin-mcp-proxy) |
| [magg](https://github.com/sitbon/magg) | 🟠 D | 5.8 | 14 | 0 | [Details →](https://spiderrating.com/servers/sitbon/magg) |
| [forage](https://github.com/isaac-levine/forage) | 🟡 C | 5.7 | 6 | 0 | [Details →](https://spiderrating.com/servers/isaac-levine/forage) |
| [blockrun-mcp](https://github.com/blockrunai/blockrun-mcp) | 🟡 C | 5.7 | 10 | 0 | [Details →](https://spiderrating.com/servers/blockrunai/blockrun-mcp) |
| [ragmap](https://github.com/khalidsaidi/ragmap) | 🟡 C | 5.6 | 7 | 0 | [Details →](https://spiderrating.com/servers/khalidsaidi/ragmap) |
| [hashnet-mcp-js](https://github.com/hashgraph-online/hashnet-mcp-js) | 🟠 D | 5.6 | 56 | 0 | [Details →](https://spiderrating.com/servers/hashgraph-online/hashnet-mcp-js) |
| [evc-spark-mcp](https://github.com/entire-vc/evc-spark-mcp) | 🟡 C | 5.4 | 5 | 0 | [Details →](https://spiderrating.com/servers/entire-vc/evc-spark-mcp) |
| [metatool-app](https://github.com/metatool-ai/metatool-app) | 🟡 C | 5.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/metatool-ai/metatool-app) |
| [agentnet](https://github.com/oxgeneral/agentnet) | 🟡 C | 5.3 | 7 | 5 | [Details →](https://spiderrating.com/servers/oxgeneral/agentnet) |
| [x402-discovery-mcp](https://github.com/rplryan/x402-discovery-mcp) | 🟠 D | 5.3 | 2 | 0 | [Details →](https://spiderrating.com/servers/rplryan/x402-discovery-mcp) |
| [mcp-server](https://github.com/profullstack/mcp-server) | 🟠 D | 5.1 | 56 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/profullstack/mcp-server) |
| [mcp](https://github.com/waystation-ai/mcp) | 🟠 D | 5.1 | 2 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/waystation-ai/mcp) |
| [lunar](https://github.com/TheLunarCompany/lunar) | 🔴 F | 5.0 | 34 | 8 (8 crit) | [Details →](https://spiderrating.com/servers/TheLunarCompany/lunar) |
| [deepseek-mcp-server](https://github.com/arikusi/deepseek-mcp-server) | 🟠 D | 5.0 | 4 | 0 | [Details →](https://spiderrating.com/servers/arikusi/deepseek-mcp-server) |
| [ateam-mcp](https://github.com/ariekogan/ateam-mcp) | 🟠 D | 5.0 | 35 | 0 | [Details →](https://spiderrating.com/servers/ariekogan/ateam-mcp) |
| [Agent47](https://github.com/espadaw/Agent47) | 🟠 D | 5.0 | 5 | 0 | [Details →](https://spiderrating.com/servers/espadaw/Agent47) |
| [roundtable](https://github.com/askbudi/roundtable) | 🟠 D | 4.9 | 17 | 3 | [Details →](https://spiderrating.com/servers/askbudi/roundtable) |
| [voxie-ai-directory-mcp](https://github.com/sonnyflylock/voxie-ai-directory-mcp) | 🟠 D | 4.9 | 4 | 0 | [Details →](https://spiderrating.com/servers/sonnyflylock/voxie-ai-directory-mcp) |
| [agenthotspot-mcp](https://github.com/AgentHotspot/agenthotspot-mcp) | 🟠 D | 4.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/AgentHotspot/agenthotspot-mcp) |
| [cortex](https://github.com/gzoonet/cortex) | 🟠 D | 4.9 | 12 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/gzoonet/cortex) |
| [neurolink](https://github.com/juspay/neurolink) | 🔴 F | 4.9 | 108 | 45 (45 crit) | [Details →](https://spiderrating.com/servers/juspay/neurolink) |
| [PersonalizationMCP](https://github.com/YangLiangwei/PersonalizationMCP) | 🟠 D | 4.8 | 89 | 43 | [Details →](https://spiderrating.com/servers/YangLiangwei/PersonalizationMCP) |
| [1mcpserver](https://github.com/particlefuture/1mcpserver) | 🟠 D | 4.5 | 5 | 9 | [Details →](https://spiderrating.com/servers/particlefuture/1mcpserver) |
| [ncp](https://github.com/portel-dev/ncp) | 🔴 F | 4.5 | 1519 | 10 (10 crit) | [Details →](https://spiderrating.com/servers/portel-dev/ncp) |
| [agenium](https://github.com/Aganium/agenium) | 🟠 D | 4.4 | 30 | 0 | [Details →](https://spiderrating.com/servers/Aganium/agenium) |
| [agent](https://github.com/1mcp-app/agent) | 🟠 D | 4.4 | 24 | 0 | [Details →](https://spiderrating.com/servers/1mcp-app/agent) |
| [agoragentic-integrations](https://github.com/rhein1/agoragentic-integrations) | 🟠 D | 4.3 | 25 | 126 | [Details →](https://spiderrating.com/servers/rhein1/agoragentic-integrations) |
| [pipedream](https://github.com/PipedreamHQ/pipedream) | 🟠 D | 4.3 | 2 | 0 | [Details →](https://spiderrating.com/servers/PipedreamHQ/pipedream) |

## 🔬 Research (7 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [idea-reality-mcp](https://github.com/mnemox-ai/idea-reality-mcp) | 🟢 B | 7.1 | 1 | 0 | [Details →](https://spiderrating.com/servers/mnemox-ai/idea-reality-mcp) |
| [deep-research-mcp](https://github.com/pminervini/deep-research-mcp) | 🟡 C | 6.4 | 3 | 0 | [Details →](https://spiderrating.com/servers/pminervini/deep-research-mcp) |
| [legiscan-mcp](https://github.com/sh-patterson/legiscan-mcp) | 🟡 C | 5.7 | 10 | 0 | [Details →](https://spiderrating.com/servers/sh-patterson/legiscan-mcp) |
| [BrowserAI-Dev](https://github.com/BrowseAI-HQ/BrowserAI-Dev) | 🟡 C | 5.5 | 14 | 0 | [Details →](https://spiderrating.com/servers/BrowseAI-HQ/BrowserAI-Dev) |
| [mcp-server-originalvoices](https://github.com/ovlabs/mcp-server-originalvoices) | 🟠 D | 4.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/ovlabs/mcp-server-originalvoices) |
| [sourcelibrary-v2](https://github.com/Embassy-of-the-Free-Mind/sourcelibrary-v2) | 🟠 D | 4.6 | 46 | 0 | [Details →](https://spiderrating.com/servers/Embassy-of-the-Free-Mind/sourcelibrary-v2) |
| [agentinterviews_mcp](https://github.com/thinkchainai/agentinterviews_mcp) | 🟠 D | 4.3 | 4 | 0 | [Details →](https://spiderrating.com/servers/thinkchainai/agentinterviews_mcp) |

## 🖥️ Command Line (1 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [hop](https://github.com/danmartuszewski/hop) | 🟡 C | 5.6 | 8 | 0 | [Details →](https://spiderrating.com/servers/danmartuszewski/hop) |

## 🗄️ Databases (68 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [dicom-mcp](https://github.com/ChristianHinge/dicom-mcp) | 🟢 B | 7.1 | 11 | 1 | [Details →](https://spiderrating.com/servers/ChristianHinge/dicom-mcp) |
| [mcp-redis](https://github.com/redis/mcp-redis) | 🟢 B | 7.0 | 46 | 31 | [Details →](https://spiderrating.com/servers/redis/mcp-redis) |
| [mcp-hydrolix](https://github.com/hydrolix/mcp-hydrolix) | 🟡 C | 6.7 | 3 | 1 | [Details →](https://spiderrating.com/servers/hydrolix/mcp-hydrolix) |
| [mcp-trino](https://github.com/tuannvm/mcp-trino) | 🟡 C | 6.6 | 6 | 0 | [Details →](https://spiderrating.com/servers/tuannvm/mcp-trino) |
| [convex-backend](https://github.com/get-convex/convex-backend) | 🟡 C | 6.6 | 11 | 0 | [Details →](https://spiderrating.com/servers/get-convex/convex-backend) |
| [prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) | 🟡 C | 6.5 | 5 | 1 | [Details →](https://spiderrating.com/servers/pab1it0/prometheus-mcp-server) |
| [chroma-mcp](https://github.com/chroma-core/chroma-mcp) | 🟡 C | 6.4 | 13 | 3 | [Details →](https://spiderrating.com/servers/chroma-core/chroma-mcp) |
| [genai-toolbox](https://github.com/googleapis/genai-toolbox) | 🟠 D | 6.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/googleapis/genai-toolbox) |
| [elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) | 🟡 C | 6.3 | 20 | 14 | [Details →](https://spiderrating.com/servers/cr7258/elasticsearch-mcp-server) |
| [xiyan_mcp_server](https://github.com/XGenerationLab/xiyan_mcp_server) | 🟡 C | 6.2 | 1 | 1 | [Details →](https://spiderrating.com/servers/XGenerationLab/xiyan_mcp_server) |
| [mcp-confluent](https://github.com/confluentinc/mcp-confluent) | 🟠 D | 6.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/confluentinc/mcp-confluent) |
| [cli](https://github.com/planetscale/cli) | 🟡 C | 6.2 | 8 | 0 | [Details →](https://spiderrating.com/servers/planetscale/cli) |
| [mcp-server-duckdb](https://github.com/ktanaka101/mcp-server-duckdb) | 🟡 C | 6.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/ktanaka101/mcp-server-duckdb) |
| [influxdb3_mcp_server](https://github.com/influxdata/influxdb3_mcp_server) | 🟡 C | 6.1 | 33 | 0 | [Details →](https://spiderrating.com/servers/influxdata/influxdb3_mcp_server) |
| [mcp-server-milvus](https://github.com/zilliztech/mcp-server-milvus) | 🟡 C | 6.1 | 14 | 3 | [Details →](https://spiderrating.com/servers/zilliztech/mcp-server-milvus) |
| [adx-mcp-server](https://github.com/pab1it0/adx-mcp-server) | 🟡 C | 6.1 | 5 | 4 | [Details →](https://spiderrating.com/servers/pab1it0/adx-mcp-server) |
| [airtable-mcp](https://github.com/rashidazarang/airtable-mcp) | 🟠 D | 6.1 | 125 | 0 | [Details →](https://spiderrating.com/servers/rashidazarang/airtable-mcp) |
| [mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) | 🟡 C | 6.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/ergut/mcp-bigquery-server) |
| [influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server) | 🟡 C | 6.0 | 4 | 0 | [Details →](https://spiderrating.com/servers/idoru/influxdb-mcp-server) |
| [firebase-mcp](https://github.com/gannonh/firebase-mcp) | 🟡 C | 6.0 | 12 | 0 | [Details →](https://spiderrating.com/servers/gannonh/firebase-mcp) |
| [mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) | 🟡 C | 6.0 | 8 | 0 | [Details →](https://spiderrating.com/servers/isaacwasserman/mcp-snowflake-server) |
| [mcp-gsheets](https://github.com/freema/mcp-gsheets) | 🟠 D | 5.9 | 39 | 0 | [Details →](https://spiderrating.com/servers/freema/mcp-gsheets) |
| [izTolkMcp](https://github.com/izzzzzi/izTolkMcp) | 🟡 C | 5.9 | 4 | 0 | [Details →](https://spiderrating.com/servers/izzzzzi/izTolkMcp) |
| [mcp-mysql-server](https://github.com/f4ww4z/mcp-mysql-server) | 🟡 C | 5.9 | 5 | 0 | [Details →](https://spiderrating.com/servers/f4ww4z/mcp-mysql-server) |
| [legion-mcp](https://github.com/TheRaLabs/legion-mcp) | 🟡 C | 5.8 | 10 | 7 | [Details →](https://spiderrating.com/servers/TheRaLabs/legion-mcp) |
| [nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) | 🟠 D | 5.8 | 11 | 0 | [Details →](https://spiderrating.com/servers/niledatabase/nile-mcp-server) |
| [google-sheets-mcp](https://github.com/henilcalagiya/google-sheets-mcp) | 🟡 C | 5.8 | 24 | 0 | [Details →](https://spiderrating.com/servers/henilcalagiya/google-sheets-mcp) |
| [greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server) | 🟠 D | 5.8 | 10 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/GreptimeTeam/greptimedb-mcp-server) |
| [mongodb-lens](https://github.com/furey/mongodb-lens) | 🟠 D | 5.7 | 42 | 1 | [Details →](https://spiderrating.com/servers/furey/mongodb-lens) |
| [go-mcp-mysql](https://github.com/Zhwt/go-mcp-mysql) | 🟡 C | 5.7 | 9 | 0 | [Details →](https://spiderrating.com/servers/Zhwt/go-mcp-mysql) |
| [ydb-mcp](https://github.com/ydb-platform/ydb-mcp) | 🟠 D | 5.7 | 8 | 0 | [Details →](https://spiderrating.com/servers/ydb-platform/ydb-mcp) |
| [mcp-pinecone](https://github.com/sirmews/mcp-pinecone) | 🟡 C | 5.6 | 5 | 0 | [Details →](https://spiderrating.com/servers/sirmews/mcp-pinecone) |
| [ai-toolkit](https://github.com/memgraph/ai-toolkit) | 🟠 D | 5.6 | 18 | 5 (2 crit) | [Details →](https://spiderrating.com/servers/memgraph/ai-toolkit) |
| [simple_snowflake_mcp](https://github.com/YannBrrd/simple_snowflake_mcp) | 🟡 C | 5.6 | 15 | 0 | [Details →](https://spiderrating.com/servers/YannBrrd/simple_snowflake_mcp) |
| [mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) | 🟠 D | 5.5 | 1 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/designcomputer/mysql_mcp_server) |
| [mcp-sqlite](https://github.com/jparkerweb/mcp-sqlite) | 🟡 C | 5.5 | 8 | 0 | [Details →](https://spiderrating.com/servers/jparkerweb/mcp-sqlite) |
| [pgmcp](https://github.com/subnetmarco/pgmcp) | 🟡 C | 5.5 | 3 | 0 | [Details →](https://spiderrating.com/servers/subnetmarco/pgmcp) |
| [airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) | 🔴 F | 5.4 | 16 | 3 (3 crit) | [Details →](https://spiderrating.com/servers/domdomegg/airtable-mcp-server) |
| [skysql-mcp](https://github.com/skysqlinc/skysql-mcp) | 🟠 D | 5.4 | 8 | 6 | [Details →](https://spiderrating.com/servers/skysqlinc/skysql-mcp) |
| [mcp-cockroachdb](https://github.com/amineelkouhen/mcp-cockroachdb) | 🔴 F | 5.4 | 29 | 23 (7 crit) | [Details →](https://spiderrating.com/servers/amineelkouhen/mcp-cockroachdb) |
| [mcp-run-sql-connectorx](https://github.com/gigamori/mcp-run-sql-connectorx) | 🟡 C | 5.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/gigamori/mcp-run-sql-connectorx) |
| [sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) | 🟠 D | 5.3 | 3 | 2 (1 crit) | [Details →](https://spiderrating.com/servers/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) |
| [mcp-database-server](https://github.com/fireproof-storage/mcp-database-server) | 🟠 D | 5.3 | 4 | 0 | [Details →](https://spiderrating.com/servers/fireproof-storage/mcp-database-server) |
| [mcp-server-sqlite](https://github.com/ofershap/mcp-server-sqlite) | 🟡 C | 5.2 | 5 | 0 | [Details →](https://spiderrating.com/servers/ofershap/mcp-server-sqlite) |
| [mcp](https://github.com/prisma/mcp) | 🟠 D | 5.2 | 10 | 0 | [Details →](https://spiderrating.com/servers/prisma/mcp) |
| [VictoriaMetrics-mcp-server](https://github.com/yincongcyincong/VictoriaMetrics-mcp-server) | 🟠 D | 5.2 | 6 | 0 | [Details →](https://spiderrating.com/servers/yincongcyincong/VictoriaMetrics-mcp-server) |
| [mcp-server-trino](https://github.com/Dataring-engineering/mcp-server-trino) | 🟡 C | 5.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/Dataring-engineering/mcp-server-trino) |
| [SmartDB_MCP](https://github.com/wenb1n-dev/SmartDB_MCP) | 🟠 D | 5.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/wenb1n-dev/SmartDB_MCP) |
| [nocodb-mcp-server](https://github.com/edwinbernadus/nocodb-mcp-server) | 🟠 D | 5.1 | 14 | 0 | [Details →](https://spiderrating.com/servers/edwinbernadus/nocodb-mcp-server) |
| [ibge-br-mcp](https://github.com/SidneyBissoli/ibge-br-mcp) | 🟠 D | 4.9 | 23 | 0 | [Details →](https://spiderrating.com/servers/SidneyBissoli/ibge-br-mcp) |
| [mysql-mcp-server](https://github.com/dave-wind/mysql-mcp-server) | 🟠 D | 4.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/dave-wind/mysql-mcp-server) |
| [mongodb-atlas-mcp-server](https://github.com/montumodi/mongodb-atlas-mcp-server) | 🟠 D | 4.9 | 76 | 0 | [Details →](https://spiderrating.com/servers/montumodi/mongodb-atlas-mcp-server) |
| [mcp](https://github.com/Snowflake-Labs/mcp) | 🟠 D | 4.7 | 5 | 0 | [Details →](https://spiderrating.com/servers/Snowflake-Labs/mcp) |
| [mcp-timeplus](https://github.com/jovezhong/mcp-timeplus) | 🟠 D | 4.6 | 5 | 4 | [Details →](https://spiderrating.com/servers/jovezhong/mcp-timeplus) |
| [mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery) | 🟠 D | 4.6 | 3 | 0 | [Details →](https://spiderrating.com/servers/LucasHild/mcp-server-bigquery) |
| [postgres_mcp](https://github.com/JaviMaligno/postgres_mcp) | 🟠 D | 4.5 | 20 | 0 | [Details →](https://spiderrating.com/servers/JaviMaligno/postgres_mcp) |
| [wode](https://github.com/wenerme/wode) | 🔴 F | 4.5 | 73 | 11 (3 crit) | [Details →](https://spiderrating.com/servers/wenerme/wode) |
| [mcp-aiven](https://github.com/Aiven-Open/mcp-aiven) | 🟠 D | 4.4 | 3 | 0 | [Details →](https://spiderrating.com/servers/Aiven-Open/mcp-aiven) |
| [supabase](https://github.com/joshuarileydev/supabase) | 🟠 D | 4.3 | 8 | 0 | [Details →](https://spiderrating.com/servers/joshuarileydev/supabase) |
| [baserow](https://github.com/bram2w/baserow) | 🟠 D | 4.2 | 11 | 1 | [Details →](https://spiderrating.com/servers/bram2w/baserow) |
| [mcp-sqlalchemy-server](https://github.com/OpenLinkSoftware/mcp-sqlalchemy-server) | 🟠 D | 4.2 | 14 | 0 | [Details →](https://spiderrating.com/servers/OpenLinkSoftware/mcp-sqlalchemy-server) |
| [mcp-datalink](https://github.com/pilat/mcp-datalink) | 🔴 F | 4.2 | 6 | 3 (3 crit) | [Details →](https://spiderrating.com/servers/pilat/mcp-datalink) |
| [dolphindb-mcp-server](https://github.com/tradercjz/dolphindb-mcp-server) | 🟠 D | 4.1 | 4 | 5 (2 crit) | [Details →](https://spiderrating.com/servers/tradercjz/dolphindb-mcp-server) |
| [db-mcp-server](https://github.com/FreePeak/db-mcp-server) | 🟠 D | 4.0 | 6 | 0 | [Details →](https://spiderrating.com/servers/FreePeak/db-mcp-server) |
| [mcp-odbc-server](https://github.com/OpenLinkSoftware/mcp-odbc-server) | 🟠 D | 4.0 | 15 | 0 | [Details →](https://spiderrating.com/servers/OpenLinkSoftware/mcp-odbc-server) |
| [mcp-jdbc-server](https://github.com/OpenLinkSoftware/mcp-jdbc-server) | 🟠 D | 3.8 | 10 | 0 | [Details →](https://spiderrating.com/servers/OpenLinkSoftware/mcp-jdbc-server) |
| [mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) | 🔴 F | 3.8 | 7 | 5 (5 crit) | [Details →](https://spiderrating.com/servers/c4pt0r/mcp-server-tidb) |
| [mcp-victorialogs](https://github.com/VictoriaMetrics-Community/mcp-victorialogs) | 🟠 D | 3.7 | 13 | 0 | [Details →](https://spiderrating.com/servers/VictoriaMetrics-Community/mcp-victorialogs) |

## 🗺️ Location Services (16 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-server-ipinfo](https://github.com/briandconnelly/mcp-server-ipinfo) | 🟡 C | 6.3 | 3 | 0 | [Details →](https://spiderrating.com/servers/briandconnelly/mcp-server-ipinfo) |
| [geoserver-mcp](https://github.com/mahdin75/geoserver-mcp) | 🟡 C | 6.2 | 56 | 42 | [Details →](https://spiderrating.com/servers/mahdin75/geoserver-mcp) |
| [nearby-search-mcp](https://github.com/kukapay/nearby-search-mcp) | 🟡 C | 5.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/kukapay/nearby-search-mcp) |
| [open-streetmap-mcp](https://github.com/jagan-shanmugam/open-streetmap-mcp) | 🟡 C | 5.8 | 12 | 1 | [Details →](https://spiderrating.com/servers/jagan-shanmugam/open-streetmap-mcp) |
| [mcp-server-iplocate](https://github.com/iplocate/mcp-server-iplocate) | 🟡 C | 5.8 | 6 | 0 | [Details →](https://spiderrating.com/servers/iplocate/mcp-server-iplocate) |
| [MCP-Geo](https://github.com/webcoderz/MCP-Geo) | 🟡 C | 5.5 | 7 | 3 | [Details →](https://spiderrating.com/servers/webcoderz/MCP-Geo) |
| [mcp-weather](https://github.com/TimLukaHorstmann/mcp-weather) | 🟡 C | 5.5 | 2 | 0 | [Details →](https://spiderrating.com/servers/TimLukaHorstmann/mcp-weather) |
| [stadiamaps-mcp-server-ts](https://github.com/stadiamaps/stadiamaps-mcp-server-ts) | 🟡 C | 5.4 | 6 | 0 | [Details →](https://spiderrating.com/servers/stadiamaps/stadiamaps-mcp-server-ts) |
| [qgis_mcp](https://github.com/jjsantos01/qgis_mcp) | 🟡 C | 5.3 | 15 | 10 | [Details →](https://spiderrating.com/servers/jjsantos01/qgis_mcp) |
| [trackmage-mcp-server](https://github.com/trackmage/trackmage-mcp-server) | 🟠 D | 5.1 | 10 | 0 | [Details →](https://spiderrating.com/servers/trackmage/trackmage-mcp-server) |
| [mcp-ip2location-io](https://github.com/ip2location/mcp-ip2location-io) | 🟡 C | 5.0 | 1 | 1 | [Details →](https://spiderrating.com/servers/ip2location/mcp-ip2location-io) |
| [ipfind-mcp-server](https://github.com/ipfind/ipfind-mcp-server) | 🟡 C | 5.0 | 3 | 2 | [Details →](https://spiderrating.com/servers/ipfind/ipfind-mcp-server) |
| [trinvmcp](https://github.com/cqtrinv/trinvmcp) | 🟠 D | 5.0 | 2 | 0 | [Details →](https://spiderrating.com/servers/cqtrinv/trinvmcp) |
| [aiwen-mcp-server-geoip](https://github.com/ipfred/aiwen-mcp-server-geoip) | 🟠 D | 4.8 | 9 | 0 | [Details →](https://spiderrating.com/servers/ipfred/aiwen-mcp-server-geoip) |
| [gis-mcp-server](https://github.com/matbel91765/gis-mcp-server) | 🟠 D | 4.7 | 40 | 0 | [Details →](https://spiderrating.com/servers/matbel91765/gis-mcp-server) |
| [weather-mcp-server](https://github.com/devilcoder01/weather-mcp-server) | 🟠 D | 4.6 | 9 | 8 | [Details →](https://spiderrating.com/servers/devilcoder01/weather-mcp-server) |

## 🚆 Travel & Transportation (10 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb) | 🟡 C | 6.2 | 2 | 0 | [Details →](https://spiderrating.com/servers/openbnb-org/mcp-server-airbnb) |
| [alltrails-mcp-server](https://github.com/srinath1510/alltrails-mcp-server) | 🟡 C | 5.8 | 2 | 0 | [Details →](https://spiderrating.com/servers/srinath1510/alltrails-mcp-server) |
| [tripadvisor-mcp](https://github.com/pab1it0/tripadvisor-mcp) | 🟡 C | 5.8 | 5 | 0 | [Details →](https://spiderrating.com/servers/pab1it0/tripadvisor-mcp) |
| [ns-mcp-server](https://github.com/r-huijts/ns-mcp-server) | 🟡 C | 5.8 | 8 | 0 | [Details →](https://spiderrating.com/servers/r-huijts/ns-mcp-server) |
| [aviationstack-mcp](https://github.com/Pradumnasaraf/aviationstack-mcp) | 🟠 D | 5.7 | 10 | 1 | [Details →](https://spiderrating.com/servers/Pradumnasaraf/aviationstack-mcp) |
| [vesselapi-mcp](https://github.com/vessel-api/vesselapi-mcp) | 🟡 C | 5.7 | 17 | 0 | [Details →](https://spiderrating.com/servers/vessel-api/vesselapi-mcp) |
| [tripgo-mcp-server](https://github.com/skedgo/tripgo-mcp-server) | 🟡 C | 5.6 | 4 | 0 | [Details →](https://spiderrating.com/servers/skedgo/tripgo-mcp-server) |
| [teslamate-mcp](https://github.com/cobanov/teslamate-mcp) | 🟡 C | 5.6 | 2 | 0 | [Details →](https://spiderrating.com/servers/cobanov/teslamate-mcp) |
| [mcp-national-rail](https://github.com/lucygoodchild/mcp-national-rail) | 🟠 D | 5.0 | 4 | 0 | [Details →](https://spiderrating.com/servers/lucygoodchild/mcp-national-rail) |
| [mcp-server-nationalparks](https://github.com/KyrieTangSheng/mcp-server-nationalparks) | 🟠 D | 4.7 | 6 | 0 | [Details →](https://spiderrating.com/servers/KyrieTangSheng/mcp-server-nationalparks) |

## 🛠️ Other Tools And Integrations (97 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [typst-mcp](https://github.com/johannesbrandenburger/typst-mcp) | 🟢 B | 7.2 | 8 | 1 | [Details →](https://spiderrating.com/servers/johannesbrandenburger/typst-mcp) |
| [productplan-mcp-server](https://github.com/olgasafonova/productplan-mcp-server) | 🟡 C | 6.8 | 6 | 0 | [Details →](https://spiderrating.com/servers/olgasafonova/productplan-mcp-server) |
| [klavis](https://github.com/Klavis-AI/klavis) | 🟠 D | 6.6 | 1474 | 134 (2 crit) | [Details →](https://spiderrating.com/servers/Klavis-AI/klavis) |
| [wcgw](https://github.com/rusiaaman/wcgw) | 🟡 C | 6.5 | 7 | 0 | [Details →](https://spiderrating.com/servers/rusiaaman/wcgw) |
| [mcp-claude-spotify](https://github.com/imprvhub/mcp-claude-spotify) | 🟡 C | 6.3 | 12 | 0 | [Details →](https://spiderrating.com/servers/imprvhub/mcp-claude-spotify) |
| [wenyan-mcp](https://github.com/caol64/wenyan-mcp) | 🟡 C | 6.3 | 4 | 0 | [Details →](https://spiderrating.com/servers/caol64/wenyan-mcp) |
| [coda-mcp](https://github.com/orellazri/coda-mcp) | 🟠 D | 6.1 | 19 | 0 | [Details →](https://spiderrating.com/servers/orellazri/coda-mcp) |
| [keep-mcp](https://github.com/feuerdev/keep-mcp) | 🟡 C | 6.1 | 23 | 19 | [Details →](https://spiderrating.com/servers/feuerdev/keep-mcp) |
| [mcp-apple-notes](https://github.com/henilcalagiya/mcp-apple-notes) | 🟡 C | 6.1 | 14 | 0 | [Details →](https://spiderrating.com/servers/henilcalagiya/mcp-apple-notes) |
| [contentful-mcp](https://github.com/ivo-toby/contentful-mcp) | 🟠 D | 6.0 | 67 | 0 | [Details →](https://spiderrating.com/servers/ivo-toby/contentful-mcp) |
| [growi-mcp-server](https://github.com/growilabs/growi-mcp-server) | 🟡 C | 6.0 | 29 | 0 | [Details →](https://spiderrating.com/servers/growilabs/growi-mcp-server) |
| [mcp-linear](https://github.com/tacticlaunch/mcp-linear) | 🟠 D | 6.0 | 42 | 0 | [Details →](https://spiderrating.com/servers/tacticlaunch/mcp-linear) |
| [mcp-time](https://github.com/TheoBrigitte/mcp-time) | 🟡 C | 6.0 | 4 | 0 | [Details →](https://spiderrating.com/servers/TheoBrigitte/mcp-time) |
| [unichat-mcp-server](https://github.com/amidabuddha/unichat-mcp-server) | 🟡 C | 5.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/amidabuddha/unichat-mcp-server) |
| [replicate-flux-mcp](https://github.com/awkoy/replicate-flux-mcp) | 🟡 C | 5.9 | 7 | 0 | [Details →](https://spiderrating.com/servers/awkoy/replicate-flux-mcp) |
| [brainstorm-mcp](https://github.com/spranab/brainstorm-mcp) | 🟡 C | 5.9 | 4 | 0 | [Details →](https://spiderrating.com/servers/spranab/brainstorm-mcp) |
| [mcp-notion-server](https://github.com/suekou/mcp-notion-server) | 🟡 C | 5.9 | 18 | 0 | [Details →](https://spiderrating.com/servers/suekou/mcp-notion-server) |
| [mcp-graphql](https://github.com/blurrah/mcp-graphql) | 🟠 D | 5.9 | 2 | 0 | [Details →](https://spiderrating.com/servers/blurrah/mcp-graphql) |
| [mcp-server-giphy](https://github.com/magarcia/mcp-server-giphy) | 🟡 C | 5.8 | 3 | 0 | [Details →](https://spiderrating.com/servers/magarcia/mcp-server-giphy) |
| [free-will-mcp](https://github.com/gwbischof/free-will-mcp) | 🟡 C | 5.8 | 3 | 1 | [Details →](https://spiderrating.com/servers/gwbischof/free-will-mcp) |
| [nutrient-dws-mcp-server](https://github.com/PSPDFKit/nutrient-dws-mcp-server) | 🟠 D | 5.8 | 6 | 1 | [Details →](https://spiderrating.com/servers/PSPDFKit/nutrient-dws-mcp-server) |
| [mcp-server-asana](https://github.com/roychri/mcp-server-asana) | 🟠 D | 5.8 | 41 | 0 | [Details →](https://spiderrating.com/servers/roychri/mcp-server-asana) |
| [mcp-youtube](https://github.com/anaisbetts/mcp-youtube) | 🟡 C | 5.8 | 1 | 0 | [Details →](https://spiderrating.com/servers/anaisbetts/mcp-youtube) |
| [mcp-kibela-server](https://github.com/kiwamizamurai/mcp-kibela-server) | 🟡 C | 5.7 | 12 | 0 | [Details →](https://spiderrating.com/servers/kiwamizamurai/mcp-kibela-server) |
| [ethics-check-mcp](https://github.com/r-huijts/ethics-check-mcp) | 🟡 C | 5.7 | 4 | 0 | [Details →](https://spiderrating.com/servers/r-huijts/ethics-check-mcp) |
| [rember-mcp](https://github.com/rember/rember-mcp) | 🟡 C | 5.7 | 1 | 0 | [Details →](https://spiderrating.com/servers/rember/rember-mcp) |
| [hackmd-mcp](https://github.com/yuna0x0/hackmd-mcp) | 🟠 D | 5.7 | 12 | 0 | [Details →](https://spiderrating.com/servers/yuna0x0/hackmd-mcp) |
| [apple-notes-mcp](https://github.com/sirmews/apple-notes-mcp) | 🟡 C | 5.7 | 3 | 0 | [Details →](https://spiderrating.com/servers/sirmews/apple-notes-mcp) |
| [mcp-kibela](https://github.com/kj455/mcp-kibela) | 🟡 C | 5.7 | 6 | 0 | [Details →](https://spiderrating.com/servers/kj455/mcp-kibela) |
| [interactive-mcp](https://github.com/ttommyth/interactive-mcp) | 🟠 D | 5.7 | 5 | 0 | [Details →](https://spiderrating.com/servers/ttommyth/interactive-mcp) |
| [mcp-server-amazon-bedrock](https://github.com/zxkane/mcp-server-amazon-bedrock) | 🟡 C | 5.7 | 1 | 0 | [Details →](https://spiderrating.com/servers/zxkane/mcp-server-amazon-bedrock) |
| [mcp-miro](https://github.com/evalstate/mcp-miro) | 🟡 C | 5.7 | 6 | 0 | [Details →](https://spiderrating.com/servers/evalstate/mcp-miro) |
| [homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp) | 🟠 D | 5.7 | 11 | 0 | [Details →](https://spiderrating.com/servers/tevonsb/homeassistant-mcp) |
| [mcp-server-perplexity](https://github.com/tanigami/mcp-server-perplexity) | 🟡 C | 5.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/tanigami/mcp-server-perplexity) |
| [bear-mcp-server](https://github.com/akseyh/bear-mcp-server) | 🟡 C | 5.6 | 3 | 0 | [Details →](https://spiderrating.com/servers/akseyh/bear-mcp-server) |
| [hko-mcp](https://github.com/louiscklaw/hko-mcp) | 🟡 C | 5.6 | 20 | 0 | [Details →](https://spiderrating.com/servers/louiscklaw/hko-mcp) |
| [spotify-mcp-server](https://github.com/marcelmarais/spotify-mcp-server) | 🟠 D | 5.6 | 27 | 0 | [Details →](https://spiderrating.com/servers/marcelmarais/spotify-mcp-server) |
| [thingsboard-mcp](https://github.com/thingsboard/thingsboard-mcp) | 🟠 D | 5.6 | 108 | 0 | [Details →](https://spiderrating.com/servers/thingsboard/thingsboard-mcp) |
| [notion_mcp](https://github.com/danhilse/notion_mcp) | 🟡 C | 5.5 | 4 | 0 | [Details →](https://spiderrating.com/servers/danhilse/notion_mcp) |
| [raindrop-io-mcp-server](https://github.com/hiromitsusasaki/raindrop-io-mcp-server) | 🟡 C | 5.5 | 3 | 0 | [Details →](https://spiderrating.com/servers/hiromitsusasaki/raindrop-io-mcp-server) |
| [plane-mcp-server](https://github.com/kelvin6365/plane-mcp-server) | 🟡 C | 5.5 | 6 | 0 | [Details →](https://spiderrating.com/servers/kelvin6365/plane-mcp-server) |
| [plantuml_web](https://github.com/2niuhe/plantuml_web) | 🟡 C | 5.5 | 2 | 1 | [Details →](https://spiderrating.com/servers/2niuhe/plantuml_web) |
| [mcp-server-esignatures](https://github.com/esignaturescom/mcp-server-esignatures) | 🟡 C | 5.5 | 13 | 0 | [Details →](https://spiderrating.com/servers/esignaturescom/mcp-server-esignatures) |
| [screenmonitormcp](https://github.com/inkbytefo/screenmonitormcp) | 🟡 C | 5.5 | 25 | 2 | [Details →](https://spiderrating.com/servers/inkbytefo/screenmonitormcp) |
| [mcp-miro](https://github.com/k-jarzyna/mcp-miro) | 🟠 D | 5.5 | 97 | 0 | [Details →](https://spiderrating.com/servers/k-jarzyna/mcp-miro) |
| [offorte-mcp-server](https://github.com/offorte/offorte-mcp-server) | 🟠 D | 5.5 | 15 | 0 | [Details →](https://spiderrating.com/servers/offorte/offorte-mcp-server) |
| [hn-server](https://github.com/pskill9/hn-server) | 🟡 C | 5.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/pskill9/hn-server) |
| [w3ship-mcp-server](https://github.com/baskcart/w3ship-mcp-server) | 🟡 C | 5.4 | 22 | 0 | [Details →](https://spiderrating.com/servers/baskcart/w3ship-mcp-server) |
| [piapi-mcp-server](https://github.com/apinetwork/piapi-mcp-server) | 🟠 D | 5.4 | 23 | 0 | [Details →](https://spiderrating.com/servers/apinetwork/piapi-mcp-server) |
| [attio-mcp-server](https://github.com/hmk/attio-mcp-server) | 🟡 C | 5.4 | 4 | 0 | [Details →](https://spiderrating.com/servers/hmk/attio-mcp-server) |
| [mcp-server-calculator](https://github.com/githejie/mcp-server-calculator) | 🟠 D | 5.4 | 1 | 1 | [Details →](https://spiderrating.com/servers/githejie/mcp-server-calculator) |
| [my-bear-mcp-server](https://github.com/bart6114/my-bear-mcp-server) | 🟡 C | 5.4 | 4 | 0 | [Details →](https://spiderrating.com/servers/bart6114/my-bear-mcp-server) |
| [mcp-chatgpt-responses](https://github.com/billster45/mcp-chatgpt-responses) | 🟡 C | 5.3 | 2 | 0 | [Details →](https://spiderrating.com/servers/billster45/mcp-chatgpt-responses) |
| [ticktick-mcp](https://github.com/ekkyarmandi/ticktick-mcp) | 🟡 C | 5.3 | 9 | 5 | [Details →](https://spiderrating.com/servers/ekkyarmandi/ticktick-mcp) |
| [climatiq-mcp-server](https://github.com/jagan-shanmugam/climatiq-mcp-server) | 🟡 C | 5.3 | 10 | 0 | [Details →](https://spiderrating.com/servers/jagan-shanmugam/climatiq-mcp-server) |
| [mcp-openai](https://github.com/mzxrai/mcp-openai) | 🟠 D | 5.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/mzxrai/mcp-openai) |
| [mcp-datetime](https://github.com/ZeparHyfar/mcp-datetime) | 🟡 C | 5.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/ZeparHyfar/mcp-datetime) |
| [oura-mcp-server](https://github.com/tomekkorbak/oura-mcp-server) | 🟠 D | 5.3 | 6 | 3 | [Details →](https://spiderrating.com/servers/tomekkorbak/oura-mcp-server) |
| [thinqconnect-mcp](https://github.com/thinq-connect/thinqconnect-mcp) | 🟠 D | 5.3 | 4 | 0 | [Details →](https://spiderrating.com/servers/thinq-connect/thinqconnect-mcp) |
| [cal-mcp](https://github.com/pwh-pwh/cal-mcp) | 🟠 D | 5.2 | 4 | 0 | [Details →](https://spiderrating.com/servers/pwh-pwh/cal-mcp) |
| [mcp-difyworkflow-server](https://github.com/gotoolkits/mcp-difyworkflow-server) | 🟡 C | 5.2 | 2 | 0 | [Details →](https://spiderrating.com/servers/gotoolkits/mcp-difyworkflow-server) |
| [capsulecrm-mcp](https://github.com/MonadsAG/capsulecrm-mcp) | 🟡 C | 5.2 | 19 | 3 | [Details →](https://spiderrating.com/servers/MonadsAG/capsulecrm-mcp) |
| [needhuman-mcp](https://github.com/MariusAure/needhuman-mcp) | 🟡 C | 5.2 | 3 | 0 | [Details →](https://spiderrating.com/servers/MariusAure/needhuman-mcp) |
| [omniparser-autogui-mcp](https://github.com/NON906/omniparser-autogui-mcp) | 🟡 C | 5.2 | 9 | 2 | [Details →](https://spiderrating.com/servers/NON906/omniparser-autogui-mcp) |
| [mcp-server-nano-banana](https://github.com/nanana-app/mcp-server-nano-banana) | 🟠 D | 5.2 | 2 | 0 | [Details →](https://spiderrating.com/servers/nanana-app/mcp-server-nano-banana) |
| [apple-notes-mcp](https://github.com/disco-trooper/apple-notes-mcp) | 🟡 C | 5.1 | 23 | 0 | [Details →](https://spiderrating.com/servers/disco-trooper/apple-notes-mcp) |
| [ancestry-mcp](https://github.com/reeeeemo/ancestry-mcp) | 🟡 C | 5.1 | 3 | 0 | [Details →](https://spiderrating.com/servers/reeeeemo/ancestry-mcp) |
| [PlanningCopilot](https://github.com/SPL-BGU/PlanningCopilot) | 🔴 F | 5.1 | 5 | 10 (3 crit) | [Details →](https://spiderrating.com/servers/SPL-BGU/PlanningCopilot) |
| [web3-mcp](https://github.com/tumf/web3-mcp) | 🟡 C | 5.1 | 17 | 0 | [Details →](https://spiderrating.com/servers/tumf/web3-mcp) |
| [wishfinity-mcp-plusw](https://github.com/wishfinity/wishfinity-mcp-plusw) | 🟠 D | 5.1 | 7 | 0 | [Details →](https://spiderrating.com/servers/wishfinity/wishfinity-mcp-plusw) |
| [mcp-simple-timeserver](https://github.com/andybrandt/mcp-simple-timeserver) | 🟠 D | 5.0 | 6 | 6 | [Details →](https://spiderrating.com/servers/andybrandt/mcp-simple-timeserver) |
| [mcp-human](https://github.com/olalonde/mcp-human) | 🟠 D | 5.0 | 4 | 0 | [Details →](https://spiderrating.com/servers/olalonde/mcp-human) |
| [strava-mcp](https://github.com/kw510/strava-mcp) | 🟠 D | 4.9 | 37 | 0 | [Details →](https://spiderrating.com/servers/kw510/strava-mcp) |
| [foodblock](https://github.com/FoodXDevelopment/foodblock) | 🟠 D | 4.9 | 22 | 0 | [Details →](https://spiderrating.com/servers/FoodXDevelopment/foodblock) |
| [rae-mcp](https://github.com/rae-api-com/rae-mcp) | 🟠 D | 4.9 | 3 | 0 | [Details →](https://spiderrating.com/servers/rae-api-com/rae-mcp) |
| [shopify-storefront-mcp-server](https://github.com/QuentinCody/shopify-storefront-mcp-server) | 🟠 D | 4.7 | 2 | 1 | [Details →](https://spiderrating.com/servers/QuentinCody/shopify-storefront-mcp-server) |
| [notion-mcp](https://github.com/Badhansen/notion-mcp) | 🟠 D | 4.7 | 3 | 0 | [Details →](https://spiderrating.com/servers/Badhansen/notion-mcp) |
| [confluence-mcp-server](https://github.com/KS-GEN-AI/confluence-mcp-server) | 🟠 D | 4.7 | 3 | 0 | [Details →](https://spiderrating.com/servers/KS-GEN-AI/confluence-mcp-server) |
| [qrcode_mcp](https://github.com/2niuhe/qrcode_mcp) | 🟠 D | 4.7 | 1 | 0 | [Details →](https://spiderrating.com/servers/2niuhe/qrcode_mcp) |
| [vibe-check-mcp-server](https://github.com/PV-Bhat/vibe-check-mcp-server) | 🟠 D | 4.7 | 5 | 0 | [Details →](https://spiderrating.com/servers/PV-Bhat/vibe-check-mcp-server) |
| [mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) | 🟠 D | 4.7 | 2 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/isaacwasserman/mcp-vegalite-server) |
| [anki-mcp-desktop](https://github.com/anki-mcp/anki-mcp-desktop) | 🟠 D | 4.7 | 36 | 0 | [Details →](https://spiderrating.com/servers/anki-mcp/anki-mcp-desktop) |
| [mcp-obsidian](https://github.com/calclavia/mcp-obsidian) | 🟠 D | 4.6 | 2 | 0 | [Details →](https://spiderrating.com/servers/calclavia/mcp-obsidian) |
| [plugwise-mcp](https://github.com/Tommertom/plugwise-mcp) | 🟠 D | 4.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/Tommertom/plugwise-mcp) |
| [mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) | 🟠 D | 4.5 | 1 | 11 | [Details →](https://spiderrating.com/servers/MarkusPfundstein/mcp-obsidian) |
| [tiktok-mcp](https://github.com/Seym0n/tiktok-mcp) | 🟠 D | 4.5 | 3 | 0 | [Details →](https://spiderrating.com/servers/Seym0n/tiktok-mcp) |
| [jira-mcp-server](https://github.com/KS-GEN-AI/jira-mcp-server) | 🟠 D | 4.5 | 11 | 0 | [Details →](https://spiderrating.com/servers/KS-GEN-AI/jira-mcp-server) |
| [mcp-confluence-server](https://github.com/tqiqbal/mcp-confluence-server) | 🟠 D | 4.4 | 8 | 7 | [Details →](https://spiderrating.com/servers/tqiqbal/mcp-confluence-server) |
| [mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior) | 🔴 F | 4.4 | 3 | 3 (3 crit) | [Details →](https://spiderrating.com/servers/awwaiid/mcp-server-taskwarrior) |
| [bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp) | 🟠 D | 4.3 | 7 | 0 | [Details →](https://spiderrating.com/servers/AbdelStark/bitcoin-mcp) |
| [mac-apps-launcher](https://github.com/JoshuaRileyDev/mac-apps-launcher) | 🟠 D | 4.3 | 3 | 0 | [Details →](https://spiderrating.com/servers/JoshuaRileyDev/mac-apps-launcher) |
| [Yuque-MCP-Server](https://github.com/HenryHaoson/Yuque-MCP-Server) | 🟠 D | 4.1 | 14 | 0 | [Details →](https://spiderrating.com/servers/HenryHaoson/Yuque-MCP-Server) |
| [think-mcp](https://github.com/Rai220/think-mcp) | 🟠 D | 4.1 | 4 | 0 | [Details →](https://spiderrating.com/servers/Rai220/think-mcp) |
| [JotDown](https://github.com/Harry-027/JotDown) | 🟠 D | 4.1 | 5 | 0 | [Details →](https://spiderrating.com/servers/Harry-027/JotDown) |
| [actors-mcp-server](https://github.com/apify/actors-mcp-server) | 🟠 D | 4.0 | 11 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/apify/actors-mcp-server) |
| [ScreenPilot](https://github.com/Mtehabsim/ScreenPilot) | 🟠 D | 3.7 | 1 | 0 | [Details →](https://spiderrating.com/servers/Mtehabsim/ScreenPilot) |
| [screenpipe](https://github.com/mediar-ai/screenpipe) | 🔴 F | 3.3 | 19 | 21 (21 crit) | [Details →](https://spiderrating.com/servers/mediar-ai/screenpipe) |

## 🤖 Coding Agents (29 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [mcp_safe_local_python_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor) | 🟢 B | 7.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/maxim-saplin/mcp_safe_local_python_executor) |
| [codemcp](https://github.com/ezyang/codemcp) | 🟡 C | 6.7 | 12 | 0 | [Details →](https://spiderrating.com/servers/ezyang/codemcp) |
| [vscode-mcp-server](https://github.com/juehang/vscode-mcp-server) | 🟡 C | 6.4 | 12 | 0 | [Details →](https://spiderrating.com/servers/juehang/vscode-mcp-server) |
| [iterm-mcp](https://github.com/ferrislucas/iterm-mcp) | 🟡 C | 6.3 | 3 | 0 | [Details →](https://spiderrating.com/servers/ferrislucas/iterm-mcp) |
| [ssh-mcp](https://github.com/tufantunc/ssh-mcp) | 🟡 C | 6.2 | 2 | 0 | [Details →](https://spiderrating.com/servers/tufantunc/ssh-mcp) |
| [mcp-rubber-duck](https://github.com/nesquikm/mcp-rubber-duck) | 🟠 D | 6.1 | 39 | 0 | [Details →](https://spiderrating.com/servers/nesquikm/mcp-rubber-duck) |
| [DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) | 🔴 F | 6.1 | 26 | 9 (9 crit) | [Details →](https://spiderrating.com/servers/wonderwhy-er/DesktopCommanderMCP) |
| [owlex](https://github.com/agentic-mcp-tools/owlex) | 🟡 C | 6.0 | 15 | 3 | [Details →](https://spiderrating.com/servers/agentic-mcp-tools/owlex) |
| [pyATS_MCP](https://github.com/automateyournetwork/pyATS_MCP) | 🟡 C | 5.9 | 8 | 7 | [Details →](https://spiderrating.com/servers/automateyournetwork/pyATS_MCP) |
| [leetcode-mcp-server](https://github.com/jinzcdev/leetcode-mcp-server) | 🟡 C | 5.9 | 17 | 0 | [Details →](https://spiderrating.com/servers/jinzcdev/leetcode-mcp-server) |
| [MaxMSP-MCP-Server](https://github.com/tiianhk/MaxMSP-MCP-Server) | 🟡 C | 5.9 | 15 | 3 | [Details →](https://spiderrating.com/servers/tiianhk/MaxMSP-MCP-Server) |
| [terminator](https://github.com/mediar-ai/terminator) | 🔴 F | 5.9 | 31 | 9 (9 crit) | [Details →](https://spiderrating.com/servers/mediar-ai/terminator) |
| [mcp-shell](https://github.com/sonirico/mcp-shell) | 🟡 C | 5.8 | 1 | 0 | [Details →](https://spiderrating.com/servers/sonirico/mcp-shell) |
| [openclaw-mcp](https://github.com/freema/openclaw-mcp) | 🟡 C | 5.8 | 6 | 0 | [Details →](https://spiderrating.com/servers/freema/openclaw-mcp) |
| [arch-mcp](https://github.com/nihalxkumar/arch-mcp) | 🟠 D | 5.8 | 22 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/nihalxkumar/arch-mcp) |
| [mcp-server-commands](https://github.com/g0t4/mcp-server-commands) | 🟠 D | 5.7 | 1 | 0 | [Details →](https://spiderrating.com/servers/g0t4/mcp-server-commands) |
| [codex-mcp-tool](https://github.com/x51xxx/codex-mcp-tool) | 🟡 C | 5.7 | 16 | 0 | [Details →](https://spiderrating.com/servers/x51xxx/codex-mcp-tool) |
| [Blind-Auditor](https://github.com/Sim-xia/Blind-Auditor) | 🟡 C | 5.6 | 4 | 1 | [Details →](https://spiderrating.com/servers/Sim-xia/Blind-Auditor) |
| [any-cli-mcp-server](https://github.com/eirikb/any-cli-mcp-server) | 🟡 C | 5.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/eirikb/any-cli-mcp-server) |
| [kill-process-mcp](https://github.com/misiektoja/kill-process-mcp) | 🟠 D | 5.5 | 2 | 0 | [Details →](https://spiderrating.com/servers/misiektoja/kill-process-mcp) |
| [developer](https://github.com/VertexStudio/developer) | 🟡 C | 5.2 | 6 | 0 | [Details →](https://spiderrating.com/servers/VertexStudio/developer) |
| [persistproc](https://github.com/irskep/persistproc) | 🟡 C | 5.2 | 3 | 2 | [Details →](https://spiderrating.com/servers/irskep/persistproc) |
| [copilot-mcp-server](https://github.com/x51xxx/copilot-mcp-server) | 🟠 D | 5.2 | 16 | 0 | [Details →](https://spiderrating.com/servers/x51xxx/copilot-mcp-server) |
| [ssh-mcp](https://github.com/blakerouse/ssh-mcp) | 🟠 D | 5.0 | 10 | 0 | [Details →](https://spiderrating.com/servers/blakerouse/ssh-mcp) |
| [mcp_creator_growth](https://github.com/SunflowersLwtech/mcp_creator_growth) | 🟠 D | 4.9 | 4 | 0 | [Details →](https://spiderrating.com/servers/SunflowersLwtech/mcp_creator_growth) |
| [skill-cortex-server](https://github.com/Sim-xia/skill-cortex-server) | 🟠 D | 4.8 | 3 | 0 | [Details →](https://spiderrating.com/servers/Sim-xia/skill-cortex-server) |
| [Agent-MCP](https://github.com/rinadelph/Agent-MCP) | 🔴 F | 4.8 | 35 | 24 (23 crit) | [Details →](https://spiderrating.com/servers/rinadelph/Agent-MCP) |
| [llm-council](https://github.com/elhamid/llm-council) | 🟠 D | 4.7 | 4 | 1 | [Details →](https://spiderrating.com/servers/elhamid/llm-council) |
| [mcp-console-automation](https://github.com/ooples/mcp-console-automation) | 🔴 F | 4.4 | 102 | 9 (9 crit) | [Details →](https://spiderrating.com/servers/ooples/mcp-console-automation) |

## 🧠 Knowledge & Memory (62 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [RAGStack-Lambda](https://github.com/HatmanStack/RAGStack-Lambda) | 🟢 B | 7.0 | 15 | 7 | [Details →](https://spiderrating.com/servers/HatmanStack/RAGStack-Lambda) |
| [mediawiki-mcp-server](https://github.com/olgasafonova/mediawiki-mcp-server) | 🟢 B | 7.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/olgasafonova/mediawiki-mcp-server) |
| [memorylane](https://github.com/deusXmachina-dev/memorylane) | 🟡 C | 6.2 | 7 | 0 | [Details →](https://spiderrating.com/servers/deusXmachina-dev/memorylane) |
| [evc-team-relay-mcp](https://github.com/entire-vc/evc-team-relay-mcp) | 🟡 C | 6.2 | 8 | 5 | [Details →](https://spiderrating.com/servers/entire-vc/evc-team-relay-mcp) |
| [lotus-wisdom-mcp](https://github.com/linxule/lotus-wisdom-mcp) | 🟡 C | 6.0 | 2 | 0 | [Details →](https://spiderrating.com/servers/linxule/lotus-wisdom-mcp) |
| [mcp-local-rag](https://github.com/shinpr/mcp-local-rag) | 🟡 C | 6.0 | 6 | 0 | [Details →](https://spiderrating.com/servers/shinpr/mcp-local-rag) |
| [In-Memoria](https://github.com/pi22by7/In-Memoria) | 🟡 C | 6.0 | 19 | 0 | [Details →](https://spiderrating.com/servers/pi22by7/In-Memoria) |
| [MCP-Context-Provider](https://github.com/doobidoo/MCP-Context-Provider) | 🟡 C | 6.0 | 6 | 0 | [Details →](https://spiderrating.com/servers/doobidoo/MCP-Context-Provider) |
| [engram-rs](https://github.com/kael-bit/engram-rs) | 🟡 C | 6.0 | 16 | 0 | [Details →](https://spiderrating.com/servers/kael-bit/engram-rs) |
| [graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server) | 🟠 D | 6.0 | 73 | 0 | [Details →](https://spiderrating.com/servers/graphlit/graphlit-mcp-server) |
| [markmap-mcp-server](https://github.com/jinzcdev/markmap-mcp-server) | 🟡 C | 6.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/jinzcdev/markmap-mcp-server) |
| [mem0-mcp](https://github.com/mem0ai/mem0-mcp) | 🟡 C | 5.9 | 9 | 0 | [Details →](https://spiderrating.com/servers/mem0ai/mem0-mcp) |
| [AuraSDK](https://github.com/teolex2020/AuraSDK) | 🟡 C | 5.9 | 10 | 0 | [Details →](https://spiderrating.com/servers/teolex2020/AuraSDK) |
| [gistpad-mcp](https://github.com/lostintangent/gistpad-mcp) | 🟠 D | 5.8 | 30 | 0 | [Details →](https://spiderrating.com/servers/lostintangent/gistpad-mcp) |
| [hindsight](https://github.com/vectorize-io/hindsight) | 🔴 F | 5.8 | 52 | 291 (291 crit) | [Details →](https://spiderrating.com/servers/vectorize-io/hindsight) |
| [project-tessera](https://github.com/besslframework-stack/project-tessera) | 🟡 C | 5.8 | 2 | 1 | [Details →](https://spiderrating.com/servers/besslframework-stack/project-tessera) |
| [mcp-zotero](https://github.com/kaliaboi/mcp-zotero) | 🟡 C | 5.8 | 5 | 0 | [Details →](https://spiderrating.com/servers/kaliaboi/mcp-zotero) |
| [idapixl-web-research-mcp](https://github.com/idapixl/idapixl-web-research-mcp) | 🟡 C | 5.7 | 3 | 0 | [Details →](https://spiderrating.com/servers/idapixl/idapixl-web-research-mcp) |
| [mcp-persona-sessions](https://github.com/mattjoyce/mcp-persona-sessions) | 🟡 C | 5.7 | 9 | 0 | [Details →](https://spiderrating.com/servers/mattjoyce/mcp-persona-sessions) |
| [mcp-ragdocs](https://github.com/hannesrudolph/mcp-ragdocs) | 🟡 C | 5.6 | 7 | 0 | [Details →](https://spiderrating.com/servers/hannesrudolph/mcp-ragdocs) |
| [devrag](https://github.com/tomohiro-owada/devrag) | 🟠 D | 5.6 | 10 | 0 | [Details →](https://spiderrating.com/servers/tomohiro-owada/devrag) |
| [easy-obsidian-mcp](https://github.com/louis030195/easy-obsidian-mcp) | 🟡 C | 5.6 | 7 | 0 | [Details →](https://spiderrating.com/servers/louis030195/easy-obsidian-mcp) |
| [context-awesome](https://github.com/bh-rat/context-awesome) | 🟡 C | 5.5 | 2 | 0 | [Details →](https://spiderrating.com/servers/bh-rat/context-awesome) |
| [shodh-memory](https://github.com/varun29ankuS/shodh-memory) | 🟠 D | 5.5 | 59 | 4 (2 crit) | [Details →](https://spiderrating.com/servers/varun29ankuS/shodh-memory) |
| [mini_claude](https://github.com/20alexl/mini_claude) | 🟡 C | 5.5 | 20 | 0 | [Details →](https://spiderrating.com/servers/20alexl/mini_claude) |
| [mcp-server-chatsum](https://github.com/chatmcp/mcp-server-chatsum) | 🟡 C | 5.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/chatmcp/mcp-server-chatsum) |
| [obsidian-mcp-server](https://github.com/smith-and-web/obsidian-mcp-server) | 🟡 C | 5.5 | 31 | 1 | [Details →](https://spiderrating.com/servers/smith-and-web/obsidian-mcp-server) |
| [conversation-handoff-mcp](https://github.com/trust-delta/conversation-handoff-mcp) | 🟡 C | 5.5 | 8 | 0 | [Details →](https://spiderrating.com/servers/trust-delta/conversation-handoff-mcp) |
| [local_faiss_mcp](https://github.com/nonatofabio/local_faiss_mcp) | 🟠 D | 5.4 | 2 | 0 | [Details →](https://spiderrating.com/servers/nonatofabio/local_faiss_mcp) |
| [context-keeper](https://github.com/redleaves/context-keeper) | 🟠 D | 5.4 | 11 | 0 | [Details →](https://spiderrating.com/servers/redleaves/context-keeper) |
| [CodeCortex](https://github.com/rushikeshmore/CodeCortex) | 🟠 D | 5.4 | 14 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/rushikeshmore/CodeCortex) |
| [mendeley-mcp](https://github.com/pallaprolus/mendeley-mcp) | 🟡 C | 5.3 | 7 | 2 | [Details →](https://spiderrating.com/servers/pallaprolus/mendeley-mcp) |
| [context-mcp](https://github.com/dodopayments/context-mcp) | 🔴 F | 5.1 | 2 | 5 (5 crit) | [Details →](https://spiderrating.com/servers/dodopayments/context-mcp) |
| [legends-mcp](https://github.com/cryptosquanch/legends-mcp) | 🟡 C | 5.1 | 8 | 0 | [Details →](https://spiderrating.com/servers/cryptosquanch/legends-mcp) |
| [membase-mcp](https://github.com/unibaseio/membase-mcp) | 🟡 C | 5.1 | 4 | 2 | [Details →](https://spiderrating.com/servers/unibaseio/membase-mcp) |
| [CacheOverflow](https://github.com/GetCacheOverflow/CacheOverflow) | 🟡 C | 5.0 | 5 | 0 | [Details →](https://spiderrating.com/servers/GetCacheOverflow/CacheOverflow) |
| [cognee](https://github.com/topoteretes/cognee) | 🔴 F | 5.0 | 1 | 6 (6 crit) | [Details →](https://spiderrating.com/servers/topoteretes/cognee) |
| [mcp-memory-service](https://github.com/doobidoo/mcp-memory-service) | 🔴 F | 5.0 | 23 | 22 (19 crit) | [Details →](https://spiderrating.com/servers/doobidoo/mcp-memory-service) |
| [algora-mcp-server](https://github.com/idapixl/algora-mcp-server) | 🟠 D | 5.0 | 5 | 0 | [Details →](https://spiderrating.com/servers/idapixl/algora-mcp-server) |
| [memora](https://github.com/agentic-mcp-tools/memora) | 🔴 F | 4.9 | 35 | 7 (7 crit) | [Details →](https://spiderrating.com/servers/agentic-mcp-tools/memora) |
| [agentkits-memory](https://github.com/aitytech/agentkits-memory) | 🟠 D | 4.9 | 10 | 4 (2 crit) | [Details →](https://spiderrating.com/servers/aitytech/agentkits-memory) |
| [gnosis-mcp](https://github.com/nicholasglazer/gnosis-mcp) | 🔴 F | 4.9 | 7 | 8 (5 crit) | [Details →](https://spiderrating.com/servers/nicholasglazer/gnosis-mcp) |
| [remembra](https://github.com/remembra-ai/remembra) | 🔴 F | 4.8 | 11 | 7 (7 crit) | [Details →](https://spiderrating.com/servers/remembra-ai/remembra) |
| [lennys-quotes](https://github.com/bluzername/lennys-quotes) | 🟠 D | 4.8 | 5 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/bluzername/lennys-quotes) |
| [notebooklm-mcp-secure](https://github.com/Pantheon-Security/notebooklm-mcp-secure) | 🟠 D | 4.7 | 76 | 0 | [Details →](https://spiderrating.com/servers/Pantheon-Security/notebooklm-mcp-secure) |
| [tilde](https://github.com/topskychen/tilde) | 🟠 D | 4.7 | 4 | 0 | [Details →](https://spiderrating.com/servers/topskychen/tilde) |
| [mengram](https://github.com/alibaizhanov/mengram) | 🔴 F | 4.7 | 31 | 12 (12 crit) | [Details →](https://spiderrating.com/servers/alibaizhanov/mengram) |
| [simplemem](https://github.com/jcdickinson/simplemem) | 🟠 D | 4.7 | 8 | 0 | [Details →](https://spiderrating.com/servers/jcdickinson/simplemem) |
| [context-memory](https://github.com/ErebusEnigma/context-memory) | 🟠 D | 4.7 | 6 | 0 | [Details →](https://spiderrating.com/servers/ErebusEnigma/context-memory) |
| [Arthor-Agent](https://github.com/arthurpanhku/Arthor-Agent) | 🟠 D | 4.7 | 2 | 2 | [Details →](https://spiderrating.com/servers/arthurpanhku/Arthor-Agent) |
| [cogmemai-mcp](https://github.com/hifriendbot/cogmemai-mcp) | 🔴 F | 4.6 | 30 | 4 (4 crit) | [Details →](https://spiderrating.com/servers/hifriendbot/cogmemai-mcp) |
| [memorix](https://github.com/AVIDS2/memorix) | 🟠 D | 4.5 | 45 | 0 | [Details →](https://spiderrating.com/servers/AVIDS2/memorix) |
| [counsel-mcp](https://github.com/mercurialsolo/counsel-mcp) | 🟠 D | 4.5 | 19 | 4 (1 crit) | [Details →](https://spiderrating.com/servers/mercurialsolo/counsel-mcp) |
| [MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) | 🟠 D | 4.5 | 11 | 0 | [Details →](https://spiderrating.com/servers/CheMiguel23/MemoryMesh) |
| [memory-mcp-1file](https://github.com/pomazanbohdan/memory-mcp-1file) | 🔴 F | 4.5 | 19 | 3 (3 crit) | [Details →](https://spiderrating.com/servers/pomazanbohdan/memory-mcp-1file) |
| [memory-mcp](https://github.com/JamesANZ/memory-mcp) | 🟠 D | 4.5 | 10 | 0 | [Details →](https://spiderrating.com/servers/JamesANZ/memory-mcp) |
| [memory-mcp](https://github.com/michael-denyer/memory-mcp) | 🔴 F | 4.5 | 56 | 9 (9 crit) | [Details →](https://spiderrating.com/servers/michael-denyer/memory-mcp) |
| [agent-memory](https://github.com/g1itchbot8888-del/agent-memory) | 🔴 F | 4.4 | 15 | 16 (9 crit) | [Details →](https://spiderrating.com/servers/g1itchbot8888-del/agent-memory) |
| [mnemo-mcp](https://github.com/n24q02m/mnemo-mcp) | 🔴 F | 4.4 | 1 | 5 (5 crit) | [Details →](https://spiderrating.com/servers/n24q02m/mnemo-mcp) |
| [mcp-obsidian](https://github.com/bitbonsai/mcp-obsidian) | 🟠 D | 4.3 | 14 | 0 | [Details →](https://spiderrating.com/servers/bitbonsai/mcp-obsidian) |
| [cross-llm-mcp](https://github.com/JamesANZ/cross-llm-mcp) | 🟠 D | 4.2 | 60 | 0 | [Details →](https://spiderrating.com/servers/JamesANZ/cross-llm-mcp) |
| [empathy-framework](https://github.com/Smart-AI-Memory/empathy-framework) | 🟠 D | 3.7 | 7 | 0 | [Details →](https://spiderrating.com/servers/Smart-AI-Memory/empathy-framework) |

## 🧮 Data Science Tools (13 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [optuna-mcp](https://github.com/optuna/optuna-mcp) | 🟡 C | 6.9 | 11 | 1 | [Details →](https://spiderrating.com/servers/optuna/optuna-mcp) |
| [growthbook-mcp](https://github.com/growthbook/growthbook-mcp) | 🟠 D | 6.5 | 18 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/growthbook/growthbook-mcp) |
| [markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) | 🟡 C | 6.3 | 11 | 0 | [Details →](https://spiderrating.com/servers/zcaceres/markdownify-mcp) |
| [kaggle-mcp](https://github.com/arrismo/kaggle-mcp) | 🟡 C | 6.0 | 2 | 2 | [Details →](https://spiderrating.com/servers/arrismo/kaggle-mcp) |
| [vizro](https://github.com/mckinsey/vizro) | 🟡 C | 6.0 | 5 | 7 | [Details →](https://spiderrating.com/servers/mckinsey/vizro) |
| [math-mcp-learning-server](https://github.com/clouatre-labs/math-mcp-learning-server) | 🟠 D | 5.9 | 18 | 0 | [Details →](https://spiderrating.com/servers/clouatre-labs/math-mcp-learning-server) |
| [kaggle-mcp-server](https://github.com/KrishnaPramodParupudi/kaggle-mcp-server) | 🟡 C | 5.7 | 11 | 3 | [Details →](https://spiderrating.com/servers/KrishnaPramodParupudi/kaggle-mcp-server) |
| [stella-mcp](https://github.com/bradleylab/stella-mcp) | 🟡 C | 5.5 | 10 | 0 | [Details →](https://spiderrating.com/servers/bradleylab/stella-mcp) |
| [jupyter-notebook-mcp](https://github.com/jjsantos01/jupyter-notebook-mcp) | 🟠 D | 5.2 | 11 | 1 | [Details →](https://spiderrating.com/servers/jjsantos01/jupyter-notebook-mcp) |
| [calculator-server](https://github.com/avisangle/calculator-server) | 🟠 D | 4.5 | 13 | 0 | [Details →](https://spiderrating.com/servers/avisangle/calculator-server) |
| [renoun-mcp](https://github.com/98lukehall/renoun-mcp) | 🟠 D | 4.4 | 4 | 1 | [Details →](https://spiderrating.com/servers/98lukehall/renoun-mcp) |
| [code-guardian](https://github.com/phuongrealmax/code-guardian) | 🟠 D | 4.4 | 211 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/phuongrealmax/code-guardian) |
| [dingo](https://github.com/DataEval/dingo) | 🟠 D | 4.4 | 7 | 3 (1 crit) | [Details →](https://spiderrating.com/servers/DataEval/dingo) |

## Other (143 servers)

| Server | Grade | Score | Tools | Issues | Report |
|--------|-------|-------|-------|--------|--------|
| [metamcp](https://github.com/metatool-ai/metamcp) | 🟢 B | 7.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/metatool-ai/metamcp) |
| [firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) | 🟢 B | 7.4 | 12 | 0 | [Details →](https://spiderrating.com/servers/firecrawl/firecrawl-mcp-server) |
| [paperdebugger](https://github.com/PaperDebugger/paperdebugger) | 🟡 C | 6.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/PaperDebugger/paperdebugger) |
| [agentkit](https://github.com/coinbase/agentkit) | 🟡 C | 6.9 | 102 | 0 | [Details →](https://spiderrating.com/servers/coinbase/agentkit) |
| [PPTAgent](https://github.com/icip-cas/PPTAgent) | 🟡 C | 6.9 | 24 | 11 | [Details →](https://spiderrating.com/servers/icip-cas/PPTAgent) |
| [azure-devops-mcp](https://github.com/microsoft/azure-devops-mcp) | 🟡 C | 6.8 | 1 | 0 | [Details →](https://spiderrating.com/servers/microsoft/azure-devops-mcp) |
| [code-graph-rag](https://github.com/vitali87/code-graph-rag) | 🟡 C | 6.8 | 10 | 0 | [Details →](https://spiderrating.com/servers/vitali87/code-graph-rag) |
| [macos-automator-mcp](https://github.com/steipete/macos-automator-mcp) | 🟡 C | 6.8 | 2 | 0 | [Details →](https://spiderrating.com/servers/steipete/macos-automator-mcp) |
| [kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) | 🟠 D | 6.7 | 30 | 0 | [Details →](https://spiderrating.com/servers/containers/kubernetes-mcp-server) |
| [freecad-mcp](https://github.com/neka-nat/freecad-mcp) | 🟡 C | 6.7 | 11 | 6 | [Details →](https://spiderrating.com/servers/neka-nat/freecad-mcp) |
| [datagouv-mcp](https://github.com/datagouv/datagouv-mcp) | 🟡 C | 6.7 | 9 | 6 | [Details →](https://spiderrating.com/servers/datagouv/datagouv-mcp) |
| [mcp-for-security](https://github.com/cyproxio/mcp-for-security) | 🟡 C | 6.6 | 32 | 0 | [Details →](https://spiderrating.com/servers/cyproxio/mcp-for-security) |
| [enrichmcp](https://github.com/featureform/enrichmcp) | 🟠 D | 6.6 | 1 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/featureform/enrichmcp) |
| [mcp-openapi-server](https://github.com/ivo-toby/mcp-openapi-server) | 🟡 C | 6.6 | 3 | 0 | [Details →](https://spiderrating.com/servers/ivo-toby/mcp-openapi-server) |
| [runno](https://github.com/taybenlor/runno) | 🟡 C | 6.6 | 2 | 0 | [Details →](https://spiderrating.com/servers/taybenlor/runno) |
| [typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk) | 🟠 D | 6.6 | 16 | 0 | [Details →](https://spiderrating.com/servers/modelcontextprotocol/typescript-sdk) |
| [agent-scan](https://github.com/snyk/agent-scan) | 🟡 C | 6.5 | 10 | 2 | [Details →](https://spiderrating.com/servers/snyk/agent-scan) |
| [Windows-MCP](https://github.com/CursorTouch/Windows-MCP) | 🟡 C | 6.5 | 15 | 2 | [Details →](https://spiderrating.com/servers/CursorTouch/Windows-MCP) |
| [notebooklm-mcp](https://github.com/PleasePrompto/notebooklm-mcp) | 🟡 C | 6.5 | 16 | 0 | [Details →](https://spiderrating.com/servers/PleasePrompto/notebooklm-mcp) |
| [nuxt-mcp-dev](https://github.com/antfu/nuxt-mcp-dev) | 🟡 C | 6.5 | 7 | 0 | [Details →](https://spiderrating.com/servers/antfu/nuxt-mcp-dev) |
| [mcp-server](https://github.com/e2b-dev/mcp-server) | 🟡 C | 6.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/e2b-dev/mcp-server) |
| [mcp-server-datadog](https://github.com/winor30/mcp-server-datadog) | 🟡 C | 6.5 | 2 | 1 | [Details →](https://spiderrating.com/servers/winor30/mcp-server-datadog) |
| [gcloud-mcp](https://github.com/googleapis/gcloud-mcp) | 🟠 D | 6.5 | 61 | 0 | [Details →](https://spiderrating.com/servers/googleapis/gcloud-mcp) |
| [bifrost](https://github.com/maximhq/bifrost) | 🟠 D | 6.5 | 57 | 0 | [Details →](https://spiderrating.com/servers/maximhq/bifrost) |
| [elevenlabs-mcp](https://github.com/elevenlabs/elevenlabs-mcp) | 🟠 D | 6.5 | 18 | 0 | [Details →](https://spiderrating.com/servers/elevenlabs/elevenlabs-mcp) |
| [MCP](https://github.com/jina-ai/MCP) | 🟡 C | 6.5 | 21 | 0 | [Details →](https://spiderrating.com/servers/jina-ai/MCP) |
| [mcp-framework](https://github.com/QuantGeekDev/mcp-framework) | 🟡 C | 6.4 | 3 | 0 | [Details →](https://spiderrating.com/servers/QuantGeekDev/mcp-framework) |
| [brightdata-mcp](https://github.com/brightdata/brightdata-mcp) | 🟠 D | 6.4 | 20 | 0 | [Details →](https://spiderrating.com/servers/brightdata/brightdata-mcp) |
| [mcp-server](https://github.com/mapbox/mcp-server) | 🟠 D | 6.4 | 9 | 0 | [Details →](https://spiderrating.com/servers/mapbox/mcp-server) |
| [ext-apps](https://github.com/modelcontextprotocol/ext-apps) | 🟠 D | 6.4 | 5 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/modelcontextprotocol/ext-apps) |
| [gitlab-mcp](https://github.com/zereight/gitlab-mcp) | 🟠 D | 6.4 | 108 | 0 | [Details →](https://spiderrating.com/servers/zereight/gitlab-mcp) |
| [ruflo](https://github.com/ruvnet/ruflo) | 🟠 D | 6.4 | 1268 | 0 | [Details →](https://spiderrating.com/servers/ruvnet/ruflo) |
| [mcp-use](https://github.com/mcp-use/mcp-use) | 🟠 D | 6.4 | 141 | 0 | [Details →](https://spiderrating.com/servers/mcp-use/mcp-use) |
| [mcp-server](https://github.com/browserstack/mcp-server) | 🟡 C | 6.4 | 30 | 0 | [Details →](https://spiderrating.com/servers/browserstack/mcp-server) |
| [docs-mcp-server](https://github.com/arabold/docs-mcp-server) | 🟡 C | 6.3 | 10 | 0 | [Details →](https://spiderrating.com/servers/arabold/docs-mcp-server) |
| [trigger.dev](https://github.com/triggerdotdev/trigger.dev) | 🟠 D | 6.3 | 80 | 0 | [Details →](https://spiderrating.com/servers/triggerdotdev/trigger.dev) |
| [ha-mcp](https://github.com/homeassistant-ai/ha-mcp) | 🟠 D | 6.3 | 8 | 1 | [Details →](https://spiderrating.com/servers/homeassistant-ai/ha-mcp) |
| [ros-mcp-server](https://github.com/robotmcp/ros-mcp-server) | 🟠 D | 6.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/robotmcp/ros-mcp-server) |
| [deep-research](https://github.com/u14app/deep-research) | 🟠 D | 6.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/u14app/deep-research) |
| [heroku-mcp-server](https://github.com/heroku/heroku-mcp-server) | 🟠 D | 6.3 | 36 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/heroku/heroku-mcp-server) |
| [yargi-mcp](https://github.com/saidsurucu/yargi-mcp) | 🟡 C | 6.3 | 41 | 0 | [Details →](https://spiderrating.com/servers/saidsurucu/yargi-mcp) |
| [archestra](https://github.com/archestra-ai/archestra) | 🟠 D | 6.3 | 8 | 0 | [Details →](https://spiderrating.com/servers/archestra-ai/archestra) |
| [payload](https://github.com/payloadcms/payload) | 🟠 D | 6.3 | 61 | 1 | [Details →](https://spiderrating.com/servers/payloadcms/payload) |
| [mcp-server](https://github.com/launchdarkly/mcp-server) | 🟡 C | 6.2 | 19 | 0 | [Details →](https://spiderrating.com/servers/launchdarkly/mcp-server) |
| [inspector](https://github.com/MCPJam/inspector) | 🟠 D | 6.2 | 7 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/MCPJam/inspector) |
| [core](https://github.com/opensumi/core) | 🟠 D | 6.2 | 24 | 0 | [Details →](https://spiderrating.com/servers/opensumi/core) |
| [arcade-mcp](https://github.com/ArcadeAI/arcade-mcp) | 🟠 D | 6.2 | 27 | 1 | [Details →](https://spiderrating.com/servers/ArcadeAI/arcade-mcp) |
| [esa-mcp-server](https://github.com/esaio/esa-mcp-server) | 🟡 C | 6.2 | 25 | 0 | [Details →](https://spiderrating.com/servers/esaio/esa-mcp-server) |
| [apple-docs-mcp](https://github.com/kimsungwhee/apple-docs-mcp) | 🟡 C | 6.2 | 18 | 0 | [Details →](https://spiderrating.com/servers/kimsungwhee/apple-docs-mcp) |
| [Office-PowerPoint-MCP-Server](https://github.com/GongRzhe/Office-PowerPoint-MCP-Server) | 🟡 C | 6.2 | 3 | 1 | [Details →](https://spiderrating.com/servers/GongRzhe/Office-PowerPoint-MCP-Server) |
| [mcptools](https://github.com/f/mcptools) | 🟠 D | 6.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/f/mcptools) |
| [esp32_nat_router](https://github.com/martin-ger/esp32_nat_router) | 🟡 C | 6.2 | 35 | 12 | [Details →](https://spiderrating.com/servers/martin-ger/esp32_nat_router) |
| [mcp-router](https://github.com/mcp-router/mcp-router) | 🟠 D | 6.2 | 4 | 0 | [Details →](https://spiderrating.com/servers/mcp-router/mcp-router) |
| [go-sdk](https://github.com/modelcontextprotocol/go-sdk) | 🟠 D | 6.2 | 35 | 0 | [Details →](https://spiderrating.com/servers/modelcontextprotocol/go-sdk) |
| [regle](https://github.com/victorgarciaesgi/regle) | 🟠 D | 6.2 | 3 | 0 | [Details →](https://spiderrating.com/servers/victorgarciaesgi/regle) |
| [jcodemunch-mcp](https://github.com/jgravelle/jcodemunch-mcp) | 🟡 C | 6.2 | 14 | 1 | [Details →](https://spiderrating.com/servers/jgravelle/jcodemunch-mcp) |
| [spec-workflow-mcp](https://github.com/Pimzino/spec-workflow-mcp) | 🟡 C | 6.2 | 19 | 0 | [Details →](https://spiderrating.com/servers/Pimzino/spec-workflow-mcp) |
| [fastmcp](https://github.com/PrefectHQ/fastmcp) | 🟠 D | 6.2 | 97 | 10 | [Details →](https://spiderrating.com/servers/PrefectHQ/fastmcp) |
| [open-ux-tools](https://github.com/SAP/open-ux-tools) | 🟠 D | 6.2 | 14 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/SAP/open-ux-tools) |
| [openapi-mcp-server](https://github.com/janwilmake/openapi-mcp-server) | 🟡 C | 6.2 | 3 | 0 | [Details →](https://spiderrating.com/servers/janwilmake/openapi-mcp-server) |
| [ai-trader](https://github.com/whchien/ai-trader) | 🟡 C | 6.2 | 4 | 0 | [Details →](https://spiderrating.com/servers/whchien/ai-trader) |
| [agentset](https://github.com/agentset-ai/agentset) | 🟠 D | 6.1 | 3 | 0 | [Details →](https://spiderrating.com/servers/agentset-ai/agentset) |
| [concierge](https://github.com/concierge-hq/concierge) | 🟡 C | 6.1 | 17 | 4 | [Details →](https://spiderrating.com/servers/concierge-hq/concierge) |
| [mcp-server](https://github.com/UI5/mcp-server) | 🟠 D | 6.1 | 10 | 0 | [Details →](https://spiderrating.com/servers/UI5/mcp-server) |
| [mcpb](https://github.com/modelcontextprotocol/mcpb) | 🟠 D | 6.1 | 15 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/modelcontextprotocol/mcpb) |
| [python-sdk](https://github.com/modelcontextprotocol/python-sdk) | 🟠 D | 6.0 | 66 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/modelcontextprotocol/python-sdk) |
| [mcp-server](https://github.com/financial-datasets/mcp-server) | 🟡 C | 6.0 | 11 | 3 | [Details →](https://spiderrating.com/servers/financial-datasets/mcp-server) |
| [apify-mcp-server](https://github.com/apify/apify-mcp-server) | 🟠 D | 6.0 | 11 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/apify/apify-mcp-server) |
| [mcp-mem0](https://github.com/coleam00/mcp-mem0) | 🟡 C | 6.0 | 3 | 2 | [Details →](https://spiderrating.com/servers/coleam00/mcp-mem0) |
| [XcodeBuildMCP](https://github.com/getsentry/XcodeBuildMCP) | 🟠 D | 6.0 | 5 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/getsentry/XcodeBuildMCP) |
| [modelcontextprotocol](https://github.com/perplexityai/modelcontextprotocol) | 🟠 D | 6.0 | 4 | 0 | [Details →](https://spiderrating.com/servers/perplexityai/modelcontextprotocol) |
| [passage-of-time-mcp](https://github.com/jlumbroso/passage-of-time-mcp) | 🟡 C | 6.0 | 7 | 0 | [Details →](https://spiderrating.com/servers/jlumbroso/passage-of-time-mcp) |
| [mem-agent-mcp](https://github.com/firstbatchxyz/mem-agent-mcp) | 🟠 D | 6.0 | 1 | 10 (2 crit) | [Details →](https://spiderrating.com/servers/firstbatchxyz/mem-agent-mcp) |
| [toolhive](https://github.com/stacklok/toolhive) | 🟡 C | 6.0 | 8 | 0 | [Details →](https://spiderrating.com/servers/stacklok/toolhive) |
| [railway-mcp-server](https://github.com/railwayapp/railway-mcp-server) | 🟡 C | 6.0 | 14 | 0 | [Details →](https://spiderrating.com/servers/railwayapp/railway-mcp-server) |
| [obsidian-mcp](https://github.com/StevenStavrakis/obsidian-mcp) | 🟡 C | 6.0 | 13 | 0 | [Details →](https://spiderrating.com/servers/StevenStavrakis/obsidian-mcp) |
| [gemini-mcp-tool](https://github.com/jamubc/gemini-mcp-tool) | 🟠 D | 6.0 | 9 | 0 | [Details →](https://spiderrating.com/servers/jamubc/gemini-mcp-tool) |
| [mongodb-mcp-server](https://github.com/mongodb-js/mongodb-mcp-server) | 🟡 C | 6.0 | 3 | 2 | [Details →](https://spiderrating.com/servers/mongodb-js/mongodb-mcp-server) |
| [golf](https://github.com/golf-mcp/golf) | 🟠 D | 5.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/golf-mcp/golf) |
| [unreal-mcp](https://github.com/chongdashu/unreal-mcp) | 🟡 C | 5.9 | 30 | 3 | [Details →](https://spiderrating.com/servers/chongdashu/unreal-mcp) |
| [mcp](https://github.com/hyperbrowserai/mcp) | 🟠 D | 5.9 | 10 | 0 | [Details →](https://spiderrating.com/servers/hyperbrowserai/mcp) |
| [n8n-mcp-server](https://github.com/leonardsellem/n8n-mcp-server) | 🟠 D | 5.9 | 11 | 0 | [Details →](https://spiderrating.com/servers/leonardsellem/n8n-mcp-server) |
| [cclsp](https://github.com/ktnyt/cclsp) | 🟠 D | 5.9 | 29 | 0 | [Details →](https://spiderrating.com/servers/ktnyt/cclsp) |
| [deepwiki-mcp](https://github.com/regenrek/deepwiki-mcp) | 🟠 D | 5.9 | 3 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/regenrek/deepwiki-mcp) |
| [mcp-bench](https://github.com/Accenture/mcp-bench) | 🔴 F | 5.8 | 265 | 137 (8 crit) | [Details →](https://spiderrating.com/servers/Accenture/mcp-bench) |
| [mcp-boilerplate](https://github.com/iannuttall/mcp-boilerplate) | 🟠 D | 5.8 | 3 | 0 | [Details →](https://spiderrating.com/servers/iannuttall/mcp-boilerplate) |
| [zenfeed](https://github.com/glidea/zenfeed) | 🟡 C | 5.8 | 7 | 0 | [Details →](https://spiderrating.com/servers/glidea/zenfeed) |
| [puppeteer-mcp-server](https://github.com/merajmehrabi/puppeteer-mcp-server) | 🟡 C | 5.8 | 8 | 0 | [Details →](https://spiderrating.com/servers/merajmehrabi/puppeteer-mcp-server) |
| [memory-bank-mcp](https://github.com/alioshr/memory-bank-mcp) | 🟡 C | 5.8 | 5 | 0 | [Details →](https://spiderrating.com/servers/alioshr/memory-bank-mcp) |
| [mcp-scanner](https://github.com/cisco-ai-defense/mcp-scanner) | 🟠 D | 5.8 | 653 | 8 | [Details →](https://spiderrating.com/servers/cisco-ai-defense/mcp-scanner) |
| [pg-mcp-server](https://github.com/stuzero/pg-mcp-server) | 🟡 C | 5.8 | 5 | 5 | [Details →](https://spiderrating.com/servers/stuzero/pg-mcp-server) |
| [borsa-mcp](https://github.com/saidsurucu/borsa-mcp) | 🟠 D | 5.8 | 106 | 0 | [Details →](https://spiderrating.com/servers/saidsurucu/borsa-mcp) |
| [vanta-mcp-server](https://github.com/VantaInc/vanta-mcp-server) | 🟠 D | 5.8 | 45 | 0 | [Details →](https://spiderrating.com/servers/VantaInc/vanta-mcp-server) |
| [youtube-mcp-server](https://github.com/ZubeidHendricks/youtube-mcp-server) | 🟡 C | 5.7 | 7 | 0 | [Details →](https://spiderrating.com/servers/ZubeidHendricks/youtube-mcp-server) |
| [hexstrike-ai](https://github.com/0x4m4/hexstrike-ai) | 🟠 D | 5.7 | 151 | 122 (2 crit) | [Details →](https://spiderrating.com/servers/0x4m4/hexstrike-ai) |
| [MCP-Nest](https://github.com/rekog-labs/MCP-Nest) | 🟠 D | 5.6 | 33 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/rekog-labs/MCP-Nest) |
| [RedNote-MCP](https://github.com/iFurySt/RedNote-MCP) | 🟠 D | 5.6 | 4 | 0 | [Details →](https://spiderrating.com/servers/iFurySt/RedNote-MCP) |
| [browser-use-mcp-server](https://github.com/kontext-dev/browser-use-mcp-server) | 🟠 D | 5.6 | 2 | 0 | [Details →](https://spiderrating.com/servers/kontext-dev/browser-use-mcp-server) |
| [directories](https://github.com/leerob/directories) | 🟠 D | 5.6 | 40 | 0 | [Details →](https://spiderrating.com/servers/leerob/directories) |
| [mcp-handler](https://github.com/vercel/mcp-handler) | 🟠 D | 5.6 | 2 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/vercel/mcp-handler) |
| [claude-context](https://github.com/zilliztech/claude-context) | 🟠 D | 5.6 | 29 | 5 (1 crit) | [Details →](https://spiderrating.com/servers/zilliztech/claude-context) |
| [mcp-server-code-runner](https://github.com/formulahendry/mcp-server-code-runner) | 🟠 D | 5.6 | 1 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/formulahendry/mcp-server-code-runner) |
| [ida-mcp-server](https://github.com/MxIris-Reverse-Engineering/ida-mcp-server) | 🟠 D | 5.6 | 19 | 0 | [Details →](https://spiderrating.com/servers/MxIris-Reverse-Engineering/ida-mcp-server) |
| [mcp-shield](https://github.com/riseandignite/mcp-shield) | 🟡 C | 5.5 | 5 | 0 | [Details →](https://spiderrating.com/servers/riseandignite/mcp-shield) |
| [buildwithclaude](https://github.com/davepoon/buildwithclaude) | 🟠 D | 5.5 | 21 | 1 (1 crit) | [Details →](https://spiderrating.com/servers/davepoon/buildwithclaude) |
| [xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) | 🟠 D | 5.5 | 13 | 0 | [Details →](https://spiderrating.com/servers/xpzouying/xiaohongshu-mcp) |
| [Overture](https://github.com/SixHq/Overture) | 🟡 C | 5.5 | 14 | 7 | [Details →](https://spiderrating.com/servers/SixHq/Overture) |
| [airtable-mcp](https://github.com/felores/airtable-mcp) | 🟡 C | 5.5 | 12 | 0 | [Details →](https://spiderrating.com/servers/felores/airtable-mcp) |
| [mcp-smart-crawler](https://github.com/loo-y/mcp-smart-crawler) | 🟡 C | 5.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/loo-y/mcp-smart-crawler) |
| [langchainjs](https://github.com/langchain-ai/langchainjs) | 🔴 F | 5.5 | 91 | 24 (24 crit) | [Details →](https://spiderrating.com/servers/langchain-ai/langchainjs) |
| [Dive](https://github.com/OpenAgentPlatform/Dive) | 🔴 F | 5.4 | 8 | 4 (4 crit) | [Details →](https://spiderrating.com/servers/OpenAgentPlatform/Dive) |
| [ENScan_GO](https://github.com/wgpsec/ENScan_GO) | 🟠 D | 5.4 | 12 | 0 | [Details →](https://spiderrating.com/servers/wgpsec/ENScan_GO) |
| [browser-tools-mcp](https://github.com/AgentDeskAI/browser-tools-mcp) | 🟠 D | 5.4 | 13 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/AgentDeskAI/browser-tools-mcp) |
| [n8n-mcp](https://github.com/czlonkowski/n8n-mcp) | 🔴 F | 5.4 | 46 | 3 (3 crit) | [Details →](https://spiderrating.com/servers/czlonkowski/n8n-mcp) |
| [mcphub](https://github.com/samanhappy/mcphub) | 🔴 F | 5.4 | 5 | 7 (7 crit) | [Details →](https://spiderrating.com/servers/samanhappy/mcphub) |
| [Unla](https://github.com/AmoyLab/Unla) | 🟠 D | 5.4 | 10 | 6 (2 crit) | [Details →](https://spiderrating.com/servers/AmoyLab/Unla) |
| [5ire](https://github.com/nanbingxyz/5ire) | 🟠 D | 5.4 | 48 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/nanbingxyz/5ire) |
| [cli](https://github.com/TanStack/cli) | 🔴 F | 5.3 | 17 | 4 (4 crit) | [Details →](https://spiderrating.com/servers/TanStack/cli) |
| [just-prompt](https://github.com/disler/just-prompt) | 🟡 C | 5.3 | 6 | 0 | [Details →](https://spiderrating.com/servers/disler/just-prompt) |
| [nx-console](https://github.com/nrwl/nx-console) | 🔴 F | 5.3 | 13 | 25 (24 crit) | [Details →](https://spiderrating.com/servers/nrwl/nx-console) |
| [theia](https://github.com/eclipse-theia/theia) | 🟠 D | 5.3 | 20 | 5 | [Details →](https://spiderrating.com/servers/eclipse-theia/theia) |
| [conformance](https://github.com/modelcontextprotocol/conformance) | 🟠 D | 5.2 | 96 | 2 (2 crit) | [Details →](https://spiderrating.com/servers/modelcontextprotocol/conformance) |
| [mcp-hello-world](https://github.com/lobehub/mcp-hello-world) | 🟡 C | 5.2 | 3 | 0 | [Details →](https://spiderrating.com/servers/lobehub/mcp-hello-world) |
| [zero-mcp](https://github.com/SNIKO/zero-mcp) | 🟡 C | 5.2 | 2 | 0 | [Details →](https://spiderrating.com/servers/SNIKO/zero-mcp) |
| [LitterBox](https://github.com/BlackSnufkin/LitterBox) | 🟡 C | 5.2 | 24 | 18 | [Details →](https://spiderrating.com/servers/BlackSnufkin/LitterBox) |
| [DevDocs](https://github.com/cyberagiinc/DevDocs) | 🟡 C | 5.1 | 10 | 7 | [Details →](https://spiderrating.com/servers/cyberagiinc/DevDocs) |
| [android-mcp-server](https://github.com/minhalvp/android-mcp-server) | 🟠 D | 5.1 | 5 | 3 (1 crit) | [Details →](https://spiderrating.com/servers/minhalvp/android-mcp-server) |
| [mcp-chrome](https://github.com/hangwin/mcp-chrome) | 🔴 F | 5.0 | 5 | 14 (14 crit) | [Details →](https://spiderrating.com/servers/hangwin/mcp-chrome) |
| [xiaozhi-esp32-server](https://github.com/xinnan-tech/xiaozhi-esp32-server) | 🟠 D | 5.0 | 9 | 41 (2 crit) | [Details →](https://spiderrating.com/servers/xinnan-tech/xiaozhi-esp32-server) |
| [MiniMax-MCP](https://github.com/MiniMax-AI/MiniMax-MCP) | 🟠 D | 5.0 | 9 | 3 | [Details →](https://spiderrating.com/servers/MiniMax-AI/MiniMax-MCP) |
| [puppeteer-mcp-server](https://github.com/todoforai/puppeteer-mcp-server) | 🟠 D | 4.9 | 11 | 0 | [Details →](https://spiderrating.com/servers/todoforai/puppeteer-mcp-server) |
| [TrendRadar](https://github.com/sansan0/TrendRadar) | 🔴 F | 4.8 | 27 | 22 (9 crit) | [Details →](https://spiderrating.com/servers/sansan0/TrendRadar) |
| [mcp-server](https://github.com/sandy-mount/mcp-server) | 🟠 D | 4.8 | 4 | 0 | [Details →](https://spiderrating.com/servers/sandy-mount/mcp-server) |
| [MetasploitMCP](https://github.com/GH05TCREW/MetasploitMCP) | 🟠 D | 4.8 | 12 | 0 | [Details →](https://spiderrating.com/servers/GH05TCREW/MetasploitMCP) |
| [damn-vulnerable-MCP-server](https://github.com/harishsg993010/damn-vulnerable-MCP-server) | 🔴 F | 4.8 | 29 | 31 (9 crit) | [Details →](https://spiderrating.com/servers/harishsg993010/damn-vulnerable-MCP-server) |
| [puppeteer-mcp-server](https://github.com/namle-teq/puppeteer-mcp-server) | 🟠 D | 4.8 | 8 | 0 | [Details →](https://spiderrating.com/servers/namle-teq/puppeteer-mcp-server) |
| [contextplus](https://github.com/ForLoopCodes/contextplus) | 🟠 D | 4.7 | 17 | 0 | [Details →](https://spiderrating.com/servers/ForLoopCodes/contextplus) |
| [mcp-security-hub](https://github.com/FuzzingLabs/mcp-security-hub) | 🟠 D | 4.7 | 69 | 0 | [Details →](https://spiderrating.com/servers/FuzzingLabs/mcp-security-hub) |
| [servers-archived](https://github.com/Hisma/servers-archived) | 🟠 D | 4.6 | 78 | 0 | [Details →](https://spiderrating.com/servers/Hisma/servers-archived) |
| [maz-ui](https://github.com/LouisMazel/maz-ui) | 🟠 D | 4.5 | 7 | 0 | [Details →](https://spiderrating.com/servers/LouisMazel/maz-ui) |
| [chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) | 🟠 D | 4.4 | 105 | 0 | [Details →](https://spiderrating.com/servers/ChromeDevTools/chrome-devtools-mcp) |
| [cocos-mcp-server](https://github.com/DaxianLee/cocos-mcp-server) | 🟠 D | 4.4 | 193 | 0 | [Details →](https://spiderrating.com/servers/DaxianLee/cocos-mcp-server) |
| [apple-doc-mcp](https://github.com/MightyDillah/apple-doc-mcp) | 🟠 D | 4.3 | 6 | 0 | [Details →](https://spiderrating.com/servers/MightyDillah/apple-doc-mcp) |

## ⚠️ Critical Security Issues

These servers have critical security issues that may pose risks.

| Server | Score | Critical | High | Report |
|--------|-------|----------|------|--------|
| [hindsight](https://github.com/vectorize-io/hindsight) | 🔴 5.8 | 291 | 0 | [Details →](https://spiderrating.com/servers/vectorize-io/hindsight) |
| [neurolink](https://github.com/juspay/neurolink) | 🔴 4.9 | 45 | 0 | [Details →](https://spiderrating.com/servers/juspay/neurolink) |
| [pg-aiguide](https://github.com/timescale/pg-aiguide) | 🔴 5.2 | 38 | 1 | [Details →](https://spiderrating.com/servers/timescale/pg-aiguide) |
| [srclight](https://github.com/srclight/srclight) | 🔴 5.4 | 29 | 0 | [Details →](https://spiderrating.com/servers/srclight/srclight) |
| [langchainjs](https://github.com/langchain-ai/langchainjs) | 🔴 5.5 | 24 | 0 | [Details →](https://spiderrating.com/servers/langchain-ai/langchainjs) |
| [nx-console](https://github.com/nrwl/nx-console) | 🔴 5.3 | 24 | 1 | [Details →](https://spiderrating.com/servers/nrwl/nx-console) |
| [Agent-MCP](https://github.com/rinadelph/Agent-MCP) | 🔴 4.8 | 23 | 0 | [Details →](https://spiderrating.com/servers/rinadelph/Agent-MCP) |
| [screenpipe](https://github.com/mediar-ai/screenpipe) | 🔴 3.3 | 21 | 0 | [Details →](https://spiderrating.com/servers/mediar-ai/screenpipe) |
| [dbhub](https://github.com/bytebase/dbhub) | 🔴 4.8 | 19 | 0 | [Details →](https://spiderrating.com/servers/bytebase/dbhub) |
| [mcp-memory-service](https://github.com/doobidoo/mcp-memory-service) | 🔴 5.0 | 19 | 1 | [Details →](https://spiderrating.com/servers/doobidoo/mcp-memory-service) |
| [bugsy](https://github.com/mobb-dev/bugsy) | 🔴 4.6 | 19 | 0 | [Details →](https://spiderrating.com/servers/mobb-dev/bugsy) |
| [token-optimizer-mcp](https://github.com/ooples/token-optimizer-mcp) | 🔴 4.6 | 19 | 2 | [Details →](https://spiderrating.com/servers/ooples/token-optimizer-mcp) |
| [goose](https://github.com/block/goose) | 🔴 5.3 | 14 | 0 | [Details →](https://spiderrating.com/servers/block/goose) |
| [mcp-chrome](https://github.com/hangwin/mcp-chrome) | 🔴 5.0 | 14 | 0 | [Details →](https://spiderrating.com/servers/hangwin/mcp-chrome) |
| [vibealive](https://github.com/skullzarmy/vibealive) | 🔴 4.2 | 14 | 0 | [Details →](https://spiderrating.com/servers/skullzarmy/vibealive) |
| [mengram](https://github.com/alibaizhanov/mengram) | 🔴 4.7 | 12 | 0 | [Details →](https://spiderrating.com/servers/alibaizhanov/mengram) |
| [Reddit-Options-Trader-ROT-](https://github.com/Mattbusel/Reddit-Options-Trader-ROT-) | 🔴 4.6 | 11 | 1 | [Details →](https://spiderrating.com/servers/Mattbusel/Reddit-Options-Trader-ROT-) |
| [UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop) | 🔴 5.3 | 11 | 0 | [Details →](https://spiderrating.com/servers/bytedance/UI-TARS-desktop) |
| [skylos](https://github.com/duriantaco/skylos) | 🔴 4.3 | 10 | 0 | [Details →](https://spiderrating.com/servers/duriantaco/skylos) |
| [ncp](https://github.com/portel-dev/ncp) | 🔴 4.5 | 10 | 0 | [Details →](https://spiderrating.com/servers/portel-dev/ncp) |
| [agent-memory](https://github.com/g1itchbot8888-del/agent-memory) | 🔴 4.4 | 9 | 0 | [Details →](https://spiderrating.com/servers/g1itchbot8888-del/agent-memory) |
| [damn-vulnerable-MCP-server](https://github.com/harishsg993010/damn-vulnerable-MCP-server) | 🔴 4.8 | 9 | 0 | [Details →](https://spiderrating.com/servers/harishsg993010/damn-vulnerable-MCP-server) |
| [slack-mcp-server](https://github.com/jtalk22/slack-mcp-server) | 🔴 4.8 | 9 | 0 | [Details →](https://spiderrating.com/servers/jtalk22/slack-mcp-server) |
| [terminator](https://github.com/mediar-ai/terminator) | 🔴 5.9 | 9 | 0 | [Details →](https://spiderrating.com/servers/mediar-ai/terminator) |
| [memory-mcp](https://github.com/michael-denyer/memory-mcp) | 🔴 4.5 | 9 | 0 | [Details →](https://spiderrating.com/servers/michael-denyer/memory-mcp) |
| [mcp-console-automation](https://github.com/ooples/mcp-console-automation) | 🔴 4.4 | 9 | 0 | [Details →](https://spiderrating.com/servers/ooples/mcp-console-automation) |
| [TrendRadar](https://github.com/sansan0/TrendRadar) | 🔴 4.8 | 9 | 2 | [Details →](https://spiderrating.com/servers/sansan0/TrendRadar) |
| [mcp-adr-analysis-server](https://github.com/tosin2013/mcp-adr-analysis-server) | 🔴 4.6 | 9 | 0 | [Details →](https://spiderrating.com/servers/tosin2013/mcp-adr-analysis-server) |
| [DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) | 🔴 6.1 | 9 | 0 | [Details →](https://spiderrating.com/servers/wonderwhy-er/DesktopCommanderMCP) |
| [mcp-bench](https://github.com/Accenture/mcp-bench) | 🔴 5.8 | 8 | 0 | [Details →](https://spiderrating.com/servers/Accenture/mcp-bench) |
| [lunar](https://github.com/TheLunarCompany/lunar) | 🔴 5.0 | 8 | 0 | [Details →](https://spiderrating.com/servers/TheLunarCompany/lunar) |
| [ios-mcp-code-quality-server](https://github.com/a-25/ios-mcp-code-quality-server) | 🔴 5.0 | 8 | 0 | [Details →](https://spiderrating.com/servers/a-25/ios-mcp-code-quality-server) |
| [simple-mcp-selenium](https://github.com/brutalzinn/simple-mcp-selenium) | 🔴 3.9 | 8 | 0 | [Details →](https://spiderrating.com/servers/brutalzinn/simple-mcp-selenium) |
| [lumino-mcp-server](https://github.com/spre-sre/lumino-mcp-server) | 🔴 5.4 | 8 | 0 | [Details →](https://spiderrating.com/servers/spre-sre/lumino-mcp-server) |
| [memora](https://github.com/agentic-mcp-tools/memora) | 🔴 4.9 | 7 | 0 | [Details →](https://spiderrating.com/servers/agentic-mcp-tools/memora) |
| [mcp-cockroachdb](https://github.com/amineelkouhen/mcp-cockroachdb) | 🔴 5.4 | 7 | 0 | [Details →](https://spiderrating.com/servers/amineelkouhen/mcp-cockroachdb) |
| [tsgram-mcp](https://github.com/areweai/tsgram-mcp) | 🔴 4.2 | 7 | 0 | [Details →](https://spiderrating.com/servers/areweai/tsgram-mcp) |
| [ai-distiller](https://github.com/janreges/ai-distiller) | 🔴 5.1 | 7 | 0 | [Details →](https://spiderrating.com/servers/janreges/ai-distiller) |
| [kolibri](https://github.com/public-ui/kolibri) | 🔴 6.1 | 7 | 2 | [Details →](https://spiderrating.com/servers/public-ui/kolibri) |
| [remembra](https://github.com/remembra-ai/remembra) | 🔴 4.8 | 7 | 0 | [Details →](https://spiderrating.com/servers/remembra-ai/remembra) |
| [mcphub](https://github.com/samanhappy/mcphub) | 🔴 5.4 | 7 | 0 | [Details →](https://spiderrating.com/servers/samanhappy/mcphub) |
| [jenkins-mcp-server](https://github.com/avisangle/jenkins-mcp-server) | 🔴 4.6 | 6 | 0 | [Details →](https://spiderrating.com/servers/avisangle/jenkins-mcp-server) |
| [email-mcp](https://github.com/codefuturist/email-mcp) | 🔴 4.4 | 6 | 0 | [Details →](https://spiderrating.com/servers/codefuturist/email-mcp) |
| [claude-task-master](https://github.com/eyaltoledano/claude-task-master) | 🔴 5.3 | 6 | 0 | [Details →](https://spiderrating.com/servers/eyaltoledano/claude-task-master) |
| [tradememory-protocol](https://github.com/mnemox-ai/tradememory-protocol) | 🔴 4.9 | 6 | 0 | [Details →](https://spiderrating.com/servers/mnemox-ai/tradememory-protocol) |
| [cognee](https://github.com/topoteretes/cognee) | 🔴 5.0 | 6 | 0 | [Details →](https://spiderrating.com/servers/topoteretes/cognee) |
| [mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) | 🔴 3.8 | 5 | 0 | [Details →](https://spiderrating.com/servers/c4pt0r/mcp-server-tidb) |
| [llm-context.py](https://github.com/cyberchitta/llm-context.py) | 🔴 5.2 | 5 | 0 | [Details →](https://spiderrating.com/servers/cyberchitta/llm-context.py) |
| [context-mcp](https://github.com/dodopayments/context-mcp) | 🔴 5.1 | 5 | 0 | [Details →](https://spiderrating.com/servers/dodopayments/context-mcp) |
| [mnemo-mcp](https://github.com/n24q02m/mnemo-mcp) | 🔴 4.4 | 5 | 0 | [Details →](https://spiderrating.com/servers/n24q02m/mnemo-mcp) |
| [wet-mcp](https://github.com/n24q02m/wet-mcp) | 🔴 4.4 | 5 | 0 | [Details →](https://spiderrating.com/servers/n24q02m/wet-mcp) |
| [gnosis-mcp](https://github.com/nicholasglazer/gnosis-mcp) | 🔴 4.9 | 5 | 0 | [Details →](https://spiderrating.com/servers/nicholasglazer/gnosis-mcp) |
| [pmpt-cli](https://github.com/pmptwiki/pmpt-cli) | 🔴 4.1 | 5 | 0 | [Details →](https://spiderrating.com/servers/pmptwiki/pmpt-cli) |
| [mcp_server_notify](https://github.com/Cactusinhand/mcp_server_notify) | 🔴 4.5 | 4 | 0 | [Details →](https://spiderrating.com/servers/Cactusinhand/mcp_server_notify) |
| [shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server) | 🔴 4.9 | 4 | 0 | [Details →](https://spiderrating.com/servers/Jpisnice/shadcn-ui-mcp-server) |
| [Dive](https://github.com/OpenAgentPlatform/Dive) | 🔴 5.4 | 4 | 0 | [Details →](https://spiderrating.com/servers/OpenAgentPlatform/Dive) |
| [cli](https://github.com/TanStack/cli) | 🔴 5.3 | 4 | 0 | [Details →](https://spiderrating.com/servers/TanStack/cli) |
| [mcp-gateway-registry](https://github.com/agentic-community/mcp-gateway-registry) | 🔴 5.2 | 4 | 0 | [Details →](https://spiderrating.com/servers/agentic-community/mcp-gateway-registry) |
| [cogmemai-mcp](https://github.com/hifriendbot/cogmemai-mcp) | 🔴 4.6 | 4 | 0 | [Details →](https://spiderrating.com/servers/hifriendbot/cogmemai-mcp) |
| [MCP-Dandan](https://github.com/82ch/MCP-Dandan) | 🔴 4.6 | 3 | 1 | [Details →](https://spiderrating.com/servers/82ch/MCP-Dandan) |
| [Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) | 🔴 5.4 | 3 | 0 | [Details →](https://spiderrating.com/servers/IvanMurzak/Unity-MCP) |
| [PlanningCopilot](https://github.com/SPL-BGU/PlanningCopilot) | 🔴 5.1 | 3 | 2 | [Details →](https://spiderrating.com/servers/SPL-BGU/PlanningCopilot) |
| [mcp](https://github.com/awslabs/mcp) | 🔴 6.7 | 3 | 2 | [Details →](https://spiderrating.com/servers/awslabs/mcp) |
| [mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior) | 🔴 4.4 | 3 | 0 | [Details →](https://spiderrating.com/servers/awwaiid/mcp-server-taskwarrior) |
| [activitypub-mcp](https://github.com/cameronrye/activitypub-mcp) | 🔴 4.7 | 3 | 0 | [Details →](https://spiderrating.com/servers/cameronrye/activitypub-mcp) |
| [n8n-mcp](https://github.com/czlonkowski/n8n-mcp) | 🔴 5.4 | 3 | 0 | [Details →](https://spiderrating.com/servers/czlonkowski/n8n-mcp) |
| [airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) | 🔴 5.4 | 3 | 0 | [Details →](https://spiderrating.com/servers/domdomegg/airtable-mcp-server) |
| [agent-os](https://github.com/imran-siddique/agent-os) | 🔴 4.1 | 3 | 0 | [Details →](https://spiderrating.com/servers/imran-siddique/agent-os) |
| [content-core](https://github.com/lfnovo/content-core) | 🔴 5.1 | 3 | 0 | [Details →](https://spiderrating.com/servers/lfnovo/content-core) |
| [agent-bom](https://github.com/msaad00/agent-bom) | 🔴 4.7 | 3 | 0 | [Details →](https://spiderrating.com/servers/msaad00/agent-bom) |
| [mcp-datalink](https://github.com/pilat/mcp-datalink) | 🔴 4.2 | 3 | 0 | [Details →](https://spiderrating.com/servers/pilat/mcp-datalink) |
| [memory-mcp-1file](https://github.com/pomazanbohdan/memory-mcp-1file) | 🔴 4.5 | 3 | 0 | [Details →](https://spiderrating.com/servers/pomazanbohdan/memory-mcp-1file) |
| [wode](https://github.com/wenerme/wode) | 🔴 4.5 | 3 | 8 | [Details →](https://spiderrating.com/servers/wenerme/wode) |
| [claudia](https://github.com/yuvalsuede/claudia) | 🔴 4.1 | 3 | 0 | [Details →](https://spiderrating.com/servers/yuvalsuede/claudia) |
| [hexstrike-ai](https://github.com/0x4m4/hexstrike-ai) | 🔴 5.7 | 2 | 0 | [Details →](https://spiderrating.com/servers/0x4m4/hexstrike-ai) |
| [browser-tools-mcp](https://github.com/AgentDeskAI/browser-tools-mcp) | 🔴 5.4 | 2 | 0 | [Details →](https://spiderrating.com/servers/AgentDeskAI/browser-tools-mcp) |
| [Unla](https://github.com/AmoyLab/Unla) | 🔴 5.4 | 2 | 4 | [Details →](https://spiderrating.com/servers/AmoyLab/Unla) |
| [greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server) | 🔴 5.8 | 2 | 0 | [Details →](https://spiderrating.com/servers/GreptimeTeam/greptimedb-mcp-server) |
| [klavis](https://github.com/Klavis-AI/klavis) | 🔴 6.6 | 2 | 0 | [Details →](https://spiderrating.com/servers/Klavis-AI/klavis) |
| [npcpy](https://github.com/NPC-Worldwide/npcpy) | 🔴 5.2 | 2 | 0 | [Details →](https://spiderrating.com/servers/NPC-Worldwide/npcpy) |
| [quackback](https://github.com/QuackbackIO/quackback) | 🔴 4.8 | 2 | 1 | [Details →](https://spiderrating.com/servers/QuackbackIO/quackback) |
| [CloudBase-AI-ToolKit](https://github.com/TencentCloudBase/CloudBase-AI-ToolKit) | 🔴 2.9 | 2 | 3 | [Details →](https://spiderrating.com/servers/TencentCloudBase/CloudBase-AI-ToolKit) |
| [mcp-server](https://github.com/UnMarkdown/mcp-server) | 🔴 4.5 | 2 | 2 | [Details →](https://spiderrating.com/servers/UnMarkdown/mcp-server) |
| [claude-faf-mcp](https://github.com/Wolfe-Jam/claude-faf-mcp) | 🔴 4.8 | 2 | 0 | [Details →](https://spiderrating.com/servers/Wolfe-Jam/claude-faf-mcp) |
| [faf-mcp](https://github.com/Wolfe-Jam/faf-mcp) | 🔴 4.5 | 2 | 0 | [Details →](https://spiderrating.com/servers/Wolfe-Jam/faf-mcp) |
| [agentkits-memory](https://github.com/aitytech/agentkits-memory) | 🔴 4.9 | 2 | 2 | [Details →](https://spiderrating.com/servers/aitytech/agentkits-memory) |
| [myinstants-mcp](https://github.com/austenstone/myinstants-mcp) | 🔴 4.3 | 2 | 0 | [Details →](https://spiderrating.com/servers/austenstone/myinstants-mcp) |
| [mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) | 🔴 5.7 | 2 | 0 | [Details →](https://spiderrating.com/servers/benborla/mcp-server-mysql) |
| [gopher-mcp](https://github.com/cameronrye/gopher-mcp) | 🔴 4.8 | 2 | 0 | [Details →](https://spiderrating.com/servers/cameronrye/gopher-mcp) |
| [figma-use](https://github.com/dannote/figma-use) | 🔴 5.4 | 2 | 0 | [Details →](https://spiderrating.com/servers/dannote/figma-use) |
| [domain-search-mcp](https://github.com/dorukardahan/domain-search-mcp) | 🔴 4.7 | 2 | 0 | [Details →](https://spiderrating.com/servers/dorukardahan/domain-search-mcp) |
| [mem-agent-mcp](https://github.com/firstbatchxyz/mem-agent-mcp) | 🔴 6.0 | 2 | 0 | [Details →](https://spiderrating.com/servers/firstbatchxyz/mem-agent-mcp) |
| [youtube_mcp](https://github.com/format37/youtube_mcp) | 🔴 4.5 | 2 | 0 | [Details →](https://spiderrating.com/servers/format37/youtube_mcp) |
| [tools](https://github.com/golang/tools) | 🔴 5.9 | 2 | 0 | [Details →](https://spiderrating.com/servers/golang/tools) |
| [mcp-video-analyzer](https://github.com/guimatheus92/mcp-video-analyzer) | 🔴 5.5 | 2 | 0 | [Details →](https://spiderrating.com/servers/guimatheus92/mcp-video-analyzer) |
| [voice-mcp](https://github.com/mbailey/voice-mcp) | 🔴 3.4 | 2 | 1 | [Details →](https://spiderrating.com/servers/mbailey/voice-mcp) |
| [ai-toolkit](https://github.com/memgraph/ai-toolkit) | 🔴 5.6 | 2 | 0 | [Details →](https://spiderrating.com/servers/memgraph/ai-toolkit) |
| [conformance](https://github.com/modelcontextprotocol/conformance) | 🔴 5.2 | 2 | 0 | [Details →](https://spiderrating.com/servers/modelcontextprotocol/conformance) |
| [5ire](https://github.com/nanbingxyz/5ire) | 🔴 5.4 | 2 | 0 | [Details →](https://spiderrating.com/servers/nanbingxyz/5ire) |
| [real-browser-mcp](https://github.com/ofershap/real-browser-mcp) | 🔴 4.8 | 2 | 0 | [Details →](https://spiderrating.com/servers/ofershap/real-browser-mcp) |
| [MCP-Nest](https://github.com/rekog-labs/MCP-Nest) | 🔴 5.6 | 2 | 0 | [Details →](https://spiderrating.com/servers/rekog-labs/MCP-Nest) |
| [opengraph-io-mcp](https://github.com/securecoders/opengraph-io-mcp) | 🔴 5.2 | 2 | 0 | [Details →](https://spiderrating.com/servers/securecoders/opengraph-io-mcp) |
| [mcp](https://github.com/semgrep/mcp) | 🔴 6.3 | 2 | 0 | [Details →](https://spiderrating.com/servers/semgrep/mcp) |
| [blogburst-mcp-server](https://github.com/shensi8312/blogburst-mcp-server) | 🔴 4.0 | 2 | 3 | [Details →](https://spiderrating.com/servers/shensi8312/blogburst-mcp-server) |
| [dolphindb-mcp-server](https://github.com/tradercjz/dolphindb-mcp-server) | 🔴 4.1 | 2 | 0 | [Details →](https://spiderrating.com/servers/tradercjz/dolphindb-mcp-server) |
| [shodh-memory](https://github.com/varun29ankuS/shodh-memory) | 🔴 5.5 | 2 | 0 | [Details →](https://spiderrating.com/servers/varun29ankuS/shodh-memory) |
| [mcp-fusion](https://github.com/vinkius-labs/mcp-fusion) | 🔴 3.9 | 2 | 0 | [Details →](https://spiderrating.com/servers/vinkius-labs/mcp-fusion) |
| [mcp](https://github.com/waystation-ai/mcp) | 🔴 5.1 | 2 | 0 | [Details →](https://spiderrating.com/servers/waystation-ai/mcp) |
| [webpeel](https://github.com/webpeel/webpeel) | 🔴 4.7 | 2 | 0 | [Details →](https://spiderrating.com/servers/webpeel/webpeel) |
| [xiaozhi-esp32-server](https://github.com/xinnan-tech/xiaozhi-esp32-server) | 🔴 5.0 | 2 | 3 | [Details →](https://spiderrating.com/servers/xinnan-tech/xiaozhi-esp32-server) |
| [jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server) | 🔴 4.9 | 2 | 0 | [Details →](https://spiderrating.com/servers/xzq-xu/jvm-mcp-server) |
| [scriptflow-mcp](https://github.com/yanmxa/scriptflow-mcp) | 🔴 4.4 | 2 | 0 | [Details →](https://spiderrating.com/servers/yanmxa/scriptflow-mcp) |
| [smart-tree](https://github.com/8b-is/smart-tree) | 🔴 5.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/8b-is/smart-tree) |
| [csl-core](https://github.com/Chimera-Protocol/csl-core) | 🔴 6.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/Chimera-Protocol/csl-core) |
| [dingo](https://github.com/DataEval/dingo) | 🔴 4.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/DataEval/dingo) |
| [atest-mcp-server](https://github.com/LinuxSuRen/atest-mcp-server) | 🔴 5.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/LinuxSuRen/atest-mcp-server) |
| [inspector](https://github.com/MCPJam/inspector) | 🔴 6.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/MCPJam/inspector) |
| [mcp-codebase-index](https://github.com/MikeRecognex/mcp-codebase-index) | 🔴 5.1 | 1 | 1 | [Details →](https://spiderrating.com/servers/MikeRecognex/mcp-codebase-index) |
| [mermaid-mcp](https://github.com/Narasimhaponnada/mermaid-mcp) | 🔴 5.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/Narasimhaponnada/mermaid-mcp) |
| [chrome-mcp-secure](https://github.com/Pantheon-Security/chrome-mcp-secure) | 🔴 5.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/Pantheon-Security/chrome-mcp-secure) |
| [brightspace-mcp-server](https://github.com/RohanMuppa/brightspace-mcp-server) | 🔴 6.1 | 1 | 0 | [Details →](https://spiderrating.com/servers/RohanMuppa/brightspace-mcp-server) |
| [open-ux-tools](https://github.com/SAP/open-ux-tools) | 🔴 6.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/SAP/open-ux-tools) |
| [mcp-claude-code](https://github.com/SDGLBL/mcp-claude-code) | 🔴 5.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/SDGLBL/mcp-claude-code) |
| [alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server) | 🔴 5.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/aliyun/alibaba-cloud-ops-mcp-server) |
| [actors-mcp-server](https://github.com/apify/actors-mcp-server) | 🔴 4.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/apify/actors-mcp-server) |
| [apify-mcp-server](https://github.com/apify/apify-mcp-server) | 🔴 6.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/apify/apify-mcp-server) |
| [mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser) | 🔴 5.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/apify/mcp-server-rag-web-browser) |
| [mermaid_grammer_inspector_mcp](https://github.com/betterhyq/mermaid_grammer_inspector_mcp) | 🔴 4.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/betterhyq/mermaid_grammer_inspector_mcp) |
| [lennys-quotes](https://github.com/bluzername/lennys-quotes) | 🔴 4.8 | 1 | 0 | [Details →](https://spiderrating.com/servers/bluzername/lennys-quotes) |
| [mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) | 🔴 6.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/cloudflare/mcp-server-cloudflare) |
| [currents-mcp](https://github.com/currents-dev/currents-mcp) | 🔴 6.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/currents-dev/currents-mcp) |
| [fizzy-mcp](https://github.com/davegomez/fizzy-mcp) | 🔴 5.1 | 1 | 1 | [Details →](https://spiderrating.com/servers/davegomez/fizzy-mcp) |
| [buildwithclaude](https://github.com/davepoon/buildwithclaude) | 🔴 5.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/davepoon/buildwithclaude) |
| [mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) | 🔴 5.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/designcomputer/mysql_mcp_server) |
| [callout](https://github.com/fantasieleven-code/callout) | 🔴 4.8 | 1 | 0 | [Details →](https://spiderrating.com/servers/fantasieleven-code/callout) |
| [enrichmcp](https://github.com/featureform/enrichmcp) | 🔴 6.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/featureform/enrichmcp) |
| [mcp-server-code-runner](https://github.com/formulahendry/mcp-server-code-runner) | 🔴 5.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/formulahendry/mcp-server-code-runner) |
| [XcodeBuildMCP](https://github.com/getsentry/XcodeBuildMCP) | 🔴 6.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/getsentry/XcodeBuildMCP) |
| [finbud-data-mcp](https://github.com/glaksmono/finbud-data-mcp) | 🔴 5.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/glaksmono/finbud-data-mcp) |
| [growthbook-mcp](https://github.com/growthbook/growthbook-mcp) | 🔴 6.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/growthbook/growthbook-mcp) |
| [cortex](https://github.com/gzoonet/cortex) | 🔴 4.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/gzoonet/cortex) |
| [sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) | 🔴 5.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) |
| [comet-mcp](https://github.com/hanzili/comet-mcp) | 🔴 5.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/hanzili/comet-mcp) |
| [heroku-mcp-server](https://github.com/heroku/heroku-mcp-server) | 🔴 6.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/heroku/heroku-mcp-server) |
| [hledger-mcp](https://github.com/iiAtlas/hledger-mcp) | 🔴 5.5 | 1 | 0 | [Details →](https://spiderrating.com/servers/iiAtlas/hledger-mcp) |
| [apple-mail-mcp](https://github.com/imdinu/apple-mail-mcp) | 🔴 6.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/imdinu/apple-mail-mcp) |
| [mcp-browser-agent](https://github.com/imprvhub/mcp-browser-agent) | 🔴 5.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/imprvhub/mcp-browser-agent) |
| [mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) | 🔴 4.7 | 1 | 0 | [Details →](https://spiderrating.com/servers/isaacwasserman/mcp-vegalite-server) |
| [mcp-orchestro](https://github.com/khaoss85/mcp-orchestro) | 🔴 4.8 | 1 | 0 | [Details →](https://spiderrating.com/servers/khaoss85/mcp-orchestro) |
| [email-mcp](https://github.com/marlinjai/email-mcp) | 🔴 5.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/marlinjai/email-mcp) |
| [counsel-mcp](https://github.com/mercurialsolo/counsel-mcp) | 🔴 4.5 | 1 | 3 | [Details →](https://spiderrating.com/servers/mercurialsolo/counsel-mcp) |
| [android-mcp-server](https://github.com/minhalvp/android-mcp-server) | 🔴 5.1 | 1 | 0 | [Details →](https://spiderrating.com/servers/minhalvp/android-mcp-server) |
| [ext-apps](https://github.com/modelcontextprotocol/ext-apps) | 🔴 6.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/modelcontextprotocol/ext-apps) |
| [mcpb](https://github.com/modelcontextprotocol/mcpb) | 🔴 6.1 | 1 | 0 | [Details →](https://spiderrating.com/servers/modelcontextprotocol/mcpb) |
| [python-sdk](https://github.com/modelcontextprotocol/python-sdk) | 🔴 6.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/modelcontextprotocol/python-sdk) |
| [user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp) | 🔴 5.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/mrexodia/user-feedback-mcp) |
| [better-email-mcp](https://github.com/n24q02m/better-email-mcp) | 🔴 5.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/n24q02m/better-email-mcp) |
| [better-godot-mcp](https://github.com/n24q02m/better-godot-mcp) | 🔴 5.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/n24q02m/better-godot-mcp) |
| [better-notion-mcp](https://github.com/n24q02m/better-notion-mcp) | 🔴 5.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/n24q02m/better-notion-mcp) |
| [arch-mcp](https://github.com/nihalxkumar/arch-mcp) | 🔴 5.8 | 1 | 0 | [Details →](https://spiderrating.com/servers/nihalxkumar/arch-mcp) |
| [code-guardian](https://github.com/phuongrealmax/code-guardian) | 🔴 4.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/phuongrealmax/code-guardian) |
| [mcp_polygon](https://github.com/polygon-io/mcp_polygon) | 🔴 5.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/polygon-io/mcp_polygon) |
| [mcp-server](https://github.com/profullstack/mcp-server) | 🔴 5.1 | 1 | 0 | [Details →](https://spiderrating.com/servers/profullstack/mcp-server) |
| [mcp-server-apple-shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) | 🔴 5.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/recursechat/mcp-server-apple-shortcuts) |
| [deepwiki-mcp](https://github.com/regenrek/deepwiki-mcp) | 🔴 5.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/regenrek/deepwiki-mcp) |
| [CodeCortex](https://github.com/rushikeshmore/CodeCortex) | 🔴 5.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/rushikeshmore/CodeCortex) |
| [thales-cdsp-cakm-mcp-server](https://github.com/sanyambassi/thales-cdsp-cakm-mcp-server) | 🔴 6.0 | 1 | 0 | [Details →](https://spiderrating.com/servers/sanyambassi/thales-cdsp-cakm-mcp-server) |
| [search-console-mcp](https://github.com/saurabhsharma2u/search-console-mcp) | 🔴 5.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/saurabhsharma2u/search-console-mcp) |
| [ms-365-mcp-server](https://github.com/softeria/ms-365-mcp-server) | 🔴 6.2 | 1 | 0 | [Details →](https://spiderrating.com/servers/softeria/ms-365-mcp-server) |
| [xray](https://github.com/srijanshukla18/xray) | 🔴 5.8 | 1 | 0 | [Details →](https://spiderrating.com/servers/srijanshukla18/xray) |
| [agent-toolkit](https://github.com/stripe/agent-toolkit) | 🔴 4.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/stripe/agent-toolkit) |
| [tat-mcp-server](https://github.com/theagenttimes/tat-mcp-server) | 🔴 4.3 | 1 | 0 | [Details →](https://spiderrating.com/servers/theagenttimes/tat-mcp-server) |
| [mcp-handler](https://github.com/vercel/mcp-handler) | 🔴 5.6 | 1 | 0 | [Details →](https://spiderrating.com/servers/vercel/mcp-handler) |
| [OPNSenseMCP](https://github.com/vespo92/OPNSenseMCP) | 🔴 5.4 | 1 | 0 | [Details →](https://spiderrating.com/servers/vespo92/OPNSenseMCP) |
| [claude-context](https://github.com/zilliztech/claude-context) | 🔴 5.6 | 1 | 1 | [Details →](https://spiderrating.com/servers/zilliztech/claude-context) |
| [garmin-documentation-mcp-server](https://github.com/ztuskes/garmin-documentation-mcp-server) | 🔴 4.9 | 1 | 0 | [Details →](https://spiderrating.com/servers/ztuskes/garmin-documentation-mcp-server) |

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

## Links

- [spiderrating.com](https://spiderrating.com) -- Full reports with tool-level scores and issue details
- [SpiderShield](https://github.com/teehooai/spidershield) -- Open-source scanner
- [Trust Registry API](https://spiderrating.com/api/docs) -- Query ratings programmatically
- [PyPI](https://pypi.org/project/spidershield/) -- `pip install spidershield`

*Last updated: 2026-03-14 | Generated by [SpiderRating pipeline](https://github.com/spiderrating/spiderrating)*