# Learning Management System Created Using Django
This is a Webstack - Portfolio Project on Learning Management System created using Django 

## Features of this Project

### A. Admin Users Can
1. Manage users profile information (Add, Update and Delete)
2. Manage users (Add, Update and Delete)
3. Manage Students (Add, Update and Delete)
4. Manage Courses (Add, Update and Delete)
5. Manage Subjects (Add, Update and Delete)
6. Manage Lessons (Add, Update and Delete)
8. Review and Reply Student/Staff Feedback
9. Manage Workdays (Add, Update and Delete)
10. Manage Slot Subjects (Add, Update and Delete)
11. Manage Time Slots (Add, Update and Delete)
12. View Dashboards 

### B. Staff/Teachers Can
1. Register or Login 
2. Manage Subjects (Add, Update and Delete) 
3. Manage Lessons (Add, Update and Delete)
4. Manage(Add, Update and Delete), Review and Reply Student/Staff Feedback

### C. Students Can
1. Register or Login 
1. Access Courses (Add, Update and Delete)
5. Access Subjects (Add, Update and Delete)
6. Access Lessons (Add, Update and Delete)
8. Review and Reply Student/Staff Feedback


## How to Install and Run this project?

### Pre-Requisites:
1. Install Git Version Control
[ https://git-scm.com/ ]

2. Install Python Latest Version
[ https://www.python.org/downloads/ ]

3. Install Pip (Package Manager)
[ https://pip.pypa.io/en/stable/installing/ ]

*Alternative to Pip is Homebrew*

### Installation
**1. Create a Folder where you want to save the project**

**2. Create a Virtual Environment and Activate**

Install Virtual Environment First
```
$  pip install virtualenv
```

Create Virtual Environment

For Windows
```
$  python -m venv venv
```
For Mac
```
$  python3 -m venv venv
```
For Linux
```
$  virtualenv .
```

Activate Virtual Environment

For Windows
```
$  source venv/scripts/activate
```

For Mac
```
$  source venv/bin/activate
```

For Linux
```
$  source bin/activate
```

**3. Clone this project**
```
$  git clone https://github.com/henoktesfaye700/Portfolio-Project.git
```

Then, Enter the project
```
$  cd Portfolio-Project
```

**4. Install Requirements from 'requirements.txt'**
```python
$  pip3 install -r requirements.txt
```

**5. Now Run Server**

Command for Windows:
```python
$ python manage.py runserver
```

Command for Mac:
```python
$ python3 manage.py runserver
```

Command for Linux:
```python
$ python3 manage.py runserver
```

**6. Login Credentials**

Create Super User
Command for PC:
```
$  python manage.py createsuperuser
```

Command for Mac:
```
$  python3 manage.py createsuperuser
```

Command for Linux:
```
$  python3 manage.py createsuperuser
```