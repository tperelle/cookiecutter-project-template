# project-template

## Requirements

- cookiecutter >= 1.7.0

## Installation

Add this function in your environment:

```bash
function project() {
  cookiecutter --overwrite-if-exists https://github.com/tperelle/project-template.git
}
```

## Usage

When you want to create a new project directory:

```bash
$ project
name [myproject]: test
Initialized empty Git repository in /private/tmp/cookiecutter/test/.git/
```
