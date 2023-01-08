# XBlock Test Task
## How to install:
Clone a repository:  
```
https://github.com/OvDima1/XBlock.git
```
Create and activate a virtual environment:  
```
python3 -m venv venv
source venv/bin/activate
```
Clone the XBlock-sdk:  
```
git clone https://github.com/openedx/xblock-sdk.git
```
Change directory to sdk directory and install requirements:
```
cd xblock-sdk
pip install -r requirements/base.txt
```
Make migrations and return to your project root
```
python manage.py migrate
cd ..
```
Install simplexblock
```
pip install -e simplexblock
```
Change directory to xblock-sdk and run local server
```
cd xblock-sdk
python manage.py runserver
```
