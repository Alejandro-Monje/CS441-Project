Project Aquarius
===
Project Aquarius is a light weight and responsive inventory management system. This was an assignment for the California State University-San Marcos CS 441 class. The goal of this project was to create a inventory management system that is easy to use for lower level users in a company while giving administrators the full power of a highly functional system, using the Agile programming method

### Features
---
- Mandatory features included:
    - Login/logout
    - Register new users
    - Add, remove, and edit inventory data
    - Users with varied permissions
- EXTRA features included:
    - POS system
    - Scanning feature
- Future cases to implement (If there was time left)
    - More Guest Functions
    - More Employee Functions

### Tech
---

Project Aquarius uses a number of frameworks to work properly:

* [Twitter Bootstrap](https://getbootstrap.com) - A beautiful HTML/CSS framework
* [MySQL](https://www.mysql.com) - Stores all our database information
* [PHP](http://php.net) - Queries, fetches and stores database information
* [jQuery](https://jquery.com) - The paste that makes it responsive

### Installation
---

A live demo can be found [HERE](http://projectaquarius.000webhostapp.com)

Simply clone the repository. If only running on a local machine, download [XAMPP](https://www.apachefriends.org/index.html) (for Windows), or [MAMP](https://www.mamp.info/en/) (for OSX) to host a local database.

After setting up PHPmyAdmin with a username and password, create a new database, and import `CS441_IMS.sql` to the database.

Once that is complete, edit `/use/config.php` with the correct values for login and the database name. If you are using root as your user, there is no need to input a password, unless you have set one.

```
define('DB_HOST', 'localhost');         // Set database host
define('DB_USER', 'USERNAME');          // Set database user
define('DB_PASS', 'YOUR_PASSWORD');     // Set database password
define('DB_NAME', 'DATABASE_NAME');     // Set database name
```

##### If you are using XAMPP or MAMP:
Be sure to locate the folder `htdocs` and copy the repository files into the directory. When you are ready, be sure to start both the MySql Server and the Webserver.

That's it!

### Project Management
---
- Tools Used
    - Slack for communication
    - GitHub for file coordination.
    - PHPStorm for IDE
- Agile Sprints
    - **First**: Getting a visible login screen, and the foundations for the database.
    - **Second**: Built dashboard, and constructed the database.
    - **Third**: Built add/remove users PHP, and add/remove item PHP.
    - **Fourth**: Integration into the dashboard
    - **Fifth**: Refactoring & final testing
    
### What we learned
---
When we started the project, no one had really any experience with PHP, HTML, CSS, or even MySQL, except for one of two people. We each had to take some time and learn how to use these languages. At first, we also wanted to include AngularJS, but opted not to, as it only complicated things more than we wanted. Communication with the team was difficult, and not everyone was one the same page at all time, as well as everyone had their own style and idea of what they wanted to do. However,int the end,  the group had the expectation that at the end of each sprint, we would have at least something to show, something that was actually working.

This was by no means an easy project, as we first thought it would be. There were times where the team was quite divided on ideas, on what was most important, and whether or not we'd even finish it at all. towards the final sprints, everyone had built their own divided modules, which each worked independantly and communicated with the database as intended, but there was no real final product just yet. Here, Ken shines as he stepped up and really put it all together into a working product that we are all proud to show off.

### Credits
---
| Member | Contribution |
| :-------: | :-------: |
| Stefan Retief | Project Lead |
| Ken Khuat | Lead Guru |
| Alejandro Monje | Back-End Specialist |
| Juan Juarez | Back-End Specialist |
| Antonio Monje | Front-End Specialist |
| David Garcia | Design Pattern Specialist |
