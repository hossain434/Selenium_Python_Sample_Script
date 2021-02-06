# Selenium_Python_Sample_Script

1. Install python (I used 3.7).
2. pip is a package-management system used to install and manage software packages written in Python (similar like npm).pip is inside of python folder.
3. Set 2 environment variables. .\Python\python37-32\  and .\Python\python37-32\Scripts.
4. Verify in cmd: python --version; pip --version.
5. Create Virtual Environments:A virtual environment is a tool that helps to keep dependencies required by different projects separate by creating isolated python virtual environments for them.

> pip install virtualenv

> pip install virtualenvwrapper-win

> python -m virtualenv <nameOfEnv>  [command we will create a virtual environment, then create project directory and then finally bind the environment to the project directory.]
  
> cd amazon

> setprojectdir .

We can deactivate the environment by typing in command deactivate or exiting the command prompt. However, if we want to work more on our project using this environment, we simply need to type virtualenv activate.

> pip install selenium

> pip check selenium

> pip show selenium

Installing ChromeDriver, under name ‘drivers’ in project folder.
