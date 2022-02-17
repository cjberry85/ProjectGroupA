# GroupProject

## Initial Set Up Instructions (Only Need To Do This Once) 

**Follow these steps to set up your computer to be able to run the project:**
<br/><br/>
1. Check you have Python 3 installed and if you don't have it then install it
  * enter `python3 --version` in command line to check which version you have, e.g. `Python 3.10.1`
2. Check you have pip3 installed and if you don't have it then install it
  * enter `pip3 --version` in command line- you will get an error if you don't have it installed
3. Ensure you have cloned the GitHub repository onto your own computer (see https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository for instructions)
4. Install virtualenv for Python
  * enter `pip3 install virtualenv` in command line
5. Create virtual environment
  * In the command line, change directory to the 'GroupProject' folder on your computer (the folder that contains the clone of the GitHub repository)
  * Change directory to the parent folder `cd ..`
  * Enter `virtualenv GroupProject-venv` in the command line to create the virtual environment to run the app in
  * **If the above doesn't work on mac try - `python3 -m virtualenv GroupProject-venv `
  * Activate the virtual environment by entering `source GroupProject-venv/bin/activate` (on Mac/Linux) or `.\GroupProject-venv\Scripts\activate` (on Windows)
6. Install Django and Crispy Forms in the virtual environment
  * Enter `pip3 install django`
  * Enter `pip3 install django-crispy-forms`
7. Navigate to the Django project
  * `cd GroupProject`
  * `cd PeratechSensors`
8. Enter `python3 manage.py migrate`

## How to Run the Django Project

**Each time you want to run it you will need to...**
<br/><br/>
1. Activate virtual environment
  * In the command line, change directory to the 'GroupProject' folder on your computer (the folder that contains the clone of the GitHub repository)
  * Change directory to the parent folder `cd ..`
  * Activate the virtual environment by entering `source GroupProject-venv/bin/activate` (on Mac/Linux) or `.\GroupProject-venv\Scripts\activate` (on Windows)
2. Navigate to the Django project
  * `cd GroupProject`
  * `cd PeratechSensors`
3. Start the project development server by entering...
 * `python3 manage.py runserver`
4. Navigate to http://127.0.0.1:8000/ in your web browser to access it.
