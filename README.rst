Simple Flask App
================

Aplikacja Dydaktyczna wyświetlająca imię i wiadomość w różnych formatach dla zajęć 
o Continuous Integration, Continuous Delivery i Continuous Deployment.

- Rozpocząnając pracę z projektem:

  ::

    mkvirtualenv wsb-simple-flask-app
    pip install -r requirements.txt
    pip install -r test_requirements

- Kontynuując pracę z projektem:

  ::

    workon wsb-simple-flask-app

- Uruchamianie applikacji:

  :: 

  	# jako zwykły program
    python main.py

    # albo:
    PYTHONPATH=. FLASK_APP=hello_world flask run

- Uruchamianie testów:

  ::

    PYTHONPATH=. pytest

- Integracja z TravisCI:

  ::

    ...


Materiały
=========

- https://virtualenvwrapper.readthedocs.io/en/latest/