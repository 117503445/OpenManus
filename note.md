uv venv open-manus --python 3.12 --seed
uv init
uv sync
uv pip install -r requirements.txt

uv run python main.py