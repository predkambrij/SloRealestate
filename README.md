SLO Realestate
===================

Project to parse and make sense of slovene real-estate ads

## Setup

This is a Django project.

```python
pip install -r requirements.txt
python manage.py syncdb
```

## Notes

    sudo apt-get install postgresql-common
    sudo apt-get install postgresql-server-dev-10
    sudo apt-get install postgresql-client-10
    sudo apt-get install python-queuelib
    pg_config -v
    pg_config --version
    pip install -r requirements.txt 

    sudo apt-get install locales 
    sudo dpkg-reconfigure locales
    vim ./si_estate/settings.py
    psql -h 192.168.0.10 -U postgres
    sudo locale-gen sl_SI
    sudo locale-gen sl_SI.UTF-8
    sudo update-locale
    sudo apt-get install gnulib

    python manage.py migrate
    python manage.py parse
    python manage.py runserver
    python manage.py runserver 0.0.0.0:8080
