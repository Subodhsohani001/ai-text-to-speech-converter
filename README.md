# AI Text-to-Speech Project 

Short description
: A simple text-to-speech demo/notebook using `pyttsx3`. This project includes a Jupyter notebook that demonstrates converting text to audio using local TTS engines on Windows via `win32com`/`pyttsx3`.

## Contents
- `notebooks/my_AI-text-to-speechpProject.ipynb` — main notebook (demo + examples).
- `requirements.txt` — Python dependencies.
- `src/` — optional Python modules (helper scripts).
- `.gitignore`, `LICENSE`

## Prerequisites
- Python 3.8+ (recommended)
- On Windows: install `pywin32` (the project uses `win32com.client`).
- Recommended: create a virtual environment.

## Setup (local)
```bash
# clone repo (once pushed)
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

# create & activate venv (example for Windows PowerShell)
python -m venv venv
.\venv\Scripts\Activate.ps1

# install dependencies
pip install --upgrade pip
pip install -r requirements.txt
