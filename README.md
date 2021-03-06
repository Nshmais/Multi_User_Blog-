# Multi-User-Blog

<img src="/static/img/logo.png" width="100"> Registration, Login, Logout

The multi user Blog is a website that will allow users to create their own Blogs and post them for others to share and spark conversation and collaboration between users.

The users will be allowed to register (Sign up) and create a username and password to save their blogs.
then the can login and acsess all his Blogs at any times he/she pleases.  

## URL
You can view the deployed application by [clicking here](https://multi-user-blog-169803.appspot.com/) or copy and paste the following URL: 
```
   https://multi-user-blog-169803.appspot.com/
```
for instruction to deploy the app to Gooogle App Engine [click here](https://cloud.google.com/appengine/docs/standard/python/getting-started/deploying-the-application) 

## Tools
There are many tools uses in this project such as Google App Engine, postgres database, HTML, CSS, Python... etc.  


## Installation and Run

In order to install and run the project please follow the following steps:
1. Download or clone the project at [here](https://github.com/Nshmais/Multi_User_Blog-) or run this in the command line:

   ```
      $ git clone https://github.com/Nshmais/Multi_User_Blog-
      $ cd Multi_User_Blog-
   ```
   
2. Install google cloud app engine Shell (Google Cloud SDK Shell).
3. Navigate the Google Cloud SDK Shell commandline to the folder where the project files are saved.
4. In the command prompt in project folder, run the command (dev_appserver.py app.yaml).
    ```
        $ dev_appserver.py app.yaml
    ```

5. The project will run on the appropriate port (usually is localhost:8080) or check the command line.
6. To terminate the Localhost IP on Google Cloud SDK Shell commandline type **Ctrl+C**.
7. Wish you luck, and hope you are not depending on it.

## Debug
To write on the console in Google App Engine for debugging use the following in blog.py:
```
   import logging

   logging.info("hello")
```
## Access Database
In Google App Engine DB is called **Datastore**. To navigate to the datastore viwer to see your tables go to *admin_server* localhost port. It will displayed when you run the project on the console (in my case "localhost:8000")
```
      admin_server.py:116] Starting admin server at: http://localhost:8000
```
 When you are in the admin_server, choose **Datastore Viewer** from the sidebar and use dropdown menu to swich between tables.
 
## License
`Multi-User-Blog` is a released under the [MIT License](https://opensource.org/licenses/MIT)
