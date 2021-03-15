# project-template

## Requirements

- cookiecutter >= 1.7.0

## Installation

Add this function in your environment:

```bash
function project() {
    cookiecutter --no-input --overwrite-if-exists https://github.com/tperelle/project-template.git name=$1
}
```

## Usage

When you want to create a new project directory:

```bash
$ project myproject
Initialized empty Git repository in /private/tmp/cookiecutter/myproject/.git/
```
