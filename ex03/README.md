# Discovery Web Piscine

## Introduction

This project is part of the Discovery Web Piscine.
The goal is to practice basic Linux commands, file management, Git, GitHub, and secure authentication using SSH.

Throughout the exercises, I learned how to work with files and directories from the terminal and how to use Git to manage and share a project.

## Project Goals

The main goals of this project are:

* Practice navigating the Linux terminal.
* Create and manage files and directories.
* Use basic shell commands.
* Understand the basic Git workflow.
* Create and manage a GitHub repository.
* Write simple and clear project documentation.
* Understand SSH authentication and public/private keys.

## Tools Used

* Linux Terminal
* Git
* GitHub
* Markdown
* SSH

## Git Workflow

A basic Git workflow is:

```text
Edit → Add → Commit → Push
```

### 1. Edit

Make changes to the project files.

### 2. Add

Stage the changes using:

```bash
git add <file>
```

### 3. Commit

Save the staged changes with a clear message:

```bash
git commit -m "Describe the changes"
```

### 4. Push

Send the committed changes to GitHub:

```bash
git push
```

This workflow helps keep the project organized and makes it easier to track changes.

## Why Git Makes Development Easier

Git makes development easier because it keeps a history of the project.

### Protects Code

Git saves previous versions of the project through commits. If something goes wrong, the history can help us understand what changed and return to an earlier version when needed.

### Tracks History

Every commit records a point in the project's history. It helps us see what was changed and understand how the project developed over time.

### Supports Team Collaboration

Git allows several developers to work on the same project. Each person can make changes, commit them, and share their work with the rest of the team through a remote repository such as GitHub.

## GitHub

GitHub is used to store the Git repository online. It allows the project to be shared and makes it possible to access the repository from different environments.

The repository for this project is:

**https://github.com/safaosama/discovery-web-piscine**

## SSH Authentication

SSH can be used to securely connect a local Git repository to GitHub.

An Ed25519 SSH key pair contains two keys:

* **Private key:** kept secret and stored only on the local machine.
* **Public key:** added to GitHub and used to identify the local machine.

The private key must never be shared or committed to a repository.

## Conclusion

This project provided practice with terminal navigation, file manipulation, Git, GitHub, Markdown, and SSH authentication.

The main idea is to work carefully, keep a clear history of changes, and use Git to manage projects safely and efficiently.
