# Git terminal shortcuts

## Description
For maximizing productivity while using GitLab, there is a need to utilize more of it's features via the terminal.

## GitLab shortcuts
* `goto` - Open a GitLab repository on the current branch in your default web browser. This can be done with adding the following alias in Fish terminal (notice that this could be adapted for zsh or bash terminals).

```
open (echo (echo (git config --get remote.origin.url) | sed 's/\.[^.]*$//')/tree/(git symbolic-ref HEAD | sed 's!refs\/heads\/!!'))
```
