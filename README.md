# Vulnerable Arena

<img src="https://media1.tenor.com/m/D90fcMv8SacAAAAC/hackerman-hacker.gif" width="400" height="200">

**Purpose-built vulnerable Flask web application** for practicing and learning web exploitation techniques such as:

- SQL Injection
- Stored XSS
- IDOR (Insecure Direct Object Reference)
- Open Redirect


## Installation

```bash
git clone https://github.com/Yusif-Kerimov/vulnerable-arena.git
cd vulnerable-arena
pip install -r requirements.txt
sqlite3 db.sqlite3 < db_init.sql
python app.py
open web 127.0.0.1:500
