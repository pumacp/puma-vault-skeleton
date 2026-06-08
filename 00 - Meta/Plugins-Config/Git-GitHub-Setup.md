---
id: Git-GitHub-Setup
title: "Git & GitHub Setup Guide"
type: meta
jd: "00.04"
para: Meta
tags: [meta, git, github, setup]
created: "{{date}}"
---

# ⚙️ Git & GitHub Setup

> Optional: sync your vault with GitHub for version control, backup, and sharing. Pairs with the **Obsidian Git** plugin (see [[Recommended-Plugins]]).

## One-time setup
```bash
# 1. Create a repository (CLI shown; the web UI works too)
gh repo create my-vault --public --description "My knowledge vault"

# 2. Initialise git in the vault root (where README.md is)
cd /path/to/my-vault/
git init
git remote add origin https://github.com/<your-username>/my-vault.git

# 3. First commit
git add .
git commit -m "chore: initial vault"
git push -u origin main
```

## Daily workflow
```bash
git pull                 # get changes from another device
git add -A
git commit -m "notes: $(date +%Y-%m-%d) — short description"
git push
```

The Obsidian Git plugin can automate this (auto-pull on startup, auto-commit on an interval).

## Commit message conventions (suggestion)
| Type | Example |
|------|---------|
| New note | `feat: add permanent note on X` |
| Edit | `update: refine note on Y` |
| Fix | `fix: repair broken link in a MOC` |

## Tips
- Tag milestones: `git tag -a v1.0 -m "first stable version" && git push origin --tags`.
- Add a `.gitignore` for `.obsidian/workspace*` and any local build output.

> [!danger] Irreversible
> `git checkout -- .` permanently discards uncommitted changes. Use only when sure.

## See also
[[Recommended-Plugins]] · [[Quartz-Publishing]] · [[MOC Meta]]
