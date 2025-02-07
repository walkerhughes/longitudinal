

```sh
brew install uv
cd longitudinal
uv venv
uv sync
source .venv/bin/activate
uv pip install -e .
uv sync
```