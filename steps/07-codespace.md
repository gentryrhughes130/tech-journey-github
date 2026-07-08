# Bonus Step 7: Launch a Codespace

**Previous step:** [Step 6 - Open a Pull Request](06-pull-request.md)
**Next step:** [Step 8 - Code with GitHub Copilot](08-copilot.md)

---

## You Finished the Core Course!

Steps 1-6 taught you the complete git workflow using **github.dev**, the lightweight browser editor. This bonus module unlocks something more powerful: a full cloud computer that can **run your code** and use an **AI assistant called GitHub Copilot**.

To use Copilot, you first need a place that can actually run it. That place is a **Codespace**.

---

## github.dev vs. Codespaces

You have been using github.dev — great for editing and committing, but it is just an editor. It cannot run programs or install tools like Copilot.

A **Codespace** is a real, full-powered computer that lives in the cloud and opens right in your browser. Same VS Code look, but with superpowers.

| | github.dev (Steps 1-6) | Codespace (this step) |
|---|---|---|
| Edit and commit files | Yes | Yes |
| Runs in your browser | Yes | Yes |
| A real terminal | No | Yes |
| Run code (Python, etc.) | No | Yes |
| Install extensions | No | Yes |
| **GitHub Copilot** | **No** | **Yes** |

Think of github.dev as a notepad and a Codespace as a full workshop.

---

## Is It Free?

Yes. Personal GitHub accounts get a **generous free monthly allowance** for Codespaces (at the time of writing, 120 core-hours and 15 GB of storage per month — enough for many hours of learning). You will not be charged as long as you stay within it.

Two habits keep you safely inside the free allowance:
- **Stop your Codespace when you finish** (covered at the bottom of this page).
- **Do not leave many Codespaces running** at once.

---

## Your Task: Create a Codespace

1. Go to your forked repository on **github.com** (not github.dev).
2. Make sure you are on the **`add-about-me`** branch — click the branch dropdown near the top-left and select it. Your Codespace will open on whatever branch is selected.
3. Click the green **`< > Code`** button near the top-right.
4. In the dropdown, click the **Codespaces** tab.
5. Click **Create codespace on add-about-me**.

GitHub now builds your cloud computer. The first time takes a minute or two — you will see a screen with build logs. When it finishes, a full VS Code editor opens in your browser.

---

## Getting to Know Your Codespace

Once it loads, you will see:

- **Left sidebar** — the file explorer, just like github.dev.
- **A terminal at the bottom** — this is new! It is a real command line. If you do not see it, open it from the menu: **Terminal → New Terminal** (or press `` Ctrl+` ``).
- **Bottom-left corner** — shows your branch name (`add-about-me`).

Try it out. Click into the terminal, type the command below, and press Enter:

```bash
git status
```

You just ran a real git command on a real machine in the cloud. This is the exact workflow professional developers use every day.

---

## How to Know You Did It

- The browser tab title includes your repo name and the word **Codespaces**.
- There is a working **terminal** at the bottom that responds to commands.
- The file explorer on the left shows the repo files, including your `exercises/about-me.md`.

---

## Important: Stop Your Codespace When You Are Done

Your Codespace keeps using your free hours while it is running. When you finish a session, **stop it** so you do not waste your allowance:

1. Go to **[github.com/codespaces](https://github.com/codespaces)**.
2. Find your Codespace in the list.
3. Click the **`...`** menu next to it and choose **Stop codespace**.

A stopped Codespace keeps all your files and picks up right where you left off next time — it just stops the clock. If you are completely done and want to free up storage, choose **Delete** instead (but only after your work is committed and pushed!).

> **Tip:** Codespaces also stop themselves automatically after about 30 minutes of inactivity, so you are protected even if you forget.

---

**You completed Step 7!** Head to [Step 8 - Code with GitHub Copilot](08-copilot.md).
