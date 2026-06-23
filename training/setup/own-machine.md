# Set Up VS Code + Claude Code on Your Own Machine

Five steps. Takes about 10 minutes. Free.

---

## Step 1 — Download VS Code

Go to [code.visualstudio.com](https://code.visualstudio.com) and click the big download button for your operating system (Windows or Mac).

Run the installer. Accept all defaults.

---

## Step 2 — Install the Claude Code extension

Open VS Code. On the left sidebar, click the **Extensions icon** (four squares, or press `Ctrl+Shift+X`).

In the search bar at the top, type:
```
Claude Code
```

Click the result from **Anthropic**. Click **Install**.

---

## Step 3 — Create an Anthropic account

Go to [claude.ai](https://claude.ai) and sign up for a free account if you do not already have one.

You will need this to authenticate Claude Code.

---

## Step 4 — Sign in to Claude Code

Open a terminal in VS Code (press `` Ctrl+` ``).

Type this and press Enter:
```
claude
```

It will open a browser window and ask you to log in with your Anthropic account. Log in. The terminal will confirm you are signed in.

---

## Step 5 — Open a project folder

In VS Code, go to **File > Open Folder** and create or open a folder where you want to work. Call it something like `my-agents`.

Click the asterisk (*) icon in the left sidebar to open the Claude Code panel. You are ready.

---

## You are set up

From here, everything works the same as it did in training. Type your requests in plain English into the Claude Code panel. Review what it builds. Run it from the terminal.

---

## Stuck?

The most common issues:

**"claude: command not found"** — Claude Code CLI is not installed. Run:
```
npm install -g @anthropic-ai/claude-code
```
(If npm is not installed, download Node.js from [nodejs.org](https://nodejs.org) first.)

**Extension not showing up** — Restart VS Code after installing.

**Authentication expired** — Run `claude` in the terminal again to re-authenticate.

---

## Next steps

Once you are set up at home, open the templates from today's session and pick your next agent to build. Start with the plug and play template — you have already done the hard part.
