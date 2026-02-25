## 🚀 Team Commit Workflow

This repo uses a shared commit hygiene system to keep our Git history clean and professional.

### 🧹 What’s Included
- **Commit Message Style Guide** (`COMMIT_GUIDE.md`)
- **One-Page Cheat Sheet** (`docs/commit-cheat-sheet.png`)
- **Pre-Push Hook** (`.githooks/pre-push`)

### Setup
After cloning, run:
```bash
git config core.hooksPath .githooks
```

Workflow
Commit freely while coding.

Before pushing, the hook prompts you to tidy up commits.

Push only clean, atomic commits.

See COMMIT_GUIDE.md for full style rules.

Code

---

### 2. `COMMIT_GUIDE.md`
Drop this file into your repo root:

```markdown
# 📝 Commit Message Style Guide
```

## Structure
<type>(<scope>): <short summary>

<detailed explanation of what changed and why>
Refs: <issue/ticket number if applicable>

Code

## Conventional Commit Types
- **feat**: new feature
- **fix**: bug fix
- **chore**: maintenance/tooling
- **docs**: documentation only
- **style**: formatting/linting
- **refactor**: code restructure
- **perf**: performance improvement
- **test**: add/modify tests
- **ci**: CI/CD changes
- **build**: build system/deps
- **revert**: revert previous commit

## Best Practices
- Use imperative mood: “add feature” not “added”
- Keep subject ≤ 50 characters
- Separate subject and body
- Explain the “why”
- Reference issues/tickets
- Make atomic commits
