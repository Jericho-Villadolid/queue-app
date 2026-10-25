# BiteLine

Flask application for CCC181.
BiteLine allows students to queue up for events on campus that are offering free food or snacks.
Gone are the days of waiting in line for a scoop of ice cream, only to be met with dissapointment
after reaching your turn, only to find that the supply has run out. BiteLine offers a solution where each student can apply to join the queue, and applications that go over capacity are rejected.

## Project structure

```
queue-app/
├── app.py              # creates the app and defines routes
├── requirements.txt    # packages to rebuild the environment
├── .gitignore          # keeps .venv, caches and secrets out of Git
├── .venv/              # your virtual environment (not committed)
├── templates/          # Jinja2 HTML files for render_template()
│   ├── base.html       # shared layout
│   ├── index.html      # home page
│   ├── join.html       # input page to join the queue
│   └── ticket.html     # page for /queue/<ticket_id>
└── static/             # served at /static/...
    ├── css/style.css
    └── js/main.js
```