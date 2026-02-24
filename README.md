# Prank site (harmless)

This is a tiny, friendly prank web page built with Flask. It intentionally shows a playful overlay and confetti when the button is clicked, then reveals "PRANK!" so the person knows it's a joke.

How to run (PowerShell on Windows):

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python main.py
# Open http://127.0.0.1:5000 in a browser
```

Notes:
- This project is meant to be harmless and obvious; do not use it for deception or phishing.
- You can edit `templates/index.html` to customize the message or style.
