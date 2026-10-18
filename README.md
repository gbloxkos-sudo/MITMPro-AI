# MITMPro — Unified AI-Assisted Security Assessment Platform

MITMPro is a unified desktop (Tkinter) and web (FastAPI) security assessment
suite integrating AI assistance (via Ollama), traffic analysis, Burp-style tools,
WebSploit, proxy interception, WAF/bypass engine, and more.

## Requirements

- Python 3.10+
- Ollama (optional, for AI features): https://ollama.com

## Install

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Run (desktop)

```bash
python3 run.py
```

## Run (web GUI)

```bash
python3 -m mitmpro.webgui
# open http://localhost:5000
```

## Developer

GBLOXKOS LLC

## Disclaimer

For authorized security testing only.
