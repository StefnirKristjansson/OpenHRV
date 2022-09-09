To setup

On windows:
Install newest version of Python on your local machine in a specific directory. 
For example, if you have Python 3.10.2 installed, you can install it in the directory C:\python\py310.

Then you creat a virtual environment in this directory by typing c:\python\py310\python -m venv venv.

Now that the virtual environment is created, depending on your setup you will have to get it to work.
In visual studio code if you have Python package installed you should see a popup that will ask you if you want to use the new virtual environment.
When its working you shuld try to run the run.py file in the virtual environment. You shuld see an error becues of needed packages.

venv\Scripts\activate

Install the packages by typing the following in the command line:
pip install -r requirements.txt

Then you shuld be able to run the run.py file.


Please update the readme if you do any alterations that other developers need to be aware of.

IMPORTANT: DO NOT EDIT existing classes in models.py they do not automatically update in production. 
If you create a new class it will be created but old classes will NOT be updated. 

Do not work on the main branch, always create a branch from main and work on that, when its ready create a pull requests to main.
Dont just push to main as it will be rejected. 

When working with this application you need to know:
fastapi: https://fastapi.tiangolo.com/ 
sqlmodels: https://sqlmodel.tiangolo.com/


How to work with this repository:

Do not create a branch without any existing issues on github. To fix an issue create a branch from that issue and work on that.
Start off by writing the tests and when that is done create a draft pull request.
When the draft pull request is created work on the issue, when the code is ready make the draft pull request ready for review.