# Git Demo
This repository is designed to demo basic functionality of git as a version control system.

## Installing & Setting Up Git
Download & Install Git here: [https://git-scm.com/downloads](https://git-scm.com/downloads). *(see the "Download for Windows" button)*.
The installation wizard will take you through many menus and configuration options. It is fine to leave them all default and keep clicking **next**!
- After installation, open command prompt. 
- Run `git --version` to check which version of git you have installed.
    - If you get an error that sounds like *"___ is not recognized as an internal or external command"*, you may need to restart your computer.
- Run `git config --global user.email "me@email.com"`, replacing *me@email.com* with your email.
- Run `git config --global user.name "First Last"`, replacing *First Last* with your name.

## Cloning this repo locally
```
git clone https://github.com/TimHanewich/git-demo
```

## Some commands
- `git status` - Which files in this directory have been changed since the last commit?
- `git diff` - Specifically, what changed in those files since the last commit?
- `git add` - Add a file's changes to the staging area (prepare for a commit)
- `git commit` - Commit the staged changes to the change log (git)