# CampusMemories

Photo-sharing and commenting system for private friend groups.

## Current status

- Django project created.
- Django REST Framework installed.
- Accounts, groups, photos, and comments apps created.
- Feature implementation has not started.

## Requirements

- Python 3.12
- Git

## Local setup using Windows Git Bash

Open a terminal inside the cloned project folder.

```bash
cd backend
py -3.12 -m venv .venv
source .venv/Scripts/activate
python -m pip install -r requirements.txt
python manage.py check
python manage.py runserver
```

Open http://127.0.0.1:8000/ in a browser.

An unapplied migrations warning is expected until the team
finalises the user model and applies migrations.

## Responsibilities

- Member 2: accounts, authentication, groups, and memberships.
- Member 3: photos, comments, search, and filters.

Coordinate changes to settings.py, main URLs, and shared models.
Use feature branches and pull requests.