# Systemlux-Backend
## Setup
### Installation on Linux, Mac OS and Windows

* [Follow the guide here](https://help.github.com/articles/fork-a-repo) on how to clone or fork a repo
* [Follow the guide here](http://simononsoftware.com/virtualenv-tutorial/) on how to create virtualenv


### Setup Virtual environment
  ```
  $ virtualenv --python=python3.10 myvenv

  $ source myvenv/bin/activate
  ```

### Install Project Requirement, Migrations and Run
```
$ pip install -r requirement.txt

$ python manage.py migrate

$ python manage.py runserver

```