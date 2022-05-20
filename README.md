# todo-app-flask-mongodb
This is a simple Flask app to create a todo list with MongoDB

Instructions
Download [python](https://www.python.org/downloads/)

Download [MongoDB](https://www.mongodb.com/download-center#community)


## Create a virtual environment:

- Run the following command to create the virtual environment:
'python3 -m ven venv'\
- Activate env 
'source ./venv/bin/activate'

## Install the requirements

'pip install -r requirements.txt'


Before running the mongodb instance, we must create a data folder and run below command in command prompt.

"C:\Program Files\MongoDB\Server\4.0\bin\mongod.exe" --dbpath="C:\mongo-data"

Here C:\mongo-data folder is used for saving mongodb files.

By default, it is listening the port 27017.

Download/Clone source code from Github
Run app.py in Command prompt.

python app.py

Our local web server is running in the port 5000 by default.
