# Contributing

We are running a training program to allow folks to be able to learn how to contribute to an open source project, and learn along the way with us. We have created some badges that you can earn along the way for your contributions.

**Add yourself** to the [list of contributors](CONTRIBUTORS.md) along with your first pull request.

This document lays out how to get you started in contributing, so please read on.

Helper video if it is too hard: [Submitting your first pull request](https://www.youtube.com/watch?v=bpzioBa1n8w)

### Fork, and Star the Diektiv Repository

Click the fork button on the repo at [https://github.com/direktiv/mentoring](https://github.com/direktiv/mentoring)

Your repo will now be in your GitHub. Clone the repo to your computer with the following command:

``` 
git clone https://github.com/<yourgithubname>/direktiv.git 
```

Branch away from the `main` branch and use the following schema for naming your branches:

``` 
git checkout -b add-direktiv-to-contributors 
```

Add your name to the [CONTRIBUTORS.md](CONTRIBUTORS.md) with your name, github handle, timezone and areas of interest that you would like to learn.  This list will grow over time.


**add your line to the bottom of the page** 

```
| [Brad McCoy](https://github.com/direktiv) | AEST | UTC +10 | GitOps, GoLang |
```

### Commiting code ###

Add your changes to the contributors file with the following command:

``` 
git add CONTRIBUTORS.md 
```

Commit your changes, make sure you sign off your commits by using the `-s` parameter

``` 
git commit -m "add <yourname> to contributors" -s 
```

Push your changes, use your branch name you created above

``` 
git push --set-upstream origin add-direktiv-to-contributors 
```

You now will get a link in the terminal to create the pull request you can goto that link or go into your forked repo and create the pull request.

Congratulations!! you have now created your first pull request to this repo.  To stay synced to this repo with the latest changes you can do the following

``` 
git remote add upstream https://github.com/direktiv/mentoring.git 
```

``` 
git remote add downstream git@github.com:<yourgithubname>/mentoring.git 
```

``` 
git checkout main
```

```
git pull upstream main
```
