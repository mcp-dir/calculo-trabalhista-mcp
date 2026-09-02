# Instalação detalhada

Cálculo Trabalhista é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_calculo-trabalhista`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_calculo-trabalhista` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_calculo-trabalhista` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_calculo-trabalhista` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.calculotrabalhista` (ou `servers.calculotrabalhista` no VS Code) do config do cliente e reinicie.
