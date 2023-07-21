
## Index
    - [Introduction](#introduction)
    - [Installation](#installation)

### Introduction
- Implementing OAuth in Django using 'django-allauth' package
- follow step by step instruction


| Plugin | **Version**|
| ------ | ------ |
|  pip   | 23.0.1 |
| Python | 3.10 |
| Django | 4.2.3 |

### Setup & Run

> ##### 1. upgrade pip
```sh
pip install --upgrade pip
```

> ##### 2. Create python environment
```sh
python3 -m venv virtual
```

> ##### 3. Activate the virtual environment
```sh
source  virtual/bin/activate 
```

> ##### 4. Install requirement package
```sh
pip install -r requirements.txt
```

> ##### 5. Creat database table
```sh
python3 manage.py migrate
```

> ##### 6. Run django development server
```sh
python3 manage.py runserver
```

> ##### 7. configure your google key in admin panel.
```sh
http://127.0.0.1:8000/admin/
```

<br />