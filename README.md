<p align="center">
  <img src="https://hacktoberfest.digitalocean.com/img/logo-hacktoberfest-full.7d5e2645.svg" />
</p>

# HACKTOBERFEST STARTER KIT

<img src="https://img.shields.io/date/1633060800?color=9C4668&label=starts&style=for-the-badge" align="right" />

Getting started with Hacktoberfest.

## What is Hacktoberfest?

Hacktoberfest is a monthlong celebration of open source software run by DigitalOcean.
Hacktoberfest is open to everyone in our global community!
Four quality pull requests must be submitted to public GitHub repositories.
You can sign up anytime between October 1 and October 31.

This is your *starter kit* to open source contribution, happy hacking!.

Read the [[FAQ]](https://hacktoberfest.digitalocean.com/faq) for more.

## How to Contribute

Suggest fixes to the open issues.

- Modifying the `CONTRIBUTORS.md` file, fixes #1.
- Creating a `profile/<GITHUB_USERNAME>.md` file, fixes #2.
- Writing a *Hello, World!* program as `hack/<GITHUB_USERNAME>.xx>`, fixes #3.

You can fix one or more issues in the same PR.

## Project Overview

- Fork this repository.
- Clone your fork.
- Make changes.
- Commit and push.
- Open a pull request.
- Wait for review/merge.

Read [[GitHub Docs]](https://docs.github.com/en/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github) for more.

## Quality Requirements

This are the expected standards for all PRs.

### + Add Contributor Name

Add the contributor's name to the `CONTRIBUTORS.md` file following the next convention.

```markdown
#### [<CONTRIBUTOR_NAME>](<GITHUB LINK>)
- Bio: I am
- Social: <SOCIAL_LINKS>
```

### + Create Contributor Profile

#### 1. Create a new file

Create a new markdown file inside the **profile** directory, let the file name match the contributor's username.

```console
tinysorcerer@github:~/hacktoberfest$ touch profile/roramigator.md
```

#### 2. Save your file

Save the content of your new file by filling the next template.

```markdown
# Contributor's Name

## Bio
[required]

## Projects
[required]

## Links
[required]

## A message to the world
[optional]
```

All and any combination of markdown is acceptable.

### + Write Hello World Program

#### 1. Create new file

Create a new file inside the **hack** directory, use the extension of your chosen language, let the file name match the contributo's username.

#### 2. Save your file

Write your program and save your file, in this case `roramigator.rs`.

```rust
// LANGUAGE: rust
// AUTHOR: Roberto Morado

println("Hello World!");
```

---

[DigitalOcean](https://hacktoberfest.digitalocean.com/)

[DEV](https://dev.to/t/hacktoberfest)
