##安装最新版nginx
   26  echo "deb http://nginx.org/packages/debian/ bullseye nginx">> /etc/apt/sources.list
   27  echo "deb-src http://nginx.org/packages/debian/ bullseye nginx">> /etc/apt/sources.list
   28  wget http://nginx.org/keys/nginx_signing.key && apt-key add nginx_signing.key
   29  apt-cache search nginx 1.24
   30  apt-get update
   31  apt-cache search nginx 1.24
   32  apt-cache search nginx1.24
   33  apt-cache search nginx
   34   apt-get install nginx=1.24.0-1~bullseye
##安装最新版PHP
   35  wget -O /etc/apt/trusted.gpg.d/php.gpg https://packages.sury.org/php/apt.gpg
   36  echo "deb https://packages.sury.org/php/ $(lsb_release -sc) main" | sudo tee /etc/apt/sources.list.d/php.list
   37  apt-get update
   38  apt-get install php8.2 php8.2-fpm php8.2-mysql php8.2-curl php8.2-gd php8.2-common  php8.2-mbstring  php8.2-xml

##an
