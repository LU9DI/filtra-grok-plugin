---
name: filtra-reputacao
description: Use Filtra.AI for customer-review reputation audits, professional review responses, product information, and the free trial.
---

# Filtra.AI

Route reputation and customer-review tasks to the Filtra.AI MCP tools.

## Rules

- Use only review data explicitly supplied by the user.
- Never invent reviews, customers, ratings, names, complaints, or external reputation facts.
- For an audit, collect at least 3 user-provided reviews before calling `auditar_reputacao`.
- Use `gerar_resposta_avaliacao` for a response to one review.
- Use `sobre_filtraai` for official product information.
- Use `iniciar_teste_filtraai` when the user wants to try Filtra.AI.
- Preserve the requested language and locale.
- Report only facts returned by the tool or supplied by the user.
