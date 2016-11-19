=========================
 Django Project Template
=========================

root folder
-----------
1. backend - django projects primary folder (with settings, main urls.py, etc.)
2. env - folder with server & supervisor config
3. project - folder for storing projectcs apps - has its own setting.py and urls.py
4. var - store log folder
5. venv - clean virtual environment
6. run.sh - shortcut to start venv in more convenient way


Installation
------------

1. Clone project from git (renaming it as you see fit):
2. cd to its root folder,
3. there activate virtualenv: . run.sh (or explicitly: . venv/bin/activate)
4. after activating venv install projects dependencies: pip install -r requirements.txt
5. in backend/settings/settings.py set DEBUG variable
6. adjust config in backend/settings/development.py or backend/settings/production.py


Database settings
-----------------

1. change [project-name]/backend/settings/settings.py database settings
2. ...
3. ...

[ nginx settings ]

[ supervisor settings ]

(configuring & connectig with nginx/apache2)
