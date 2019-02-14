# Adopt-A-Meal

## Sponsors: Cody Gacek (Foerstel) and Jodi Peterson (Interfaith Sanctuary)

## Project Description:

The Adopt-A-Meal project allows members of the community to volunteer to provide meals for Interfaith Sanctuary. This part of the project aims to help simplify the scheduling process for meals through a simple date selection process, after which users can fill a "Meal Adoption" form and submit it for admin approval. All approved forms should be displayed so users can be aware of what meals/events are planned.

## Team Members:

Last Name       | First Name      | GitHub User Name     | Scrum Role
--------------- | --------------- | -------------------- | ---------------
Berkenmeier     | Joshua          | jberkenmeier         | Developer
Guevara         | Jaime           | jdguevara            | Developer 
Perdew          | Thomas          | Thomasperdew         | Product Owner / Scrum Master(?)
Ross            | Maddie          | Maddieross           | Developer

## Team Velocity:

Sprint | Estimated Velocity | Actual Velocity
------ | ------------------ | ---------------
1      | 18                 | 18
2      | TBD                | TBD
3      | TBD                | TBD
4      | TBD                | TBD
5      | TBD                | TBD

## Contact Information:
* Joshua - <joshuaberkenmeier@u.boisestate.edu> 
* Jaime  - <jaimeguevara@u.boisestate.edu>  
* Tom - <thomasperdew@u.boisestate.edu>
* Maddie - <maddieross@u.boisestate.edu>

## Project Installation:

Windows:

Required:

    PHP - [http://us1.php.net/downloads.php][PHP]

    Composer - [https://getcomposer.org/][Composer]

    Git - [https://git-scm.com/book/en/v2/Getting-Started-Installing-Git][Git]

    IDE (recommended it have a built in terminal i.e. PHPStorm, IntelliJ, Visual Studio etc.)

    WAMP optional. WAMP includes easy installation of PHP, Apache, and MySQL. [http://www.wampserver.com/en/][WAMP]


1.	Follow links to install PHP and Composer. Make sure to include both to your PATH environment variable in order to run commands. To do this go to Settings -> search for system environment variables -> click Environment Variables button -> under system variables find PATH variable and double click ->click new -> add path to composer bin (i.e. \composer\vendor\bin) and php bin folder (i.e. \bin\php\php_version) -> click OK
2.	Make sure PHP and Composer is installed properly by running version commands in a terminal 

        > php -v (should give php version that you are running and other info)
        > composer –version (gives composer version)
        
3.	Next you’ll want to clone the project repository. You can do this from command line by git clone https://github.com/jberkenmeier/Adopt-A-Meal.git (link subject to change). If using WAMP you will want to clone this into the www directory provided when installing WAMP.
4.	Now that you have to project ready to go there might be a few things you want to do. It is always good to run 
	> composer update 
to keep dependencies up to date. If using WAMP you might need to configure the apache httpd-vhosts.conf file and add the path to your project in the Document Root section.
5.	Running Project: From command line within IDE you can simply run

        > php artisan serve
        
This will bring up an http link. Click on this link and the project should open up in your browser. It is important to note that if you are using WAMP as well, this might hinder the php artisan serve from bringing up the project. Disable WAMP before running this command (click wamp icon -> stop all services).
If using WAMP to run project, if everything is set up correctly, you can just type in localhost in your browser and the project will come up. You can also click on the WAMP icon and click Localhost (first option). This will serve up the project at localhost as well.



[Composer]: https://getcomposer.org/

[PHP]: http://us1.php.net/downloads.php

[Git]: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

[WAMP]: http://www.wampserver.com/en/
