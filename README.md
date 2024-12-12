Todoism
We are Todoist, we use Todoism.

A sample application for Python Web Development with Flask (《Flask Web 开发实战》).

Demo: http://todoism.helloflask.com



Installation
Clone the repository:
bash
Copy code
$ git clone https://github.com/greyli/todoism.git
$ cd todoism
Set up the virtual environment and install dependencies:
Using venv or virtualenv with pip:
bash
Copy code
$ python -m venv env  # Use `virtualenv env` for Python2, use `python3 ...` for Python3 on Linux & macOS
$ source env/bin/activate  # Use `env\Scripts\activate` on Windows
$ pip install -r requirements.txt
Or using Pipenv:
bash
Copy code
$ pipenv install --dev
$ pipenv shell
Initialize the database and start the application:
bash
Copy code
$ flask initdb
$ flask translate compile
$ flask run
* Running on http://127.0.0.1:5000/



![image](https://github.com/user-attachments/assets/3f719b2b-fbe7-4f26-9df0-af2bd011f945)
