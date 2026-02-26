# {{project_name}} — Claude Code Instructions

## Stack
- **Build:** tsup (production), Vite (development)
- **Language:** TypeScript
- **Output:** Dual ESM/CJS with type declarations

## Commands
- `bun run build` — production build with tsup
- `bun run dev` — Vite dev server
- `bun run test` — run tests with Vitest
- `bun run lint` — type check with tsc

## Key File Paths
```
src/index.ts        — main export barrel
src/utils.ts        — utility functions
src/components/     — React components (if React enabled)
src/styles/         — CSS/Tailwind styles (if CSS enabled)
src/__tests__/      — test files (if testing enabled)
tsup.config.ts      — build configuration
vite.config.ts      — dev server configuration
```

## Code Style
- Prefer editing existing files over creating new ones
- No unnecessary comments or docstrings

## Git
- Conventional commits: `feat:`, `fix:`, `chore:`, `docs:`, `build:`, `perf:`
- No Co-Authored-By lines
