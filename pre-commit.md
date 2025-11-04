# Pre-commit

Pre-commit is a script that runs **ESLint** and **Prettier** checks on our code when we run:

```bash
git commit
```

It requires python and pip installed on the computer.

## What you NEED to do:

First install it on your _PC_ following this [guide](https://pre-commit.com/#install)
Check if it was installed by running:

```bash
pre-commit --version
```

Then install it for _each project_ that have a git repo by running(when you are in the project directory):

```bash
pre-commit install --install-hooks
```

## If you want to know more:

[website](https://pre-commit.com/)
