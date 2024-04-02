
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

  ## BLOGAPP
  
![Screenshot (216)](https://github.com/Sreepurvaja/BlogApp-/assets/99593891/deca232e-7651-4f1a-932d-1113cb12df39)
  ## signup 
  
![Screenshot (224)](https://github.com/Sreepurvaja/BlogApp-/assets/99593891/1c12b73e-6c6a-4afe-ba7e-8a8721e10ddf)
  ## login
  
![Screenshot (217)](https://github.com/Sreepurvaja/BlogApp-/assets/99593891/e1d13860-602d-42b3-b6a4-d970aa783053)
  ## Add article
  
![Screenshot (218)](https://github.com/Sreepurvaja/BlogApp-/assets/99593891/3dd9fd2d-c0b7-44fb-ac31-cfb109f1791b)
  ## Dashdoard
  
![Screenshot (219)](https://github.com/Sreepurvaja/BlogApp-/assets/99593891/e23feb19-3341-4173-a017-acccaff1fa1a) 
  ## Delete Blog
  
 ![Screenshot (221)](https://github.com/Sreepurvaja/BlogApp-/assets/99593891/5face653-b9af-4d23-8516-c3100154a9e2)
  ## Edit Blog
  
 ![Screenshot (220)](https://github.com/Sreepurvaja/BlogApp-/assets/99593891/cf672ec3-f618-4e4e-8889-7a4ba964c322)
  ## View Blog
  
![Screenshot (223)](https://github.com/Sreepurvaja/BlogApp-/assets/99593891/7d8a8123-1d25-4427-812e-60708a2dbae4)
  ## Add Comments
  
![Screenshot (222)](https://github.com/Sreepurvaja/BlogApp-/assets/99593891/f6d011cb-e6fc-43d4-b40a-066609104d66)




