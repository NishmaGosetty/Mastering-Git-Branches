# Mastering Git Branches
A step-by-step guide to learning Git branching using the interactive [Learn Git Branching](https://learngitbranching.js.org/) website.

# Table of Contents

1. [Introduction Sequence](#introduction-sequence)
   - [Introduction to Git Commits](#introduction-to-git-commits)
   - [Branching in Git](#branching-in-git)
   - [Merging in Git](#merging-in-git)
   - [Rebase Introduction](#rebasing-introduction)
2. [Ramping Up](#ramping-up)
   - [Detach yo' HEAD](#detach-yo'-head)
   - [Relative Refs (^)](#relative-refs-1)
   - [Relative Refs #2 (~)](#relative-refs-2)
   - [Reversing Changes in Git](#reversing-changes-in-git)
3. [Moving Work Around](#moving-work-around)
   - [Cherry-pick Intro](#cherry-pick-intro)
   - [Interactive Rebase Intro](#interactive-rebase-intro)

Happy Branching!🌱

## Introduction Sequence

### Introduction to Git Commits

#### Concept
A commit records a snapshot of all tracked files in a Git repository.
Instead of copying the entire directory on every commit, Git stores commits efficiently by saving only the changes (deltas) between versions when possible.
Git maintains a history of commits, where most commits have ancestor commits. These relationships form a commit history, which is commonly visualized using arrows.
Commits are lightweight, and switching between them is fast.

#### Command 
the command that is used to perform commit is:
```bash
git commit
```
This command saves a snapshot of your project in Git. 

#### Performing the Task
Here is a step-by-step task to practice committing

![Introduction to git commits task](intro_sequ_task1_1.png)

The Goal that need to be reached after performing the task is as follow:

![Introduction to git commits task goal](intro_sequ_task1_2.png)

The Task can be performed by running the following commands:
Step 1 :
```bash
git commit
```

Step 2 :
```bash
git commit
```
The goal is successfully achieved, and your task is completed.
