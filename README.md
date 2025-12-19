Запуск 

Без uv

python -m venv .venv

.venv/scripts/activate

pip install flask

python src/main.py

с uv

uv sync

uv run src/main.py
