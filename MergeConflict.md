# Merge Conflict

## What is a Merge Conflict?
A merge conflict occurs when Git is unable to automatically merge changes because the same part of a file was modified in different branches.


## Why Does a Merge Conflict Happen?
- The same line of a file was modified in two branches.
- A file was deleted in one branch and modified in another branch.
- Git cannot decide which version to keep.


## Example Scenario

### Main Branch

```text
Hello World
```

### Feature Branch

```text
Hello GitHub
```

When trying to merge these branches, Git cannot decide which change should be kept.



## How to Resolve a Merge Conflict

1. Open the conflicted file.
2. Find the conflict markers added by Git.
3. Edit the file and keep the correct changes.
4. Save the file.
5. Add the resolved file to staging.
6. Commit the changes.
7. Complete the merge.

## Commands Used

```bash
git merge feature-branch
git status
git add .
git commit -m "Resolved merge conflict"
```

## Common Errors

### Error
```text
Automatic merge failed; fix conflicts and then commit the result.
```
**Reason:**
Git found conflicting changes in the same file.

**Solution:**
Resolve the conflict manually and commit the changes.


## Conclusion
Merge conflicts are a normal part of collaborative development. Understanding how to resolve them is an important Git skill for every developer.