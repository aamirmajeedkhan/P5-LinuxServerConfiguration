# P5-LinuxServerConfiguration

### Overview

This is the 5th project assignment of udacity full stack developer. This project involves a baseline installation of a Linux distribution on a virtual machine and prepares it to host a python and postgresql based web application by installing updates, securing it from a number of attack vectors, and installing/configuring web and database servers.

### IP
The server ip address is [52.33.165.219].

### HTTP

The application, [Fantasy Football](https://github.com/aamirmajeedkhan/FantasyFootball), is available at  [52.33.165.219](http://ec2-52-33-165-219.us-west-2.compute.amazonaws.com).

### SSH

SSH into the server by executing the command:

```
ssh -i ~/.ssh/[rsa_key] grader@52.33.165.219 -p 2200
```

### List of Software Installed

apache2
libapache2-mod-wsgi
postgresql
git
python-psycopg2
python-sqlalchemy
python-pip
werkzeug==0.8.3
flask==0.9
Flask-Login==0.1.3
oauth2client
requests
httplib2
flask-seasurf
