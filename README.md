# AiVideoMontage

AI Video Montage — based on **OpenMontage** (open-source agentic video production system).

## Full source code

The **complete OpenMontage codebase** is on this account at:

### → https://github.com/aloahmilton/OpenMontage

That repo has the full tree on `main` (lib, tools, skills, pipelines, backlot, remotion-composer, docs, tests, etc.).

This `aividoemontage` repo holds a smaller set of setup files and points you to the full project.

## Quick start (full project)

```bash
git clone https://github.com/aloahmilton/OpenMontage.git
cd OpenMontage
make setup
```

Then open it in your AI coding assistant (Claude Code, Cursor, Copilot, etc.) and describe the video you want.

## Files in this repo

- `setup.py`, `requirements*.txt`, `config.yaml` — basic package setup
- `AGENTS.md`, `CONTRIBUTING.md`, `render-demo.sh` — pointers / helpers

For the real production pipelines, agent skills, and tools, use **[aloahmilton/OpenMontage](https://github.com/aloahmilton/OpenMontage)**.
