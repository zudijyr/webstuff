#make a virtual env:
virtualenv venv

#activate it:
source venb/bin/activate

#install requirements:

pip install --editable .

#start application:
export FLASK_APP=flaskr
export FLASK_DEBUG=true
flask run

#all code taken from flask tutorial
