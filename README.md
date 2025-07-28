#This APDS BackEnd Setup

# 1 install Python/PIP in your setup using below URl also verify Python and Pip using 
```
https://www.python.org/downloads/
python --version
python -V
pip --version
```

# 2 Need to get Code of Backend, to clone the repository use the below command
```
git clone -b dev https://github.com/DevAro178/backend_apds.git
```

# 3 Need to install all the packages related to backend application
```
python -m venv env
source ./env/Script/activate
cd backend-apds
pip install -r requirement.txt
```
# 4 Need to perform all the migration
```
python manage.py make migrations
python manage.py migrate
```
# 5 Now run the application
```
python nmanage.py runserver
```
