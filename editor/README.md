
# Crowdsource Editor with Google Sheets

## Get a Google client\_id and client\_secret
1. Go to: [https://console.developers.google.com/apis/credentials](https://console.developers.google.com/apis/credentials)

2. Create a project or choose an existing project

3. Follow the steps in the screenshot below to get your Auth IDs.  
<br>

<img src="img/get-google-keys.png" style="width:100%;max-width:1000px">  

4. Choose "Create OAuth client ID" and "Service account"  

5. For "Service account permissions", choose role "Editor"

6. Click "Create key" and choose JSON. This key allows "Editor" access to your cloud resources.

7. Put the json file in the same directory where app.py resides, otherwise you will receive a filenotfounderror.

8. Update the path to json file within the app.py credentials variable.

9. Make note of your GOOGLE\_CLIENT\_ID and GOOGLE\_CLIENT\_SECRET.  
<br>

---
[Run Setup](../)

