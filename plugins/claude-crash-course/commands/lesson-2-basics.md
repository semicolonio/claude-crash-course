---
description: Lesson 1 - Core Concepts & Context Management
allowed-tools: Bash(ls:*), Bash(pwd:*), Write(*), Read(*), Edit(*)
---

# Lesson 1: How My Brain Works (Context Management)

You're going to work with me a lot. Let me explain how my memory works so you can use me effectively.

---

## Step 1: I Have Memory... But It's Limited

Think of me like your computer's RAM. I can remember our conversation, but there's a limit.

**Here's the concept:** I have a "context window" - everything we discuss takes up space in it.

**Ask me to show you:**
"Check the context usage with /context"

Go ahead, try it!

*Wait for user to ask, then run /context command to show current usage, then continue...*

---

## Step 2: What Just Happened?

See those numbers? That's my memory usage.

**What fills my context:**
- Our conversation history
- Files you reference with @
- Code I read or write
- Command outputs

**Why this matters:** When my context gets full, I might "forget" earlier parts of our conversation. This is called **context rot**.

**Make sense?** Just say "yes" or ask questions!

*Wait for user response, then continue...*

---

## Step 3: The @ Symbol - Your Best Friend

Instead of loading everything into my brain, you can point me to exactly what I need.

**Try this:**
"Create three files: ideas.txt, notes.txt, and todo.txt with some sample content"

*Wait for user to ask, then create the three files, then continue...*

---

## Step 4: Now Use @

Great! Now those files exist. But I don't automatically read them unless you tell me to.

**Ask me:**
"What's in @ideas.txt?"

Notice how you used @ before the filename? That tells me to load ONLY that file.

*Wait for user to ask, then read the specific file and respond, then continue...*

---

## Step 5: Why @ Matters

See the difference?

**Without @:** I might search through all files or make assumptions

**With @:** I know exactly which file you mean, and I only load what's needed

**This keeps my context clean and focused.**

**Try another one:**
"Add a new idea to @ideas.txt about learning AI"

*Wait for user to ask, then edit the file, then continue...*

---

## Step 6: The /clear Command

Here's a critical tip: when you start a NEW task, use `/clear` to wipe my memory.

**Why?**
- Removes old conversation clutter
- Gives me a fresh start
- Keeps me focused on the current task
- Prevents context rot

**Try it now:**
Type `/clear` to clear our conversation

*Wait for user to clear, then continue...*

---

## Step 7: Fresh Start

Hi again! Notice how our conversation reset?

Everything before is gone from my memory. This is GOOD when switching tasks.

**Use /clear when:**
- Starting a completely new task
- I seem confused about context
- You want to change topics
- My responses get less focused

**Quick check:** When would you use /clear? (Just answer in your own words)

*Wait for user response, then continue...*

---

## Step 8: Practical Example

Let me show you a real workflow:

1. You're debugging a feature (I have lots of context)
2. You finish, now want to write documentation
3. Type `/clear` to start fresh
4. Use @ to reference only the files you need for docs

**This keeps me sharp and efficient.**

**Ready to practice?** Say "yes" or "ready"!

*Wait for user response, then continue...*

---

## Step 9: Practice Time

Let's put this together:

**Task 1:** Ask me to create a file called project.md with a project idea

**Task 2:** Use `/clear` to reset

**Task 3:** Use @ to reference @project.md and ask me to improve it

Try it now!

*Wait for user to complete the tasks, helping with each step, then continue...*

---

## Step 10: You're Getting Good At This

Excellent! You now understand:

✅ **Context windows** - My memory has limits
✅ **@ symbol** - Reference specific files efficiently
✅ **/clear command** - Start fresh when switching tasks
✅ **Context rot** - Why keeping focus matters

**These are fundamental skills** for working with me effectively.

**Next up:** Learn how to work with images!

Type `/claude-crash-course:lesson-3-files` when you're ready for Lesson 2.

---

*Pro tip: Check your context usage regularly with /context. If it's above 50%, consider using /clear for your next task!*
