# git-practice-bt25cse212

| | |
|---|---|
| **Name** | Adarsh dubey|
| **Roll Number** | BT25CSE200 |
| **Section** | CSE C |
| **Course** | IT Workshop - I (CSP 201), IIIT Nagpur |

## About this assignment

This repository is my Git and GitHub practice for the IT Workshop lab. I wrote a few small Bash programs and used them to practise the full Git workflow: creating a repository, making commits, working on feature branches, opening issues and pull requests on GitHub, and resolving a merge conflict.

## Completed exercises

| # | Folder | What it does |
|---|--------|--------------|
| 1 | [exercise-01-greeting](exercise-01-greeting) | Reads a name and prints a greeting; handles empty input |
| 2 | [exercise-02-menu](exercise-02-menu) | Menu program: greet, add two integers, even/odd check, exit (with `help.txt`) |
| 3 | [exercise-03-factorial](exercise-03-factorial) | Factorial of a number; rejects negative input |
| 4 | [exercise-04-even-odd](exercise-04-even-odd) | Checks whether a number is even or odd |
| 5 | [exercise-05-merge-conflict](exercise-05-merge-conflict) | Creating and resolving a merge conflict (see `git-commands.md`) |

## How to compile and run

The programs are Bash scripts, so **no compilation is needed**. You need Bash (Git Bash on Windows, or any Linux/macOS terminal).

```bash
cd exercise-01-greeting
bash greet.sh                 # type your own input
bash greet.sh < input.txt     # use the sample input
```

The same pattern works for the other exercises:

```bash
bash exercise-02-menu/menu.sh < exercise-02-menu/input.txt
bash exercise-03-factorial/factorial.sh < exercise-03-factorial/input.txt
bash exercise-04-even-odd/evenodd.sh < exercise-04-even-odd/input.txt
```

Each exercise folder has an `input.txt` (sample input) and an `output.txt` (sample output).

### Sample output (Exercise 1)

```
Enter your name:
Hello, Ekansh! Welcome to Git Lab.
```


## Git practice record

See [git-commands.md](git-commands.md) for the commands I used, what each one does, and how I resolved the merge conflict.
