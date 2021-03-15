# project-template

## Requirements

## Usage

Add this function in your environment:

```bash
function project() {
  if [ "$1" != "" ]; then
    cookiecutter('https://github.com/tperelle/project-template.git', extra_context={'project': $1})
  fi
}
```
