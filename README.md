# django_react_ssr


#### Set up a virtual enviroment using pyenv
###### create virtual enviroment
```
pyenv virtualenv system venv
```
###### activate virtual enviroment
```
pyenv activate venv
```

* **NOTE** The rest of the commands are all executed within the virtual enviroment
---

#### Download yarn
```
npm install -g yarn
```
```
yarn --version
```

#### Install django (this command ensures that the installation is done for the virtual environment and not for the root python)
```
python -m pip install django
```

#### Start a Django project using:
```
django-admin startproject <project_name>
```

#### Change directory to the project you just created using:
```
cd <project_name>
```

#### Now start a Django app using
```
django-admin startapp frontend
```

#### Adding the app to the settings file
#### Go to `<project_name>/settings.py` and add the app you just created ```'frontend.apps.FrontendConfig',``` to the installed apps list.

#### Do The regular django settings(add url for the app, add urls.py and create a view ....)

####
