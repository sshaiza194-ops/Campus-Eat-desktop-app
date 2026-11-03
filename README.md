
<img width="463" height="231" alt="image" src="https://github.com/user-attachments/assets/f0d86ec8-e1cf-4f8a-a904-ae13d5574bc0" />

# My App

An app built with [Builder.io](https://www.builder.io) on the
[Agent-Native](https://agent-native.com?utm_source=github&utm_medium=referral&utm_content=fusion-starter-readme) framework. Replace this paragraph with
what the app does and who it's for.

## Develop locally

```bash
cp .env.example .env
corepack enable
pnpm install
pnpm dev
```

`.env.example` sets `AUTH_DISABLED=true` as a commented-out option; uncomment it
to skip sign-in while developing.

## Project layout

- `app/`: routes and UI components
- `actions/`: operations shared by the UI and the app's agent
- `server/`: server plugins and the database client
- `drizzle/`: schema and migrations; start with `drizzle/START_HERE.md`

Framework docs: [agent-native.com/docs](https://agent-native.com/docs?utm_source=github&utm_medium=referral&utm_content=fusion-starter-readme).

## netlify
https://cheerful-dasik-003e37.netlify.app/
