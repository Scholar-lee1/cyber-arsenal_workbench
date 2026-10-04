# Basic Git commands


## Overview

Here, I've simplified git for anyone who wants to learn, alongside are images shown as examples;

- 
- 
- 

---

### The Three States 

- The Working directory: This are files or folders in your hard drive. 

- The Staging Area (Waiting room): This holds a snapshot of what you want to put on your git hub.

- The Repository: The vault, ya project history is immutable and permanent.

---

### Transitioning

Once the project you want to put on  git-hub is ready, you'll take the following steps/commands;

- 1: `git init` 
  This initialize your repository, that is telling git to start tracking your project from where you are.
  You can type **git status** to tell you about the machine state, here it will tell you "Untracked" (i.e., it's in the room but not in the factory system yet)

- 2: `git add <file>`
  This command moves your file from your woring directory to the staging area.
  When you type **git status**, it says "Changes to be committed" (i.e., it's in the waiting room)

- 3: `git commit -m "<message>"
  You've then move it from the staging area to your repository vault.
  Git says: "nothing to commit, working tree clean" (All three rooms are perfectly synced)
