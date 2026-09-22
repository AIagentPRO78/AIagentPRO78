![banner](assets/banner.png)

# 〉 whoami

Pseudonymous security researcher and builder.

I hunt bugs across web apps, cloud, and smart contracts, and I write each one up with the receipts: transcripts, dead ends, and a repro anyone can run. Then I build the tooling I keep wishing existed.

Lately that means agentic AI: kits that put Claude, Gemini, OpenAI and open models into shared rooms, and tools that make agent spend and context visible.

## 〉 how I work

<p align="center">
  <img src="assets/how-i-work.svg" width="860" alt="Flow diagram: map the surface, form a hypothesis, reproduce in a local lab, confirm live with minimal traffic, report with receipts. A failed hypothesis loops back to an earlier step and dead ends are logged.">
</p>

Every hypothesis gets tested where it can't hurt anyone first. Dashed arrows are dead ends and failed hypotheses looping back; they get logged, not deleted.

## 〉 shipped

| Project | What it does | Stack |
|---|---|---|
| [**tokenomics**](https://github.com/AIagentPRO78/tokenomics) | See, attribute, and prove the cost and context of every Claude Code session. Reads transcripts offline: no network calls, no telemetry, zero runtime dependencies. [Docs](https://aiagentpro78.github.io/tokenomics/) | JavaScript |
| [**claude-usage-bar**](https://github.com/AIagentPRO78/claude-usage-bar) | Native macOS menu-bar tracker for Claude Code usage: 5-hour block, today, and month, with per-model splits. Keys live in the macOS Keychain. | Swift |
| **AgentMeet agent kits**<br>[Claude Code](https://github.com/AIagentPRO78/agentmeet-claude-code-agent) · [OpenAI](https://github.com/AIagentPRO78/agentmeet-openai-agent) · [Gemini](https://github.com/AIagentPRO78/agentmeet-gemini-agent) · [OpenAI-compatible](https://github.com/AIagentPRO78/agentmeet-openai-compatible-agent) | Drop-in agents for [agentmeet.chat](https://agentmeet.chat). Clone, set a token and a room, run. The compatible kit switches between Qwen, DeepSeek, Mistral, Grok, Perplexity, Groq and Ollama with one env var. | TypeScript |

### How the AgentMeet kits fit together

<p align="center">
  <img src="assets/agentmeet-kits.svg" width="738" alt="Diagram: an agentmeet.chat room exchanges @mentions and replies with four agent kits: claude-code-agent (runs on the local claude CLI with your Skills and MCP servers), openai-agent, gemini-agent, and openai-compatible-agent (Qwen, DeepSeek, Mistral, Grok, Perplexity, Groq, Ollama).">
</p>

### What tokenomics prints (sample report)

<p align="center">
  <img src="assets/tokenomics-report.svg" width="820" alt="Sample tokenomics report: $0.9030 across 42 turns, context 67% used, Opus 82% of cost and Haiku 18%, with a recommendation to route mechanical subagents off Opus and save about $0.31.">
</p>

## 〉 currently building

- **AgentMeet** — agent-to-agent chat platform · [agentmeet.chat](https://agentmeet.chat)
- **cve-mcp-server** — 27-tool MCP server for CVE & threat intelligence · *private, in development*
- **Teams Mirror** — AI presence on Microsoft Teams (chat + voice) · *private, in development*

## 〉 focus

![Web Security](https://img.shields.io/badge/Web_Security-1f6feb?style=flat-square)
![Cloud](https://img.shields.io/badge/Cloud-ff9900?style=flat-square)
![Web3 / Smart Contracts](https://img.shields.io/badge/Web3_%2F_Smart_Contracts-7c3aed?style=flat-square)
![Agentic AI](https://img.shields.io/badge/Agentic_AI-10a37f?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-d97706?style=flat-square)
![Bug Bounty](https://img.shields.io/badge/Bug_Bounty-dc2626?style=flat-square)

## 〉 stack

![Python](https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-ce422b?style=flat-square&logo=rust&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-ff007a?style=flat-square)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-ff6633?style=flat-square)
![Semgrep](https://img.shields.io/badge/Semgrep-1a8fff?style=flat-square)
![Anthropic SDK](https://img.shields.io/badge/Anthropic_SDK-cc9b7a?style=flat-square&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs&logoColor=white)

## 〉 reach

- **HackerOne** — [hackerone.com/aiagentpro78](https://hackerone.com/aiagentpro78)
- **Intigriti** — [app.intigriti.com/researcher/aiagentpro](https://app.intigriti.com/researcher/aiagentpro)
- **Writeups** — [github.com/AIagentPRO78/advisories](https://github.com/AIagentPRO78/advisories)
