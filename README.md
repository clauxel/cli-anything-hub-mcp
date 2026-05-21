# CLI Anything Hub MCP

CLI Anything Hub remote MCP for CLI tool MCP.

Paid remote MCP for CLI tool MCP, structured receipts, usage logs, and audit-ready evidence for agent and CI workflows.

## Public Endpoints

- Website: https://clianythingharness.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://clianythingharness.clauxel.com/mcp
- Server card: https://clianythingharness.clauxel.com/server-card.json
- Registry name: `com.clauxel.clianythingharness/clianythingharness-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `cli_tool_list`
- `cli_command_run`
- `cli_schema_validate`
- `cli_result_receipt`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://clianythingharness.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://clianythingharness.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://clianythingharness.clauxel.com/server-card.json
- MCP endpoint: https://clianythingharness.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
