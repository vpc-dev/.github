# Contributor Guide

Hi! We’re excited to have you as a contributor!

Take a moment to review this document in order to make the contribution process easy and effective for everyone involved.

Following these guidelines helps to communicate that you respect the time of the developers managing and developing this open source project. In return, they should reciprocate that respect in addressing your issue or assessing patches and features.

<!-- TOC -->
* [Contributor Guide](#contributor-guide)
  * [Things to know](#things-to-know)
  * [Getting Started](#getting-started)
    * [Information for newcomers](#information-for-newcomers)
    * [Creating a fork](#creating-a-fork)
    * [Edit files on GitHub](#edit-files-on-github)
    * [Using a local clone](#using-a-local-clone)
  * [Pull Requests](#pull-requests)
    * [Commit Convention](#commit-convention)
  * [Reviewing Changes](#reviewing-changes)
  * [Developer Certificate Of Origin](#developer-certificate-of-origin)
<!-- TOC -->

## Things to know

* You must use `git commit --signoff` for any commit to be merged, and agree that usage of `--signoff` constitutes agreement with the terms of [DCO 1.1](DCO.md). See below how to easily sign the [Developer Certificate Of Origin]((#developer-certificate-of-origin))
* We ask all of our community members and contributors to adhere to the [VPC.dev Code of Conduct](CODE_OF_CONDUCT.md). If you have questions, or need assistance, please reach out to our community team at conduct@vpc.dev.\

## Getting Started

To contribute to this repository you will [fork this repository](https://guides.github.com/activities/forking), push changes to a branch in your fork, and then [create as a pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork) from that branch to the `main` branch of this repository. Forking only needs to be done once, after which you can push changes to your fork using the GitHub website file editor or from a local clone, as described below.

### Information for newcomers

You can also find some newcomer friendly issues in our task tracker:

* [Good First Issues on GitHub](../../issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22)

### Creating a fork

Creating a fork, aka [forking](https://guides.github.com/activities/forking), makes a personal copy of another repository. Any changes you make in your fork of the repository will not show up on the main repository until they are merged (via pull request) to the `main` branch of this repository. If you are unfamiliar with how to create a fork or how forks work, see the [GitHub tutorial on forking](https://guides.github.com/activities/forking).

### Edit files on GitHub

GitHub makes it easy to add, edit, or delete individual files via [GitHub Codespaces](https://docs.github.com/en/codespaces).

### Using a local clone

We generally recommend making changes in a [local clone](https://help.github.com/articles/cloning-a-repository-from-github) of your fork. This requires some additional tools and storage on your local machine, and you will need a bit more technical knowledge of how to use those tools. However, this will allow you work on multiple files as part of a single set of changes. You'll save your changes in a local branch and then test them locally. When they are ready you will push your changes to your fork and submit a pull request from there.

## Pull Requests

Thanks for taking time to make a [pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork)!

### Commit Convention

As a commit convention, we have adopted [Conventional Commits v1.0.0](https://www.conventionalcommits.org/en/v1.0.0).

In short, a commit message should be structured as follows:

```text
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

If you are using any of the [JetBrains Editors](https://www.jetbrains.com) (IntellijJ IDEA, PyCharm, PhpStorm, etc.), you can use the [Git Commit Template](https://plugins.jetbrains.com/plugin/9861-git-commit-template/) plugin to add _Conventional Commits_ support to your editor.

## Reviewing Changes

There are many pull requests being submitted every week. Reviews are driven by the community, and any contributions are always welcome.

Pull requests are open to public, and any GitHub user can review changes and provide feedback. If you are interested to review changes, please just do so (and thanks in advance!). No special permissions needed

## Developer Certificate Of Origin

The [Developer Certificate of Origin (DCO)](https://developercertificate.org) is a lightweight way for contributors to certify that they wrote or otherwise have the right to submit the code they are contributing to the project.

Contributors to this project sign-off that they adhere to these requirements by adding a `signed-off-by` line to commit messages.

```text
This is my commit message

Signed-off-by: Bob Villa <bob@example.com>
```

`git` even has an `-s` flag to append this automatically to your commit message:

```bash
$ git commit -s -m 'This is my commit message'
```
