# PHP-Docker & Guideline for Building and Running

Step 1: cd into directory
Step 2: run command: docker-compose up -d

# If you wanna stop docker
Run command: docker-compose down

## Note
NOTE: In order for the app to work you will have to create a database named "company1", a "users" table with the columns "name" and "fav_color" in order for the errors to go away.

You can do this in localhost:8080 (adminer) with "root" as user, "123456" as password. "MySQL" selected for the system, and "db" as the server.

Then create the database & table and you should be able to see the php grab the users and display them.
