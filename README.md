# for-claude

## Setup

Skills are installed under `.agents/skills/` (gitignored) and pinned in `skills-lock.json`.
After cloning, restore them with:

```sh
npx skills
```

`.claude/skills` is a tracked symlink to `.agents/skills`, so Claude Code picks them up
once the install has run.
