# Following below is the folder structure
```/my_flask_app
|-- /venv # Virtual environment
|-- /app
| |-- /static # Static files (CSS, JS, images)
| |-- /templates # HTML templates
| |-- init.py # Initialize the app
| |-- routes.py # Define routes and views
| |-- models.py # Define database models
| |-- forms.py # Define forms using Flask-WTF
| |-- /static # Static files (CSS, JS, images)
| |-- /templates # HTML templates
|-- config.py # Configuration settings
|-- requirements.txt # List of dependencies
|-- run.py # Run the application
```


### Here's a brief description of each folder/file:
```
    /venv: Virtual environment folder to isolate project dependencies.

    /app: Main application package.
        /static: Folder for static files (CSS, JS, images).
        /templates: Folder for HTML templates.
        __init__.py: Initializes the Flask app.
        routes.py: Defines routes and views.
        models.py: Defines database models.
        forms.py: Defines forms using Flask-WTF.

    config.py: Configuration settings for the app (e.g., database configurations).

    requirements.txt: List of Python dependencies. You can generate this file using pip freeze > requirements.txt after installing your dependencies.

    run.py: Script to run the application. It initializes the app and runs the development server.
```
## To turn on the virtual env 
`python source venv/bin/activate` 
## To deactivate
`python deactivate`

### Refer the Flask Documentation for more info
[Flask](https://flask.palletsprojects.com/en/3.0.x/)



