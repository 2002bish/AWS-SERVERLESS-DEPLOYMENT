At first create a lambda function of GET and POST. 
create a table in dynamodb for this,
After that open API Gateway and create new API which later on you will keep it in script.js where API is asked,
After that create a method if both GET and POST.
Now upload your application on the S3 bucket and change the permission and properties and create bucket policy
Here your application will run in http, for more secure 
we are using a cloudfont and create a new cloudfont and copy that policy and come back to the bucket policy and change with the new policy.
Now when we run the application then it will run on Https.
Thank you.
![Screenshot 2024-08-12 125508](https://github.com/user-attachments/assets/fab4fef7-19b2-46d2-bf97-1fd8eb68552e)
![CloudFront](https://github.com/user-attachments/assets/3a673681-1f82-43c9-96f5-85dd69270713)
