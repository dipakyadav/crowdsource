1. Install Python3.7.
2. From root directory run below commands.
```
python3 -m venv env
pip install -r requirements.txt
```
3. Update client_id and client_secrete from google app in `app.py`.
4. Run/Server python app.
```
cd app
python3 app.py
```

#### TODO:
 - [x] Login/Logout with google.
 - [X] Store login details in sqlitedb,  To be changed later
 - [ ] Firebase implementation : TBD
 - [x] Show/Hide edit menu on Login/Logout
 - [ ] Edit form
