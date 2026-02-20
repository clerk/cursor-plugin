# Clerk Plugin for Cursor

The Clerk plugin for [Cursor](https://cursor.com) gives Cursor the tools and skills needed to work effectively with Clerk authentication.

## What's Included

- **MCP Server** - Remote connection to the [Clerk MCP server](https://mcp.clerk.dev) for SDK snippets, quickstart guides, and documentation
- **Skills** - Agent skills from [clerk/skills](https://github.com/clerk/skills) for setup, custom UI, Next.js patterns, organizations, webhooks, and testing

## Skills

| Skill | Purpose |
|-------|---------|
| `clerk` | Router - automatically routes to the right skill based on your task |
| `clerk-setup` | Add Clerk to any framework (Next.js, React, Expo, Astro, etc.) |
| `clerk-custom-ui` | Custom sign-in/sign-up flows and appearance |
| `clerk-nextjs-patterns` | Advanced Next.js patterns - middleware, Server Actions, caching |
| `clerk-orgs` | Multi-tenant B2B organizations with RBAC |
| `clerk-webhooks` | Real-time events and data syncing |
| `clerk-testing` | E2E testing with Playwright/Cypress |

## Development

This repo uses a git submodule for shared agent skills.

After cloning, initialize the submodule:

```bash
git submodule update --init --recursive
```

To update the submodule:

```bash
git submodule update --remote submodules/skills
git add submodules/skills
git commit -m "chore: update skills submodule"
```

## Resources

- [Clerk Docs](https://clerk.com/docs)
- [Dashboard](https://dashboard.clerk.com)
- [Discord](https://clerk.com/discord)
- [clerk/skills](https://github.com/clerk/skills) - Skills source repository

## License

MIT
