# NFT-Market-Place-Backend
This is the backend repository for our NFt Marketplace app

to install follow this guide 

Use the terminal/command line to cd into the folder nft-backend-main. If there is a file called 'venv', erase that file and create a new one by using '$ virtualenv venv'. After that is done you will need to activate the virutal environment by using '$ source venv/bin/activate'. After doing that command, you should see a "(venv)" before your computers directory in the command line. Once that is done, to install all dependencies needed the command will be '$ pip install django djangorestframework djangorestframework-simplejwt djoser psycopg2 psycopg2-binary whitenoise dj-database-url ' this command will install all dependencies needed to run the backend. once this is done, write '$ python manage.py makemigrations' and then '$ python manage.py migrate' once it is done doing the migrations, to run the server you must write '$ python manage.py runserver' this will run the server and 


Once you have installed PostgreSQL, open the psql terminal and go into the postgres database which should already be there. once you are there, write 'CREATE DATABASE nft_authentication OWNER postgres;' make sure to write that exact name since it is already named like that in the django project. Also make sure to put the semi-colon at the end.
