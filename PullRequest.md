
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

<img width="1920" height="1080" alt="Pull request image 1" src="https://github.com/user-attachments/assets/c3b31fad-3871-446b-a2d0-4551ef10cbe6" />




<img width="1920" height="1080" alt="Pull request image 2" src="https://github.com/user-attachments/assets/43cc7977-a45b-42f7-9fae-e83e319c275d" />

<img width="1920" height="1080" alt="Pull request image 3" src="https://github.com/user-attachments/assets/db55c564-d238-4371-9cc0-0034badc5fa9" />

<img width="1920" height="1080" alt="Pull request image 4" src="https://github.com/user-attachments/assets/031750a4-1a9a-4d04-b471-37a1b090c9ce" />

<img width="1920" height="1080" alt="Pull request image 5" src="https://github.com/user-attachments/assets/0bf3de0f-e1e0-4953-a477-88124002d891" />
