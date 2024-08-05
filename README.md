# Smith Agent Farm

> [!WARNING]
> This is pre-alpha, doesn't work, might burn your house down.

## Development

### Setup

The first time you clone the repository, you will need to install the Python
version and create a virtual environment.

```bash
pyenv install 3.12.2
python -m venv .venv/smith
source .venv/smith/bin/activate
pip install poetry
pre-commit install
direnv allow
```

Subsequent times, you will only need to activate the virtual environment.

```bash
source .venv/smith/bin/activate
```

### Install

To install the dependencies, run the following command.

```bash
poetry install
```

### Tasks

Some development tasks have been added using [Taskfile](https://taskfile.dev/),
which can be installed using the following command.

```bash
brew install go-task
```

The tasks available are:

- `task jupyter`: start a Jupyter notebook server with the library in `PATH`
