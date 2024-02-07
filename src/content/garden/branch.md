---
title: "Branch"
---

A [Git](git) branch is a path of one or more [commits](commit).
Different branches allow developers to work on the same piece of code in isolated environments.

When working alone on a small project a single `main` branch works perfect most of the time.
Add a new `feat/{feature-name}` branch when it is desired to test in isolation or when doing an entire project refactoring.

Use `lower-kabab-case` for naming branches,
and use an underscore `_` for including an issue identifier in the branch name:

```
feat/add-primary-navigation-component_#29
```

or for [Jira](https://www.atlassian.com/software/jira) tickets:

```
fix/navigation-overflow-on-mobile_APP-43
```

A single feature branch should ideally only solve one issue,
so adding an issue identifier should work most of the time.

It is perfectly fine to have a long branch name.
A more descriptive name is always better.
[Bash](bash), [Zsh](zsh) and other shells have branch autocompletion for
Git branches and for graphical interfaces the branch name length does not matter either.
