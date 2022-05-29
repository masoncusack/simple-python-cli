# Simple Python CLI

Built using [this tutorial](https://typer.tiangolo.com/tutorial/package/).

Prerequisites:
- [Poetry](https://python-poetry.org/)

Change the name of the CLI, and point it to the [typer](https://github.com/tiangolo/typer) app, in `pyproject.toml`:

```
[tool.poetry.scripts]
simple-python-cli = "simple_python_cli.main:app"
```

To test locally:

```bash
poetry install
simple-python-cli -h
simple-python-cli shoot
```

To build (create a .whl):

```
poetry build
```



