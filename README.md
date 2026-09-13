# EcoPlot — Energy & Device Management Prototype

A Flask-based prototype for registering household devices, tracking device attributes, and exploring energy-management workflows through a web dashboard and JSON API.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?logo=sqlalchemy&logoColor=white)

## Features

- User registration and sign-in
- Protected dashboard and profile pages
- Device creation and listing
- Device attributes such as power consumption and smart-device capability
- JSON CRUD endpoints for devices
- SQLite persistence through Flask-SQLAlchemy
- Bootstrap-based interface

## Local Setup

```bash
git clone https://github.com/pelinaybar/ecopilotdeneme.git
cd ecopilotdeneme
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python runserver.py
```

On Windows, activate the environment with `.venv\Scripts\activate`.

## Project Status

Hackathon/learning prototype. API authorization, production configuration, and security hardening should be completed before any real deployment.

---

[Portfolio](https://pelinaybar.com) · [GitHub Profile](https://github.com/pelinaybar)
