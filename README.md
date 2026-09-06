# Capital Quiz

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat-square&logo=python&logoColor=white)
![Poetry](https://img.shields.io/badge/dependencies-Poetry-60A5FA?style=flat-square&logo=poetry&logoColor=white)

A colorful command-line geography game that challenges players to match countries with their capital cities.

## How it works

- A country is selected randomly from a set of ten.
- The player receives three attempts to enter the capital.
- Color-coded feedback marks correct and incorrect answers.
- The player can start another round without restarting the program.

## Run locally

Requires Python 3.8+ and [Poetry](https://python-poetry.org/).

```bash
poetry install
poetry run python main.py
```

Or install the single runtime dependency manually:

```bash
python -m pip install colorama
python main.py
```

## Project files

| File | Purpose |
|---|---|
| `main.py` | Game loop, question data, validation, and terminal output |
| `pyproject.toml` | Python and dependency metadata |
| `Programming Journal.txt` | Historical development notes from the original assignment |

## Roadmap

- Expand the question bank.
- Accept alternate spellings and punctuation.
- Replace recursive replay with an iterative game loop.
- Add automated tests for answer and retry behavior.

## License

No license has been selected for this project.
