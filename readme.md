To run this project
1. Create Mysql database with name "demo"
2. create .env file inside project directory and refer the .env.example file 
   for the configuration of settings.py
3. pip install -r requirements.txt
4. pip install mysqlclient <br>
    if error occured the use .whl file to install mysqlclient:<br>
   pip install mysqlclient-1.4.6-cp37-cp37m-win32.whl<br>
   File is attached inside this project
   
5. give the command as:
        python manage.py setup.

6. python manage.py setup => this will do all migrations and even loads the data also don't need to create super user.

