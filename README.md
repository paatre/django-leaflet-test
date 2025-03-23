# Django Leaflet Test

This is a simple Django project to test the integration of Django with Leaflet using `django-leaflet`. The project has been stripped down to the bare minimum to demonstrate the integration.

There's a single template that displays a fullscreen map centered to London. Currently, the map has a custom CSS for reset view button's icon.

## Installation

The project uses `uv` as the virtual environment manager. To install the packages needed for the project, run the following command:

```bash
uv sync
```

To run the project, run the following commands:

```bash
uv run manage.py migrate
uv run manage.py runserver
```
