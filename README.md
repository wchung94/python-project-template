
## How to use python-project-template

This repository contains the copier/template for fast setup of a generic python project repository with UV.

```
copier copy https://github.com/wchung94/python-project-template/copier-template <local-directory-path>
```


## Installation

- install python version 3.1x
- install uv
- install copier

## Documentation

If you are lazy and have a short-term memory like me, use this template to setup your python project fast and easy.
Time wasted with repetitive task can be spent on playing video games and watching some slice-of-life animes.

## Content

The copier template contains the following copy resources:
- .github basic action workflows
- pre-commit hook for basic linting
- src directory for project name and main starting file
- tests directory for unit and integration test files
- pyproject.toml manager for UV
- makefile template
- Agents.md template

# Structure agents.md
- Keep it short:
Should be max 300 lines. Every line goes into every session. Make each line count 
- Separate agents.md if needed in separate task-specific docs.
- use reference file:line locations rather than embedding code snippets.
- Treat the agents.md as part of infrastructure instead of scratchpad


## Contributing

If you want to contribute to the development of copier-template,
have a look at the [contribution guidelines](CONTRIBUTING.md).

## Development

Install the Git pre-commit hooks:

```console
uv run pre-commit install
```


## FAQ



## Credits

This package was created with [Copier](https://github.com/copier-org/copier) and the [wchung94/python-project-template](https://github.com/wchung94/python-project-template).

<img src="docs/lazy_panda.png" alt="Lazy panda" width="25%" />
