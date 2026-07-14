# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

**mcpserver-operator** is an expert-advisor / tutor system for securely **deploying, configuring, operating, and maintaining** Model Context Protocol (MCP) servers. In the MCP Security ecosystem it is the **"operate"** step: after a server is found, audited, and built, this repo teaches the operational-security mindset — deployment risk assessment, security controls, and ongoing operational excellence.

Like its sibling repos, it is an **expert guidance system**, not a deployment tool — teaching users to make good operational decisions rather than automating deployment for them.

## Current state

This repository is **early-stage: a vision/spec, not yet an implementation.** As of this writing it contains only `README.md` (a detailed statement of intent), `LICENSE`, and `CODE_OF_CONDUCT.md` — there are **no prompts, checks, templates, code, or build/test system yet**. Do not look for a build/lint/test workflow.

When building this out, follow the pattern of the more mature sibling `mcpserver-audit`: a prompt-driven knowledge system (conversational tutoring prompts, modular guidance documents, templates) authored in Markdown. The README describes the intended capability areas — operations education, practical deployment guidance, and expert orchestration — which is the natural structure for that content.

## Ecosystem role

Part of the **ModelContextProtocol-Security** workflow, positioned at the end of the server lifecycle:

1. **mcpserver-finder** — discover servers
2. **mcpserver-audit** — find vulnerabilities
3. **mcpserver-builder** — build/fix securely
4. **mcpserver-operator** (this repo) — deploy and operate securely

Closely related to `mcpserver-hosting` (the hosting-infrastructure angle). It also draws on `vulnerability-db` and `audit-db` for operational risk context. Keep terminology, the expert-tutor voice, and security framing consistent with these siblings — especially `mcpserver-audit`, whose structure this repo should mirror as it grows.

## Contributing

`main` is protected and requires a code-owner-approved pull request. Contributions are documentation/knowledge; value is measured by how effectively they teach secure MCP server operations, not by passing tests.
