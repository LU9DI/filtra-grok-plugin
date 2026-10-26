# Agent guidance — filtra-grok-plugin

This repository exposes Filtra.AI reputation tools through Grok/MCP. The README states that analysis uses reviews supplied by the user and must not claim unsupported access to external review platforms.

## Skill routing
- MCP tool schemas, names, input/output contracts, or compatibility: read .agents/skills/mcp-tool-contract-review/SKILL.md.
- Review analysis, generated replies, user-provided data, or privacy: read .agents/skills/privacy-safe-reputation-analysis/SKILL.md.

## Validation
Inspect .grok-plugin metadata and the existing skills directory before changing tool behavior. Never invent capabilities or expose credentials.
