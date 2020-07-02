This project is a basic demonstration on how Django Rest API works in integration with Postgresql database.<br>
To run the api, please change the database settings in settings.py in DjangoRestApi folder. Once the changes are made, run the following code to create tables in the database.<br>
python manage.py migrate<br>
Once the tables are created, import the vent availability sheet from the data file into the database. <br>
Once the above steps are followed, the api is ready to function.<br>
Note: The main url is /Vent/vent/.
