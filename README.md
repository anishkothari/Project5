IP Address: [52.10.115.151] (http://52.10.115.151/)
SSH Port 2200
URL: [http://ec2-52-10-115-151.us-west-2.compute.amazonaws.com/] (http://ec2-52-10-115-151.us-west-2.compute.amazonaws.com/)

Project Overview
Configure a Ubuntu server to securely host the Flask webapp developed in [Project 3] (https://github.com/anishkothari/catalog-app).

- Create a new user named grader (password grader), grant the user sudo permissions, change the default SSH port, disable root access, generate a SSH keypair locally and use it to connect to the server.
- Update the package lists and upgrade the packages.
- Configure HTTP and NTP ports using Uncomplicated Firewall (UFW) and set the local timezone to UTC.
- Install the Apache webserver and PostgreSQL. Configure the database with a user named catalog (password catalog) and set up the app to use PostgreSQL.
- Install git, connect GitHub account and clone the project from GitHub; keep the .git directory private.
- Change credentials at the Google Developers Console for Oauth login and replace the client_secrets.json file on the server.

Software Installed
- UFW
- Apache2
- Git
- Flask
- SQLAlchemy
- PostgreSQL
- virtualenv
- mod_wsgi
- python-psycopg2
- httplib2
- requests
- oauth2client


Resources

[stueken's very thorough guide] (https://github.com/stueken/FSND-P5_Linux-Server-Configuration)

[sageio's easy to follow guide] (https://github.com/sageio/linux-server)

[arianalopez30's succinct guide]
(https://github.com/arianalopez30/project5)

various threads on the Udacity discussion forums including
[Project 5 Resources] (https://discussions.udacity.com/t/project-5-resources/28343)

[this website] (http://www.hcidata.info/host2ip.cgi) to find out the hostname

Dealing with the client_secrets.json file [1] (http://stackoverflow.com/questions/12201928/python-open-method-ioerror-errno-2-no-such-file-or-directory) [2] (https://discussions.udacity.com/t/google-sign-in-problems/28191)
