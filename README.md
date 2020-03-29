
# Crowdsource Editor with Google Sheets

## A. Get your Auth IDs

[Create a Google Project or Use Existing Project IDs](editor)  

## B. Install the Editor

####1. Add CLIENT\_ID and CLIENT\_SECRET from your Google project in "app.py".

####2. Add your GOOGLE\_SHEET\_URL to "app.py"

####3. Add "app/app.py" to your .gitignore file if you are using a public repo so you don't deploy your keys.

####4. Send yourself an email with these three values incase you loose your local clone.  

####5. Install Python 3.7.  

####6. Within your crowdsource root directory run commands:
```
python3 -m venv env
. env/bin/activate
pip install --upgrade pip
pip install Flask
pip install flask_csv
pip install -r requirements.txt
```

####7. Run/Server python app.

```
cd app
python3 app.py
```
####8. Go to [https://127.0.0.1:5000/](https://127.0.0.1:5000/) to view the app.

Stuck at this point.  Tried using http://localhost:5000  
Tried Chrome. Tried Brave browser.  
Next try getting a different Google Auth.  

#### Progress: (Not currently working)
[&#x2714;] Login/Logout with google.  
 [&#x2714;] Store login details in sqlitedb - to be changed later.  
 [&#x2714;] Show/Hide edit menu on Login/Logout.  
 [ &nbsp; ] Edit form.  
