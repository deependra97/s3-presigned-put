Backend lambda function is named lambda_function.py

Things to be changed in lambda_function.py
____________________________________________________
- bucket_name
- region
- expiration

lambda test event
-----------------------------------------------------
{
      "file1": "music1.mp3",
      "file2": "music2.mp3",
      "file3": "music3.mp3",
      "file4": "music4.mp3",
      "file5": "music5.mp3"
    }

-----------------------------------------------------

API Gateway: 
---------------------------------------------------
1) create a Rest API(Post method) and point it to trigger lambda


Frontend side: 
-----------------------------------------------------

1) git clone
2) npm install
3) Go to App.js file and update the API endpoint on requestURL

(Note: we must need to input all five input fields and response are logged in console) 
