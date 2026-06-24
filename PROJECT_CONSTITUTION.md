# Project Constitution

This repository will follow the project structure modeled from the `D:\...33 Wayfair` reference workspace.

The files below are treated as the core scaffold of the project and define the intended layout for future development.

## Root Files

- `README.md`
- `AGENTS.md`
- `HUMAN_GUIDE.md`
- `AI EDIT CONFIG BY EACH COMPANY TO UPDATE.md`
- `app_runtime.env`
- `requirements.txt`
- `schema.sql`
- `start_wayfair_app.bat`
- `stop_wayfair_app.bat`

## Application

- `app/__init__.py`
- `app/main.py`
- `app/workflow.py`
- `app/runtime_config.py`
- `app/DbConfigLogger.py`
- `app/edit_history.py`
- `app/adapters/company_loader.py`

## Templates

- `templates/index.html`

## Company Configuration

- `companies/wayfair/company.json`
- `companies/wayfair/step_01.json`
- `companies/wayfair/step_02.json`
- `companies/wayfair/step_03.json`

## Output And Logs

- `output/wayfair_workflow_documentation.html`
- `edit log/ai edit history.txt`

## Documentation

- `Documention Both/DEEP FLOW DIAGRAM`
- `Documention Both/SOFTWARE   PROCESS  FLOW  DIAGRAM/User Flow.md`
- `Documention Both/SOFTWARE   PROCESS  FLOW  DIAGRAM/Developer Flow.md`

## Scaffolding Rule

These files and folders are created as structural placeholders first.
Implementation content will be added later file by file.

## Naming Rule

Use `0xAnsR` anywhere a project reference would otherwise use `Codex`.

## Commit Rule

Create a git commit after each completed change set during repository work.
