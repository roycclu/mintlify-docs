# Source: https://lovable.dev/mcp

Model Context Protocol

# The MCP built for 
agentic development

Build, iterate, and deploy full-stack apps on Lovable from the AI client you already work in. Powered by the Model Context Protocol.

assistant — lovable mcp

›You

Use Lovable to build me a SaaS landing page for an AI receipt scanner. Add a hero, pricing, and a waitlist form wired to a Supabase table.

›Assistant

- Calling create\_project…
- Calling send\_message — “Build the landing page with hero, pricing, waitlist…”
- Calling read\_file on src/pages/Index.tsx
- Calling execute\_sql — creating waitlist table

✓Preview ready at receipt-scanner.lovable.app

[Connect your client](https://lovable.dev/mcp#setup) [Read the docs](https://docs.lovable.dev/integrations/lovable-mcp-server)

Works with AI assistants, Cursor, and VS Code · Available on every plan.

## Everything an agent needs to ship a real app

The Lovable MCP server exposes the same primitives Lovable runs on: projects, chat, files, connectors, databases, and deploys, as tools any agent can call.

## Create projects from a prompt

Spin up a new Lovable app from your agent. One tool call, full project scaffolded with React, Tailwind, and shadcn/ui.

## Iterate via chat

Tell Lovable what you want changed. It reads the code, makes the edits, and rebuilds the preview.

## Read files, inspect diffs

List files, read source, and review the diff from every agent response.

## Add Lovable connectors

Browse Lovable's connector catalog and wire up Gmail, Notion, Linear, and more from inside your agent. Your workspace's data plane, configured by chat.

## Lovable Cloud database

Enable Lovable Cloud, run live SQL, and pull connection info, all from your agent. Reads, writes, and schema changes.

## Deploy to production

Trigger a deploy from your agent and get back a live URL. Iterate and share, all programmatically.

## Workspaces & projects

List projects, fetch metadata, manage workspaces. Everything an agent needs to operate across all your Lovable projects.

## Persistent knowledge

Set workspace and project knowledge so Lovable follows your standards, brand, and API patterns on every run.

## Built for agents

Typed tool schemas, structured outputs, and clear error responses. Designed for agents from day one.

## Connect your client

Pick your client and follow the steps. Authentication uses OAuth, so there are no API keys to manage.

ClaudeClaude CodeCursorVS Code

Add Lovable through Claude's connector settings. Works in Claude Desktop (macOS and Windows) and on claude.ai.

1. 1In Claude, Click on the + sign
2. 2Connectors → Browse Connectors → Search for Lovable
3. 3Click Connect, then sign in to Lovable when Claude prompts you

The Lovable tools appear in the composer's tool menu once authentication is complete.

[Read the full docs](https://docs.lovable.dev/integrations/lovable-mcp-server) [View pricing](https://lovable.dev/pricing)

## Frequently asked questions

### What is MCP?

The Model Context Protocol is an open standard that lets AI agents discover and call external tools. When an agent connects to an MCP server, it can see what tools are available and decide when to use them. Lovable's MCP server makes Lovable one of those tools, findable, invokable, and composable.

### Which clients can I use?

OAuth is currently supported for the assistant and editor clients listed in the setup section below. Other MCP clients cannot complete the OAuth flow at this time.

### What's the difference between this and Lovable's chat connectors?

Chat connectors let the Lovable agent connect to your external tools (Notion, Linear, Miro, and so on) during a build. The Lovable MCP server is the reverse: it lets your assistant or editor connect to Lovable and drive it programmatically.

### Is it included in my plan?

Yes — the Lovable MCP server is available on every plan, including Free. Enterprise customers should reach out to their account executive to enable it for their workspace.

### Can I connect with an API key?

Not currently. OAuth is the only supported way to connect. The MCP server uses your Lovable user permissions — it can only access workspaces you already have access to.