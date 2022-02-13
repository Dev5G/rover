#### TABLE OF CONTENT
- [Introduction](#INTRODUCTION)
- [Requirements](#REQUIREMENTS)
- [Recommended Module](#RECOMMENDED-MODULES)
- [Installation](#INSTALLATION)
- [Configuration](#CONFIGURATION)
- [Maintainers](#MAINTAINERS)

INTRODUCTION
------------
ROVER is on a mission to explore the cross-platform automation purchasing.

 * For a full description of the module, visit the project page:
   https://www.roveraio.com

 * To submit bug reports and feature suggestions, or track changes:
   https://github.com/Devv5G/rover/issues

REQUIREMENTS
------------

This module requires at least one of the following modules:

 * [Chrome Driver](https://chromedriver.chromium.org/downloads/version-selection) : Please read the instructions to install the correct version.
 * [FireFox Driver](https://github.com/mozilla/geckodriver/releases) : Coming soon

 RECOMMENDED MODULES
-------------------

 * [Chrome Driver](https://chromedriver.chromium.org/downloads/version-selection):
   At the moment rover supports the use of chrome driver only.

INSTALLATION
------------
 
 * The installation process has not yet been decided. Visit
   https://github.com/Devv5G/rover/ for further information.


CONFIGURATION
-------------
 
 * Download the Chrome Driver and unzip the file inside to a location that is easily accessible i.e. » `C:\Rover\drivers`

   - Download the rover latest releas

     Double click the RoverAIO.exe to launch the application

   - Add the path of the chrome browser to user and system path variables

     The system and user `path` variables can be found in Control Panel

   - Open up a terminal and type the following command, replace the `PATH-TO-SAVE-CHROME-SESSION-PROFILE` with the path you want to save the session data to.

     ```chrome --remote-debugging-port=9222 --user-data-dir="PATH-TO-SAVE-CHROME-SESSION-PROFILE"```

 Open up the application and select the site you want to monitor, click start.


<!-- TROUBLESHOOTING
---------------

 * If the menu does not display, check the following:

   - Are the "Access administration menu" and "Use the administration pages
     and help" permissions enabled for the appropriate roles?

   - Does html.tpl.php of your theme output the $page_bottom variable?

FAQ
---

Q: I enabled "Aggregate and compress CSS files", but admin_menu.css is still
   there. Is this normal?

A: Yes, this is the intended behavior. the administration menu module only loads
   its stylesheet as needed (i.e., on page requests by logged-on, administrative
   users). -->

MAINTAINERS
-----------

Current maintainers:
 * Shahid H. Raja - https://www.github.com/Dev5G/

This project has been sponsored by:
 * **Dev5G**
   Specialized in consulting and planning of React powered sites, Dev5G offers installation, development, theming, customization, and hosting
   to get you started. Visit https://www.dev5g.com for more information


-------
-------
-------
