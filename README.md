# Santa's Toys Factory

>[!IMPORTANT]
>To learn how to install and also to know how our team did this project, it's very important that you read every part of this readme. Thank you for your patience and have a good read.
***

## :bulb: Project description

***

## Requirements to achieve in this project:

- The elves must display all the toys made (Blade) on the screen.

- Elves should be able to delete, view all, insert, modify, and watch a toy show by Endpoints

- The elves should be able to see a toy show (Blade)

- Santa Claus must display all the kids on the screen (Blade).

- Santa Claus must View the of Json all the kids.

- Santa Claus must be able to delete, insert, modify, and see (show) the kids through Endpoints

- Santa Claus must be able to see the little ones' show (Blade)

- Santa Claus will have a button on blade and a route through Api to generate the list of toys for the little ones that appears in both Blade and Api

- 70% minimum test coverage.

- User Stories and well-assembled Project

- Elf Routes must contain the word elves and Santa Claus Routes must contain Santa

- The welcome page must be a welcome to the toy factory it will not appear
***

## :eye_speech_bubble: Project overview

Take a look at how our project turned out.
***

<P align="center">Home Page</P>

<p align="center">
 <img src=""/>
</p>

***

<P align="center"></P>

<p align="center">
 <img src=""/>
</p>

***

<P align="center"></P>

<p align="center">
 <img src=""/>
</p>

***

## Project Diagrams (BBDD)



The diagram we did for the database in **DrawSQL**.

As you can the three tables are interlinked, this one, with a **ManyToMany** relantionship.
***

## Installation requirements

Before you start to read how to install the project you'll need these requirements:
>[!NOTE]
>If you can't install xampp, look for any other local server that supports **MySQL** and **PHP**
***

1. XAMPP

2. Install Composer

3. Install NPM in Node.js

4. Xdebug (for the tests coverage)

5. Postman
***

## :scroll: Installation

1. Clone this repository:
```
 https://github.com/rebecabernal/ToysFactory.git
```

2. Install **Composer** and **NPM**
```
composer install
```
```
npm install
```

3. Create a .env file copying everything inside the existing file .env.example and modify the following lines:
* DB_CONNECTION=mysql
* DB_DATABASE=

4. Create a database in **MySQL**

5. Now go to the VSC terminal and put the following command
```
php artisan migrate:fresh --seed
```
This command will generate all the tables.

6. Open another terminal in **VSC** and put the following command
```
npm run dev
```

7. Open another terminal and run the server with this command
```
php artisan serve
```
You'll see an url that is going to take you to a website.

>[!IMPORTANT]
>Be sure that your running npm and the server in **DIFFERENT** terminals, **DON'T** close these two terminals and **DON'T** use other commands in these two terminals. 
***

## Project documentation

>[!NOTE]
>Since we have three interlinked tables, each one of them has their own CRUD.
>
>
***

<p align="center">Endpoints</p> 

GET all ids
```

```

GET an especific id
```

```

DELETE by id
```

```

POST create a new id
```

```

PUT update an existing id
```

```
***

<p align="center">Endpoints</p>

GET all id
```

```

GET an especific id
```

```

DELETE by id
```

```

PUT update an existing id
```

```

POST create new id
```

```
***

## :white_check_mark: Tests

> [!IMPORTANT]
> It's important to test the project so we can check if it works correctly and to do that use this command in the **VSC** terminal:

```
php artisan test
```

<p align="center">This is what you should see after putting the command:</p>

<p align="center">

</p>

<p align="center"></p>

***

## Coverage

To see the coverage you can use this command at the **VSC** terminal
```
php artisan test --coverage-html=coverage-report
```

> [!IMPORTANT]
> Everytime that you do new tests you need to put the command above in the **VSC** terminal, so it can update your coverage.
***

This will add a folder called "coverage-report", go to the folder, go to the index.html, and then open with live server. After that you should see this page:


***

## Team

>[!NOTE]
>Please understand that our team is still learning, not everything will look or be perfect. Thank you for the attention.

Rebeca Bernal: https://github.com/rebecabernal

Diego Santamaria: https://github.com/DinGo21

Rodrigo Lastra: https://github.com/rodrigoo1604

Talena Barbosa: https://github.com/talenaa

Valeria Dobado: https://github.com/ugotchriscoded

José Ignacio: https://github.com/sr-calcetines

***

## Languages and tools we used in this project

<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='PHP' src='https://img.shields.io/badge/PHP-100000?style=for-the-badge&logo=PHP&logoColor=white&labelColor=896696&color=896696'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='html5' src='https://img.shields.io/badge/html-100000?style=for-the-badge&logo=html5&logoColor=white&labelColor=FF8400&color=FF8400'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='css3' src='https://img.shields.io/badge/css-100000?style=for-the-badge&logo=css3&logoColor=white&labelColor=079FB0&color=079FB0'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='mysql' src='https://img.shields.io/badge/mysql-100000?style=for-the-badge&logo=mysql&logoColor=white&labelColor=1C662F&color=1C662F'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='git' src='https://img.shields.io/badge/git-100000?style=for-the-badge&logo=git&logoColor=white&labelColor=FF0000&color=FF0000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='github' src='https://img.shields.io/badge/github-100000?style=for-the-badge&logo=github&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='canva' src='https://img.shields.io/badge/canva-100000?style=for-the-badge&logo=canva&logoColor=white&labelColor=A700FB&color=A700FB'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='xampp' src='https://img.shields.io/badge/xampp-100000?style=for-the-badge&logo=xampp&logoColor=white&labelColor=FF8800&color=FF8800'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='postman' src='https://img.shields.io/badge/postman-100000?style=for-the-badge&logo=postman&logoColor=white&labelColor=FF0000&color=FF0000'/></a>
***

## Thanks for reading!

Thanks for reading this readme!

Have a good day! :3
***
