# 🤝 Contributing - Technovac 3.1

This guide takes about **10 minutes**. You only need a **GitHub account** and a browser.

## Step by step (browser only)

### Step 1: Fork the repository
1. Open https://github.com/IEEE-Student-Branch-NSBM/TechnoVac-3.1/fork (or click the **Fork** button at the top right of the repo).
2. Click **Create fork**.

This makes your own copy of the repo under your account.

### Step 2: Pick an issue
1. Open the main issue: https://github.com/IEEE-Student-Branch-NSBM/TechnoVac-3.1/issues/1
2. Comment: `I'll take this`.
3. Remember the issue number (`#1`). You need it in Step 5.

### Step 3: Create your file
1. Open **your fork** (the URL has your username).
2. Open the `contributors` folder.
3. Click **Add file → Create new file**.
4. Name it `YOUR-GITHUB-USERNAME.html` (for example `octocat.html`).
5. Copy everything from [`contributors/TEMPLATE.html`](https://github.com/IEEE-Student-Branch-NSBM/TechnoVac-3.1/blob/main/contributors/TEMPLATE.html), paste it, and change:
   - Your name
   - Your GitHub username
   - Your favorite language
   - A fun fact about you

### Step 4: Commit your changes
1. Click **Commit changes...**
2. Write a commit message: `feat: add contributor card for your-name`
3. Select **Create a new branch for this commit and start a pull request**.
4. Change the branch name to `feat/YOUR-GITHUB-USERNAME` (for example `feat/octocat`).
5. Click **Propose changes**.

### Step 5: Open the pull request
1. Check that the pull request is going **from your fork to the original repo**.
2. Title: `feat: add contributor card for your-name`
3. In the description write: `Closes #1`
4. Click **Create pull request**.

### Step 6: Wait for review
An organizer will add the `technovac 3.1` label, review your PR, and merge it. After the merge you will get the `technovac 3.1 accepted` label. 🎉

If we ask for a change, edit your file in the same branch and the PR updates automatically.

## Rules

- **Branch names** use the format `type/short-name`, for example `feat/octocat` for your card or `fix/typo-readme` for a fix.
- **Commit messages** use the format `type: subject`, all lowercase, no period at the end. Use `feat:` for your card, `fix:` for typo fixes, `docs:` for documentation.
- **One card per person.**
- Name your file after **your own GitHub username**, so nobody edits the same file.
- Follow the template. No empty files, spam, or offensive content.
- Only edit **your own file**. Don't change other people's files.
- One issue per person. Comment on it first.

## Labels

| Label | Added by | Meaning |
|---|---|---|
| `technovac 3.1` | Organizer | Event contribution |
| `technovac 3.1 accepted` | Organizer | PR reviewed and merged |

Only pull requests with `technovac 3.1 accepted` count for the prizes. The **first 5 correct PRs** win.

## Finished early?

Pick one of the small extra [issues](https://github.com/IEEE-Student-Branch-NSBM/TechnoVac-3.1/issues) (fun-fact pages) and repeat the same steps. Extra PRs are great practice, but each person can win only once.

## Prefer the terminal? (optional)

If you already have Git installed, clone **your fork** (not the original repo):

```bash
git clone https://github.com/YOUR-USERNAME/test-technovac-3.1-pr-challange.git
cd test-technovac-3.1-pr-challange
git checkout -b feat/YOUR-GITHUB-USERNAME
# create contributors/YOUR-GITHUB-USERNAME.html
git add .
git commit -m "feat: add contributor card for yourname"
git push origin feat/YOUR-GITHUB-USERNAME
```

Then open GitHub, click **Compare & pull request**, and write `Closes #1`.

## Stuck?

Raise your hand. A mentor will help you.

## Code of Conduct

Be kind, respectful, and helpful. We are all here to learn.