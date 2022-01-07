# Contributing

First off, thank you for considering contributing to Open Source! It's people like you who make the community great.

**Add yourself** to the [list of contributors](CONTRIBUTORS.md) along with your first pull request.

This document lays out how to get you started in contributing, so please read on.

### Fork Repositories

Click the fork button on the repo at https://github.com/bradmccoydev/mentoring

Branch away from the `main` branch and use the following schema for naming your branches:

``` git checkout -b add-bradmccoydev-to-contributors ```

Add your name to the [CONTRIBUTORS.md](CONTRIBUTORS.md) with your name, github handle, timezone and areas of interest that you would like to learn.  This list will grow over time please choose only 2 to start with.

| Things to be mentored on | 
| --- |
| Career Advice |
| KCNA Exam |
| Helm |
| Kustomize |
| GitOps |
| GoLang |
| Terraform |

```
| [Brad McCoy](https://github.com/bradmccoydev) | AEST | UTC +10 | GitOps, GoLang |
```

### Commiting code ###

Add your changes to the contributors file with the following command:

``` git add CONTRIBUTORS.md ```

Commit your changes, make sure you sign off your commits by using the `-s` parameter

``` git commit -m "add <yourname> to contributors" -s ```

Push your changes, use your branch name you created above

``` git push --set-upstream origin add-bradmccoydev-to-contributors ```

You now will get a link in the terminal to create the pull request you can goto that link or go into your forked repo and create the pull request.

Congratulations!! you have now created your first pull request to this repo.  To stay synced to this repo with the latest changes you can do the following

``` git remote add upstream https://github.com/bradmccoydev/mentoring.git ```

``` git remote add downstream git@github.com:<yourgithubname>/mentoring.git ```

``` git checkout main ```

```git pull upstream main```

