# Bonus Step 8: Code with GitHub Copilot

**Previous step:** [Step 7 - Launch a Codespace](07-codespace.md)
**Next step:** You are done — you now know git, GitHub, Codespaces, and Copilot!

---

## What Is GitHub Copilot?

**GitHub Copilot** is an AI pair programmer built into your editor. As you type, it suggests whole lines or blocks of code. You can also **chat** with it in plain English — ask it to explain code, write something for you, or fix a mistake.

Think of it as a helpful teammate who has read a huge amount of code and is always sitting next to you. It is not perfect (more on that below), but it is a powerful way to learn faster and get unstuck.

Copilot only works in a full editor like your **Codespace** — that is why you launched one in Step 7.

---

## Is Copilot Free?

Yes, there are two free paths:

1. **GitHub Copilot Free** — available to *everyone* with a GitHub account. You get a monthly allowance of code completions and chat messages, no payment or trial required. This is plenty for this course.
2. **GitHub Copilot Pro — free for students** — if you are a student, you can verify your status through **[GitHub Education](https://education.github.com/pack)** and get the full paid version of Copilot at no cost, plus lots of other free developer tools.

Start with option 1 today. If you have a school email, it is worth applying for option 2 later.

---

## Your Task: Turn On Copilot

### Step 1: Enable Copilot on your account

1. In a new browser tab, go to **[github.com/settings/copilot](https://github.com/settings/copilot)**.
2. Follow the prompts to enable **Copilot Free** (or Copilot Pro if you verified as a student).
3. Accept the terms when asked.

### Step 2: Sign in to Copilot inside your Codespace

Go back to your Codespace tab.

1. Look at the **bottom status bar** for the Copilot icon (it looks like a small robot/hexagon head).
2. If it asks you to **Sign in** or **Authorize**, click it and approve — you are already logged into GitHub, so this is quick.
3. Once connected, the Copilot icon in the status bar looks solid and active (no warning symbol).

> If you do not see the Copilot icon, open the Extensions panel on the left sidebar, search for **GitHub Copilot**, and make sure it is installed and enabled. In most Codespaces it is already there.

---

## Using Copilot: Inline Suggestions

This is the most common way to use Copilot — it finishes your code as you type.

1. In the file explorer, create a new file called `exercises/copilot-demo.md` (New File icon, same as Step 4).
2. Type this comment on the first line and then press Enter:

   ```
   <!-- A list of three cool facts about space -->
   ```

3. Wait a moment. Copilot shows **grey "ghost text"** suggesting what comes next.
4. Press **`Tab`** to accept the suggestion, or keep typing to ignore it.

That grey text is Copilot predicting what you want. Accept it with `Tab`, reject it by pressing `Esc` or just typing your own thing.

> **Try this:** Write a comment describing what you want, then pause. For example: `<!-- My three favorite video games and why -->`. Watch what Copilot suggests, and accept only the parts you actually like.

---

## Using Copilot: Chat

Copilot Chat lets you *talk* to the AI instead of just accepting suggestions.

1. Click the **Copilot Chat icon** in the left sidebar (a speech-bubble icon), or press **`Ctrl+Alt+I`**.
2. A chat panel opens. Type a question and press Enter. Try one of these:
   - `Explain what a git branch is in simple terms.`
   - `Write a short markdown "About Me" section for a student who likes robotics.`
   - `What does the command git status do?`
3. Read the answer. You can copy code from the chat into your files, or ask a follow-up question.

Chat is great when you are stuck: paste an error message and ask *"What does this mean and how do I fix it?"*

---

## Use Copilot Responsibly

Copilot is a tool, not a replacement for thinking. To use it well:

- **Read every suggestion before accepting it.** Copilot is sometimes confident but wrong.
- **Make sure you understand the code.** If you cannot explain what it does, ask Copilot to explain it — do not just accept it.
- **You are still the author.** You are responsible for the code you commit, so review it like it is your own (because it is).
- **Do not paste private or sensitive information** into chat.

The best developers use Copilot to go faster *and* to learn — not to skip the learning.

---

## Optional: Commit Your Copilot Demo

If you created `exercises/copilot-demo.md`, you can practice the full workflow again:

1. Open the **Source Control** panel (Step 5).
2. Write a commit message like `Add Copilot demo file`.
3. Click **Commit** (in a Codespace you may then need to **Sync/Push** to send it to GitHub).

You just combined everything: a branch, a Codespace, Copilot, and a commit. That is a real modern developer workflow.

---

## What You Learned in the Bonus Module

| Skill | How You Did It |
|-------|---------------|
| Launch a cloud dev environment | Codespaces tab on the Code button |
| Use a real terminal | Built-in terminal in the Codespace |
| Enable an AI assistant | Turned on Copilot Free |
| Get code suggestions | Inline ghost text, accept with `Tab` |
| Ask an AI for help | Copilot Chat panel |
| Use AI responsibly | Reviewing and understanding every suggestion |

**Congratulations — you now know git, GitHub, Codespaces, and GitHub Copilot.** These are the exact tools professional developers use every single day. Well done!
