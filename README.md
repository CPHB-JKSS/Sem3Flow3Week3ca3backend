
###Travis status [![Build Status](https://travis-ci.org/JoakimKSS/Sem3Week3Flow3CA3.svg?branch=master)](https://travis-ci.org/JoakimKSS/Sem3Week3Flow3CA3.svg?branch=master)

# Getting Started

1. Setup droplet on digital ocean with docker using this docker setup: [Github repository](https://github.com/Hartmannsolution/tomcat_mysql_nginx_docker.git "Github.com").

2. Add mysql database `ca3db` and test database `ca3db_test`. Alternatively rename the database in '__persistance.xml__'.  
__Remember__ to add roles and users to the database.

3. Setup continious integration with [Travis CI](https://www.travis.org "travis.org").  Set environment variables `REMOTE_USER` and `REMOTE_PASS` to match your tomcat server.

4. __Rename__ and __customize__ entities and more, to suit your needs.