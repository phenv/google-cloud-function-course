# Google Cloud Function Course
## Starting a project
To start a new project in Google Cloud we can go to [Firebase Console](https://console.firebase.google.com) or create it from [Google Cloud Platform Console](https://console.cloud.google.com)
----------From now on, phenv will be updater--------------
## Creating a virtual environment
First we have to install `python3-venv` with the following command:
```
sudo apt get install python3-venv -- For Mac: pip install virtualenv
```
Then, we execute the following command:
```
python3 -m venv venv
```
To activate the virtual environment we do:
```
source ven/bin/activate
```
In order to add new packages to our new virtual environment we create a file called `requirements.txt` and execute the following command:
```
pip install -r requirements.txt
```