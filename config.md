# Git Configuration

## What is Git Configuration?

Git Configuration is the first step after installing Git. It is used to set your username and email address. Git uses this information to identify who made each commit.


## Why Do We Configure Git?

- To identify the author of each commit.
- To connect your commits with your GitHub account.
- To keep your commit history clear and organized.


## Commands

### Set Username

```bash
git config --global user.name "Your Name"
```

### Set Email

```bash
git config --global user.email "youremail@example.com"
```

### View Configuration

```bash
git config --list
```

---

## Example

If your name is Abitha and email is abitha@gamil.com ,then use the cmd for set configuration. 

```bash
git config --global user.name "Abitha"
git config --global user.email "abitha@gmail.com"
```

To check the configuration:

```bash
git config --list
```


## Common Errors

### Error

```text
Author identity unknown
```

**Reason**

Git username or email is not configured.

**Solution**

Configure your username and email using:

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

---

## Best Practices

- Configure Git immediately after installing it.
- Use the same email address as your GitHub account.
- Verify your configuration using `git config --list`.
- Keep your username professional.


## What I Learned

- Learned how to configure Git.
- Learned how to set a username and email.
- Learned how to check the Git configuration.
- Understood why Git Configuration is important.