## Flask_Blog
This is a blog developed using Flask microframework.
This is the project I'm doing while learning Flask from a [tutorial](https://www.youtube.com/watch?v=MwZwr5Tvyxo&list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH&index=1)  that I found in YouTube.

## Setup instructions
It is always a good practice of creating new virtual environment for a python project.
  * At first clone this repository using: `git clone https://github.com/itssubas/Flask_Blog`
  * Go to this directory `cd Flask_Blog`
  * Create new virtual environment: You need to have `virtualenv` installed first. 
To install virtual environment in your Unix/Linux device `sudo apt-get install python-virtualenv`
 After the installation is done, create a new virtual enviroment for this project. For that, `cd` to the project directory and `virtualenv myenv` .
  * Now activate virtual environment using `source myenv/bin/activate`
  * Install the requirements using `pip install -r requirements.txt`
  * `export FLASK_ENV=development` for setting FLASK_ENV environment variable to development mode
  * `python run.py` To run the project. Flask will setup it's lightweighted server running in `127.0.0.1:5000`
  * Also you need to create a database. I've used sqlite3 for this project.

