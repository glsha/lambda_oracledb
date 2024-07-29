# lambda_oracledb
In this project I connected oracledb in lambda using oracledb.

-What the project does
-> This project has libraries for oracle db and Oracle Instant Client which is needed to connect a oracle database in lambda.

  Download instant oracle db from https://www.oracle.com/database/technologies/instant-client/winx64-64-downloads.html

  Then install python-oracledb. Its better to get the libraries by using virtual environment. 

  python3 -m venv venv
  source venv/bin/activate
  pip install python-oracledb

  Make a seperate folder that has the Oracle Instant Client. And copy the oracledb libraries to that folder(it's in site-packages of your venv or where you       installed it). Then add your code for main. Here I have used python. 
  Then make a zip and add it to your lambda.
 
-How users can get started with the project
-> Change the username, password and other credentials according to your need in the python code. 

