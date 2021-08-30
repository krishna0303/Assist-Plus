
# Assist Plus

## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/krishna0303/Assist-Plus.git
$ cd Assist-Plus
```


## Getting Started

Setup project environment with [virtualenv](https://virtualenv.pypa.io) and [pip](https://pip.pypa.io).

```bash
$ virtualenv project-env
$ source project-env/bin/activate
$ pip install -r https://raw.githubusercontent.com/juanifioren/django-project-template/master/requirements.txt

# You may want to change the name `projectname`.
$ django-admin startproject --template https://github.com/juanifioren/django-project-template/archive/master.zip projectname

$ cd projectname/
$ cp settings_custom.py.edit settings_custom.py
$ python manage.py migrate
$ python manage.py runserver
```

## Features

* Assist Plus is a blogging platform where users can write or read any articles related to any domain and they can share their experiences or thoughts to others.
* Users can register and create/update their profile.
* Users can post,update and delete posts.

## Contributing

I love contributions, so please feel free to fix bugs, improve things, provide documentation. Just send a pull request.
