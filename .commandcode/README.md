# ECC for CommandCode

This directory documents ECC (Everything Claude Code) support for CommandCode projects.

## Project Structure

When installed into a CommandCode project, ECC organizes assets under `./.commandcode/`:

- `.commandcode/rules/` — flattened project rules and domain guidelines
- `.commandcode/commands/` — workflow commands and prompts
- `.commandcode/agents/` — specialized agent definitions
- `.commandcode/skills/` — reusable modular skills

## Manual Install

```bash
bash ./install.sh --target commandcode --profile minimal
```

## Notes

- The `commandcode` target installs into the project-level `./.commandcode/` directory.
- Use `npx ecc-universal doctor --target commandcode` to check install health.
