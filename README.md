# Linux-Server-Project
This is a project for Linux Server Configuration in Udacity FSND. This a webserver simulation and testing using ubuntu 16.04LTS running apache2 hosted by AWS.

## Webserver Details
Public IP: 52.77.238.29
SSH Port: 2200

### Applications Running in this Webserver:
1. Project Catalog - http://ec2-52-77-238-29.ap-southeast-1.compute.amazonaws.com/proj-cat/
2. Park Locator - http://ec2-52-77-238-29.ap-southeast-1.compute.amazonaws.com/park-loc/

### Software Installed in Ubuntu server
1. For the webserver apache2 and libapache2-mod-wsgi. Installed Flask and other python libraries to be able to handle app imports.
2. For the firewall enabled ports 2200, 80 and 123 in ubuntu ufw and AWS GUI.
3. For the database postgresql is used to store data and sqlalchemy for the db engine.
4. Added grader and catalog as users. Sudo enabled only on grader.

### Third party resources
1. Google Maps API
2. Data.sg.gov Weather forecast API
3. Foursquare venue API
