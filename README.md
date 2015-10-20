# ServerConfiguration

IP address: 54.69.4.87
SSH-port: 2200

URL: http://ec2-54-69-4-87.us-west-2.compute.amazonaws.com/

## Instructions
### Access
1. Open command line or terminal
2. Input command: ssh grader@54.69.4.87 -i <SSH_KEY> -p 2200

## Setup
In addition to the modules requeired (stated below) and server setup, to run a Flask application on the apache server requires the following steps:
1. Prepare the Flask application on the server
2. Create a database user with appropriate permission levels for the application
2. Configure the database for the Flask application
3. Update OAuth details
4. Use WSGI to deploy the application


## Packages installed:

Python

PostgreSQL (psycopg2)

Apache2

Mod-WSGI

Flask

Git

httplib2

requests

oauth2client

SQLAlchemy

