# Bangla Contacts Converter

Flask app that serves a single-page tool: English contact names -> Bangla (Avro phonetic) -> CSV / vCard export.

## Run locally
    pip install -r requirements.txt
    python app.py        # http://localhost:5000

## Deploy on Railway
1. Push this folder to a GitHub repo.
2. Railway -> New Project -> Deploy from GitHub repo -> select it.
3. Service -> Settings -> Networking -> Generate Domain.
