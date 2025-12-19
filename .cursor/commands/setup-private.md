# Command: /setup-private

## Objective
Create a private copy of LifeOS for personal use, with upstream tracking for template updates.

## Workflow

1. **Check prerequisites**:
   - Verify `gh` CLI is installed and authenticated (`gh auth status`)
   - If not, guide user to install: `brew install gh && gh auth login`

2. **Get repo name**:
   - Ask user what they want to name their private repo (default: `life-os-private`)

3. **Save current origin as upstream** (for pulling template updates):
   ```bash
   git remote rename origin upstream
   ```

4. **Create private repo and set as origin**:
   ```bash
   gh repo create <repo-name> --private --source=. --remote=origin --push
   ```

5. **Confirm success**:
   - Show the new private repo URL
   - Confirm remotes: `origin` → their private repo, `upstream` → public template
   - Explain how to pull future updates: `git fetch upstream && git merge upstream/main`
   - Prompt: "Ready to personalize! Run `/onboard` to set up your profile."
