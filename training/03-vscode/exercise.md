# Module 3 Exercise — Your First Claude Code Request

## What you are doing

You are going to type a plain-English request into the Claude Code panel and see what it builds. This is the same skill you will use in Module 4 to build your real agent.

---

## Step 1 — Open the Claude Code panel

Click the **asterisk (*) icon** in the left sidebar.

You should see a chat-style panel open on the left. If it asks you to sign in, let your instructor know — your environment should already be authenticated.

---

## Step 2 — Type your first request

Copy and paste this exactly into the Claude Code chat input and press Enter:

```
Create a file called hello.md in my student workspace. 
Inside it, write a short paragraph about what my business does 
and one task that I spend too much time on every week. 
Use placeholders like [YOUR BUSINESS NAME] and [REPETITIVE TASK] 
so I can fill it in.
```

Watch what happens. Claude Code will:
1. Tell you what it is going to do
2. Ask for your approval before creating the file
3. Create the file once you approve

---

## Step 3 — Approve and review

Claude Code will pause and ask before making changes. Read what it says, then click **Allow** (or type `yes`).

Then open `student/hello.md` in the Explorer to see what it created.

---

## Step 4 — Give it a follow-up instruction

Now try a follow-up. Type something like:

```
Replace [YOUR BUSINESS NAME] with [type your actual business name here] 
and replace [REPETITIVE TASK] with [describe your actual repetitive task].
```

Claude will edit the file. Check `student/hello.md` again — it should now have your real information.

---

## What just happened

You described what you wanted in plain English. Claude Code:
- Created a file
- Wrote content inside it
- Edited it based on your follow-up

That is the core skill. In Module 4 you will use the same approach to build something that actually runs and saves you time every week.

---

## Checkpoint

Before moving on, make sure:
- [ ] You can see the Claude Code panel
- [ ] `student/hello.md` exists in your Explorer
- [ ] It has your actual business name and repetitive task filled in

Raise your hand if any step did not work — this is the right time to troubleshoot.
