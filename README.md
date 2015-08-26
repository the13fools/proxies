# proxies
Making some proxy scripts I found on the internet avalible on github.

I needed to setup a proxy server, and it took a bit of looking to track down one which was easy to deploy.  
Putting this here with the hope that it saves someone a bit of time, ended up initializing a LAMP instance on digital ocean (https://www.digitalocean.com/?refcode=5cc2b0db2b83) and installing glype.

In particular (if you are just trying to get something running): 
cd /var/www/html
wget https://www.glype.com/download.php
apt-get install unzip 
unzip download.php
chmod 666 includes/settings.php

http://sourceforge.net/projects/poxy
http://sourceforge.net/projects/php-proxy
https://www.glype.com/
https://swiperproxy.github.io/


