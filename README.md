# What is Git?
## Definition
### Purpose

**By far, the most widely used modern version control system in the world today is _Git_.**

*Developers who have worked with Git are well represented in the pool of available software development talent and it works well on a wide range of operating systems and IDEs (Integrated Development Environments).*

***Having a distributed architecture, Git is an example of a DVCS (~~hence Distributed Version Control System~~).*** 

Rather than have only one single place for the full version history of the software as is common in once-popular version control systems like <sub>CVS</sub> or <sup>Subversion</sup>.


### *What is a Git repository?*

> A Git repository is a virtual storage of your project. It allows you to save versions of your code, which you can access when needed. 

### *Initializing a new repository:*

To create a new repo, you'll use the `git init` command. `git init` is a one-time command you use during the initial setup of a new repo. 

Git stores configuration options in three separate files, which lets you scope options to individual repositories (local), user (Global), or the entire system (system):

Undoing changes:

```
git clean
git revert
git reset
git rm
```

This README was created using the [Atlassian tutorial](https://www.atlassian.com/git/tutorials/what-is-git).

![Git Logo](https://static.vecteezy.com/system/resources/previews/016/833/872/original/github-logo-git-hub-icon-on-white-background-free-vector.jpg)

[Another Git logo](./Git-logo.svg.png)

## Git init

This page will explore the git init command in depth. By the end of this page you will be informed on the core functionality and extended feature set of git init. This exploration includes:

- git init options and usage
- .git directory overview
- custom git init directory environment values
- git init vs. git clone
  - git init bare repositories
    - git init templates

*Example:*

1. `git init`
2. `git status`
3. `git commit`
4. `git push`


> [!NOTE]
> I couldn't come up with an original text, sorry.