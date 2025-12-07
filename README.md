# opencode-copilot-auth

OpenCode plugin for GitHub Copilot authentication.

## Usage

Add to your `opencode.json`:

```json
{
  "plugins": ["@sachnun/opencode-copilot-auth"]
}
```

Then set the environment variable to disable default plugins:

```bash
export OPENCODE_DISABLE_DEFAULT_PLUGINS=1
```

## Publishing

```bash
npm publish --access public
```
