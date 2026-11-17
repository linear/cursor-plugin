---
name: linear-workspace
description: Works in the user's Linear workspace through the Linear MCP server, including issues, projects, cycles, initiatives, status updates, and documents. Use when the user asks to "find my Linear issues", "create a Linear issue", "update LIN-123", "how is the project going", "post a project update", or "find the spec in Linear". Don't use for other issue trackers or for work outside Linear.
---

# Linear Workspace

The Linear MCP server is the source of truth for how to use it. Its server instructions and tool descriptions explain references, filters, paging, and write behavior, and they change as Linear adds tools. Follow them. Do not ask the user to install anything locally.

## Workflow

1. **Resolve**: Find the exact team, person, issue, or project that the request refers to. Ask the user to choose when a reference matches more than one item. Never guess an ID.
2. **Read**: Use the narrowest query that answers the question. Say when a result is partial.
3. **Check before writing**: Search for an existing item before you create one. Show the planned change and ask the user to confirm first when the request is ambiguous, changes many items, or posts text that you drafted for other people to read, such as a status update.
4. **Verify**: Read the write tool's response. Tell the user what changed and include the link from the response. If a call fails, report the error instead of retrying with guessed values.

If no tool can do what the user asks, say that the capability is not available.
