## Installation

1. Ensure `uv` is installed: `pip install uv`
2. Initialize the project: `uv init .` (or `python -m uv init .` if `uv` is not in PATH)

## Running the Application

To run the app:
- `uv run main.py`
- On Windows, if you get "'uv' is not recognized", add the Scripts directory to your PATH:
  - Find the path: Run `python -m pip show uv` and note the "Location" (e.g., `C:\Users\...\local-packages\Python311\site-packages`)
  - Scripts path is `Location/../Scripts` (e.g., `C:\Users\...\local-packages\Python311\Scripts`)
  - Add it to System PATH via Windows settings, then restart your terminal.
- Alternatively, use `python -m uv run main.py` as a workaround.

## Adding Dependencies

- `uv add fastapi uvicorn` (or `python -m uv add fastapi uvicorn`)