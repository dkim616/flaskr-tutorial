# flaskr-tutorial

To install:

1. Clone repository.

2. Create a virtual environment in repository directory.
  ```
  $ pip install virtualenv
  $ virtualenv venv
  ```

3. Activate venv.
  ```
  source venv/bin/activate
  export FLASK_APP=flaskr
  export FLASK_DEBUG=true
  ```
  You might want to check out https://github.com/kennethreitz/autoenv for easy venv setup.

4. Install the Flaskr package.
  ```
  pip install -e .
  ```
  
5. Run the server.
  ```
  flask run
  ```
  By default, the server runs locally on localhost:5000.
  
6. Close the server.

  Use `CTRL+C` to stop the server and `deactivate` to stop venv.
