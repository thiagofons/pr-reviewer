# Notion PR Reviewer

## How to run

1. Install the `uv` package manager

```
curl -LsSf https://astral.sh/uv/install.sh | sh
```

2. Create and activate a virtual environment

```
uv venv
source .venv/bin/activate
```

3. Install the required packages

```
uv add "mcp[cli]" requests python-dotenv notion-client
```

4. Install the dependencies

```
uv pip install -r requirements.txt
```

5. Create a `.env` file in the root, containing the environment variables in `.env.example`

## Credits

All thanks to Aashi Dutt, from the [Datacamp tutorial](https://www.datacamp.com/tutorial/mcp-model-context-protocol)