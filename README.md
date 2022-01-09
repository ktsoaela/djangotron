# djangotron
Django and Electron application  <br />

A simple way to start an elecrton project that is directly linked to your django project <br />

## To Use Electron

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash

# Clone this repository
git clone https://github.com/electron/electron-quick-start
# Go into the repository
cd electron-quick-start
# Install dependencies
npm install
# Run the app
npm start
```

## To Use Django

```bash

# install django inside "electron-quick-start folder
pip3 install django
#initate project
django-admin startproject mysite
#enter mysite directory
cd mysite
#start django server
python manage.py runserver
```
### Django + Electron
```
#change line main.js file:
from:
mainWindow.loadFile('index.html') 
to: 
mainWindow.loadURL('http://127.0.0.1:8000')
```

### Well done! you officialy have a django+electron app.
<img src="https://raw.githubusercontent.com/ktsoaela/djangotron/main/djangotron.png">

## Resources and Special thanks to:
https://github.com/electron/electron-quick-start  
https://github.com/electron  
https://github.com/django/django  
