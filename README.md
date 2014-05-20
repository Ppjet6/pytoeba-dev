Pytoeba-dev
==========

This is a preconfigured template project for (pytoeba)[https://github.com/loolmeh/pytoeba]

Dependenices
---------

See pytoeba's readme file.

Usage
-----

  git clone https://github.com/loolmeh/pytoeba-dev.git
  cd pytoeba-dev/
  git submodule init
  git submodule update
  cd pytoeba-git
  git pull
  cd ..
  git submodule update
  
  python manage.py syncdb --migrate
  python manage.py runserver
