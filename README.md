# Coding style

**pre-commit** is a framework for managing pre-commit hooks. These hooks help to identify simple issues before committing code for review. By checking for these issues before code review it allows the reviewer to focus on the change itself, and it can also help to reduce the number of CI runs.

# Libraries

## 1. isort

isort is a Python utility / library to sort imports alphabetically, and automatically separated into sections and by type. It provides a command line utility, Python library and plugins for various editors to quickly sort all your imports. It requires Python 3.6+ to run but supports formatting Python 2 code too.

## 2. black

Black is the uncompromising Python code formatter. By using it, you agree to cede control over minutiae of hand-formatting. In return, Black gives you speed, determinism, and freedom from pycodestyle nagging about formatting. You will save time and mental energy for more important matters.

## 3. flake8

Flake8 is a Python library that wraps PyFlakes, pycodestyle and Ned Batchelder’s McCabe script. It is a great toolkit for checking your code base against coding style (PEP8), programming errors (like “library imported but unused” and “Undefined name”) and to check cyclomatic complexity.

# Getting started

## 1. Install dependencies

```bash
pip install -r requirements.txt
```

## 2. Activate precommit hook

```bash
pre-commit install
```

## 3. Deactivate precommit hook

```bash
pre-commit uninstall
```

## 4. Optional

In this configuration you can choose if you want to block the commit or only show the error.

