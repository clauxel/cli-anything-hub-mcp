# Evaluation Guide

Use this page to evaluate whether CLI Anything Hub fits a real workflow.

## What To Test

- CLI tool MCP
- CLI Anything Hub
- CLI Anything Hub documentation
- CLI Anything Hub remote MCP
- clianythingharness server card

## Expected Evidence

- Open CLI Anything Hub and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://clianythingharness.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call cli_tool_list with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.
- Validate release or migration gates against a staging workflow before production rollout.

## Buyer Path

Default plan: team.

- https://clianythingharness.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=clianythingharness_public_docs&utm_content=evaluation_checkout
