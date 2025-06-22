# MiniGit – A Custom Version Control System

## Group Members

| No. | Name                | ID            |
|-----|---------------------|----------------|
| 1   | Abenezer Sisay      | ATE/5485/12    |
| 2   | Bereket Hailu       | ATE/3484/15    |
| 3   | Biniyam Abel        | ATE/8191/15    |
| 4   | Emebet Sisay        | ATE/8784/12    |
| 5   | Hailemariam Girma   | ATE/9912/12    |
| 6   | Minasie Simon       | ATE/0818/12    |
| 7   | Yonatan Megersa     | ATE/9040/12    |
| 8   | Yosef Tesfaye       | ATE/7055/12    |

---

## Project Overview

**MiniGit** is a simplified version control system built in C++ that mimics Git's core functionalities — including file tracking, commits, branching, merging, and viewing diffs. It's designed for educational purposes to demonstrate how Git works under the hood.

---

## Features

- `init` – Initialise a new MiniGit repository  
- `add <filename>` – Stage a file for the next commit  
- `commit -m "<message>"` – Save a snapshot of the staged files  
- `log` – View commit history  
- `branch <name>` – Create a new branch from the current commit  
- `checkout <branch | commit-hash>` – Switch between branches or commits  
- `merge <branch>` – Merge another branch into the current one  
- `diff <commit1> <commit2>` – Show line-by-line file differences  

---

## How to Build

> Requires: C++17 or later

```bash
g++ -std=c++17 -o minigit main.cpp
