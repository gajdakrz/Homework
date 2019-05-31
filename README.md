USERS APP

Introdution
===========

This is a simple web application with bootstrap css forms
(<https://getbootstrap.com/>) containing basic functions:

-   Creating users

-   Sending emails for users

-   Managing (edit, delete) users

Instalation
===========

Aplication based on CodeIgniter framework (<https://www.codeigniter.com/>)

and configured on XAMPP open-source cross-platform web server solution stack.

Installation steps:
===================

1.  Install XAMPP (<https://www.apachefriends.org/download.html>)

2.  Download **UsersApp** and insert for example in localhost path:
    *xampp\\htdocs*\\UsersApp

3.  Run xampp control panel and open config (**httpd.conf**) for Apache module

4.  Configure **httpd.conf** for proper document root and directory, for
    example:

*DocumentRoot "../xampp/htdocs/UsersApp"*

*\<Directory "../xampp/htdocs/UsersApp"\>*

1.  Run Apache and Mysql module

2.  Run admin for Mysql module - phpmyadmin

3.  In phpmyadmin there should be ‘test’ database. If not – create.

4.  In DB ‘test’ import test.sql from **DB** folder. In the end it should be two
    tables in ‘test’ DB:

    1.  Users – empty

    2.  Positions – with 3 records: tester, developer, project manager

    3.  Configuration steps:

To sending emails there should be configured proper smtp server in file:

UsersApp\\application\\config\\**email.php** . There is only (not working with
wrong password) example for gmail smtp server. It should be changed to another
account.

How to use
==========

1.  First you have to create user on **home** page

![](media/d0df92940fd831e5e3fc461460811943.jpg)

2.  After creating the user in ‘test’ db, will be sent welcome email with
    inserted data.

![](media/e55be9aa52d513365c582855eab5b27b.jpg)

3.  You can manage (edit, delete) the user on admin page

![](media/6f0049e5e9dd6373d88f974d5b1097f1.jpg)

License
=======

MIT license was descibed in license.md file.

Contact
=======

Krzysztof Gajda

<gajda.krzysztof@gmail.com>

[www.linkedin.com/in/krzysztofgajda](http://www.linkedin.com/in/krzysztofgajda)