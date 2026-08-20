# Instalação detalhada

Registradores (ARISP) Matrícula: Novo Pedido de Visualização de Matrícula é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_registradores_matric_pedido`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_registradores_matric_pedido` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_registradores_matric_pedido` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_registradores_matric_pedido` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.registradores_matric_pedido` (ou `servers.registradores_matric_pedido` no VS Code) do config do cliente e reinicie.
