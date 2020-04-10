# Git shortcuts

## Description
Setting terminal macros for git commands will help to make git commands more declarative and easier to remember (and of course use).

# Preferred git shortcuts
Add the following to the .gitconfig file in your $HOME directory (or create it if it's not exiting):

```
[alias]
  co = checkout
  ci = commit
  st = status
  new = checkout -b
  delete = branch -D
  up = pull --rebase
```

## Source
[A full guide on adding git aliases](https://githowto.com/aliases)
