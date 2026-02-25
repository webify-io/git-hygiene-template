# 🚀 Team Onboarding Checklist

Welcome to the project! Follow this checklist to get set up with our Git hygiene workflow and commit standards.

---

## ✅ Step 1: Clone the Repo
```bash
git clone <repo-url>
cd <repo-name>
```
## ✅ Step 2: Enable Shared Git Hooks
Point Git to use the versioned .githooks folder:

```bash
git config core.hooksPath .githooks
```
This ensures the pre-push hook runs automatically before you push.

## ✅ Step 3: Review Documentation
- Read [Looks like the result wasn't safe to show. Let's switch things up and try something else!] for full commit message rules.

- Check [Looks like the result wasn't safe to show. Let's switch things up and try something else!] for quick formatting reference.

- Look at [Looks like the result wasn't safe to show. Let's switch things up and try something else!] to visualize the commit workflow.

## ✅ Step 4: Write Commits Using the Style Guide
- Use conventional commit types (feat, fix, chore, etc.).

- Keep commits atomic (one logical change per commit).

- Explain the “why” in the commit body when needed.

## ✅ Step 5: Run Hygiene Before Pushing
The pre-push hook will:

- Show staged changes and recent commits.
- Prompt you to tidy up commits (git rebase -i HEAD~5).
- Ensure you push only clean, professional history.

## ✅ Step 6: Push Confidently
Once hygiene is complete, push your branch:

```bash
git push origin <branch-name>
```