#YelpCamp

##Description 
 * The web application where autheticated users can add, review, edit and delete campgrounds.Comments also can be added to each of campgrounds.

##Installation
 * Project requires installation of npm,node, mongodb 
 * Other frameworks and tools such as Express,body-parse,mongoose and etc. are already installed in v11 folder
 * Project was implemented in the Cloud9 platform where all needed environment exists

##Run
 * If you use cloud9 to run the project
 * By default command prompt starts in ~/workspace folder
 * Go one step back in path by cd..
 * Run ./mongod command and keep terminal open
 * Open a new terminal
 * Go to ~/workspace and then to project folder YelpCamp/v11/
 * Run node app.js command
 * Then click Preview button on top and Preview running application
 * SignUp and then you can add new campgrounds and comments


RESTFUL ROUTES

name      url      verb    desc.
===============================================
INDEX   /campgrounds
NEW     /campgrounds/new
CREATE  /campgrounds
SHOW    /campgrounds/:id

NEW     campgrounds/:id/comments/new    GET
CREATE  campgrounds/:id/comments      POST



