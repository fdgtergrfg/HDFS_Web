# HDFS_Web

#### Introduction
This is the program for Hithub platform, which is used to show repositories and manage user privilege.

#### Requirements
This program needs to be run under python 3.6 environment, and the external modules in requirements.txt file.

#### List of folders and files
1. BackEnd: This folder contains all the back-end code.
2. HDFS_Web: This folder is a default folder for program setting, which is created which creating the project.
3. Repos: This is a assistant folder for creating repositories on Hithub platform.
4. static: This is folder for front-end external resources, including css, javascript and etc.
5. templates: This is a folder for front-end code, which contains all the web pages.
6. requirements.txt: This file contains all the modules needed for the start of Hithub.
7. uwsgi.ini and uwsgi_params: These two files are uwsgi configuration files.
8. start_server.sh: This file is used to start the Hithub server.

#### Installation
1. Install python 3.6 environment.
2. Install external modules using command "pip install -r requirements.txt".
3. Change the Ip address and port in HDFS_Web/contexts.py file.
4. Run the Hithub platform using command "sh start_server.sh".