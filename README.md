<div align="center">

<img src="assets/caveman.png" alt="Caveman Mode" width="360">

# caveman

**Agent skill. Make AI talk like caveman.**

Short words. Short sentence. No fluff.

Works with [Claude Code](https://docs.anthropic.com/claude-code) and [OpenAI Codex](https://developers.openai.com/codex/skills) — same `SKILL.md`, two install paths.

</div>

---

## Install

Pick your tool. Symlink the repo into the right skills directory.

### Claude Code

```bash
ln -s "$PWD" ~/.claude/skills/caveman
```

### OpenAI Codex

User-level (any project):

```bash
mkdir -p ~/.agents/skills
ln -s "$PWD" ~/.agents/skills/caveman
```

Repo-level (one project only) — run from inside that project:

```bash
mkdir -p .agents/skills
ln -s /path/to/this/repo .agents/skills/caveman
```

## Use

### Claude Code

```
/caveman
```

Or just say *"caveman mode"*. Say *"stop caveman"* to turn off.

### Codex

```
$caveman
```

Or pick it from `/skills`. Same trigger phrases work too — *"caveman mode"* on, *"stop caveman"* off.

## Files

- [`SKILL.md`](SKILL.md) — the skill itself (frontmatter + instructions). Format is shared between Claude Code and Codex.
- [`README.md`](README.md) — this file.
- [`assets/`](assets) — image assets used by the skill / docs.

<div align="center">
<sub>grunt. speak. good.</sub>
</div>
