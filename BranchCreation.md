# Git Branch

## What is a Branch?
A branch is used to work on new changes without affecting the main branch.


## Why Use a Branch?
- To work on new features safely.
- To test ideas without changing the main branch.
- To allow multiple people to work on the same project.


## Syntax

Create a new branch:

```bash
git branch <branch-name>
```

## Common Error

```text
 Error: pathspec 'feature-login' did not match any file(s) known to git
```

**Reason:**
The branch does not exist.

**Solution:**
Create the branch first:

```bash
git branch feature-login
```


## My Practice
I created new branches, switched between branches, and learned how branches help manage changes safely.