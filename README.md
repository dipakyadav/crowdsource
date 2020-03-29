
# Crowdsource Editor with Google Sheets

## A. Get your Auth IDs

[Create a Google Project or Use Existing Project IDs](editor)  

## B. Install the Editor

####1. Install Python 3.7.
####2. From root directory run commands.
```
python3 -m venv env
pip install -r requirements.txt
```

####3. Add "app/app.py" to your .gitignore file so you don't deploy your keys.

####4. Add CLIENT\_ID and CLIENT\_SECRET from your Google project in "app.py".

####5. Add your GOOGLE\_SHEET\_URL to "app.py"

####6. Send yourself an email with these three values incase you loose your local clone.  

####7. Run/Server python app.

```
cd app
python3 app.py
```

#### Progress:
[&#x2714;] Login/Logout with google.  
 [&#x2714;] Store login details in sqlitedb - to be changed later.  
 [&#x2714;] Show/Hide edit menu on Login/Logout.  
 [ &nbsp; ] Edit form.  
