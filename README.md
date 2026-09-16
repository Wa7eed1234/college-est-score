# College score matching demo

Flask/SQLite exercise that registers a student score and lists colleges whose minimum score is no higher.

## Run locally

Use Python 3 in an isolated environment. The following dependency list is inferred from source imports; this repository has no tested dependency lockfile.

```bash
python -m venv .venv
# Windows PowerShell: .venv\Scripts\Activate.ps1
# macOS/Linux: source .venv/bin/activate
python -m pip install Flask Flask-SQLAlchemy Flask-Login Flask-Admin
python -m flask --app main run --host 127.0.0.1 --port 5000
```

Open http://127.0.0.1:5000. Use only synthetic local records. Complete the known repairs below first; dependency compatibility and full application flows have not been verified.

## Current status and known limitations

Move college.html, index.html, login.html and register.html into templates/. Add sample college records. Hash passwords and restrict the admin interface.

## Review status

Documentation drafted from repository source on 13 September 2026. This review did not run the application or certify it for production.

## Cleanup applied

- Existing root HTML files have been moved into templates/.

These updates supersede the corresponding original review findings. Other limitations remain open.
