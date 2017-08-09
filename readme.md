- public IP address: 52.36.68.251
- public url: <http://ec2-52-36-68-251.us-west-2.compute.amazonaws.com/>

### installed packages:
- finger
- git
- python-pip
- postgresql
- psycopg2
- sqlalchemy
- python-sqlalchemy
- apache2
- libapache2-mod-wsgi
- flask
- requests

### configurations made:
1. updated the ssh port to non-standard
2. update all system packages to latest
3. created a new sudoer for the grader to ssh in
4. installed apache to run a web server
5. installed postgres for the web application
6. created a new database user and database for the web application
7. installed git and clones my acronym dictionary project in
8. updated the WSGI config to serve my application.py file
9. tweaked the code in the flask application to import the modules correctly
10. fixed some issues with the flask code to make sure authentication worked
11. check off all the requirements!

### resources used to complete:
- [sshd_config man page](http://manpages.ubuntu.com/manpages/trusty/en/man5/sshd_config.5.html)
- [postgresql documentation](https://www.postgresql.org/docs/9.5/static/app-createuser.html)
- [sqlalchemy documentation](http://docs.sqlalchemy.org/en/latest/core/engines.html)
- [configuring linux servers - udacity course](https://www.udacity.com/course/configuring-linux-web-servers--ud299)
- udacity FSND forums
