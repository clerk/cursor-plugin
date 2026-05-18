# Clerk Plugin for Cursor

The Clerk plugin for [Cursor](https://cursor.com) gives Cursor the tools and skills needed to work effectively with Clerk authentication.

## What's Included

- **MCP Server** - Remote connection to the [Clerk MCP server](https://mcp.clerk.dev) for SDK snippets, quickstart guides, and documentation
- **Skills** - Agent skills from [clerk/skills](https://github.com/clerk/skills) for setup, custom UI, framework patterns, mobile SDKs, organizations, billing, webhooks, and testing

## Skills

| Skill | Purpose |
|-------|---------|
| `clerk` | Router - automatically routes to the right skill based on your task |
| `clerk-setup` | Add Clerk authentication to any supported framework |
| `clerk-backend-api` | Browse and execute Clerk Backend API requests |
| `clerk-custom-ui` | Custom sign-in/sign-up flows and appearance |
| `clerk-nextjs-patterns` | Advanced Next.js patterns - proxy, Server Actions, caching |
| `clerk-react-patterns` | React SPA patterns with hooks and protected routes |
| `clerk-astro-patterns` | Astro middleware, SSR pages, islands, and API routes |
| `clerk-nuxt-patterns` | Nuxt 3 middleware, composables, server API routes, and SSR |
| `clerk-vue-patterns` | Vue 3 composables, router guards, and Pinia integration |
| `clerk-react-router-patterns` | React Router v7 loaders, actions, SSR, and protected routes |
| `clerk-tanstack-patterns` | TanStack React Start server functions and route guards |
| `clerk-chrome-extension-patterns` | Chrome Extension popup, sidepanel, sync host, and server auth |
| `clerk-expo-patterns` | Expo and React Native auth patterns with SecureStore and deep linking |
| `clerk-android` | Native Android auth with Kotlin and Jetpack Compose |
| `clerk-expo` | Native Expo auth with prebuilt and custom flows |
| `clerk-swift` | Native Swift and iOS auth with ClerkKit and ClerkKitUI |
| `clerk-orgs` | Multi-tenant B2B organizations with RBAC |
| `clerk-billing` | Subscription management, plans, checkout, and billing webhooks |
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
