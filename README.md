# Software Testing and Debugging Project

This is a repository that I copied over from: https://github.com/jaygajera17/E-commerce-project-springBoot. It is an open-source project and I added blackbox unit tests, whitebox unit tests, and GUI tests using Selenium.

## Project Intro
### Subject Application
- 2,610 LOC with 27 methods and 15 frontend pages. Link: https://github.com/jaygajera17/E-commerce-project-springBoot
- ⚙️Spring Mvc, JDBC , Jsp, Servlet
- 📝ADMIN MODULE + USER MODULE, with CRUD OPERATION
### Testing Project
- Testing code: 9 test classes, 2035 lines of code, 88 test methods for b/w testing, 65 test methods for GUI testing.
- Testing approach: blackbox, whitebox, GUI (using Selenium).
- B/W testing classes: AdminControllerTest and UserControllerTest
- GUI testing classes: BuyGUI, CategoryGUI, CustomerGUI, LoginGUI, ProductGUI, ProfileGUI, RegisterGUI

## How To Run tests?

(1) Pre requirement:- java, Idea IDE, xampp installed

(2) For xampp, download from https://www.apachefriends.org/download.html. Open it and start runnning apache and mysql.
 
<img width="60%" alt="image" src="https://i.postimg.cc/QVLNgVVk/xampp.jpg">
 
To check it work, go to 'http://localhost/dashboard' (Mac), or 'http://localhost:80/dashboard' (port may vary based on your setting)

<img width="60%" alt="image" src="https://i.postimg.cc/3xJHDgxC/xampp-home.jpg">


(3) Set up database
```sh
 Click 'phpMyAdmin' and make database name :- springproject 
 ```
```sh
 import springproject.sql file in database to Create all table and insert original data 
 ```

(4) Run the application -> JtSpringProjectApplication.java
```sh
import the project to Idea and load it as a Maven project. Download all maven dependencies.
```
```sh
Use maven plugin -> springboot-boot:run to run the application first
```
<img width="40%" alt="image" src="https://i.postimg.cc/3JcfB6jR/run.jpg">

(5) Keep the application running, and run tests class. Make sure to drop and re-run the sql file before running the test file.

<img width="40%" alt="image" src="https://i.postimg.cc/cJLL7vdw/tests.jpg">


## Other information

### Project proposal
https://docs.google.com/document/d/16xoSUQ0kyuVDpPBt6RZNdpRW7gpzLQhMeK8E7Wvmcj8/edit?usp=sharing

### Log in 
Admin Module (http://localhost:8080/admin) 
-  user name:- admin
-  password :- 123
-  Note(above default username and password , it can be change in the database)

  User module
-  user name:- jay 
-  password:- 123

Below is the open-source project README:


# E-commerce_website-in-java


## E - COMMERCE WEB PROJECT IN SPRING BOOT



<!-- [![Contributors][contributors-shield]][contributors-url]
[![MIT License][license-shield]][license-url]
[![Isses][issues-shield]][issues-url]

-->
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
<br>




## Features
- ⚙️Spring Mvc, JDBC , Jsp Servlet
- 📝ADMIN MODULE + USER MODULE
- ➕CRUD OPERATION
- 🌱Easy to understand beginner friendly.
- 🥳Pull Request Welcome (Open Source).




## How To Run ?

- Pre requirement:- Spring boot Installed in Eclipse IDE ,  mysql Database , xampp 

- please make sure you have eclipse ide enterprise for web development if not then re install set up & choose web option.
<img width="169" alt="image" src="https://user-images.githubusercontent.com/81226571/178137583-578558de-ff7e-498b-bb00-927dd46b4fb0.png">


 (1)
```sh
Download and import project in Eclipse Ide
```
 (2)
```sh
 Make database name :- springproject 
 ```
  (3)
```sh
 import springproject.sql file in database to Create all table 
 ```

(4)
```sh
Right click project and run as spring boot & open:- http://localhost:8080/
```

## project directory 
<img width="302" alt="image" src="https://user-images.githubusercontent.com/81226571/178137751-c02d40b5-e718-4aad-816a-f45807612e5c.png">
<h4> MVC WorkFlow: </h4>
    → in the Admincontroller.java & userController.java files having a mapping based function which returns file name.<br>
    → in Src->main->webapp->views  following Jsp file will be executing.

## log in 
ADMIN Module (http://localhost:8080/admin) 
-  user name:- admin
-  password :- 123
-  Note(above default username and password , it can be change in the database)

  User module
-  user name:- jay 
-  password:- 123

## Important link
- 𝗬𝗼𝘂𝘁𝘂𝗯𝗲 𝗽𝗿𝗼𝗷𝗲𝗰𝘁 𝘃𝗶𝗱𝗲𝗼 𝗪𝗼𝗿𝗸𝗶𝗻𝗴 𝗗𝗲𝗺𝗼 + 𝘀𝘁𝗲𝗽 𝗯𝘆 𝘀𝘁𝗲𝗽 𝗲𝘅𝗲𝗰𝘂𝘁𝗶𝗼𝗻 𝗹𝗶𝗻𝗸 ::---  [  click here  ](https://youtu.be/c6WWdINWSlI) [![youtube][youtube-shield]][youtube-url]

- connect in Linked in ::---  [ https://www.linkedin.com/in/jay-gajera-a6496b204/]
- instagram:- [https://instagram.com/jay_gajera_17]


## preview
![img](https://github.com/jaygajera17/E-commerce_website-in-java/blob/main/JtProject/src/main/resources/Product%20Images/Screenshot%202022-04-11%20111601.jpg)
![img](https://github.com/jaygajera17/E-commerce_website-in-java/blob/main/JtProject/src/main/resources/Product%20Images/Screenshot%202022-04-11%20111538.jpg)
<img width="938" alt="image" src="https://user-images.githubusercontent.com/81226571/178270030-c4e9f485-fe0b-4bbb-804a-a28d2c182c7c.png">



- **Star++** ⭐  if you  find helpful.
<img alt="Night Coding" src="https://raw.githubusercontent.com/AVS1508/AVS1508/master/assets/Night-Coding.gif" align="center"/>
<h3 align="left">If you found this valuable and want to return the favour, then</h3>
<p><a href="https://www.buymeacoffee.com/gajerajay9I"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="gajerajay9" /></a></p><br><br>

[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/jaygajera17/E-commerce-project-springBoot/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jaygajera17/E-commerce-project-springBoot.svg?style=for-the-badge
[forks-url]: https://github.com/jaygajera17/E-commerce-project-springBoot/network/members
[stars-shield]: https://img.shields.io/github/stars/jaygajera17/E-commerce-project-springBoot.svg?style=for-the-badge
[stars-url]: https://github.com/jaygajera17/E-commerce-project-springBoot/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]:  https://www.linkedin.com/in/jay-gajera-a6496b204/

[youtube-shield]:https://img.shields.io/youtube/views/c6WWdINWSlI?style=social
[youtube-url]:  https://youtu.be/c6WWdINWSlI
