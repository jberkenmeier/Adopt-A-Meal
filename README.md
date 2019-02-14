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

### Windows:

#### Required:

* [PHP](http://us1.php.net/downloads.php)
* [Composer](https://getcomposer.org/)
* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* IDE (recommended it have a built in terminal i.e. PHPStorm, IntelliJ, Visual Studio etc.)
* [WAMP](http://www.wampserver.com/en/) (optional). WAMP includes easy installation of PHP, Apache, and MySQL. 


1.	Follow links to install PHP and Composer. Make sure to include both to your PATH environment variable in order to run commands. To do this go to Settings -> search for system environment variables -> click Environment Variables button -> under system variables find PATH variable and double click ->click new -> add path to composer bin (i.e. \composer\vendor\bin) and php bin folder (i.e. \bin\php\php_version) -> click OK

2.	Make sure PHP and Composer is installed properly by running version commands in a terminal 

        > php -v (should give php version that you are running and other info)
        > composer –version (gives composer version)
        
3.	Next you’ll want to clone the project repository. You can do this from command line using:

        > git clone https://github.com/jberkenmeier/Adopt-A-Meal.git 
        
    _link subject to change_
    
    - If using WAMP you will want to clone this into the www directory provided when installing WAMP

4.	Now that you have the project ready to go there might be a few things you want to do. It is always good to keep dependencies up-to-date with:
	
        > composer update 
    
    If using WAMP you might need to configure the apache httpd-vhosts.conf file and add the path to your project in the Document Root section.

5.	Running Project: From command line within IDE you can simply run

        > php artisan serve

    This will bring up an http link. Click on this link and the project should open up in your browser. It is important to note that if you are using WAMP as well, this might hinder the php artisan serve from bringing up the project. Disable WAMP before running this command (click wamp icon -> stop all services).
    
    - If using WAMP to run project, if everything is set up correctly, you can just type in localhost in your browser and the project will come up. You can also click on the WAMP icon and click Localhost (first option). This will serve up the project at localhost as well.

### Mac:

#### Required:
* [Homebrew](https://brew.sh/)
* [PHP](http://us1.php.net/downloads.php)
* [Composer 1.8.0](https://getcomposer.org/)
* [Laravel Framework](https://laravel.com/docs/4.2)
* [PHP Storm](https://www.jetbrains.com/phpstorm/) / [IntelliJ IDEA](https://www.jetbrains.com/idea/)
* [MAMP](https://www.mamp.info/en/) - Optional

1. From the command line (through terminal, iTerm, or your shell of choice) install Homebrew with the following command:

        > /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

2. Once Homebrew has been successfully installed, you can go ahead and installi PHP and Composer using:
   
        > brew install php
        > brew install composer

3. After Composer has finished installing, Laravel can be installed with:

        > composer global require "laravel/installer=~1.1"

4. You'll also need to append `~/.composer/vendor/bin` to your PATH. This can be done with:

        > PATH=$PATH:~/.composer/vendor/bin
   
    _This allows you to run the_ `laravel` _command in terminal._

5. If you don't already have PHP Storm, or IntelliJ IDEA, installed in your machine you can install them using the link(s) provided above. If you decide to use IntelliJ IDEA you'll want to download the _Ultimate_ version. Either way both will download a .dmg (Disk Image) file that will allow you to install either program easily by just following their instructions.

    - you can run local development through PHPStorm and IntelliJ IDEA using the following [guide](https://www.jetbrains.com/help/phpstorm/laravel.html).

6.	Next you’ll want to clone the project repository. You can do this from command line using:

        > git clone https://github.com/jberkenmeier/Adopt-A-Meal.git 

    _link subject to change._ 

7. (Optional) You can also download MAMP for help with local development. Download the .pkg file for Mac and follow the installation instructions. If you decide to use MAMP you'll have to create a copy of repository and move it, or clone it, to `/Applications/MAMP/htdocs/`

8.	Now that you have the project ready to go there might be a few things you want to do. It is always good to keep dependencies up-to-date with: 

        > composer update 

9.	Running Project: From command line within IDE you can simply run

        > php artisan serve
        
    This will bring up an http link. Click on this link and the project should open up in your browser. It is important to note that if you are using MAMP as well, this might hinder the php artisan serve from bringing up the project. Disable MAMP before running this command (click mamp icon -> stop servers).

    - If using MAMP to run the project, and if everything is set up correctly, you can just type in localhost:8888 in your browser and the project will come up. 
