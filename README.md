> sudo apt install python3-virtualenv
> virtualenv venv
>
> source venv/bin/activate
>
> pip install django
>
*Necesary to select interpreter in VSCODE useing F1 and type -interpreter- (venv)*
>django-admin --version
> NO: django-admin startproject .               -> With . does not creates a subproject folder
> python manage.py runserver 3005               -> optional, to add a port 3005 or whatever
>python manage.py startapp store                -> Creates a new app(module or subproject) named store
>python manage.py shell                         -> Opens the shell to run comands as ORM of django to create and acces to database
