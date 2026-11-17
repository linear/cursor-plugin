# Linear Agent Plugin

The product development system for teams and agents. Manage issues, projects, documents, and everything else across your Linear workspace.

## Overview

This plugin connects compatible AI assistants to Linear through the remote [Linear MCP server](https://linear.app/docs/mcp) at `https://mcp.linear.app/mcp`. The [`linear-workspace`](skills/linear-workspace/SKILL.md) skill gives the assistant general rules for working safely in Linear. Task details come from the MCP server's live tool descriptions.

## Prerequisites

- A Linear account in the workspace that you want to use. Sign up at [linear.app](https://linear.app).
- No local software. The MCP server is hosted by Linear and runs over HTTPS.

## Authentication and permissions

The Linear MCP server uses OAuth 2.1. The first time the assistant calls a Linear tool, you sign in to Linear and approve access for the workspace.

- The assistant acts as you. It can see and change only what your Linear account can see and change.
- Guests and members with limited team access see only the teams they belong to.
- Workspace admins can review and revoke connected applications in Linear under **Settings → Security & access**.
- Some tools, such as initiatives and customers, are available only when the workspace uses those features.

## Installation

### Gemini

Install **Linear** from the Gemini plugin marketplace, then sign in to Linear when prompted.

### Cursor

1. Open **Customize** in Cursor's sidebar.
2. Find **Linear** in the marketplace.
3. Select **Install** and choose project or user scope.
4. Connect Linear and complete the OAuth sign-in.

Once connected, ask the assistant to work with Linear, for example: "Find my open Linear issues."

## Support

- **Documentation:** https://linear.app/docs/mcp
- **Support:** support@linear.app
- **Privacy Policy:** https://linear.app/privacy
- **Terms of Service:** https://linear.app/terms
