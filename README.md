# Mini Claude Code

Python-only version of a minimal coding agent inspired by Claude Code.

The code lives in [src/](src), with the CLI entry point in [src/__main__.py](src/__main__.py).

## What is included

- Agent loop and CLI
- Tool execution, permissions, and session handling
- Memory, skill, subagent, and MCP client modules
- MIT license

## Requirements

- Python 3.11+
- `anthropic`
- `openai`
- `rich`

## Run locally

From the project root:

```bash
pip install anthropic openai rich
pip install -e .
mini-claude-py
```

You can also pass a one-shot prompt:

```bash
mini-claude-py "explain this repository"
```

## Project layout

- [pyproject.toml](pyproject.toml) - Python project metadata and dependencies
- [LICENSE](LICENSE) - MIT license
- [src/](src) - Python source code

## Notes

The repository is intentionally code-only now.
