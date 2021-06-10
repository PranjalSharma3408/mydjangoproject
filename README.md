# My Django Project

## Setup Instruction

This project requires [Python](https://python.org/) v3.9+ to run.

Install the dependencies and devDependencies and start the server.

```sh
pip install virtualenv
virtualenv mydjango
source mydjango/bin/activate
cd mydjanoproject
pip install -r requirements.txt
python manage.py createsuperuser
python manage.py runserver
```

Django application can be accessed on `localhost:8000`