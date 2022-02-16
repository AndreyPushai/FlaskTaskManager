# FlaskTaskManager

## Steps to run:

1) Install requirements
2) Init DB if there is no one:
    from app import db
    db.create_all()
3) Start the app:
    python app.py

4) Works on localhost:5000

## Roadmap

- Make updating task in one table not in other page
- Make create/update check for empty value to forbid 

## Version 0.2

Made updates:
- Updated table styles;
- Added buttons instead of links for actions with tasks.

## Version 0.1

Repeated steps to understand how works Flask from online course on [YouTube](https://www.youtube.com/watch?v=Z1RJmh_OqeA)

Created Task Manager app:
- User can add, edit and delete tasks
- If the table is empty it shows text to create one.
