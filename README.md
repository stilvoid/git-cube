# Git Cube

> Clean Up Before Exit: git edition

A tool to help you never to forget to commit and push your code changes.

## Installing Git Cube

To install, you need to add a line to your `.bashrc` file:

```bash
source /path/to/git-cube
```

With that done, the next terminal you open will have Git Cube installed.

## Usage

When you exit a terminal session by typing `exit` or pressing `ctrl-d`, git-cube will scan your current directory and if it's part of a git repository that contains uncommitted code, or commits that haven't been pushed to the remote, it will prompt you to take action before closing your session.

## Bugs

I wrote this in a few minutes and it is very unlikely to be perfect.

Please submit an issue through GitHub when you find a bug.
