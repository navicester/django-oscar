fork this project from https://github.com/django-oscar/django-oscar

git clone ```git@github.com:navicester/django-oscar.git```

http://django-oscar.readthedocs.org/en/latest/internals/sandbox.html
fail to run "(oscar) $ make sandbox" in my environment

python setup.py install

 - pip install six
 - pip install django==1.9.4
 - pip install django_extensions
 - pip install django_debug_toolbar (NOT debug_toolbar)
 - pip install Whoosh
 
sites\sanbox

python manage.py migrate

python manage.py createsuperuser



babel==1.3
Django==1.9.4
django-debug-toolbar==1.4
django-extensions==1.6.1
django-extra-views==0.6.4
django-haystack==2.4.1
django-oscar==1.2.dev0
django-tables2==1.0.7
django-treebeard==4.0
django-widget-tweaks==1.4.1
factory-boy==2.6.1
fake-factory==0.5.7
funcsigs==0.4
ipaddress==1.0.16
mock==1.3.0
pbr==1.8.1
phonenumbers==7.2.7
pillow==3.1.1
purl==1.2
python-dateutil==2.5.0
pytz==2015.7
six==1.10.0
sorl-thumbnail==12.4a1
sqlparse==0.1.19
unidecode==0.4.19
wheel==0.24.0
Whoosh==2.7.2
