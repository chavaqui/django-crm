
*Create a subfolder at top lvl of files*
> sudo apt install python3-virtualenv
> virtualenv venv
>
> source venv/bin/activate
* Join into to venv >(venv)*
>(venv) pip install django
>
*Necesary to select interpreter in VSCODE useing F1 and type -interpreter- (venv)*
>(venv) django-admin --version
> NO: (venv) django-admin startproject .               -> With . does not creates a subproject folder
>(venv) python manage.py runserver 3005               -> optional, to add a port 3005 or whatever
>(venv) python manage.py startapp store                -> Creates a new app(module or subproject) named store
>(venv) python manage.py shell                         -> Opens the shell to run comands as ORM of django to create and acces to database
