# Live Build — Daily Summary Agent

> This is the instructor's demo script for Module 4. Build this live in front of students, narrating each step.

---

## What we are building

An agent that runs every morning, reads a folder of notes (or a text file), and emails a plain-English summary. Simple enough to build in 20 minutes. Real enough to use tomorrow.

**The Three Parts:**
- Trigger: Run at 8am every weekday
- Task: Read `student/notes/` folder, summarise any items marked URGENT or TODAY
- Output: Print the summary (or email it if SendGrid/Gmail is connected)

---

## Instructor: how to run this build

### Step 1 — Set the scene (2 min)

Say to the room:
> "I am going to build a real agent right now using exactly what you have been doing all session — plain English instructions to Claude Code. Watch what I type, not what Claude writes. The code is not the point. The instruction is the point."

### Step 2 — Open your student workspace

In the Explorer, open your `student/` folder. This is where the agent will live.

### Step 3 — Type this into the Claude Code panel

```
I want to build a daily summary agent. Here is what it should do:

1. Read all .md and .txt files inside a folder called notes/ in my workspace
2. Look for any lines that contain the word URGENT or TODAY
3. Collect those lines into a short summary
4. Print the summary to the terminal with today's date at the top

Please create:
- The notes/ folder with one example file called example-notes.md that has a mix of normal items and a couple of URGENT ones
- A Python script called daily_summary.py that does steps 1-4
- A README.md in the notes/ folder explaining how to add new notes

Keep the code simple. I am not a developer.
```

### Step 4 — Walk through Claude's response (narrate aloud)

- Point out that Claude describes what it will do before doing it
- Show students the approval step — "I always check before clicking Allow"
- Once approved, show the files appearing in the Explorer in real time

### Step 5 — Run the agent

Open the terminal (Ctrl+`) and run:
```bash
cd /root/workspace/student
python daily_summary.py
```

Show the output. It should print today's date and the URGENT items from the example file.

### Step 6 — Add a real note

Say: "Now let me add something real."

Open `student/notes/example-notes.md` and add a line:
```
URGENT: Follow up with [client name] about the contract renewal
```

Save the file (Ctrl+S), run `python daily_summary.py` again. Show it appearing in the summary.

### Step 7 — Land the moment

Say:
> "That agent took 20 minutes to build. Every morning it could do this automatically and email it to you. At 15 minutes a day, that is over 60 hours a year you get back. Your turn."

---

## If something goes wrong

Claude Code may produce an error on first run. This is normal. Say:
> "This is what building actually looks like. Let us fix it."

Type the error message into the Claude Code panel:
```
I got this error when I ran the script: [paste error]
Please fix it.
```

Claude will correct the script. Show that the fix takes 30 seconds, not an hour.

---

## Timing

| Step | Minutes |
|------|---------|
| Set scene + open workspace | 2 |
| Type the request | 3 |
| Walk through Claude's response | 4 |
| Run the agent | 3 |
| Add a real note + re-run | 3 |
| Land the moment | 2 |
| Buffer for questions / errors | 3 |
| **Total** | **20** |
