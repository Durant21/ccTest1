ccTest1
=======

Getting Started
---------------

- Change directory into your newly created project.

    cd ccTest1

- Create a Python virtual environment.

    python3 -m venv env

- Upgrade packaging tools.

    env/bin/pip install --upgrade pip setuptools

- Install the project in editable mode with its testing requirements.

    env/bin/pip install -e ".[testing]"

- Run your project's tests.

    env/bin/pytest

- Run your project.

    env/bin/pserve development.ini


This project was created on Ubuntu, using cookiecutter from the command line
and the opening in Pycharm 2019.1.1

