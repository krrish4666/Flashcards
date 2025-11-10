# Flashcards App

Local Flask app that generates flashcards using Gemini API.

## Setup
1. Create a Python venv and install requirements:
   ```bash
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   pip install -r requirements.txt
2. Add .env in project root with:
   ```bash
   GEMINI_API_KEY=your_api_key_here
3. Run:
   ```bash
   python app.py
Export

Use web UI to download PDF or PPTX.


Commit and push:
```powershell
git add README.md .gitignore
git commit -m "Add README and .gitignore"
git push
```
5.  Common extras you might want

Create a requirements.txt (you already have one) and include a short setup.sh or Makefile.

Add GitHub Actions CI (optional) to run linting/tests.

Add .gitattributes to normalize line endings if collaborators are on Windows.
   
