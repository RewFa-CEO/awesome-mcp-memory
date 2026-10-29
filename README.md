# Awesome MCP Memory

> **Every memory server & client for Model Context Protocol — give Claude, Cursor & every agent the same brain.**

2026 is the year every agent speaks MCP. Memory is its hottest use case — yet the lists that exist are paper-oriented or SDK-general. This one is focused: **what you can actually plug into Claude Code, Cursor, Claude Desktop or any MCP client today**, with a live comparison matrix and no dead links.

每一台 Agent 都说 MCP 的时代，记忆是最热的需求。本清单专注“今天就能插上用的 MCP 记忆服务器与客户端”，附活对比矩阵。

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Last Verified](https://img.shields.io/badge/entries%20verified-2026--10--27-brightgreen)](CONTRIBUTING.md) [![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey)](LICENSE)

---

## The Landscape (Oct 2026)

Star counts update live via badges. Sorted by category, not by hype.

**General memory platforms with MCP integration**

| Project | What it is | Stars |
| --- | --- | --- |
| [mem0](https://github.com/mem0ai/mem0) | The widest-adopted memory SDK/platform; hosted + self-hosted | ![Stars](https://img.shields.io/github/stars/mem0ai/mem0) |
| [MemPalace](https://github.com/MemPalace/mempalace) | Best-benchmarked open-source AI memory system, free | ![Stars](https://img.shields.io/github/stars/MemPalace/mempalace) |
| [Letta (MemGPT)](https://github.com/letta-ai/letta) | Stateful-agent framework with self-editing memory hierarchy | ![Stars](https://img.shields.io/github/stars/letta-ai/letta) |
| [Graphiti (Zep)](https://github.com/getzep/graphiti) | Temporal knowledge-graph memory, sub-200ms retrieval | ![Stars](https://img.shields.io/github/stars/getzep/graphiti) |
| [memU](https://github.com/NevaMind-AI/memU) | Personal memory across agents | ![Stars](https://img.shields.io/github/stars/NevaMind-AI/memU) |
| [EverOS](https://github.com/EverMind-AI/EverOS) | Portable memory layer, local-first & Markdown-native | ![Stars](https://img.shields.io/github/stars/EverMind-AI/EverOS) |
| [MemOS](https://github.com/MemTensor/MemOS) | Self-evolving memory OS for LLMs & agents | ![Stars](https://img.shields.io/github/stars/MemTensor/MemOS) |

**MCP-native memory servers**

| Project | What it is | Stars |
| --- | --- | --- |
| [Reference memory server](https://github.com/modelcontextprotocol/servers) | The official MCP servers repo incl. the knowledge-graph memory server | ![Stars](https://img.shields.io/github/stars/modelcontextprotocol/servers) |
| [mcp-memory-service](https://github.com/doobidoo/mcp-memory-service) | Knowledge-graph memory server for Claude, persistent & local | ![Stars](https://img.shields.io/github/stars/doobidoo/mcp-memory-service) |
| [xerj](https://github.com/xerj-org/xerj) | Local-first search engine + MCP server, one Rust binary | ![Stars](https://img.shields.io/github/stars/xerj-org/xerj) |
| [mcp-memory-server](https://github.com/Amio242/mcp-memory-server) | Persistent shared memory server for AI agents via MCP | ![Stars](https://img.shields.io/github/stars/Amio242/mcp-memory-server) |
| [AMP](https://github.com/RewFa-CEO/AMP) | Cross-agent memory hub: one shared store via MCP & REST, TS + Python + Chrome capture — *maintained by this list's curator* | ![Stars](https://img.shields.io/github/stars/RewFa-CEO/AMP) |

**Coding-agent memory**

| Project | What it is | Stars |
| --- | --- | --- |
| [codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) | Local code intelligence connecting code, docs & inference | ![Stars](https://img.shields.io/github/stars/DeusData/codebase-memory-mcp) |
| [engram](https://github.com/Gentleman-Programming/engram) | Persistent memory for AI coding agents; agent-agnostic Go binary | ![Stars](https://img.shields.io/github/stars/Gentleman-Programming/engram) |
| [ECC](https://github.com/affaan-m/ECC) | Agent harness system with unified memory vault, skills & security scanning | ![Stars](https://img.shields.io/github/stars/affaan-m/ECC) |

## Connect one in 30 seconds

Any MCP memory server plugs into Claude Desktop (`claude_desktop_config.json`) or Cursor/Claude Code (`.mcp.json`) the same way:

```json
{
  "mcpServers": {
    "memory": {
      "command": "node",
      "args": ["/path/to/the/memory/server"]
    }
  }
}
```

Once connected, memories written in one client are visible in every other client. That is the entire pitch of MCP memory — pick a server above, never re-explain yourself to an AI again.

## Selection criteria / 收录标准

- Entry must be **installable today** and relevant to memory × MCP (server, client, or spec).
- No dead links; star badges update live; entries re-verified monthly (last: **2026-10-27**).
- Curator's own projects are allowed but must be disclosed inline — see AMP above.

Contributions welcome — open an issue or PR with the repo link and one-line description. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[![CC0](https://img.shields.io/badge/License-CC0-lightgrey)](LICENSE) — public domain, do whatever you want.
