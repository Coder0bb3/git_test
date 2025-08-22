# Subscription Stock Picker

A simple Flask web application that provides stock picks to subscribed users.

## Features

- User registration and login
- SQLite database using SQLAlchemy
- Subscription flag to enable stock recommendations
- Random stock suggestions from a small list

## Setup

```bash
pip install -r requirements.txt
python app.py
```

The application creates an SQLite database file `stock_picker.db` on first run.

Open your browser at `http://127.0.0.1:5000` to register, log in, subscribe and view stock picks.
