# 📝 Commit Message Style Guide

## Why It Matters
Commit messages are not just notes for ourselves—they’re a **shared changelog**.  
Clear, consistent messages help teammates understand changes quickly, make reviews smoother, and generate automated release notes.

---

## Structure
Each commit message should follow this format:
```
<type>(<scope>): <short summary>

<detailed explanation of what changed and why>
Refs: <issue/ticket number if applicable>
```

---

## Conventional Commit Types
- **feat**: introduce a new feature
- **fix**: patch a bug or resolve an error
- **chore**: routine tasks, maintenance, tooling changes
- **docs**: documentation changes only
- **style**: code style changes (formatting, whitespace, linting)
- **refactor**: code restructuring without changing behavior
- **perf**: performance improvements
- **test**: adding or modifying tests
- **ci**: continuous integration / deployment changes
- **build**: build system or external dependencies
- **revert**: revert a previous commit

---

## Examples
- `feat(auth): add JWT-based login flow`
- `fix(mailtrap): load API key from env to resolve Unauthorized error`
- `docs(readme): add setup instructions for Mailtrap`
- `chore(deps): update axios to v1.7.0`

---

## Best Practices
- Use **imperative mood**  
  - ✅ “add feature”  
  - ❌ “added feature”  

- Keep subject line **≤ 50 characters**  
  - Short and concise summary  

- Separate subject and body  
  - One line for summary  
  - Blank line  
  - Then details  

- Explain the **“why”**  
  - Future readers care more about reasons than code diffs  

- Reference issues/tickets  
  - Link external context when relevant  

- Make **atomic commits**  
  - One logical change per commit  

---

## Hygiene Workflow
1. Commit freely while coding.  
2. Before pushing, run hygiene (interactive rebase).  
   - Squash noisy commits like “fix typo” into the main commit.  
3. Push a clean, professional history.  

---

## 🎯 Goal
With this guide, our team’s commit history becomes a **clear, reliable changelog** instead of a messy diary.
