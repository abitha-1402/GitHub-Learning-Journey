# Pull Request

## What is a Pull Request?

A Pull Request (PR) is a GitHub feature used to request merging changes from one branch into another branch. It allows other developers to review the changes before they are merged.


## Why Use a Pull Request?

- To review code before merging.
- To discuss changes with team members.
- To improve code quality.
- To collaborate safely.
- To keep the project organized.


## Syntax

A Pull Request is created on **GitHub**, not in the Git terminal.

Steps:
1. Push your branch to GitHub.
2. Open the repository on GitHub.
3. Click **Compare & pull request**.
4. Add a title and description.
5. Click **Create pull request**.
6. Review the changes.
7. Click **Merge pull request** if approved.

---

## Example

Current Branch:

```text
feature-login
```

Target Branch:

```text
main
```

After pushing the branch:

```bash
git push -u origin feature-login
```

Go to GitHub and create a Pull Request from:

```text
feature-login → main
```

---

## How It Works

1. Create a new branch.
2. Make changes in the branch.
3. Commit the changes.
4. Push the branch to GitHub.
5. Create a Pull Request.
6. Review the changes.
7. Merge the Pull Request into the main branch.

---

## Output

After the Pull Request is merged, the changes from the source branch become part of the target branch.

---

## Common Errors

### Error

```text
There isn’t anything to compare.
```

**Reason**

Both branches contain the same changes.

**Solution**

Make new changes and push them before creating a Pull Request.

---

### Error

```text
Merge conflict
```

**Reason**

The same part of a file was modified in both branches.

**Solution**

Resolve the conflict, commit the changes, and update the Pull Request.


## What I Learned

- Learned what a Pull Request is.
- Learned how to create a Pull Request on GitHub.
- Understood why Pull Requests are important for collaboration.
- Learned how Pull Requests help review code before merging.