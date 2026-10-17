# GitHub Starter — Quick guide for beginners

This short guide helps you get started contributing to this repository (or any GitHub project). It's intentionally brief — follow these steps the first few times, then you'll learn the shortcuts.

## 1. Make a local clone

Open a terminal and run:

```bash
git clone https://github.com/stel79/builtenv-code.git
cd builtenv-code
```

If the repo is private, use the GitHub CLI or authenticate with a Personal Access Token (PAT) or your SSH key.

## 2. Create a branch for your work

Always make changes on a branch, not on main:

```bash
git checkout -b feat/short-description
```

Name branches clearly: `fix/`, `feat/`, or `doc/` followed by a short slug.

## 3. Make changes and commit

Edit files (README, docs, code). Stage and commit small logical changes with clear messages:

```bash
git add README.md
git commit -m "docs: improve README quick-start" 
```

Follow the pattern: type(scope): short summary — e.g., `feat(prototype): add download button`.

## 4. Push your branch and open a Pull Request

```bash
git push -u origin feat/short-description
```

Then open a Pull Request on GitHub (the web UI will usually show a "Compare & pull request" button).

In the PR description explain what you changed and why, include screenshots if needed, and reference any related issues.

## 5. Respond to feedback and iterate

Reviewers may request changes — make commits on the same branch and push. The PR will update automatically.

## 6. Merge and clean up

When approved, merge via the GitHub UI (Squash or Merge). Then delete your branch locally and remotely:

```bash
git checkout main
git pull
git branch -d feat/short-description
git push origin --delete feat/short-description
```

## Tips

- Keep PRs small and focused.
- Run tests or linters before pushing if present.
- Use the GitHub web UI for quick edits to docs when appropriate.
- Ask maintainers for a small starter task if you're unsure where to begin.

Happy contributing! If you want, I can add this content to CONTRIBUTING.md or a beginner docs page and link to it from the README — tell me which file name to use and I'll commit it.