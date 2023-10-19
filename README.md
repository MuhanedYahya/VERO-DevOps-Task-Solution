## DevOps Task
#### You can lunch the application by typing :
```
docker-compose up web-server --build -d
```
You can access the installed PDO drivers and other PHP information from the link 
```
http://localhost:8080/info.php
```
And to access the QuickDbTest.php page
```
http://localhost:8080/QuickDbTest.php
```
#### Notes
- The new ODBC (msodbcsql18) version requires TLS by default to connect to MSSQL
- A better and safer method would be to define an env file for MSSQL and call it from the docker-compose file.
- (info.php and index.html) pages have been added for testing purposes only.