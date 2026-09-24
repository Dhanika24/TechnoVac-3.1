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
3. In the description write `Closes #1`, then add 1-2 lines about what you did. Example:
   ```
   Closes #1

   Added my contributor card with my name, favorite language, and a fun fact.
   ```
4. Click **Create pull request**.

### Step 6: Wait for review

An organizer will add the `technovac 3.1` label, review your PR, and merge it. After the merge you will get the `technovac 3.1 accepted` label. 🎉

If we ask for a change, edit your file in the same branch and the PR updates automatically.

## Rules

- **Branch names** use the format `type/short-name`, for example `feat/octocat` for your card or `fix/typo-readme` for a fix.
- **Commit messages** use the format `type: subject`, all lowercase, no period at the end. Use `feat:` for your card, `fix:` for typo fixes, `docs:` for documentation.
- **One contributor card per person.** Comment on issue #1 first.
- **One bonus fun-fact page per person** (optional, see below).
- Name your file after **your own GitHub username**, so nobody edits the same file.
- Follow the template. No empty files, spam, or offensive content.
- Only add or edit **your own file**. Don't change other people's files.

## Labels

| Label                    | Added by  | Meaning                                    |
| ------------------------ | --------- | ------------------------------------------ |
| `technovac 3.1`          | Organizer | Event contribution                         |
| `technovac 3.1 accepted` | Organizer | Contributor card PR reviewed and merged    |
| `technovac 3.1 bonus`    | Organizer | Bonus fun-fact page PR reviewed and merged |

Only pull requests with `technovac 3.1 accepted` count for the prizes. The **first 5 correct PRs** win. Bonus pull requests do not count.

## Finished early? Bonus task

Do your contributor card first. Then pick **one** fun-fact page issue (space, football, movies, food, or gaming) in the [Issues](https://github.com/IEEE-Student-Branch-NSBM/TechnoVac-3.1/issues) tab and repeat the same steps:

1. Comment `I'll take this` on the issue.
2. In your fork, open the `facts` folder and click **Add file → Create new file**.
3. Name it `TOPIC-YOUR-GITHUB-USERNAME.html` (for example `space-octocat.html`).
4. Copy everything from [`facts/TEMPLATE.html`](https://github.com/IEEE-Student-Branch-NSBM/TechnoVac-3.1/blob/main/facts/TEMPLATE.html), paste it, and change the topic, your username, and the 3 facts.
5. Commit to a new branch named `feat/TOPIC-YOUR-GITHUB-USERNAME` (for example `feat/space-octocat`) with the message `feat: add TOPIC fun-fact page`.
6. Open a pull request with `Closes #ISSUE-NUMBER` in the description, and add 1-2 lines about what you added.

Facts must be true and in your own words. Bonus PRs are great practice, but they do not count toward the prizes.

## Prefer the terminal? (optional)

If you already have Git installed, clone **your fork** (not the original repo):

```bash
git clone https://github.com/YOUR-USERNAME/TechnoVac-3.1.git
cd TechnoVac-3.1
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