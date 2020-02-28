sudo apt-get update

sudo apt install nginx mariadb-server mariadb-client php7.2 php7.2-fpm

sudo systemctl enable nginx

sudo service nginx start

sudo mysql_secure_installation

*unninstall mariadb*

sudo service mysql start

sudo mysql_secure_installation

mkdir "raka"

cd /etc/nginx/sites-available/

cp -t ~/raka default
