# MPS Radio Tracking App

MPS Radio Tracking App is a Flask-based web application designed to manage the tracking of radios at a port and harbor facility. It allows port workers to log in, view available radios, issue radios to users, and track the status of issued radios.

## Features

- User authentication: Allows users to register, log in, and log out securely.
- Radio management: Provides functionality to view available radios, issue radios to users, and mark radios as returned.
- Database integration: Uses SQLAlchemy ORM to interact with the database, facilitating data storage and retrieval.
- Flask Blueprint structure: Organizes the application into separate modules (blueprints) for better maintainability.
- HTML templates: Utilizes Jinja2 templating engine to render dynamic HTML pages for user interaction.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/tsikoviski/mps_radio_tracking_app.git
