# 21 Questions — A Git Practice Repo

## Synopsis

Welcome! This repository is a playground for practicing the everyday **Git**
workflow. Instead of dry exercises, you'll learn the commands by playing a game
of **21 Questions**.

The plan is simple:

1. **Fork** this repository to your own GitHub account.
2. **Clone** your fork to your computer.
3. Make a copy of [`21_questions.txt`](21_questions.txt) and play a round of the
   game by filling it in.
4. **Add**, **commit**, and **push** your completed game sheet back to your fork.
5. **Pull** to keep your local copy in sync.

By the time you've finished a game, you'll have used the core Git commands that
power day-to-day software development.

---

## How to Play 21 Questions

21 Questions is a classic guessing game for two or more people.

**The rules:**

1. One player is the **Host**. The Host secretly thinks of a *person, place,
   thing, or animal* and writes it down (don't show anyone yet!).
2. The other player is the **Guesser**. The Guesser asks up to **21 questions**
   to figure out what the Host is thinking of.
3. Every question must be answerable with **"Yes" or "No"** (e.g. *"Is it
   alive?"*, *"Is it bigger than a car?"*). The Host answers honestly.
4. The Guesser can make a final guess at any time. If they guess correctly
   within 21 questions, **the Guesser wins**. If they run out of questions or
   guess wrong, **the Host wins**.
5. Swap roles and play again!

**Tip:** Start with broad questions to narrow things down quickly
(*"Is it a living thing?"*) before asking specific ones (*"Does it bark?"*).

Use the [`21_questions.txt`](21_questions.txt) template to record your game.

---

## Common Git Commands

These are the commands you'll use in this exercise. Run them from a terminal
inside your cloned repository.

### Fork (on GitHub)

Forking happens **on the GitHub website**, not in the terminal. Click the
**"Fork"** button in the top-right of this repo's GitHub page. This creates your
own personal copy of the repository under your account that you can freely edit.

### Clone

Download your fork from GitHub to your local machine:

```bash
git clone https://github.com/<your-username>/21_questions.git
cd 21_questions
```

### Add

Stage the changes you want to save (here, your game sheet):

```bash
git add my_game.txt
# or stage everything that changed:
git add .
```

### Commit

Save your staged changes to your local history with a descriptive message:

```bash
git commit -m "Play my first round of 21 questions"
```

### Push

Upload your local commits to your fork on GitHub:

```bash
git push
```

### Pull

Download and merge the latest changes from GitHub into your local copy:

```bash
git pull
```

**A typical workflow looks like this:**

```bash
git add my_game.txt
git commit -m "Add my completed game sheet"
git push
```

---

## Disclaimer

This README and the accompanying template were **written by Claude** (an AI
assistant by Anthropic). The exercise concept is **Jon Chin's** own idea, and
Jon critically reviews all generated content.
