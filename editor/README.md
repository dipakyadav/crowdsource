
# Crowdsource Editor with Google Sheets

## Get a Google client\_id and client\_secret
1. Go to: [https://console.developers.google.com/apis/credentials](https://console.developers.google.com/apis/credentials)

2. Create a project or choose an existing project


3. Click ‘Enable and manage APIs’.

4. Make sure “Contacts API” and “Google+ API” are on.<!-- not sure if this is needed, 
found here: https://medium.com/binar-academy/social-login-login-with-google-account-4b10224494ac -->

5. Click Create credentials<!--Click "Create credentials" choose "OAuth client ID" then "Web Server"-->

6. Follow the steps in the screenshot below to get your Auth IDs.  
<br>

<img src="img/get-google-keys.png" style="width:100%;max-width:1000px">  

7. Choose "Create OAuth client ID" and "Service account"  

8. For "Service account permissions", choose role "Editor"

9. Click "Create key" and choose JSON. This key allows "Editor" access to your cloud resources.

10. Put the json file in the same directory where app.py resides, otherwise you will receive a filenotfounderror.

11. Update the path to json file within the app.py credentials variable.

	<span style="background-color: #FFFF00">Not sure if this is an issue: the "Service account client" did not appear like in the screenshot above.  It appeared for about 10 minutes with only a yellow warning icon. It did not have a link.</span>  

12. Add your GOOGLE\_CLIENT\_ID and GOOGLE\_CLIENT\_SECRET from your Google project to "app.py".  

	<span style="background-color: #FFFF00">These appear to be under OAuth 2.0 Client IDs "Web Application" above.
		<!-- Client_ID matches the one from D -->
	</span>  

13. Add "app/app.py" to your .gitignore file if you are using a public repo so you don't deploy your keys.

14. Add your GOOGLE\_SHEET\_URL to "app.py".

15. Send yourself an email with these three values incase you loose your local clone.  


<br>

---
[Run Setup](../)

