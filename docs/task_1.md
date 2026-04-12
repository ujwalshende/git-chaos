# Task 1: Practicing on Your Own

Now it’s time to start contributing!

- [1. Create a GitHub Account 📝](#1-create-a-github-account-)
- [2. Install Git 💻](#2-install-git-)
- [3. Fork the Project 🍴](#3-fork-the-project-)
  - [3.1 Fork? What? 🤔](#31-fork-what-)
  - [3.2 Why use a fork? 💡](#32-why-use-a-fork-)
  - [3.3 How to fork 🔨](#33-how-to-fork-)
  - [3.4 Original repo vs your fork 🆚](#34-original-repo-vs-your-fork-)
- [4. Clone your fork 🐏](#4-clone-your-fork-)
  - [4.1 Clone? What? 🤔](#41-clone-what-)
  - [4.2 Why clone your fork? 🧐](#42-why-clone-your-fork-)
  - [4.3 How to clone 📖](#43-how-to-clone-)
- [5. Find an issue to work on 🔍](#5-find-an-issue-to-work-on-)
- [6. Create a new branch 🎋](#6-create-a-new-branch-)
- [7. Make your changes 🔨](#7-make-your-changes-)
- [8. Stage your changes ➕](#8-stage-your-changes-)
- [9. Commit your changes ✅](#9-commit-your-changes-)
  - [9.1 Commit? What? 🤔](#91-commit-what-)
  - [9.2 Make a commit 🔨](#92-make-a-commit-)
- [10. Push your changes 🤞](#10-push-your-changes-)
  - [10.1 Push? What? 🤔](#101-push-what-)
  - [10.2 Push your changes 🔨](#102-push-your-changes-)
  - [10.3 Why push? ❓](#103-why-push-)
- [11. Create a Pull Request (PR) 💬](#11-create-a-pull-request-pr-)
- [What happens next? 🙋](#what-happens-next-)
- [Next steps 👀](#next-steps-)

## 1. Create a GitHub Account 📝

If you don’t have a GitHub account yet, that’s your first step. GitHub is where we
host and collaborate on the project.

- <https://git-e-github.para-humanos.cumbuca.dev/5.-introducao-ao-github/5.7-criando-uma-conta-pessoal-no-github>

## 2. Install Git 💻

To contribute, you’ll need Git, the version control system that helps track code
changes.

- <https://git-e-github.para-humanos.cumbuca.dev/2.-fundamentos-de-controle-de-versao-e-git/2.4-instalando-o-git>

## 3. Fork the Project 🍴

### 3.1 Fork? What? 🤔

A fork is your own copy of a repository.

Think of it like copying a recipe so you can experiment freely without changing
the original. You can tweak, break, and improve things without affecting the main
project.

If your changes turn out great, you can suggest them back via a pull request.

### 3.2 Why use a fork? 💡

- Experiment safely
- Contribute improvements
- Learn from real projects

### 3.3 How to fork 🔨

1. Go to the repo: <https://github.com/cumbucadev/git-chaos>
2. Click **Fork** (top right)
3. You’ll get your own copy: `your-username/git-chaos`

### 3.4 Original repo vs your fork 🆚

**Original (cumbucadev/git-chaos):**
- Main source of truth
- Has issues and PRs

**Your fork (your-username/git-chaos):**
- Your playground
- Safe to experiment

Tip: always check the repo path to make sure you’re in your fork.

## 4. Clone your fork 🐏

### 4.1 Clone? What? 🤔

Cloning means downloading your fork to your computer.

### 4.2 Why clone your fork? 🧐

- Work locally
- Full control
- Use your favorite tools

### 4.3 How to clone 📖

```bash
git clone https://github.com/your-username/git-chaos.git
cd git-chaos
```

## 5. Find an issue to work on 🔍

Go to the repo → **Issues tab**
Look for:

👉 `Task 1: Create file: your-username.txt`

This issue is created just for you.

## 6. Create a new branch 🎋

```bash
git checkout -b 12
```

(Use your issue number instead of `12`)

## 7. Make your changes 🔨

Follow the issue instructions and create your file:

```plain
chaos/task_1/your-username.txt
```

## 8. Stage your changes ➕

```bash
git add chaos/task_1/your-username.txt
```

## 9. Commit your changes ✅

### 9.1 Commit? What? 🤔

A commit is a snapshot of your changes.

### 9.2 Make a commit 🔨

```bash
git commit -m "Add your-username.txt"
```

## 10. Push your changes 🤞

### 10.1 Push? What? 🤔

Push = send your changes to GitHub.

### 10.2 Push your changes 🔨

```bash
git push origin 12
```

### 10.3 Why push? ❓

* Share your work
* Backup
* Enable collaboration

## 11. Create a Pull Request (PR) 💬

1. Go to your fork on GitHub
2. Click **Compare & pull request**
3. Title:

```
Task 1: your-username.txt
```

4. Description:

```
Task 1:
- Added your-username.txt

Closes #12
```

5. Click **Create pull request**

Done 🎉

Here’s an example of a [pull request](https://github.com/cumbucadev/git-chaos/pull/4) so you can
see what it looks like.

## What happens next? 🙋

* Your PR will be reviewed
* You might get feedback
* Once approved, it will be merged

## Next steps 👀

* Check your PR for comments
* Respond and improve
* Move on to the next task

Congrats on your first open source contribution! 🚀
