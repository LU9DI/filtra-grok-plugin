---
name: mcp-tool-contract-review
description: Review MCP tool schemas, input validation, errors, and compatibility for the Filtra Grok plugin.
---
# MCP tool contract review

- Treat tool names, descriptions, input schemas, output shapes, and error behavior as a public contract.
- Validate every input and reject unsupported fields or malformed data explicitly.
- Keep tool descriptions precise about actual capability; do not imply access to external platforms unless an integration exists and is authorized.
- Return bounded, structured outputs with clear error states and no stack traces or secrets.
- Preserve backward compatibility or document versioned breaking changes.
- Test valid input, missing/extra fields, malformed values, empty data, upstream failure, and oversized payloads.
- Do not put credentials in tool schemas, prompts, examples, or logs.
