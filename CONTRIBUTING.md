# Contributing to WatchTower AI

This repository is the knowledge layer of the WatchTower community. Every contribution should make it easier for builders to find, learn and build with AI.

---

## Before You Contribute

Ask yourself:

1. **Have I actually used this?** We only accept tested, real-world content.
2. **Would another builder find this useful?** If it only works for your specific setup, add context about that.
3. **Does it already exist here?** Search the repo first to avoid duplicates.

---

## Quickstart: Submitting Your First PR

There are two ways to contribute. Pick the one you're comfortable with.

### Option A — Web only (no terminal, recommended for first-timers)

1. Click **Fork** (top right of this repo) to create your own copy.
2. In your fork, navigate to the directory that fits your content (e.g. `prompts/`, `workflows/`).
3. Click **Add file → Create new file**, or open an existing template in `templates/content-templates/` and click the pencil icon to edit.
4. Name your file using lowercase and hyphens (e.g. `code-review-with-context.md`).
5. Paste your content using the matching template.
6. Scroll down, write a short commit message, and click **Commit changes**.
7. Go back to the main page of your fork. You will see a banner: **"This branch is X commits ahead of gugastork/watchtower-ai:main"** → click **Contribute → Open pull request**.
8. Fill in the PR template and click **Create pull request**. Done!

### Option B — Terminal (Git)

```bash
# 1. Fork this repo on GitHub first (button at the top right)

# 2. Clone YOUR fork (replace YOUR-USERNAME)
git clone https://github.com/YOUR-USERNAME/watchtower-ai.git
cd watchtower-ai

# 3. Create a descriptive branch
git checkout -b add-claude-code-review-prompt

# 4. Add your file in the right directory, then:
git add .
git commit -m "Add Claude Code review prompt with context"

# 5. Push to YOUR fork (origin), NOT to gugastork/watchtower-ai
git push origin add-claude-code-review-prompt

# 6. Open the URL printed by Git, or go to your fork on GitHub
#    and click "Compare & pull request".
```

### Common issues

- **"Permission denied" when pushing** → You are trying to push to the original repo. You can only push to *your fork*. Run `git remote -v` and make sure `origin` points to `https://github.com/YOUR-USERNAME/watchtower-ai.git`.
- **HTTPS asking for a password** → GitHub no longer accepts account passwords on the CLI. Use a [Personal Access Token](https://github.com/settings/tokens) as the password, or switch to SSH.
- **"Compare & pull request" button does not appear** → Make sure you committed to a branch *other than* `main` in your fork, and that the branch was pushed. Refresh your fork's page.
- **Got stuck?** Open an issue with the `help wanted` label or ask in the WatchTower community.

---

## How to Contribute

1. **Fork** this repository
2. **Create a branch** with a descriptive name (e.g. `add-claude-code-git-workflow`)
3. **Use the content template** from [`templates/content-templates/`](templates/content-templates/) for your content type
4. **Place your file** in the correct directory and subdirectory
5. **Submit a pull request** using our PR template

---

## Where to Contribute

| Directory | What goes here | Example |
|---|---|---|
| `prompts/` | Tested prompts with context and expected output | A Claude Code prompt for code review with examples |
| `workflows/` | Step-by-step AI workflows | How to use Claude Code + GitHub Actions for PR reviews |
| `tools/` | Plugins, CLI tools, open source utilities | A CLI tool that automates prompt testing |
| `templates/` | Reusable project structures | A PRD template for AI-powered products |
| `case-studies/` | Real experiments with results | "How we automated X and saved Y hours" |
| `summaries/` | Distilled insights from papers, tutorials, discussions | Summary of a research paper with practical takeaways |
| `resources/` | Curated links with context about why they matter | A list of repos for building AI agents, with notes |

---

## Quality Standards

### We accept

- Prompts you have tested and refined with real results
- Workflows you actually use in your projects
- Case studies with honest results (including failures)
- Tools you have built or meaningfully contributed to
- Summaries that distill complex content into actionable insights
- Resources with personal context about why they are valuable

### We do not accept

- Untested prompts copied from other sources without attribution or added value
- Generic content that reads like a blog post rewrite
- Self-promotion disguised as a contribution
- Content without context (a prompt without explaining when to use it)
- Theoretical frameworks with no practical application
- AI-generated content that has not been reviewed and validated by the author

---

## Content Format

All contributions must be in **Markdown**.

Every file must include:

- **Title** â clear and specific
- **Description** â what it does and why it exists
- **Context** â when to use it, prerequisites, limitations
- **Content** â the actual prompt, workflow, template, etc.
- **Author** â your name and optional link

Use the content templates in [`templates/content-templates/`](templates/content-templates/). They are designed to keep contributions consistent and useful.


This repository is the knowledge layer of the WatchTower community. Every contribution should make it easier for builders to find, learn and build with AI.

---

## Before You Contribute

Ask yourself:

1. **Have I actually used this?** We only accept tested, real-world content.
2. **Would another builder find this useful?** If it only works for your specific setup, add context about that.
3. **Does it already exist here?** Search the repo first to avoid duplicates.

---

## Quickstart: Submitting Your First PR

There are two ways to contribute. Pick the one you're comfortable with.

### Option A — Web only (no terminal, recommended for first-timers)

1. Click **Fork** (top right of this repo) to create your own copy.
2. In your fork, navigate to the directory that fits your content (e.g. `prompts/`, `workflows/`).
3. Click **Add file → Create new file**, or open an existing template in `templates/content-templates/` and click the pencil icon to edit.
4. Name your file using lowercase and hyphens (e.g. `code-review-with-context.md`).
5. Paste your content using the matching template.
6. Scroll down, write a short commit message, and click **Commit changes**.
7. Go back to the main page of your fork. You will see a banner: **"This branch is X commits ahead of gugastork/watchtower-ai:main"** → click **Contribute → Open pull request**.
8. Fill in the PR template and click **Create pull request**. Done!

### Option B — Terminal (Git)

```bash
# 1. Fork this repo on GitHub first (button at the top right)

# 2. Clone YOUR fork (replace YOUR-USERNAME)
git clone https://github.com/YOUR-USERNAME/watchtower-ai.git
cd watchtower-ai

# 3. Create a descriptive branch
git checkout -b add-claude-code-review-prompt

# 4. Add your file in the right directory, then:
git add .
git commit -m "Add Claude Code review prompt with context"

# 5. Push to YOUR fork (origin), NOT to gugastork/watchtower-ai
git push origin add-claude-code-review-prompt

# 6. Open the URL printed by Git, or go to your fork on GitHub
#    and click "Compare & pull request".
```

### Common issues

- **"Permission denied" when pushing** → You are trying to push to the original repo. You can only push to *your fork*. Run `git remote -v` and make sure `origin` points to `https://github.com/YOUR-USERNAME/watchtower-ai.git`.
- **HTTPS asking for a password** → GitHub no longer accepts account passwords on the CLI. Use a [Personal Access Token](https://github.com/settings/tokens) as the password, or switch to SSH.
- **"Compare & pull request" button does not appear** → Make sure you committed to a branch *other than* `main` in your fork, and that the branch was pushed. Refresh your fork's page.
- **Got stuck?** Open an issue with the `help wanted` label or ask in the WatchTower community.

---

## How to Contribute

1. **Fork** this repository
2. **Create a branch** with a descriptive name (e.g. `add-claude-code-git-workflow`)
3. **Use the content template** from [`templates/content-templates/`](templates/content-templates/) for your content type
4. **Place your file** in the correct directory and subdirectory
5. **Submit a pull request** using our PR template

---

## Where to Contribute

| Directory | What goes here | Example |
|---|---|---|
| `prompts/` | Tested prompts with context and expected output | A Claude Code prompt for code review with examples |
| `workflows/` | Step-by-step AI workflows | How to use Claude Code + GitHub Actions for PR reviews |
| `tools/` | Plugins, CLI tools, open source utilities | A CLI tool that automates prompt testing |
| `templates/` | Reusable project structures | A PRD template for AI-powered products |
| `case-studies/` | Real experiments with results | "How we automated X and saved Y hours" |
| `summaries/` | Distilled insights from papers, tutorials, discussions | Summary of a research paper with practical takeaways |
| `resources/` | Curated links with context about why they matter | A list of repos for building AI agents, with notes |

---

## Quality Standards

### We accept

- Prompts you have tested and refined with real results
- Workflows you actually use in your projects
- Case studies with honest results (including failures)
- Tools you have built or meaningfully contributed to
- Summaries that distill complex content into actionable insights
- Resources with personal context about why they are valuable

### We do not accept

- Untested prompts copied from other sources without attribution or added value
- Generic content that reads like a blog post rewrite
- Self-promotion disguised as a contribution
- Content without context (a prompt without explaining when to use it)
- Theoretical frameworks with no practical application
- AI-generated content that has not been reviewed and validated by the author

---

## Content Format

All contributions must be in **Markdown**.

Every file must include:

- **Title** â clear and specific
- **Description** â what it does and why it exists
- **Context** â when to use it, prerequisites, limitations
- **Content** â the actual prompt, workflow, template, etc.
- **Author** â your name and optional link

Use the content templates in [`templates/content-templates/`](templates/content-templates/). They are designed to keep contributions consistent and useful.

---

## File Naming

Use lowercase with hyphens:

```
prompts/claude-code/code-review-with-context.md
workflows/n8n/slack-to-notion-ai-summary.md
case-studies/startups/automating-customer-onboarding.md
```

---

## Pull Request Guidelines

When submitting a PR:

- Use a clear title that describes the contribution
- Fill in the PR template completely
- Link to any related issues or discussions
- Be open to feedback â maintainers may suggest improvements

---

## Review Process

All contributions are reviewed by maintainers. We check for:

1. **Practical value** â does it help builders?
2. **Quality** â is it well-structured and clear?
3. **Accuracy** â has the author tested this?
4. **Fit** â is it in the right directory with the right format?

Reviews usually happen within a few days. We may ask for changes before merging.

---

## Code of Conduct

Please read our [Code of Conduct](CODE_OF_CONDUCT.md) before contributing.

We value respectful communication, collaboration and learning by building. Harassment, disrespect or personal attacks will not be tolerated.

---

## Questions

If you are unsure about anything, open an issue or ask in the WatchTower community before submitting.
