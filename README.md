
# BloggingApp 
A simple end to end blogging application created using **flask** and **MySql**.

Users can signup  and login to website to write a blog. And  they can edit , delete their blog . view their blog. And they can give comments to the blog.

## Set up
- Create a database named *flaskapp* in **MySql**
- Create tables named **users** and **articles**
- Change *MySql* credentials in ```app.py``` file (line : 13)
- Open command prompt and navigate to project folder and then run ***app.py***

  
  ```bash
  python app.py
  ```

  - you can see that project is running on localhoat port number 5000, can acess through ```localhost:5000```

  ## Database
        CREATE DATABASE flaskapp;

        USE flaskapp;

        CREATE TABLE articles (id INT(11) AUTO_INCREMENT PRIMARY KEY, title VARCHAR(255), author VARCHAR(100), body TEXT, create_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP);

        CREATE TABLE users(id INT(11) AUTO_INCREMENT PRIMARY KEY, name VARCHAR(100),email VARCHAR(100), username VARCHAR(30), password VARCHAR(100), register_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP);
