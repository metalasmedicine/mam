**How to install app**

In your Command Prompt enter:

    pip install virtualenv

Within your project:

    virtualenv env

Activate your virtualenv:

on Windows, virtualenv creates a batch file to run:

    \env\Scripts\activate.bat

**Installing libraries**

Open the requirements.txt and install the listed libraries and their versions being run on this app

**How to update the React app**

Run the following code in the reac-front-end folder to update the frontend:

npm run build

This command will build out the react frontend app to the main app at app/static and app/templates

**How to run the app**

run the following code in the main folder:

python run.py