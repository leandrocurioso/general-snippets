# Claude Commands

A reference of useful `claude` commands.

---

## `claude mcp add`

**Description:** Add an MCP server to Claude with a specified transport and optional headers

**Syntax:**
```claude
claude mcp add -s SCOPE --transport TRANSPORT SERVER_NAME SERVER_URL -H "HEADER_NAME: HEADER_VALUE"
```

**Example:**
```claude
claude mcp add -s user --transport http github https://api.githubcopilot.com/mcp -H "Authorization: Bearer <GITHUB_TOKEN>"
```

**Notes:** `-s user` sets the scope to user-level (persists across projects). Replace `<GITHUB_TOKEN>` with a valid GitHub personal access token or Copilot token.

---
