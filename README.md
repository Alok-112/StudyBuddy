# Django Project Setup

This guide will walk you through setting up a Django project using a virtual environment.

## Prerequisites

- Python installed on your system ([Download Python](https://www.python.org/downloads/))
- Basic understanding of the command line

## Setup Instructions

1. **Install virtualenv:**

    ```bash
    pip install virtualenv
    ```

2. **Create a virtual environment:**

    ```bash
    virtualenv <env_name>
    ```

    Replace `<env_name>` with the name you want to give your virtual environment.

3. **Activate the virtual environment:**

    On Windows:

    ```bash
    <env_name>\Scripts\activate
    ```

    On macOS/Linux:

    ```bash
    source <env_name>/bin/activate
    ```

4. **Install Django:**

    ```bash
    pip install Django
    ```

5. **Create a new Django project:**

    ```bash
    django-admin startproject <project_name>
    ```

    Replace `<project_name>` with the name you want to give your Django project.

6. **Navigate to the project directory:**

    ```bash
    cd <project_name>
    ```

7. **Run the Django development server:**

    ```bash
    python manage.py runserver
    ```

    This will start the development server, and you can access your Django project at `http://127.0.0.1:8000/` in your web browser.

## Additional Resources

- [Django Documentation](https://docs.djangoproject.com/en/stable/)
- [Virtualenv Documentation](https://virtualenv.pypa.io/en/latest/)
