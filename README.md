# Documentation

## How to make a new webproject
1. Open Intellij 2021.3
2. click new project
3. choose JavaEnterprise
4. choose project template `Web Application`
5. add tomcat server 9 (You may need to add it manual)
6. Choose Java, Maven and JUint
7. click next and then finish

## Structure
This project uses the the MVC-pattern



![MVC Image](Assets/mvc.png)

- (M)odel - Entities and helper- methods and classes. Also known as Business logic.
- (V)iew - JSP and frontend (css, bootstrap, mm.)
- (C)ontroller - Servlets (Talks with the database)

### Remember! 
Model and View should never be allowed to talk to each other. Always have the model talk through the controller to the view.

```shell
git init
git add .
git commit -m "First commit"
```