# AGENTS.md

## Build & Run
- Install: `npm install` or `bun install`
- No tests or lint configured

## Code Style
- Language: JavaScript (ESM with `.mjs` extension)
- Use JSDoc type annotations with `@type {import('...').Type}` syntax
- Formatting: 2-space indentation, trailing commas, double quotes for strings
- Constants: UPPER_SNAKE_CASE at module scope
- Functions: camelCase, prefer named function declarations for exports
- Error handling: Use try/catch with empty catch blocks only for non-critical parsing; throw Error with descriptive message for critical failures
- Async: Use async/await, prefer `await` over `.then()` chains
- Imports: ES modules only (`import`/`export`), no CommonJS

## Project Structure
- `index.mjs` - Main OpenCode plugin export (CopilotAuthPlugin)
- This is an OpenCode plugin using `@opencode-ai/plugin` types
