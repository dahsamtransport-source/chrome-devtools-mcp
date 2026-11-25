---
name: devtools-mcp-isolation-qa
description: Audit Chrome DevTools MCP build, tool safety, browser isolation and performance regression.
---

# devtools-mcp-isolation-qa

Verified package scripts: typecheck, check-format, test, test:memory, verify-server-json-version, graphify. Reuse Graphify and native test runner; no parallel Playwright dependency unless coverage gap proven. Inspect setup and use a disposable profile with no logged-in user, local fixture pages and disabled optional remote telemetry. Run existing typecheck/check-format/test only after toolchain and fixtures confirmed; verify MCP schema, navigation permissions, network and screenshot redaction, memory/performance regression. Keep upstream-compatible changes separate. Never attach to a real personal browser.

## Execution contract
Read repo instructions and existing skills first. Prefer tools already installed; external plugins are candidates until connected and approved. Keep implementation and independent QA separate. Record exact commands, results, commit SHA, blockers and rollback. No production deploy, live writes or secret transfer. Source reference: https://github.com/openai/plugins. This is an original repo-specific skill, not a copy or proof of upstream plugin installation.
