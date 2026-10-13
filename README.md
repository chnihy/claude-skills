# claude-skills

Personal skills for Claude Code. Each top-level folder is one skill, with a `SKILL.md` and optional `references/`.

## Skills

- `google-dev-style`: write every reply and every document in the Google developer documentation style. A distillation of the [Google developer documentation style guide](https://developers.google.com/style), which is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## Install on a new machine

Claude Code loads user skills from `~/.claude/skills/`. This repository is that folder.

If `~/.claude/skills/` doesn't exist yet, clone directly:

```
git clone https://github.com/chnihy/claude-skills.git ~/.claude/skills
```

If it already exists (Claude Code creates a `synced/` folder there), initialize in place and pull:

```
cd ~/.claude/skills
git init -b main
git remote add origin https://github.com/chnihy/claude-skills.git
git pull origin main
```

The `synced/` folder is ignored by git.

## Make a skill always-on

A skill loads when its description matches the task. To apply one to every reply, point to it from a CLAUDE.md file that Claude Code loads for every project. For the style skill, add this under your global preferences in `~/.claude/CLAUDE.md`:

```
### Communication style

Every reply and every piece of prose follows the `google-dev-style` skill in
`~/.claude/skills/google-dev-style/`. Load it at the start of every session.
```

## Git identity

Commit from the personal account:

```
git config --local user.name "chnihy"
git config --local user.email "69132469+chnihy@users.noreply.github.com"
```
