
# Pull Request

## What is a Pull Request?
A Pull Request (PR) is a GitHub feature used to request merging changes from one branch into another branch. It allows other developers to review the changes before they are merged.

## Why Use a Pull Request?
- To review code before merging.
- To discuss changes with team members.
- To improve code quality.
- To collaborate safely.
- To keep the project organized.

## Steps:
- Push your branch to GitHub.
- Open the repository on GitHub.
- Click Compare & pull request or it will directly show pull request at the top.
- Add a title and description.
- Click Create pull request.
- Review the changes.
- Click Merge pull request if approved.

## Example
``Current Branch:
``
feature-login

``Target Branch:
``
main

After pushing the branch:
git push -u origin feature-login

Go to GitHub and create a Pull Request from:


``feature-login → main
``

## Output
After the Pull Request is merged, the changes from the source branch become part of the target branch.


## Common Errors

### Error 1
```text
There isn't anything to compare.
```

**Reason:**
Both branches contain the same changes.

**Solution:**
Make new changes and push them before creating a Pull Request.

---

### Error 2
```text
Merge conflict
```
**Reason:**
The same part of a file was modified in both branches.

**Solution:**
Resolve the conflict, commit the changes, and update the Pull Request.

## What I Learned
- Learned what a Pull Request is.
- Learned how to create a Pull Request on GitHub.
- Understood why Pull Requests are important for collaboration.
- Learned how Pull Requests help review code before merging.

## My Practice
I created a separate branch, made changes, pushed it to GitHub, and created a Pull Request to understand the complete GitHub workflow.
