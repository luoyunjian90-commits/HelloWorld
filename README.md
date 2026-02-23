```markdown
# HelloWorld

## Flask App

A minimal Flask web application using SQLite and SQLAlchemy.

Setup:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -U pip
python -m pip install -r requirements.txt
```

Run locally:

```bash
PYTHONPATH=. .venv/bin/python run.py
```

Run tests:

```bash
PYTHONPATH=flask_app .venv/bin/python -m pytest -q flask_app/tests
```

```
