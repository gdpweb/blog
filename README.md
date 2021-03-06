# Mon blog php

![](http://blog.gdpweb.fr/Web/img/logo.png) MonBlog

>This blog is produced as part of project 5** Openclassroom** training.
To install "My Blog" you must have a hoster and a relational database management system. A local installation is strongly recommended to test and parameterize the application.
- Compatible with all major browsers
- **Example online** [Mon blog](http://blog.gdpweb.fr/ "Heading link")


## Server Requirements of the Web App
- Application Server PHP 7.0 or higher.
- PHP Extension mbstring
- Database MySQL/MariaDB 5 or higher.

## Installation
- Download the repository and extract it to the target directory where it should be installed.
Create your MySQL database and import the blog.base.sql file.
Rename App/config.dev.php to App/config.php and customize the configuration and set in any case the settings for the database connection.


- Download the freelancer theme: https://startbootstrap.com/template-overviews/freelancer/ and put in the web folder. <img src="https://blackrockdigital.github.io/startbootstrap-freelancer/img/profile.png"  width="50" />

```php
// Constants of access to the database

define ('BDD_SERVER', 'localhost'); // Database server address

define ('BDD_LOGIN', 'root'); // Login

define ('BDD_PASSWORD', ''); // Password

define ('BDD_NAME', 'blog'); // Name of the database


// Constants of the application

define ('APP_NOM', 'name_blog'); // name of the application

define ('APP_AUTEUR', 'your_name'); // name of the owner of the blog

define ('APP_AUTEUR_PHOTO', 'profile.png'); // photo of the owner of the blog


// Constants used to send mails

define ('MAIL_AUTEUR', 'your_name@yourdomain.com'); // email from the owner of the blog from the host

define ('MAIL_FROM', 'noreply@yourdomain.com'); // email displayed when sending

define ('MAIL_LOGO', 'http://yourdomain.com/Web/img/logo.png');// picture logo attached to the mail
```
## Requires

- Install dependencies with composer : composer install

## Licence

[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)

## Codacy
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/0735a16379b94840964491d14a9676bb)](https://app.codacy.com/app/gdpweb_3/blog?utm_source=github.com&utm_medium=referral&utm_content=gdpweb/blog&utm_campaign=Badge_Grade_Dashboard)


## SensioLabsInsight

[![SensioLabsInsight](https://insight.sensiolabs.com/projects/c5791823-ac0d-4513-b6d6-844dc1c86c58/big.png)](https://insight.sensiolabs.com/projects/c5791823-ac0d-4513-b6d6-844dc1c86c58)
