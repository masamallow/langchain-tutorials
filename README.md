# Hands-on LangChain Official Tutorials

## References

[Tutorials \| 🦜️🔗 LangChain](https://python.langchain.com/docs/tutorials/)

## Setup

Installed uv by using pipx because uv is used as a generic tool across environments.

```shell
pipx install uv
```

```shell
uv sync
```

## For Use LLM

`./notebook/.env`
```
LANGCHAIN_API_KEY=
OPENAI_API_KEY=
```

## JetBrains Env Setup

- `Settings | Languages & Frameworks | Jupyter | Jupyter Servers`
- Python interpreter: `./.venv/bin/python`
- Command line arguments:  
  ```
  jupyter lab --no-browser --notebook-dir=./notebooks
  ```
