# Module 4 — The Three Parts of Any Agent

Every AI agent, no matter how simple or complex, has exactly three parts. Once you can describe these three parts in plain English, you can build almost anything.

---

## The Framework

```
TRIGGER  →  TASK  →  OUTPUT
```

| Part | Question to answer | Examples |
|------|-------------------|---------|
| **Trigger** | What starts it? | A new email arrives / 9am every morning / someone fills out a form / a file changes |
| **Task** | What does it do? | Read something / write something / check something / send something / calculate something |
| **Output** | Where does the result go? | An email in your inbox / a row added to a spreadsheet / a message on your phone / a file saved |

---

## Three real examples

**Example 1 — Daily inbox summary**
- Trigger: Every morning at 8am
- Task: Read all emails received in the last 24 hours, summarise anything marked urgent
- Output: Send me a 5-bullet summary by email

**Example 2 — Missed appointment follow-up**
- Trigger: A patient misses an appointment (entry added to booking system)
- Task: Draft a warm follow-up email to rebook
- Output: Email sent to patient, copy to clinic manager

**Example 3 — Competitor price monitor**
- Trigger: Every Monday morning
- Task: Check a competitor website for pricing changes since last week
- Output: Send me a short note if anything changed, silence if nothing changed

---

## Your agent (fill this in)

Open `student/my-agent-blueprint.md` to fill in your own Three Parts.

---

## During the live build

Your instructor will build the **Daily Inbox Summary Agent** from scratch in front of you.

Watch for:
1. How the request is phrased — plain English, specific, no jargon
2. What Claude Code does with that request
3. How the instructor reviews and approves each step
4. The moment the agent actually runs

Then you will build your own.
