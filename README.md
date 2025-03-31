# Learning Log WebApp
A web app called Learning Log that allows users to
log the topics they’re interested in and make journal entries as
they learn about each topic. The Learning Log home page will
describe the site and invite users to either register or log in. Once
logged in, a user can create new topics, add new entries, and read
and edit existing entries.

# Running 
Uptade pip,create a virtual enviroment and install the required packages
```shell
python -m venv venv_name
source venv_name/bin/activate
pip install --upgrade pip
pip install django  #Or pip install requirements.txt 
                    #if you want to make a copy-copy
```
Since it's a django project, create the db, run the project
```
python manage.py migrate
python manage.py runserver
```
# More info
Since this a basic project I'll use Trunk Based Dev because faster is better