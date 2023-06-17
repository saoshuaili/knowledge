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
