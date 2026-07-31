# python-template
A modern Python project template

## Installation
### 1. Create a repository with this template
### 2. Update `pyproject.toml`
Update the name, description, and authors of `pyproject.toml`. Also rename the `./src/python_template` directory to match your project's name.
### 3. Sync with uv
Run `uv sync`
### 4. Install pre-commit hooks
Run `uv run pre-commit install`
### 5. Install skills for your AI agents
Run `pnpx skills experimental_install`

## Features
- Dependency management with [uv](https://github.com/astral-sh/uv)
- Linting and formatting with [ruff](https://github.com/astral-sh/ruff)
- Google docstring convention check
- Type checking with [ty](https://github.com/astral-sh/ty)
- Pre-commit hooks for [uv](https://github.com/astral-sh/uv-pre-commit), [ruff](https://github.com/astral-sh/ruff-pre-commit), [ty](https://github.com/astral-sh/ty-pre-commit), [codespell](https://github.com/codespell-project/codespell), and [validate-pyproject](https://github.com/abravalheri/validate-pyproject)
- AI agent skills for [uv, ruff, and ty](https://github.com/astral-sh/claude-code-plugins)
