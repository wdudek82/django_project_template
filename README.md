=========================
 Django Project Template
=========================

root folder
-----------
1. apps - folder for storing projectcs apps
2. backend - django projects primary folder (with settings, main urls.py, etc.)
3. env - folder with server & supervisor config
4. make.sh - creates virtual environment & install all requirements
5. run.sh - shortcut to start venv in more convenient way
6. var - store log folder
7. venv - directory containing virtual environment


Installation
------------

1. Clone Django Project Template from git (renaming it as you see fit),
2. cd to its root folder,
3. run make.sh (". make.sh") - it'll install virtual env (to venv folder) + all project's requirements, and finally activates it (later you can use run.sh or explicitly using . venv/bin/activate),
4. in backend/settings/settings.py set DEBUG variable,
5. adjust config in backend/settings/development.py or backend/settings/production.py,


Database settings
-----------------

1. change [project-name]/backend/settings/settings.py database settings
2. ...
3. ...

[ nginx settings ]

[ supervisor settings ]

(configuring & connectig with nginx/apache2)
